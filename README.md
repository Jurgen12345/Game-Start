# **Game Start**

## *Project Description*
  This project is a Steam-like game library application that displays a collection of games stored in a Google Firebase NoSQL database. The available games are shown in a store interface, where users can purchase titles and add them to their personal library.

<p align="center">
  <img src="/app/src/main/res/drawable/final_gamestart_logo.png" width="300">
</p>

## *Technologies Used*

  The application was developed using Android Studio as both the IDE and the platform for building the graphical user interface. XML is used to define and structure the application’s layout and overall design, while Kotlin serves as the primary programming language for interacting with the Firebase NoSQL database, including data retrieval, processing, and integration within the app.
Additionally, Adobe Photoshop was used to design the GameStart application logo.

## *Database Architecture and User Flow*
  The database is composed of two primary objects: a User object and a Game object. The User object stores user-related information such as name, surname, username, password, total games owned, and wishlist data. The Game object contains all relevant information associated with each available game.

During authentication, user credentials are retrieved from the database and validated against the provided username and password. Upon successful login, the user’s library and wishlist are loaded. When a user adds a game to either their library or wishlist, the database is updated accordingly, reflecting the change in the appropriate collection.


Note: The Firebase database used for this project is temporary and may expire. As a result, the application may be unable to authenticate users or retrieve library data once the database is no longer active.
