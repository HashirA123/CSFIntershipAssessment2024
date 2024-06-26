# CSF Intership Assessment 2024

If you are interested in an internship opportunity with the Canadian Sheep Federation for Summer 2023, please complete the tasks outlined in the .md file relevant to what you are interested in doing this summer.

E.g. those interested in QA should complete the QA assignment.

# CSFIntershipAssessment2024 /SoftwareDeveloperAssessment

## Description

This project is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It uses a public
anime API to to allow users to search different anime. The users can also write reviews for these anime of their choice.

## Technologies Used

- **Frontend**:
  - React.js
  - React Bootstrap
  - HTML/CSS
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (with Mongoose ORM)
- **Deployment**:
  - TBD
- **Other Tools**:
  - Git (Version control)
  - ESLint, Prettier (Code linting and formatting)
  - NPM (Package management)

## Getting Started

### Prerequisites

- Node.js installed on your machine
- MongoDB Atlas account for the database

### Installation

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd SoftwareDeveloperAssessment`
3. Install dependencies for both the frontend and backend:
   ```bash
   cd client
   npm install
   cd server
   npm install
   ```

### Setup Environment Variables

- Create a .env file in the server directory and define the following variables:

```makefile
    DATABASE_URL=<your-mongodb-uri>>
```

### Running the project

- Run the following commands

```bash
   cd server
   npm run start
   cd client
   npm start
```

# Bonus Points

## Discuss how the application and api could be extended and improved

- This app would greatly benifit by adding users. This will allow users to store and share their reviews with others and
  also see what others have to say.
- Following this, we would also need to add user Authentication, with we can use OAuth for to make it easy.
- We can also improve the user interface, the current work was done with very limited time.
- Another really interesting idea would be to add a comment/Blog section where people can create communities
  around their favourite animes, kind of like Reddit.

## Discuss how the application and api should be deployed

The easiest way would be to use a tool like Heroku, which makes the deployment of both the server and frontend together very easy.
