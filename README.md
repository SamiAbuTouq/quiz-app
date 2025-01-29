# Quiz App

## Overview
The Quiz App is a Flutter-based application designed to provide an engaging and interactive way for users to test their knowledge on various topics. Users are presented with multiple-choice questions, can select their answers, and receive instant feedback. At the end of the quiz, a summary of their performance is displayed, helping them review their answers.

This app is built with modular and scalable architecture, making it easy to customize and expand.

## Features
- Interactive quiz interface
- Tracks user answers
- Displays results with a summary
- Modular and scalable code structure
- User-friendly UI
- Dynamic question loading

## Project Structure
```
lib/
├── main.dart                    # Entry point of the application
├── quiz.dart                    # Core quiz widget
├── start_screen.dart            # Initial screen of the quiz
├── questions_screen.dart        # Displays quiz questions
├── results_screen.dart          # Shows quiz results
│
├── data/
│   ├── questions.dart           # Contains quiz questions
│
├── models/
│   ├── quiz_question.dart       # Model for a quiz question
│
├── questions_summary/
│   ├── questions_summary.dart   # Summary of user answers
│   ├── question_identifier.dart # Identifies question numbers
│   ├── summary_item.dart        # Represents a summary item
│
├── widgets/
│   ├── answer_button.dart       # Custom button for answers
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/quiz-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd quiz-app
   ```
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run the application:
   ```sh
   flutter run
   ```

## Requirements
- Flutter SDK
- Dart SDK
- Compatible IDE (VS Code, Android Studio, etc.)

## Contributing
1. Fork the repository.
2. Create a new branch (`feature-xyz`).
3. Commit your changes.
4. Push to your branch and submit a pull request.

## License
This project is licensed under the MIT License.

