## Flutter Interview App

You are required to follow the instructions stated below in order to successfully complete the flutter coding interview

##### **Instructions**

* Fork this repository
* Git clone the forked repository and create a new branch named as your name
* Complete the tasks mentioned below and merge your branch with the parent branch

#### What to Do

In this test you are supposed to develop <span class="colour" style="color: rgb(235, 235, 235);">a simple note taking app using Firebase Auth and Cloud Firestore.</span>

#### Task 1

Create a basic UI for the app

* Add 2 textfield for email and password respctively and a button on both LoginScreen.dart and RegisterScreen.dart
* Add a listview to display users notes and a FloatingActionButton on the HomeScren.dart
* Add a multi-line textfield in AddNoteScreen.dart and a save button
* Use Form widget and do proper validation for all textfields

#### **Task 2**

Create a firebase project and connect it with the app. Do neccessary changes for adding Firebase Auth and Cloud Firestore too - Use the documentation [Add Firebase to your Flutter app](https://firebase.google.com/docs/flutter/setup?platform=android)

* Use the UI created on task 1 and implement a login and register system using firebase [ Email authentication only ]

#### **Task 3**

* After the user logs in redirect the user to HomeScreen.dart when login details are correct else show a snackbar with login error message
* On the press of the Floating Action Button in the HomeScreen open a Bottomsheet which includes a multi-line textfield and a save button

#### **Task 4**

* Store the data entered in the multi-lined text field to the Cloud Firestore when the user clicks the save button
* After the data has been stored sucessfully close the bottomsheet

#### **Task 5**

* View a list of all notes entries, sorted by most recent date on the HomeScreen
* The list in the homescreen should update in realtime when the data changes on Firestore

#### Bonus features (Optional )

Some bonus features that you can add in the app is ability to edit/delete exisiting notes entries in the firestore

#### Notes:

* Feel free to use any flutter plugins you want.
* Highly recommended to use a state management libraries like Providers, Bloc, Get etc.
* If some instructions appears to be vague or lak sufficient details, make assumpions based on your own judgment.