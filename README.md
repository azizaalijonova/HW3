# HW3
Aziza Alijonova's Third Homework


This Flutter project demonstrates the implementation of a simple mobile application with multiple screens.

## Project Structure

### 1. Screens

- **Home Screen (lib/screens/home_screen.dart):**
  - Displays a welcome message on the home screen.
  - Acts as the initial screen when the app is launched.

- **Screen1 (lib/screens/screen1.dart):**
  Contains various widgets for demonstration purposes and Navigational button to move to Screen2.

- **Screen2 (lib/screens/screen2.dart):**

- **Screen3 (lib/screens/screen3.dart):**

- **Screen4 (lib/screens/screen4.dart):**
All other screens have the same functions

### 2. Main App (lib/main.dart)

- **MyApp:**
  The main entry point of the application. Uses `MaterialApp` to define the app title and initial route. Defines routes for each screen using the `routes` property.

- **Routes:**
  - `'/': HomeScreen()`
  - `'/screen1': Screen1()`
  - `'/screen2': Screen2()`
  - `'/screen3': Screen3()`
  - `'/screen4': Screen4()`
