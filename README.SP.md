# Christophe Study Planner

A Flutter application that helps students organize courses, track planned study hours, and monitor learning progress.

## Current features

* Display a list of study courses.
* Add a course with its name and planned hours.
* Mark a course as completed or not completed.
* Delete a course.
* Display total, completed, and remaining course counts.
* Display study progress with a progress bar.

## Technologies

* Flutter
* Dart
* Visual Studio Code
* Firebase Cloud Firestore (planned; not connected yet)

## Run locally

1. Install Flutter and Visual Studio Code.
2. Clone this repository:

bash
git clone <YOUR\_GITHUB\_REPOSITORY\_URL>
   

3. Open the project folder:

bash
cd study\_planner
   

4. Install dependencies:

bash
flutter pub get
  

5. Run the web application:

bash
   flutter run -d chrome
  

## Project status

The current version includes course management, completion tracking, summary counters, and a progress indicator. Firebase Cloud Firestore integration is the next planned development stage. Course data is not yet stored in Firestore.

## Future improvements

* Connect Flutter to Firebase Cloud Firestore.
* Read, create, update, and delete course documents in Firestore.
* Improve validation and error handling.
* Add authentication if required.

## Author

Christophe Ombe

Educational project.

