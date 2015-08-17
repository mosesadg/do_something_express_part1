## DOSomething.ly
Homework tonight is to create an express app!

In your application
- Create a variable `tasks` as an array of 5 objects.
  - Each object should contain 3 properties
    - id, integer
    - body, string
    - completed, boolean
- Create an index route that shows a list of all of the objects
  - each todo should have a link to its corresponding show page.
  - each todo will have its body and its completed status
- Create a show route that shows one single `todo`
- Create a `POST` route that allows you to add an object to the array
  - *note that this will not update the file, if you exit the application and restart, you will lose everything created in the `POST` route.*

### BONUS
- Make a post/put request that changes an existing todo from uncompleted to completed. Maybe render different index view to visualize the completed todos versus incomplete.
- Implement CRUD actions for lists in addition to tasks

### Super BONUS
- Using file I/O fake the funk of a database!
