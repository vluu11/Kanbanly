# Kanbanly

## Description

Krazy Kanban Board is a React-based Kanban board application that helps users organize tasks across different stages of development: "Todo," "In Progress," and "Done." The app is secured using JSON Web Tokens (JWT), enabling user authentication and ensuring tasks are accessible only to authenticated users. It demonstrates TypeScript integration with React for scalability and reliability in a full-stack development environment.

## Table of Contents

- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [Contributions](#how-to-contribute)
- [Tests](#tests)

## Usage

The application can be deployed and accessed through the provided link. Below are the steps to use the app:

1. **Login**:
   - Navigate to the login page.
   - Enter your username and password to authenticate.
   - If the credentials are valid, you'll be redirected to the Kanban board.
2. **View Tasks**:
   - The Kanban board displays tasks categorized into three columns: "Todo," "In Progress," and "Done."
   - Tasks are color-coded for easy differentiation.
3. **Create a New Task**:
   - Click the "New Ticket" button to open the form for creating a new task.
   - Fill in the required fields and save the task to add it to the "Todo" column.
4. **Move Tasks**:
   - Drag and drop tasks between columns to update their status.
5. **Delete Tasks**:
   - Use the delete button on any task card to remove it from the board.
6. **Logout**:
   - Click the logout button to end your session. This removes the JWT from local storage and redirects you to the login page.

## Credits

- Developer: Vuong Luu
- GitHub: https://github.com/vluu11/Kanbanly
- Deployment: 

## License

MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Badges

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Features

- **User Authentication**: Secure login using JWT for user authentication.
- **Dynamic Task Management**: Add, update, delete, and categorize tasks in three Kanban board stages.
- **Responsive Design**: Optimized UI for desktop and mobile devices.
- **Protected Routes**: Tasks and board content are only accessible to authenticated users.
- **Session Management**: Automatically logs out users after inactivity to enhance security.

## How to Contribute

Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request. Suggestions for improving functionality, UI/UX, or adding new features are greatly appreciated.

## Tests

No automated tests are currently provided, but you can manually test the following features:
- User login and authentication with valid and invalid credentials.
- Task creation, deletion, and status updates.
- Logout and session expiration functionality.
