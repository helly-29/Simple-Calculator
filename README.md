# Flutter Calculator App – Helly Leuva

A simple and user-friendly calculator app built using Flutter. This application performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

##  Features

* Input two numbers
* Perform basic arithmetic operations:

  * Addition (+)
  * Subtraction (-)
  * Multiplication (*)
  * Division (/)
* Handles invalid inputs safely
* Prevents division by zero
* Clean and responsive UI

##  Getting Started

### Prerequisites

Make sure you have installed:

* Flutter SDK
* Dart
* Android Studio or Visual Studio Code
* Emulator or physical device

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/flutter-calculator-app.git
   ```

2. Navigate to the project folder:

   ```bash
   cd flutter-calculator-app
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:

   ```bash
   flutter run
   ```

##  Project Structure

```id="proj123"
lib/
 └── main.dart   # Main file containing calculator logic and UI
```

##  How It Works

* Uses `TextEditingController` to capture user input
* Converts input strings into numbers using `double.tryParse()`
* Performs operations based on button clicks
* Updates result dynamically using `setState()`

##  UI Components

* **TextFields** for number input
* **ElevatedButtons** for operations
* **Text Widget** to display result
* **Wrap Widget** for responsive button layout

##  Notes

* If invalid input is entered, it defaults to `0`
* Division by zero returns `0` to avoid crashes

##  Future Improvements

* Add advanced operations (%, square root, power)
* Improve UI with modern design
* Add input validation messages
* Support dark mode
* Convert into scientific calculator

##  Author

**Helly Leuva**

##  License

This project is open-source and available under the MIT License.
