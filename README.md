# 📝 Notes App (Room Database)

**Notes App** is a simple, fast, and offline-first Android application built to help users create, manage, and organize their daily notes efficiently. The app uses **Room Database** to store data locally, ensuring reliability, speed, and full offline support.

---

## 🚀 Features

* ✍️ Create new notes
* 📝 Edit existing notes
* 🗑️ Delete notes
* 🔍 View all saved notes
* 💾 Offline storage using Room Database
* ⚡ Fast & lightweight performance
* 🎨 Simple and clean UI

---

## 🛠 Tech Stack

* **Language:** Kotlin
* **Database:** Room Database
* **Architecture:** MVVM
* **UI:** XML + Material Design
* **Minimum SDK:** Android 6.0 (API 23)

---

## 🧠 Architecture Overview

The app follows **MVVM (Model–View–ViewModel)** architecture:

* **Entity** – Defines the Notes table
* **DAO** – Handles database operations
* **Database** – Room database instance
* **ViewModel** – Manages UI-related data
* **Repository** – Acts as a data mediator

---

## 📂 Project Structure

```
notes_app
 ├── data
 │    ├── entity
 │    ├── dao
 │    └── database
 ├── repository
 ├── viewmodel
 └── ui
```

---

## 🔐 Permissions

This app does **NOT** require any special permissions.

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/muhammadawaisnoul/NotesApp.git
   ```
2. Open the project in **Android Studio**
3. Sync Gradle files
4. Run the app on an emulator or real device

---

## 🎯 Use Cases

* Daily personal notes
* Study notes for students
* Quick reminders
* Offline note-taking

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repository
* Create a feature branch
* Commit your changes
* Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Author

**Awais**
Android App Developer

If you find this project useful, don’t forget to ⭐ star the repository!

---

## 📬 Feedback

For bugs, suggestions, or improvements, please open an issue on GitHub.

Happy Coding! 🚀
