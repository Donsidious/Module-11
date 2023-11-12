# Note Taker (powered by Express.js)
Week-11 Challenge

## Table of Contents

 * [Description](#description)

 * [Live-URL-of-Deployed-Application](#live-url-of-deployed-application)

 * [Live-Screen-Recording-of-Application-Functionality](#live-screen-recording-of-application-functionality)

 * [Technologies-Used](#technologies-used)

 * [Installation](#installation)

 * [Features](#features)

 * [Usage-Information](#usage-information)

 * [License](#license)

## Description

This application was created with the intention of providing users with a platform to organize their thoughts and manage tasks by storing notes. It is powered by Express and JavaScript, utilizing a json file (db.json) as a pseudo-database to store and retrieve data. My responsibilities included bridging the backend and frontend of the application through the implementation of GET, POST, and DELETE requests in Express, enabling users to interact with the application's frontend user interface (UI) for data storage, retrieval, posting, and deletion. I leveraged the Insomnia application for efficient testing of these routes, streamlining the development process by eliminating the need for a separate index.html and script.js file. During this project, I gained valuable insights into Express's capabilities, particularly its potential for large-scale databases and API interactions. I also encountered challenges related to race conditions and concurrency issues, which would be addressed in future development through improved route organization, such as creating a dedicated routes folder, and potentially transitioning to an actual database like MySQL for data storage and management.

## Live URL of Deployed Application

## Live Screen Recording of Application Functionality

https://drive.google.com/file/d/1eP3xAYPPrOuyl6HCNGf9dw09ItOKDHRU/view

## Technologies Used

This project is driven by Express.js, Node.js (v16.19.1), and JavaScript. It relies on uniqid (Node package manager) and the file system module (Node package manager) as essential dependencies. Additionally, testing of GET, POST, and DELETE request routes was facilitated using the Insomnia application, eliminating the need for a pre-built frontend framework during the testing phase.

## Installation

1. Start by cloning the repository using the following command:
   ```
   git clone https://github.com/Donsidious/Module-11
   ```

2. Open the project in Visual Studio Code (VS Code). If you don't have VS Code installed, you'll need to download and install it.

3. In your terminal, install Node.js version 16. If you're using Homebrew, you can run the following command (brew install node@16), but please consult the documentation for other installation methods.

4. Once Node.js version 16 is installed, initialize a package.json file for your project by running the following command in the terminal:
   ```
   npm init -y
   ```

5. Next, install the dependencies required for this application. Developers may need to install Express and Uniqid directly from the command line. To do so, you can use the following commands:
   ```
   npm i express
   npm i uniqid
   ```

6. To start the server, simply type the following command in the terminal:
   ```
   npm start
   ```
   Alternatively, you can use:
   ```
   node server.js
   ```

7. Once the server is up and running, you can access the application's frontend through your web browser to explore its full functionality.

## Features

Key features of this application include the user's capability to retrieve and save notes to a simulated database.json file, ensuring data persistence even after page reloads unless explicitly deleted.

## Usage Information

This application operates using Express, requiring a running server for proper functionality. To start the server, navigate to the application's directory, install dependencies with 'npm i,' and initiate it using either 'npm start' or 'node index.js.' Upon success, a message will confirm the server is running at 'http://localhost:3001 🚀.' Access the front end directly by holding the 'Command' key and clicking the link. Users can then manage existing notes or create new ones, which are automatically saved to the database for persistent storage.

## License

NOTICE: This application is covered under the MIT License
