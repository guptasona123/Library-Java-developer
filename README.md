# Library-Java-developer
This project is an Android App which aims to provide a solution to manage a Book Library. Designed for both Users/Students and Library Admins, various operations such as adding/removing/updating books, searching books, issuing/re-issuing/returning books, seeing issued books with due dates, collecting fines, etc. can be performed. The App uses Cloud Firestore as the back-end database for storing details of the Books and Users. Firebase Cloud Messaging is used to send realtime notifications to Users if a return deadline is approaching, his/her fine is increased, or when a new book is added to the Library. Cloud Functions are used to monitor the database in order to update fines and trigger notifications. The App has a user-friendly and interactive interface.

Usage
This App is not live at the moment and won't work off the shelf.

Create a new Firebase Project (with Firestore Database) on Firebase Console and configure it with the App.
Setup a Node.js and Firebase CLI environment to deploy the Cloud Functions.
Setup a cron job to trigger the "updateFine" Function once every day through a HTTPS request.
I would recommend following YouTube Tutorials, Online Guides, and Official Documentation to get help in setting up the Project.
This is where I started: Cloud Firestore Android Tutorial
