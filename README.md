# 📚 Learning Hub - Mathematics Learning App

## 📖 Overview

**Learning Hub** is an interactive Android application designed to help children and beginners learn basic mathematical operations easily and effectively. The app provides comprehensive guides, practice exercises, quizzes, and progress tracking to make learning mathematics fun and engaging.

## ✨ Features

### 📱 Main Sections
|---------------------------------------------------------------------------------------------------------|
|          Section           |                             Description                                    |
|----------------------------|----------------------------------------------------------------------------|
| ➕ **Addition**            | Step-by-step guide with examples (single & two-digit, with/without carry)  |
| ➖ **Subtraction**         | Learn borrowing techniques with practical examples                         |
| ✖️ **Multiplication**      | Complete guide with times tables (1-20)                                    |
| ➗ **Division**            | Learn division concepts with/without remainders                            |
| 🔢 **BODMAS**              | Master the order of operations                                             |
| 📊 **Tables**              | Interactive multiplication tables with custom number generator             |
| 🧮 **2-Digit Calculator**  | Practice operations with 2-digit numbers                                   |
| 📝 **Quizzes**             | 20 mixed questions covering all operations                                 |
| 📈 **My Progress**         | Track performance with statistics and history                              |
|---------------------------------------------------------------------------------------------------------|

### 🎯 Key Features

- ✅ Interactive UI - User-friendly, colorful interface designed for kids
- ✅ Step-by-Step Guides - Detailed explanations with examples
- ✅ Practice Problems - Each section includes practice questions with answers
- ✅ Custom Table Generator - Generate multiplication tables for any number
- ✅ 20-Question Quiz - Mixed operations quiz with instant scoring
- ✅ Progress Tracking - SQLite database stores all quiz attempts
- ✅ Performance Analytics - View statistics, charts, and grade history
- ✅ Visual Progress Charts - Bar charts showing score progression
- ✅ Grade System - A+ to F grading based on performance

## 🛠️ Tech Stack

Language: Java
UI Framework: XML with Material Design
Database: SQLite (Local storage)
Architecture: MVC (Model-View-Controller)
Minimum SDK: Android 7.0 (API 24)

### Dependencies

implementation 'androidx.appcompat:appcompat:1.6.1'
implementation 'com.google.android.material:material:1.10.0'
implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
implementation 'androidx.cardview:cardview:1.0.0'

## 🚀 Installation

### Prerequisites

- Android Studio Hedgehog or later
- JDK 8 or later
- Android SDK with API 24+

### Steps to Run

1. Clone the repository
2. Open in Android Studio
3. Sync Gradle dependencies
4. Run the app on device or emulator

### APK Installation

1. Build APK: Build → Build Bundle(s)/APK(s) → Build APK(s)
2. Transfer APK to Android device
3. Enable "Install from Unknown Sources" in settings
4. Tap the APK to install

## 📊 Database Schema

### Quiz Results Table
|------------------------------------------------|
|   Column   |   Type   |      Description       |
|------------|----------|------------------------|
| id         | INTEGER  | Primary key            |
| date       | TEXT     | Date & time of attempt |
| score      | INTEGER  | Score achieved         |
| total      | INTEGER  | Total questions (20)   |
| percentage | REAL     | Percentage score       |
|------------------------------------------------|

### Quiz Attempts Table
|------------------------------------------------------|
|     Column     |  Type   |        Description        |
|----------------|---------|---------------------------|
| id             | INTEGER | Primary key               |
| date           | TEXT    | Date & time of attempt    |
| attempt_number | INTEGER | Sequential attempt number |
| score          | INTEGER | Score achieved            |
| total          | INTEGER | Total questions (20)      |
| percentage     | REAL    | Percentage score          |
| answers        | TEXT    | Answers summary (✓/✗)    |
|------------------------------------------------------|

## 🎮 How to Use

### For Students

1. Learn Concepts - Start with Addition, Subtraction, Multiplication, or Division guides
2. Understand Rules - Study BODMAS for complex calculations
3. Practice Tables - Use the Tables section to memorize multiplication
4. Use Calculator - Practice 2-digit operations
5. Take Quiz - Test your knowledge with 20 questions
6. Track Progress - Check your performance in the Progress section

### For Teachers/Parents

- Monitor progress through the statistics dashboard
- Check quiz history with dates and scores
- Identify weak areas through performance charts
- Encourage repeated attempts for improvement

## 🎯 Quiz Grading System
|----------------------------------------|
| Percentage | Grade | Performance Level |
|------------|-------|-------------------|
| 90-100%    | A+    | Excellent         |
| 80-89%     | A     | Very Good         |
| 70-79%     | B     | Good              |
| 60-69%     | C     | Fair              |
| 50-59%     | D     | Pass              |
| Below 50%  | F     | Need Improvement  |
|----------------------------------------|

## 👥 Developers
|---------------------------------------------------------------------------------------------|
|             Name              |     Role      |                  Contact                    |
|-------------------------------|---------------|---------------------------------------------|
| Syed Muhammad Sajawal Hussain | Developer-1   | 0328-0841432 / bsitf23e110766@gcbskp.edu.pk |
| Usama Ashraf                  | Developer-2   | 0319-9272955 / bsitf23e110769@gcbskp.edu.pk |
|---------------------------------------------------------------------------------------------|

## 📞 Support

Contact-1: 0328-0841432
Contact-2: 0319-9272955
Email-1: bsitf23e110766@gcbskp.edu.pk
Email-2: bsitf23e110769@gcbskp.edu.pk

## 📄 License

This project is developed for educational purposes. All rights reserved.

## 📱 Minimum Requirements

- Operating System: Android 7.0 (Nougat) or higher
- RAM: 2GB minimum
- Storage: 50MB free space
- Internet: Not required (offline app)

---

Made with ❤️ for young learners

"Making mathematics fun and easy for everyone"
