# Installation Guide — Christophe Study Planner

## 1\. Requirements

Install:

* Flutter SDK
* Visual Studio Code
* Flutter and Dart extensions for VS Code
* Google Chrome for web testing

Official Flutter installation guide: https://docs.flutter.dev/get-started/install

## 2\. Check the environment

Open a terminal and run:

```bash
flutter doctor
```

Follow any setup instructions shown.

## 3\. Get the project

Clone the repository:

bash
git clone <YOUR\\GITHUB\\REPOSITORY\\URL>
cd study\\planner


If the project is already on your computer, open its existing folder in VS Code.

## 4\. Install dependencies

bash
flutter pub get


## 5\. Run the application

bash
flutter run -d chrome


## 6\. Firebase setup status

Firebase Cloud Firestore is planned but has not yet been configured in this project.

When ready, follow the official FlutterFire setup guide:
https://firebase.google.com/docs/flutter/setup

Do not add Firebase configuration files or packages until the Firebase setup has been completed.

## 7\. Useful commands

|Command|Purpose|
|-|-|
|flutter doctor|Check the Flutter environment|
|flutter pub get|Install dependencies|
|flutter run -d chrome|Run the web application|
|flutter analyze|Analyze the Dart code|
|flutter test|Run tests|

## 8\. Troubleshooting

If Flutter is not recognized, check that the Flutter SDK `bin` directory is added to the system PATH.

If dependencies are missing, run:

bash
flutter pub get


If the app does not start, run:

bash
flutter doctor
flutter analyze


Then review the terminal output.

## 9\. Security

Never commit passwords, private keys, service-account JSON files, or other secrets to GitHub. Review files before committing.

