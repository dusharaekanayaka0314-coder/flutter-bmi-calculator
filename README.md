# 📱 BMI Calculator (Flutter)

A simple and clean BMI Calculator mobile app built with **Flutter** and **Dart**. Enter your height and weight, and the app shows your BMI and your weight category instantly.

I built this project while completing the **Introduction to Flutter** course on Simplilearn.

## 📸 Screenshot

! <img width="600" height="747" alt="image" src="https://github.com/user-attachments/assets/2db0d657-d533-48cc-989b-8fc5e36c466c" />
! <img width="597" height="753" alt="image" src="https://github.com/user-attachments/assets/bf8fdd86-a95b-4a7a-a43c-2b4f91a6adb4" />


## ✨ Features

- Enter height in **cm** and weight in **kg**
- Calculates BMI instantly
- Shows the category: Underweight, Normal weight, Overweight or Obese
- Clean result card with the BMI value
- Clear button to reset the inputs
- BMI category guide at the bottom of the screen
- Scrollable, responsive layout

## 📊 BMI Categories

| BMI Range | Category |
|-----------|----------|
| Below 18.5 | Underweight |
| 18.5 - 24.9 | Normal weight |
| 25 - 29.9 | Overweight |
| 30 or above | Obese |

## 🧮 Formula

```
BMI = weight (kg) / (height (m) × height (m))
```

The app converts height from cm to metres first, then applies the formula.

## 🛠️ Built With

- [Flutter](https://flutter.dev/)
- [Dart](https://dart.dev/)
- Material Design widgets

## 📚 What I Learned

- Building UI with `Scaffold`, `Column`, `TextField` and `Container`
- Managing state with `StatefulWidget` and `setState()`
- Using `TextEditingController` to read user input
- Loading local images using assets
- Styling widgets with `InputDecoration` and `BoxDecoration`

## 🚀 How to Run

1. Make sure Flutter is installed. Check with:
```
   flutter --version
```
2. Clone this repository:
```
   git clone https://github.com/YOUR_USERNAME/flutter-bmi-calculator.git
```
3. Go to the project folder:
```
   cd flutter-bmi-calculator
```
4. Get the packages:
```
   flutter pub get
```
5. Run the app:
```
   flutter run
```

## 📁 Project Structure

```
flutter-bmi-calculator/
├── lib/
│   └── main.dart          # App code
├── assets/
│   └── images/
│       └── bmi.png        # App image
├── screenshots/
│   └── app.png            # README screenshot
└── pubspec.yaml
```

## 🔮 Future Improvements

- Input validation for empty or invalid values
- Support for pounds and feet/inches
- Dark mode
- BMI history

## 👨‍💻 Author

**Your Name**
- GitHub:https://github.com/dusharaekanayaka0314-coder/flutter-bmi-calculator.git
- LinkedIn:www.linkedin.com/in/dushara-ekanayaka-42a6a927a

---

⭐ If you like this project, give it a star!
