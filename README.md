# Health-and-fitness-tracker-application
A desktop-based **Health & Fitness Tracker** built using **C++ and Qt Framework** as part of an Object-Oriented Programming (OOP) project.
This application helps users track workouts, monitor calorie burn, calculate BMI, and follow basic diet guidance — all in a clean, interactive UI.

---

## 📌 Features

### 👤 User Management

* Create a new profile (signup)
* Login with existing credentials
* Persistent data storage using local files
* Tracks:

  * Days completed
  * Total calories burned
  * Workout history

---

### 🏋️ Workout Tracker

* Predefined exercises:

  * Cardio (Jumping Jacks, Running, Burpees)
  * Strength (Squats)
* Mark exercises as completed
* Real-time progress bar
* Daily calorie tracking
* End-of-day summary saved automatically

---

### 📊 Progress History

* View calories burned per day
* Tracks long-term fitness progress

---

### ⚖️ BMI Calculator

* Input:

  * Weight (kg)
  * Height (m)
* Outputs:

  * BMI value
  * Health status:

    * Underweight
    * Healthy
    * Overweight
    * Obese
  * Ideal weight range

---

### 🥗 Diet Guidance

Includes categorized nutrition tips:

* Proteins
* Carbohydrates
* Fruits & Vegetables
* Hydration
* Foods to Avoid

---

## 🧠 OOP Concepts Used

This project demonstrates strong use of Object-Oriented Programming:

* **Encapsulation**

  * `User` class manages all user data securely

* **Inheritance**

  * `Exercise` → `CardioExercise`, `StrengthExercise`
  * `FoodCategory` → multiple diet categories

* **Polymorphism**

  * Virtual functions like `getLabel()` and `content()`

* **Abstraction**

  * Abstract base classes (`Exercise`, `FoodCategory`)

---

## 🛠️ Technologies Used

* **C++**
* **Qt Framework (Qt Widgets)**
* File Handling (`QFile`, `QTextStream`)
* UI Components:

  * `QStackedWidget`
  * `QVBoxLayout`, `QHBoxLayout`
  * `QProgressBar`
  * `QScrollArea`

---

## 📂 Project Structure

```
├── main.cpp
├── users/           # Auto-created folder for storing user data
│   └── <username>.txt
```

---

## 💾 Data Storage

* Each user has a separate file:

  ```
  users/<username>.txt
  ```
* Stores:

  * Username & password
  * Current day
  * Total calories
  * Daily history

---

## ▶️ How to Run

1. Install Qt (Qt Creator recommended)
2. Open the project in Qt Creator
3. Build the project
4. Run the application

---

## 🚀 Future Improvements

* Add custom exercises
* Graphical progress charts
* Dark/light theme toggle
* Cloud-based data storage
* Mobile version (Qt/QML)

---

## 👨‍💻 Authors

* OOP Project by students
  (Add your names here)

---

## 📜 License

This project is for educational purposes.

---

## 🎯 Summary

This application is a complete beginner-to-intermediate level OOP project that combines:

* GUI development
* File handling
* Object-oriented design

It provides a practical and user-friendly way to manage fitness routines and health metrics.

---
