# 🚀 Task Manager: Manage Your Tasks with Ease! 🔓
-----------------------------------------------

### Tagline: 💪 Efficient Task Management, Simplified! 💪

-----------------------------------------------

### Description

Task Manager is a web-based application built using Java Spring Boot and Maven, designed to help you manage your tasks with ease. With Task Manager, you can create, edit, and delete tasks, set deadlines, and track your progress. Whether you're a student, professional, or simply someone who needs to stay organized, Task Manager is the perfect tool to help you stay on top of your tasks.

Task Manager is a simple and intuitive application that allows you to focus on your tasks, rather than wasting time on complex task management systems. With a clean and user-friendly interface, you can quickly and easily create and manage your tasks, set deadlines, and track your progress.

### Features

1. **Task Management**: Create, edit, and delete tasks, set deadlines, and track your progress.
2. **Task Prioritization**: Easily prioritize your tasks using our drag-and-drop interface.
3. **Task Filtering**: Filter your tasks by date, priority, or status to quickly find the task you need.
4. **Task Tagging**: Tag your tasks with keywords or colors to easily find and filter them.
5. **Task Collaboration**: Invite others to collaborate on your tasks, making it easy to work with team members.
6. **Task Notifications**: Receive notifications when tasks are created, edited, or completed.
7. **Task Export**: Export your tasks in CSV or JSON format for easy import into other applications.
8. **Task Import**: Import tasks from other applications, such as Trello or Asana, into Task Manager.
9. **Customizable**: Customize your Task Manager experience by choosing your own colors, fonts, and layouts.
10. **Security**: Task Manager is secured with end-to-end encryption, ensuring your data is safe and secure.

### Tech Stack

| Frontend | Backend | Tools |
| --- | --- | --- |
| HTML, CSS, JavaScript, Bootstrap | Java, Spring Boot, Spring Security, Maven | Apache Maven, Git, Eclipse |

### Project Structure

* `com.example.taskmanager`:
	+ `model`: Contains the Task entity class, representing a task in the system.
	+ `repository`: Contains the TaskRepository interface, extending JpaRepository, for managing tasks in the database.
	+ `controller`: Contains the TaskController class, responsible for handling HTTP requests and responses.
	+ `application`: Contains the TaskmanagerApplication class, starting the Spring Boot application.
* `index.html`: The main HTML file for the Task Manager web application.
* `pom.xml`: The Maven build file for the project, containing dependencies and configuration settings.
* `TaskmanagerApplicationTests.java`: Unit tests for the TaskmanagerApplication class, testing the application's startup and configuration.
* `TaskRepository.java`: Repository interface for managing tasks in the database.
* `TaskController.java`: Controller class responsible for handling HTTP requests and responses.
* `Task.java`: Entity class representing a task in the system.
* `index.html`: The main HTML file for the Task Manager web application.

### How to Run

1. Clone the project from GitHub using Git.
2. Install the necessary dependencies by running `mvn install` in the project root.
3. Run the application by executing the following command: `mvn spring-boot:run`
4. Access the application by visiting `http://localhost:8080` in your web browser.
5. Log in with the default username and password: `username: admin, password: password`

### Testing Instructions

1. Run the unit tests by executing the following command: `mvn test`
2. Verify that all tests pass successfully.
3. Perform integration testing by using the Task Manager web application and verifying that it functions as expected.

### Screenshots

<img width="601" height="587" alt="Screenshot (647)" src="https://github.com/user-attachments/assets/36776be7-f766-4387-bf2b-bdf14c33ada9" />
<img width="1366" height="440" alt="Screenshot (648)" src="https://github.com/user-attachments/assets/d270e7b8-ea1c-4efa-bf6c-de7e29d043b8" />

### Author

Udheja Faizan

### License

[Apache-2.0 License](https://opensource.org/licenses/Apache-2.0)
