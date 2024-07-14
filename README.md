# Library Management System

## Project Overview

**Library Management System** is a full-stack application designed to manage a library's collection, users, and transactions. This platform caters to individuals and administrators, providing tools for tracking book inventory, managing user accounts, and handling book borrowing and returning processes.

## Live Preview
Check out the live version of **Library Management System** here:

[![Library Management System](https://iili.io/dfvbujV.png)](https://library-management-system.vercel.app/)

## Tech Stack

![HTML5](https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/react%20-%2314354C.svg?&style=for-the-badge&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/nodejs%20-%2314354C.svg?&style=for-the-badge&logo=nodejs&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?&style=for-the-badge&logo=markdown&logoColor=white)
![GitHub](https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/git%20-%23121011.svg?&style=for-the-badge&logo=git&logoColor=green)
![Next.js](https://img.shields.io/badge/next.js%20-%23000000.svg?&style=for-the-badge&logo=next.js&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel%20-%23000000.svg?&style=for-the-badge&logo=vercel&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)

- **Full Stack Framework:** Next.js
- **Frontend:** React
- **Backend:** Node.js, PostgreSQL, Prisma
- **Version Control:** Git and GitHub
- **Hosting:** Vercel
- **Code Editor and Tools:** VS Code, Gemini AI

## Features

- **User Management**: Admin can manage users, including adding, updating, and deleting user records.
- **Book Management**: Full CRUD operations for managing the library's book collection.
- **Transaction Management**: Borrowing and returning books with a clear transaction history.
- **Search and Filter**: Efficient search and filter capabilities for books and users.
- **Responsive Design**: Fully responsive design for seamless use across devices.

## Installation

1. **Fork the Repository**: Start by forking the repository to your own GitHub account.

2. **Clone the Repository**: Next, clone the forked repository to your local machine:

    ```bash
    git clone https://github.com/<your-username>/<repository-name>.git
    ```

3. **Create a New Branch**: Navigate into the cloned repository and create a new branch for your changes:

    ```bash
    cd <repository-name>
    git checkout -b <branch-name>
    ```

    Replace `<branch-name>` with a descriptive name for your branch (e.g., `add-new-feature`).

4. **Make Your Changes**: Make the changes you want to contribute. Be sure to follow the project's coding standards and conventions.

5. **Commit Your Changes**: Once you've made your changes, stage and commit them:

    ```bash
    git add .
    git commit -m "Your descriptive commit message"
    ```

6. **Push Your Changes**: Push your changes to your forked repository on GitHub:

    ```bash
    git push origin <branch-name>
    ```

7. **Set Up Environment Variables**: Configure the necessary environment variables in a `.env` file in the project root directory:

## Environment Variables Setup

| Environment Variable          | Description                                      |
|-------------------------------|--------------------------------------------------|
| `POSTGRES_DATABASE`           | The name of your PostgreSQL database             |
| `POSTGRES_HOST`               | The host address of your PostgreSQL database     |
| `POSTGRES_PASSWORD`           | The password for your PostgreSQL database        |
| `POSTGRES_PRISMA_URL`         | Prisma connection string for your PostgreSQL database with pooling |
| `POSTGRES_URL`                | Connection string for your PostgreSQL database   |
| `POSTGRES_URL_NON_POOLING`    | Connection string for your PostgreSQL database without pooling |
| `POSTGRES_URL_NO_SSL`         | Connection string for your PostgreSQL database without SSL |
| `POSTGRES_USER`               | The user for your PostgreSQL database            |
| `DATABASE_URL`                | Your PostgreSQL connection string                |
| `GITHUB_ID`                   | Your GitHub App ID                               |
| `GITHUB_SECRET`               | Your GitHub App Secret                           |
| `GOOGLE_ID`                   | Your Google Client ID                            |
| `GOOGLE_SECRET`               | Your Google Client Secret                        |
| `NEXTAUTH_SECRET`             | Your NextAuth Secret                             |
| `NEXTAUTH_URL`                | The URL for your NextAuth application            |

## Contributing to the Project
Thank you for your contribution to **Library Management System**! We appreciate your help in making our project better.

## Refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file for more information on how to contribute to this project.

### License

[Insert License Here]

This project is open source and available under the [Insert License Name] License.
