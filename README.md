# Note Taker (powered by Express.js)
Week-11 Challenge

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

 * [Description](#description)

 * [Live-Screen-Recording-of-Application-Functionality](#live-screen-recording-of-application-functionality)

 * [Screenshots](#screenshots)

 * [Technologies-Used](#technologies-used)

 * [Installation](#installation)

 * [Features](#features)

 * [Usage-Information](#usage-information)

 * [Contribution-Guidelines](#contribution-guidelines)

 * [Test-Instructions](#test-instructions)

 * [License](#license)

* [Questions](#questions)

## Description

This application was designed to give users a place to store notes to help them organize their thoughts and to keep track of tasks they need to complete. It is powered by Express and JavaScript and implements an imitation database using a json file (db.json) to save and retrieve data. I was responsible for connecting the backend and frontend of this application through the use of GET, POST, and DELETE requests within Express which allows users to save, retrieve, post new data, and delete data from the application by use of the front end user interface (UI). I utilized an application called Insomnia to test GET, POST, and DELETE routes. This allowed me to test my routes without needing a user interface (UI) and cut down on testing time; it is definitely a very very useful application when implementing backend development. As I just stated, it allowed for me to see what my routes were sending, returning, and deleting without needing an index.html file and a linked script.js file.  Through building this application, I learned some basic functionality of what Express can do and how powerful this framework can be when large scale databases interacting with APIs to send and retrieve data to one another. I also did experience some strange errors when building out the application, which I believe had to do with whats called a raise condition and concurrency issues. Future development of this application would definitely aim to further evaluate how to avoid creating raise issues within the routing, creating a routes folder for further file organization-keeping the server.js file less cluttered, and potentially implementing the use of an actual database to save, post, and delete data from (would use MySQL).

## Live Screen Recording of Application Functionality

https://youtu.be/RXhZbAIlBsU

## Screenshots

![Screenshot1-week-11-challenge]![/Users/johnabizmo/bootcamp/challenge-11/Assets/Pictures/Screen Shot 2024-01-11 at 10.22.39 PM.png
](<Assets/Pictures/Screen Shot 2024-01-11 at 10.22.39 PM.png>)
![Screenshot2-week-11-challenge]![/Users/johnabizmo/bootcamp/challenge-11/Assets/Pictures/Screen Shot 2024-01-11 at 10.23.16 PM.png](<Assets/Pictures/Screen Shot 2024-01-11 at 10.23.16 PM.png>)

![Screenshot3-week-11-challenge]![/Users/johnabizmo/bootcamp/challenge-11/Assets/Pictures/Screen Shot 2024-01-11 at 10.23.54 PM.png
](<Assets/Pictures/Screen Shot 2024-01-11 at 10.23.54 PM.png>)
![Screenshot4-week-11-challenge]![/Users/johnabizmo/bootcamp/challenge-11/Assets/Pictures/Screen Shot 2024-01-11 at 10.24.17 PM.png](<Assets/Pictures/Screen Shot 2024-01-11 at 10.24.17 PM.png>)

## Technologies Used

This project is powered by Express.js, Node.js, and JavaScript. It utilizes uniqid (node package manager), and file system module (node package manager) as dependencies, and utilized an application called Insomnia to test GET, POST, and DELETE request routes without needing a front end framework built out.

## Installation

1. Clone the repo:
   git clone https://github.com/johnlott1/challenge-11.git

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js. If you have homebrew this may vary and the documentation should be consulted.

4. Once node.js is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install express and uniqid directly from the command line, to do so the command for express will be npm i express to install the latests version of Express framework globally so that it can be used within the node terminal, and npm i uniqid to install the latest version of uniqid).

6. To run the server, within the terminal, type the command npm start or node server.js.

7. Once the server is running, users can then access the front end of the application within the browser to observe full functionality of the site.

## Features

Features of this application include the users ability to retrieve and save notes from/to a mock database.json file which will persist on page load unless deleted.  

## Usage Information

This application is powered by Express meaning for it to function properly, there needs to be a server running in the background. To start the server, navigate to the directory of the application, install all dependencies (npm i), then type the command npm start (or node index.js). A message should then display in the command line saying "App listening at http://localhost:3001 🚀". Once the server is running, then navigate to the front end of the application directly from the command line by holding command and clicking the link http://localhost:3001. From there, users can pull up any existing notes saved to the database or create new notes, which once saved will be pushed to the database and persisted.

## License

NOTICE: This application is covered under the MIT License

## Questions

Have additional questions? Click the links below to reach me through my GitHub account.

[Link to Github](https://github.com/johnlott1)

