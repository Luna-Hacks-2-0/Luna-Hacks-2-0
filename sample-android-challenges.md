**Note**: All projects are  to built using Kotlin. For dependency injection you could use Koin, Hilt or another dependency injection framework. If new to dependency injection, use Koin. It's lightweight and relatively faster to learn. Use Android Architecture components as you'll find relevant. Unless specified feel free to use Jetpack compose or xml for the UI.

Remember to put your projects on Github😃

1. ### Offline first Approach

**Level**: Intermediate/Advanced
**Challenge Description**
Create an app that fetches data from an API of your choice and shows the the items list on the screen. The app should store data fetched from the API locally. 

#### Checklist
- The app fetches data daily on the background when the user has internet connection. Check WorkManager on scheduling tasks.
- A user should see data on the app, even when they are offline. They should see data saved locally when offline
This projcet will be built using Koltin, Room, Retrofit, WorkManager. 

#### Bonus: 
- Show a pop up dialog with the details of the item clickes
- Animate the pop up dialog
- Write unit tests for the App
2. ### My First Compose App
**Level**: Beginner, Intermediate
**Challenge Description**: 
Create an Android app that fetches A list of items from an API of your choice and shows the list on the screen. When user clicks on an item on the screen, the should be navigated to the detail screen. 
 
This project will be built with Kotlin, Jetpack Compose, Retrofit(for network calls), Coil(For Image loading), Android Architecture components, Jetpack Compose Navigation(Feel free to use another naviagtion library), Material3(Optional)

#### Bonus 
Animate navigation to the detail screen

Api options:
- Dog API: https://documenter.getpostman.com/view/4016432/the-dog-api/RW81vZ4Z
- TMDB api(This requires an api key): https://developers.themoviedb.org/3/getting-started/introduction
- Any other API of your choice

3. ### Handling Configuration changes and process death in Android
**level**: Intermediate, Advanced
**Challenge Description**
You can build an new project  or use an existing one. Optimize to survive configuration changes such as screen rotation, keyboard availability and process death
This project will use Android Architecture components: ViewModel, ViewModel saved state. For Jetpack Compose apps, check ```rememberSaveable``` Api.
Check this blog for guidance: https://www.kodeco.com/33044382-surviving-configuration-changes-in-android

5. ### Pagination
**Level**: Intermediate/Advanced
**Challenge Decription**
Create an app that fetches large lists of data from the backend and use pagination to load and display data. 
6. ### Note taking app
**Level**: Beginner, intermediate, advance
**Challenge Description**
A Note taking app
- The app should provide UI for users to enter note. 
- Notes are saved in the local db
- The app shows a  list of notes from the db
- Optimize the app to survive configuration changes and process death
- When a user clicks on an item, they should navigate to the detail screen. 

###Bonus
- Optimize the app for large screens and different form factors. Check this tutorial for guidelines: https://www.kodeco.com/34785195-large-screens-foldables-tutorial-for-android

This project uses Jetpack Compose

7. ### A blog or presentation
Research and write a blog or prepare a presentaion about an Architecure design pattern. It could be MVVM, MVI or another design pattern. A sample project would be a bonus. 

#### Checklist
- Explain the challenges the design pattern tries to solve
- Show an understanding of the design pattern