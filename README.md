# DashMaster - MERN Admin Dashboard

Welcome to DashMaster! This project showcases a fully functional admin dashboard built using the MERN stack. We utilize Material UI, Material UI Data Grid, Nivo Charts, Redux Toolkit, and Redux Toolkit Query for the frontend, and Node JS, Express JS, Mongoose, and MongoDB for the backend. Additionally, we cover data modeling using Entity Relationship Diagrams and making aggregate calls in MongoDB.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Links](#links)
- [License](#license)

## Features

- **Admin Dashboard**: A comprehensive admin panel to manage data.
- **Data Visualization**: Interactive charts and graphs using Nivo Charts.
- **Data Grid**: Efficient data management with Material UI Data Grid.
- **State Management**: Seamless state management with Redux Toolkit and Redux Toolkit Query.
- **Backend Integration**: Robust backend setup with Node JS, Express JS, and MongoDB.
- **Data Modeling**: Learn to model data using Entity Relationship Diagrams.
- **Aggregate Calls**: Perform advanced data queries with MongoDB aggregate.

## Technologies Used

### Frontend

- React
- Material UI
- Material UI Data Grid
- Nivo Charts
- Redux Toolkit
- Redux Toolkit Query
- React Router
- React Date Picker

### Backend

- Node JS
- Express JS
- Mongoose
- MongoDB

## Prerequisites

Ensure you have the following installed:

- [Node JS](https://nodejs.org/en/download/)
- [NPX](https://www.npmjs.com/package/npx)
- [VSCode](https://code.visualstudio.com/download)
- [Nodemon](https://github.com/remy/nodemon)
- [MongoDB](https://www.mongodb.com/)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/dashmaster.git
    cd dashmaster
    ```

2. Install dependencies for both frontend and backend:

    ```bash
    cd frontend
    npm install
    cd ../backend
    npm install
    ```

3. Set up environment variables:

    Create a `.env` file in the `backend` directory and add the following:

    ```env
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

## Usage

1. Start the backend server:

    ```bash
    cd backend
    npm run dev
    ```

2. Start the frontend development server:

    ```bash
    cd frontend
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` to view the admin dashboard.

## Links

- [Node JS](https://nodejs.org/en/download/)
- [NPX](https://www.npmjs.com/package/npx)
- [VSCode](https://code.visualstudio.com/download)
- [Nodemon](https://github.com/remy/nodemon)
- [Nivo](https://nivo.rocks/)
- [Material UI](https://mui.com/material-ui/getting-started/installation/)
- [Material UI Data Grid](https://mui.com/x/react-data-grid/)
- [React Router](https://reactrouter.com/en/v6.3.0/getting-started/overview/)
- [React Date Picker](https://reactdatepicker.com/#example-usage)
- [Redux Toolkit](https://redux-toolkit.js.org/introduction/getting-started)
- [Redux Toolkit Query](https://redux-toolkit.js.org/rtk-query/overview)
- [Dotenv](https://github.com/motdotla/dotenv)
- [JsonWebToken](https://github.com/auth0/node-jsonwebtoken)
- [Google Fonts](https://fonts.google.com/)
- [Render](https://render.com/)
- [Railway](https://railway.app/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://github.com/Automattic/mongoose)
- [MongoDB Aggregate](https://www.mongodb.com/docs/manual/reference/operator/aggregation-pipeline/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

