## Forkify

Recipe application to search and upload recipes.

## Project Structure

This project follows the Model-View-Controller (MVC) architectural pattern. MVC is a design pattern commonly used in web development to separate the application logic into three interconnected components:

- **Model:** Responsible for managing the application's data and business logic. It represents the data structure and typically interacts with the database.
- **View:** Responsible for displaying the user interface and presenting the data to the user. It receives input from the user and sends commands to the controller.
- **Controller:** Responsible for handling user inputs, processing requests from the view, and updating the model accordingly. It acts as an intermediary between the model and the view, interpreting the user's actions and updating the view accordingly.

The MVC architecture promotes the separation of concerns, making it easier to manage, maintain, and scale the application.

|
|-- src/
| |-- img/
| |-- js/
| | |-- config.js
| | |-- controller.js
| | |-- helpers.js
| | |-- model.js
| |-- sass
| | |--\_base.scss
| | |--\_components.scss
| | |--\_header.scss
| | |--\_preview.scss
| | |--\_recipe.scss
| | |--\_searchResults.scss
| | |--\_upload.scss
| | |--\_main.scss
|-- .gitignore
|-- .prettier
|-- index.html
|-- package-lock.json
|-- pacckage.json
|\_\_ README.md

## How to use

1. write this command on our terminal: "git clone https://github.com/vache02/Forkify.git"
2. cd <where you stored cloned repo>
3. write another command to install necessary packages: npm install
4. to run project local machine you can write: npm start

## licence

licensed under ISC license
