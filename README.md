# Riddle Me This

**Riddle Me This** is a web application where users can create, view, edit, and delete riddles, as well as manage their own profiles. This application is built using C#, HTML, CSS, JavaScript, and SQL.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Guidelines](#guidelines)
- [License](#license)

## Overview

Riddle Me This is an engaging platform designed for riddle enthusiasts. It allows users to interact with riddles by performing various operations, such as creating new riddles, viewing details, editing, and deleting them. Additionally, users can create and manage their profiles to track their interactions with the riddles.

## Features

- **Create Riddles**: Users can create their own riddles by providing a question and an answer.
- **View Riddle Details**: Click on the "Details" button to view detailed information about a riddle.
- **Edit Riddles**: Update existing riddles to correct mistakes or modify them as needed.
- **Delete Riddles**: Remove riddles from the system when they are no longer needed.
- **User Profiles**: Create and manage user profiles to track your riddles and interactions.

## Technologies Used

- **Backend**: C# with ASP.NET for server-side logic
- **Frontend**: HTML, CSS, and JavaScript for client-side development
- **Database**: SQL for managing and storing data
- **Version Control**: Git for source code management

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/riddle-me-this.git
2. **Navigate to the Project Directory**
    cd riddle-me-this
Set Up the Database

3. **Create a new SQL database in your SQL Server.**
- Run the provided SQL scripts to set up the schema and initial data.
- Configure the Application

4. **Open the appsettings.json file in the project.**
- Update the database connection string with your local SQL Server instance details.
- Build and Run the Application

5. **Open the project in Visual Studio.**
- Build the solution to restore dependencies and compile the code.
- Run the project using Visual

   Studio or through the command line.

## Usage

1. **Access the Website**

   - Navigate to `http://localhost:5000` (or the URL configured in your settings) in your web browser to access the application.

2. **Create an Account**

   - Register a new user account by providing necessary details.

3. **Explore Features**

   - **Create Riddle**: Go to the "Create Riddle" page and fill out the form to submit a new riddle.
   - **View Riddle Details**: Click on the "Details" button next to any riddle to view more information.
   - **Edit Riddle**: Click the "Edit" button to modify a riddle.
   - **Delete Riddle**: Click the "Delete" button to remove a riddle.
   - **Manage Profile**: Access your profile from the navigation menu to view your riddle submissions and settings.

## Guidelines

- **Contributions**: If you wish to contribute to the project, please fork the repository and submit a pull request. Ensure that your code follows the existing coding standards and includes appropriate documentation.
- **Reporting Issues**: Report any issues or bugs by opening an issue on the GitHub repository. Provide detailed information about the problem and steps to reproduce it.
- **Code Style**: Follow the coding conventions used in the project, including naming conventions and code formatting, to maintain consistency.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
