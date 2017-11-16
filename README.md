# Exercise

Develop a Java EE web application that uses JavaServer Faces to implement its user interface.

You can solve a problem of your own choosing (e.g. if there is something you want to do related to your project or other coursework), or if you can't think of one, use the example below.

# Example problem

The requirements of the system are (in recommended order of implementation):

1. Web application.
2. Entry page displays a list of people and their contact details. When the application is first run, this list will be empty.
3. Entry page also has a form that allows the user to add a person and their contact details to the list. Once added, the entry page is shown again with an updated list displayed.
    - Hint: store the list internally in a managed bean - make the managed bean session-scoped.
    - Hint: maintain an MVC pattern throughout development of your solution.
    - Hint: use one class to store a person and their contact details.
4. Add user input validation to the application (e.g. name must not be empty; email address must conform to standard syntax, etc.)
5. Add a "delete" button next to each displayed person that, when pressed delete's their entry from the list (and redisplays the entry page).
6. Add an "edit" button next to each displayed person that brings up a separate page containing a form pre-populated with their details, allows them to be edited (with validation), and then updated (displaying the entry page again).


At this stage it is not necessary to store the list of people and their contact details in a database.
