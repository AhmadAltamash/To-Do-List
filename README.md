# To-Do List App
=================

This is a simple to-do list app that uses IndexedDB to store and retrieve to-do list items locally on the user's device.

## Features
--------

* Add new to-do list items
* Edit existing to-do list items
* Delete to-do list items
* Store to-do list items locally using IndexedDB

## Technologies Used
-------------------

* HTML5
* CSS3
* JavaScript
* SCSS
* IndexedD
## Technical Details

This app uses IndexedDB to store to-do list items locally on the user's device. The app creates a database named "TodoDatabase" with a single object store named "todos". Each to-do list item is stored as an object with a unique ID and a text property.

The app uses the following IndexedDB events:

onsuccess: Fired when the database is opened successfully.
onerror: Fired when an error occurs while opening the database.
onupgradeneeded: Fired when the database needs to be upgraded.
The app also uses the following IndexedDB methods:

transaction(): Creates a new transaction on the database.
objectStore(): Retrieves an object store from the database.
add(): Adds a new object to the object store.
put(): Updates an existing object in the object store.
delete(): Deletes an object from the object store.
getAll(): Retrieves all objects from the object store.

## Demo
-----

You can view a live demo of the app [here](https://your-github-username.github.io/to-do-list-app/)

## Installation
------------

To run the app locally, simply clone the repository and open the `index.html` file in your web browser.

## bash
git clone https://github.com/your-github-username/to-do-list-app.git
cd to-do-list-app
open index.html

## Contributing
Contributions are welcome! If you'd like to contribute to the app, please fork the repository and submit a pull request.

## License
This app is licensed under the MIT License.

## Author
Altamash Ahmad
