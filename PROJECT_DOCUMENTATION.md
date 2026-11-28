# Project Documentation — Christophe Study Planner

## 1\. Introduction

Christophe Study Planner is a Flutter application designed to help students organize courses and monitor study progress.

## 2\. Objectives

* Keep study courses organized.
* Record planned study hours.
* Track completed courses.
* Show an overview of study progress.

## 3\. Current features

### Course list

Displays each course name and its planned study hours.

### Add a course

The plus (+) button opens a dialog for entering a course name and planned study hours.

### Complete a course

A checkbox changes the course completion status.

### Delete a course

A delete icon removes a course from the displayed list.

### Progress summary

The dashboard displays total courses, completed courses, remaining courses, and a progress percentage/bar.

## 4\. Technologies

|Technology|Purpose|
|-|-|
|Flutter|Application interface and framework|
|Dart|Application programming language|
|Visual Studio Code|Development environment|
|Firebase Cloud Firestore|Planned cloud database|

## 5\. Current course data structure

The current application uses these fields for a course:

|Field|Meaning|Example|
|-|-|-|
|subject|Course name|Database|
|hours|Planned study hours|3|
|done|Completion status|false|

Example:

dart
{
  'subject': 'Database',
  'hours': 3,
  'done': false,
}


## 6\. Planned Firestore structure

The following is a proposed structure, not a configured database yet:

text
courses (collection)
  courseDocumentId (document)
    subject: "Database"
    hours: 3
    done: false

## 7\. Planned development stages

1. Create a Firebase project.
2. Configure Cloud Firestore.
3. Connect Flutter to Firebase.
4. Create and read course documents.
5. Update course completion status.
6. Delete course documents.
7. Test database operations.

## 8\. Conclusion

The current version provides the basic course-management interface. The next major milestone is integrating Firebase Cloud Firestore for cloud data storage.

