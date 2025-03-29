# task_manager_app
 
A Flutter-based task management app with Back4App integration, designed as part of MTech assignment in Cross Platform Application Development.
 
## Getting Started
 
To get this project up and running on your local machine for development and testing purposes, follow these simple example steps.
 
### Prerequisites
 
  - Flutter installed on your machine
  - Android SDK or Android Studio installed on your machine
  - An IDE (e.g., Android Studio, VS Code, etc.)
  - An account on Back4App and your unique Application ID and Client Key
 
### Installation
  1. Create a Back4App account via [https://www.back4app.com/]
  2. In Back4App create a class named "tasks" with coloums:
      - title (string)
      - description (string)
      - status (string)
      - userId (pointer) (target: _User)
  3. Edit the class's "Class Level Permission" to allow Read, Write permission for Authenticated user only.
  4. Clone the repository:
          git clone https://github.com/AnkanBhowmick-99/Task_Manager_Application.git
  5. Replace the "X-Parse-Application-Id" and "X-Parse-REST-API-Key" values wtih your backend service's actual, Application ID and REST API key in every header lib/main.dart from Back4App.
  6. Navigate to the project directory
 
         cd task_manager_app
  7. Install dependencies:
 
          flutter pub get
  8. Run the app:
 
         flutter run
 
## Usage
 
Once the app is running on an emulator or device, you can:
 
- Login or Signup
- View all tasks on dashboard
- Add new tasks using the '+' button.
- Click on edit icon to edit a task.
- Use the delete icon to delete items.
 
## License
Free to use
