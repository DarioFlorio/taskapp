# taskapp
The Task Manager Application is a tool designed to help users organize and manage their tasks efficiently.


Description:
Built with modern web technologies and integrated into a Flutter application, it provides a seamless user experience across various devices. The app allows users to create, edit, and delete tasks, and it categorizes them into pending and completed sections. The tasks are stored locally in the browser's storage, ensuring that the data is persistent across sessions.

Technologies Used:

Flutter: For building the cross-platform mobile application.
WebView: To display the HTML, CSS, and JavaScript content within the Flutter app.
HTML/CSS: For structuring and styling the user interface.
Bootstrap: For responsive design and modern UI components.
Font Awesome: For icons used in the actions column.
JavaScript: For client-side logic and local storage manipulation.
Features:

Task Creation: Users can add new tasks with details such as title, description, start date, start time, end date, end time, and completion status.
Task Editing: Users can edit existing tasks. When editing, the task details are populated in the form, and the submit button changes to "Update Task".
Task Deletion: Users can delete individual tasks.
Task Categorization: Tasks are categorized into "Pending Tasks" and "Completed Tasks" based on their completion status.
Local Storage: Tasks are saved in the browser's local storage, ensuring data persistence.
How It Works:

Form Submission: The user fills out the form and clicks the "Create Task" button. The task details are validated and saved to local storage.
Edit and Update: When the user clicks the edit icon, the task details are loaded into the form. The user can update the details and save them.
Delete: Clicking the delete icon removes the task from the local storage and the table.
Categorization: Tasks are displayed in separate tables based on their completion status.
Examples:

Adding a Task:

Task Name: Learn JavaScript
Description: Complete the JavaScript course on Udemy.
Start Date: 2024-07-13
Start Time: 10:00 AM
End Date: 2024-07-20
End Time: 5:00 PM
Complete: False
Editing a Task:

Click the edit icon next to the task.
Update the details in the form.
Click "Update Task" to save the changes.
Deleting a Task:

Click the delete icon next to the task to remove it from the list.
Viewing Tasks:

Pending tasks and completed tasks are displayed in separate sections for easy management.
