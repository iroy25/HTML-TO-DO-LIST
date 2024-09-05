                                                           HTML TO DO LIST
                                                                        
TASK :  CREATE A TO DO LIST USING HTML PROGRAMMING LANGUAGE

This project provides an overview of the process involved in creating a to do list using html and bootstrap, focusing on its purpose, design, development, and key considerations. The "HTML To-Do List Application" project aims to develop a web-based task management tool using HTML. The objective is to provide users with a simple and accessible platform for creating, organizing, and tracking their to-do lists. Key objectives include user-friendliness, cross-platform compatibility, data persistence, and adherence to accessibility standards. This project is designed to provide users with a simple and intuitive way to manage their tasks and stay organized. 

                                                          KEY FEATURES 

a.	CRUD operation: Users can add, edit, and delete tasks from their to-do list. Each task is associated with a title and can be marked as completed or pending.

b.	To enhance task organization, the application allows users to create multiple to-do lists or categories. Each list is visually distinct, making it easier for users to manage different types of tasks.

c.	The web-based nature of the application ensures that it can be accessed from any device with a web browser, making it a versatile solution for task management.

d.	The user interface is designed to be simple and easy to navigate, providing an intuitive experience for users of all levels of technical proficiency.

                                                        VARIOUS APPLICATIONS OF TO-DO LIST 

1.	Individuals can use this web application to manage their daily tasks and to-do lists. They can add, edit, mark tasks as done, and keep track of their responsibilities and deadlines.
   
2.	Small teams or individuals working on projects can utilize this tool to keep track of project tasks, responsibilities, and deadlines.

3.	Students can use this tool to manage their homework assignments, projects, and coursework. They can keep track of due dates, assignments, and study schedules.
   
4.	Event planners and organizers can use this application to manage event-related tasks, such as setting up venues, contacting vendors, and coordinating schedules.

                                                        PRE-REQUISITE MATERIALS 
a.	Code editor 

b.	Web browser

c.	Downloaded version or CDN link for jQuery.
Note : For this project we have downloaded jQuery and saved in “vendor1” folder.

d.	Downloaded version of Bootstrap to access css and js.
Note : For this project we have downloaded Bootstrap and saved in “vendor” folder.

e.	Downloaded version or CDN version of Popper.js
Note : For this project CDN link for popper.js is used.


                                                          WORKING PRINCIPLE

This project implements a basic task management system using JavaScript and browser local storage to persist user tasks. 
When a user adds a task via a form, the addTask() function is triggered, which collects the form data, serializes it into an object, and stores it in local storage. If there are existing tasks in storage, they are retrieved, appended with the new task, and then the updated task list is stored back in local storage.
The tasks are displayed on the web page by dynamically generating an HTML table through the createHtmlfromStorage() function, which reads the tasks from local storage, formats them into a table row, and inserts them into the table body.

The markAsDone() function allows users to delete tasks by removing them from local storage, while editTask() retrieves a specific task, populates the edit form, and displays it in a modal window for the user to update.
Once updated, the updateTask() function saves the modified task back into local storage and refreshes the task list on the page. 
This creates a full-cycle task management system that maintains state using local storage, ensuring tasks persist across page reloads without needing a server or database.

                                                          OUTPUT


![Screenshot 2024-09-05 124127](https://github.com/user-attachments/assets/8742434a-01f2-4aae-bf4d-78961e362968)


![Screenshot 2024-09-05 124139](https://github.com/user-attachments/assets/34809221-8682-492c-8674-4f2e63227c54)


                                                          
