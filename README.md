# CS360
MOBILE ARCHETICURE

# CS 360 – Study Planner Mobile Application

## Project Overview

The Study Planner application was developed to help students organize and manage their academic assignments in one convenient mobile application. The main goal was to create an application that allows users to create an account, securely log in, add assignments, view their assignments, update assignment information, and delete assignments when they are no longer needed. The application also includes optional SMS reminders to help users stay aware of upcoming assignments.

The application was designed around the needs of students who may have multiple assignments, courses, and due dates to manage. Instead of relying on separate notes or reminders, the Study Planner provides a centralized location where students can keep track of their academic responsibilities.

## User-Centered Design

Several screens and features were necessary to support the user's needs. The application includes a login screen, account creation functionality, a main dashboard, assignment creation and management features, and SMS notification settings.

The login and account creation screens allow users to access their own information while keeping the experience straightforward. The main dashboard was designed to give users a clear view of their assignments without requiring them to navigate through multiple screens. Assignment management allows users to create, read, update, and delete assignments based on changes to their academic workload.

The UI was designed with simplicity and ease of navigation in mind. I tried to keep controls clearly labeled and organized so that users could understand what each feature was intended to do. The design was successful because the interface focuses on the primary purpose of the application—helping students manage their assignments—without adding unnecessary features or complicated navigation.

## App Development Approach

I approached the coding process by developing the application in smaller sections and testing each feature as I progressed. I started with the UI design created during Project Two and then used that design as the foundation for implementing the application's functionality in Android Studio.

I separated responsibilities between different parts of the application instead of putting all of the functionality into one class. For example, the SQLite database functionality is handled separately from the activities responsible for displaying the user interface. This made it easier to manage the application and troubleshoot problems.

I also used consistent naming conventions and comments throughout the code to make the application easier to understand. When implementing new functionality, I tested it before moving on to another part of the application. This approach helped me identify problems earlier instead of having to troubleshoot the entire application at the end.

These strategies can be applied to future projects by continuing to break larger applications into smaller components, testing frequently, and keeping code organized. Developing features incrementally also makes it easier to identify where an error originated.

## Testing and Functionality

Testing was an important part of developing the Study Planner application. I used the Android Studio Emulator to test the application's functionality throughout development. I tested account creation and login to verify that users could create accounts and access the application with their credentials.

I also tested the SQLite database functionality by creating, viewing, updating, and deleting assignments. Testing was performed to make sure that information remained available after closing and reopening the application, which confirmed that the database was persistent.

The SMS notification feature was tested with the Android permission system. I tested the application when SMS permission was granted and verified that the application could send the configured reminder. I also tested what happened when SMS permission was denied to make sure that the rest of the application continued functioning without the SMS feature.

Testing revealed issues such as layout and code organization errors during development. These problems were corrected before finalizing the application. This process was important because an application can appear complete from a UI perspective while still having problems with its underlying functionality. Repeated testing helped ensure that the final application worked as intended.

## Innovation and Problem Solving

One of the challenges during development was connecting the original UI design to the functional application. The UI created during Project Two provided the foundation, but additional code and database functionality were required to turn the design into a working application.

I had to troubleshoot issues involving the Android layout, database operations, user authentication, and SMS permissions. Rather than changing the entire application when an issue occurred, I worked through the problem and tested the affected feature individually.

The SMS permission system was another area where problem solving was important. The application needed to account for both situations where a user grants permission and where a user denies permission. I designed the application so that denying SMS permission would not prevent the user from using the rest of the Study Planner. This allowed the application to respect the user's decision while maintaining the core functionality.

## Successful Component

The component I believe best demonstrates my knowledge, skills, and experience is the application's database and assignment management functionality. The application uses SQLite to provide persistent storage and supports the full CRUD process: creating, reading, updating, and deleting assignment records.

This component required me to connect the user interface to the database and make sure that changes made by the user were correctly stored and displayed. It also required consideration of user-specific information so that the application could maintain the appropriate data for the logged-in user.

I was also successful in implementing the SMS notification functionality because it required both Android permissions and application logic. Testing both permission outcomes helped demonstrate that the application could provide an additional feature while still allowing users to use the core application if they chose not to grant permission.

## Conclusion

Developing the Study Planner gave me experience with the complete mobile application development process, from initial UI design through functional coding, database implementation, testing, and preparation for launch. The project allowed me to apply user-centered design principles while also developing practical programming skills.

The completed application demonstrates my ability to create a functional Android application, work with persistent data, implement authentication and CRUD functionality, handle Android permissions, and test an application using the Android Emulator. The development process also showed me the importance of planning, incremental development, troubleshooting, and testing throughout the entire application lifecycle.
