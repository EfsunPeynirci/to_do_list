# 📝 To-Do List Application

## 🌟 Overview
This is a simple and user-friendly To-Do List application developed using Flutter. It allows users to:
- Add tasks to their list
- Mark tasks as completed
- Delete tasks

The application is designed to help you stay organized and keep track of your daily activities effortlessly.

---

## 🛠️ Technologies Used
- **Flutter**: Frontend framework
- **Dart**: Programming language
- **Provider**: State management

---

## 🚀 Features

### ➕ Add a Task
- Tap the **+** button in the bottom-right corner to add a new task.
- Enter the task description in the pop-up input field.
- Press **Add** to save the task.

### ✅ Mark a Task as Completed
- Tap the checkbox next to a task to mark it as completed.
- Completed tasks will have a strikethrough effect.

### 🗑️ Delete a Task
- Long press on a task to delete it from the list.

---

## 📸 Screenshots
### Home Screen

![to_do_list-0](https://github.com/user-attachments/assets/260847a9-1add-4c0d-a2e9-0ca57c6c8613)

### Add Task Screen

![to_do_list-2](https://github.com/user-attachments/assets/0437b7a8-7a5f-464d-bce3-66fcc50c5c74)

![to_do_list-3](https://github.com/user-attachments/assets/50341bb1-d9d8-4c1e-a277-5731dcec8f70)

### Marking a Task as Done

![to_do_list-1](https://github.com/user-attachments/assets/ee58f6ba-d83e-4913-8510-e027d2af50e6)

---

## 🎥 Demo Video

https://github.com/user-attachments/assets/77048c4f-07fc-415d-9725-4ebbc5df98dd

---

## 📂 Project Structure
```plaintext
lib
├── main.dart                # Entry point of the application
├── models
│   ├── task.dart            # Task model
│   └── task_data.dart       # Task management logic
├── screens
│   ├── tasks_screen.dart    # Main screen of the application, displaying the list of tasks
│   └── add_task_screen.dart # Screen for adding new tasks
└── widgets
    ├── tasks_list.dart      # Widget for rendering the list of tasks using a ListView
    └── task_tile.dart       # Widget for rendering individual tasks, including checkbox and delete functionality.
```

---

## 📦 Dependencies Used

### 🛠 Provider
- **State Management**: Used to manage the state of tasks efficiently across the application.
- **Features**:
  - `ChangeNotifier`: Notifies listeners of state changes.
  - `Provider.of`: Accesses data from the provider.
  - `Consumer`: Automatically rebuilds widgets when data changes.

### 🎨 Material Design
- **UI Framework**: Provides the building blocks for creating responsive and beautiful UIs.
- **Widgets Used**:
  - `Scaffold`: Provides a layout structure for the app.
  - `ListTile`: Displays tasks with customizable title and trailing components.
  - `FloatingActionButton`: Adds a circular button for task creation.

### 📱 Flutter Widgets
- **Key Components**:
  - `ListView.builder`: Dynamically generates a scrollable list of tasks.
  - `TextField`: Accepts user input for new tasks.
  - `TextButton`: Provides an actionable button for saving tasks.
  - `ModalBottomSheet`: Displays a bottom sheet for task input.

---

## 🙏 Acknowledgments
Special thanks to Dr. Angela Yu for her comprehensive course, [The Complete Flutter Development Bootcamp with Dart](https://www.udemy.com/course/flutter-bootcamp-with-dart/), on Udemy. This project was developed as part of her amazing lessons, and her guidance has been invaluable in building this application.
