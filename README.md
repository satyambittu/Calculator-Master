# ProCalax – A Professional Calculator Suite  
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)  
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)  
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/satyambittu/Calculator-Master/blob/main/LICENSE)  

**ProCalax** is a versatile calculator app built with Flutter and Dart, crafted for students, professionals, and anyone who needs quick and reliable calculations. It blends an easy-to-use interface with advanced utilities, delivering both everyday and specialized calculation features.  

---

## ✨ Highlights

### Core Tools
- **Standard Calculator** – clean UI for quick arithmetic operations  
- **Loan / EMI Calculator** – compute installments, interest, and repayment timelines  
- **Unit Converters** – real-time conversion across:  
  - Length, Area, Weight, Volume  
  - Data Storage (B/KB/MB/GB/TB)  
  - Temperature (°C, °F, Kelvin)  
- **BMI Tracker** – body mass index calculator with health categorization  

### User-Friendly Features
- 🌗 **Dark & Light Themes** – adaptive design for better usability  
- 📝 **History Log** – stores previous calculations with options to manage them  
- 🎯 **Accuracy Control** – configure decimal precision  
- 📱 **Responsive Layout** – optimized for phones and tablets  

---

## 🚀 Roadmap Features
- Currency converter with live exchange rates (API based)  
- Scientific calculator functionality  
- Multi-language support  
- Customizable unit presets  

---

## 🛠️ Tech Stack
- **Framework:** Flutter  
- **Language:** Dart (null safety enabled)  
- **State Management:** Provider with `setState`  
- **Storage:** SharedPreferences for persistence  
- **Architecture:** Modular and reusable components  

---

## 📂 Project Layout
```plaintext
lib/
├── main.dart              # App entry point
├── screens/               # Screens & views
│   ├── home_screen.dart   # Navigation hub
│   ├── calculator/        # Core calculator modules
│   ├── converters/        # Unit conversion modules
│   └── bmi/               # BMI calculator
├── widgets/               # Reusable UI components
├── utils/                 # Helpers & constants
│   ├── calculation.dart   # Math functions
│   ├── converters/        # Conversion logic
│   └── theme.dart         # Theme settings
└── models/                # Data models
