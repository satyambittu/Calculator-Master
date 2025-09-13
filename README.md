# ProCalax – A Professional Calculator Suite  
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)  
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)  
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/satyambittu/Calculator-Master/blob/main/LICENSE)  

**ProCalax** is a next-generation calculator application designed to be more than just a basic calculator. Built with **Flutter** and **Dart**, it aims to provide a complete toolkit for students, engineers, finance professionals, and everyday users.  
It delivers speed, accuracy, and flexibility in a clean, modern interface while offering a variety of specialized tools.  

---

## ✨ Key Features

### Core Tools
- **Standard Calculator** – smooth and clutter-free for everyday arithmetic operations  
- **Loan / EMI Calculator** – calculate monthly EMIs, total interest, and repayment schedules instantly  
- **Unit Converters** – fast real-time conversion across multiple categories:  
  - Length (meters, feet, inches, etc.)  
  - Area (sq.m, acres, sq.ft)  
  - Weight (kg, lbs, ounces)  
  - Volume (liters, gallons, cubic meters)  
  - Data Storage (bytes → TB)  
  - Temperature (Celsius, Fahrenheit, Kelvin)  
- **BMI Tracker** – accurate BMI calculation with health classification  

### User-Friendly Features
- 🌗 **Dark & Light Themes** – adaptive theming for day/night use  
- 📝 **Calculation History** – automatically stores past results for easy access  
- 🎯 **Precision Control** – lets you configure decimal accuracy for exact results  
- 📱 **Cross-Platform UI** – runs seamlessly on Android, iOS, and desktop (via Flutter)  

---

## 🚀 Roadmap & Planned Features
- 🌍 **Live Currency Converter** – fetch exchange rates using an API  
- 🔬 **Scientific Calculator** – add trigonometric, logarithmic, and power functions  
- 🌐 **Localization** – multi-language support for wider adoption  
- ⚙️ **Custom Presets** – save frequently used conversions for quicker access  
- ☁️ **Cloud Backup** – sync calculation history across devices  

---

## 🛠️ Technology Stack

- **Framework:** Flutter – chosen for its cross-platform capabilities and rich UI support  
- **Language:** Dart (null-safety enabled) – provides type safety and performance  
- **State Management:** Provider + `setState` for simple yet effective app state control  
- **Local Storage:** SharedPreferences – lightweight solution for saving history & settings  
- **Architecture:** Modular, component-based, ensuring scalability and maintainability  

---

## 📂 Project Layout
```plaintext
lib/
├── main.dart              # App entry point
├── screens/               # Screens & views
│   ├── home_screen.dart   # Main navigation hub
│   ├── calculator/        # Calculator modules
│   ├── converters/        # Unit conversion handlers
│   └── bmi/               # BMI calculation
├── widgets/               # Reusable UI components
├── utils/                 # Helpers & constants
│   ├── calculation.dart   # Core math functions
│   ├── converters/        # Conversion logic
│   └── theme.dart         # Theme configuration
└── models/                # Data models
