# AstronautApp
iOS App where a user can select from a number of historical NASA Astronauts and learn of their missions. 


AstronautApp:

- SwiftUI code base

- UI
    GeometryReader: Size images to a percentage of the view.
    ScrollView: UI friendly access to individual astronauts and details. 
    LazyVGrid: Increased app efficiency by only loading data that is essential to the view. 
    ForEach: Creating a list of each Astronaut for user selection. 
    preferredColorScheme: .dark
    

- NavigationStack
    MissionView: Displaying Mission details relevant to the selected Astronaut. 
                 Data pulled from the "Mission" Model and displayed through a custom "CrewMember" struct. 
    
    AstronautView: Displaying individual Astronaut details. 
                   Data is pulled from the "Astronaut" Model and displayed directly to the view.

- Extensions 
    Bundle: Decoding 2 different JSON Types as Generics.
    
    ShapeStyle: Custom Dark & Light Background colors.
    
- JSON
    astronuats(Key : Value Pairs): { "Astronaut name": { "id": String, "name": "String, "description": "String } }
    missions(Key : Value Pairs): { "id": Int, "crew": [ { "name": String, "role": String } ] }

![Screenshot 2023-04-13 at 2 13 01 PM](https://user-images.githubusercontent.com/130512610/231848787-511b435b-3c9f-4911-ab06-47462f3969e3.png)
![Screenshot 2023-04-13 at 2 13 10 PM](https://user-images.githubusercontent.com/130512610/231848816-0017f5f3-f4fa-4e7c-8c1e-175ffd86ab92.png)
![Screenshot 2023-04-13 at 2 13 15 PM](https://user-images.githubusercontent.com/130512610/231848823-550d70d9-e347-449c-8b20-911a4ea90404.png)
![Screenshot 2023-04-13 at 2 13 21 PM](https://user-images.githubusercontent.com/130512610/231848850-57eda196-ae8f-48eb-b72a-b8ad2796a5d4.png)
