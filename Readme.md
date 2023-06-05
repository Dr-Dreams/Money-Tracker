# Money Tracker Web App

This is a budget-tracking web application built with React.js and Node.js.

## Features

### Backend

- REST API backend
- List of known users (friends)
- Creating, updating, and deleting transactions
- Transactions are associated with a set of users to split it across
- Users can be members or non-members
- Transactions have a spending category
- MongoDB is used as the database

### Frontend

- User interface displays the list of transactions
- Users can filter transactions by date and category
- User interface shows the total amount spent and the remaining budget based on the transactions
- User interface allows creating, updating, and deleting transactions
- Application shows who owes you or who you owe

### Technologies Used

- React.js
- Node.js
- MongoDB
  The application utilizes MongoDB as the database for storing transaction data. It is important to note that the MongoDB Atlas database used for this application will be disabled after one week. This is to ensure efficient resource utilization and prevent unnecessary costs. If you plan to continue using the application beyond the one-week period, you will need to set up your own MongoDB database or extend the usage of the provided database.

## Prerequisites

Before running the script, make sure you have the following:

1. Node.js installed on your machine.

## Setup

1. Clone the repository.
   ```bash
   git clone https://github.com/Dr-Dreams/Money-Tracker.git
   ```
2. Navigate to the project directory.
   ```bash
   cd Money-Tracker
   ```
3. Install the dependencies by running the following command in the project directory:
   ```bash
   npm run install-all
   ```
4. Start the application:
   ```bash
   npm start
   ```
   This will start both the frontend and backend concurrently.
5. Access the Money Tracker web app in your browser at http://localhost:3000/login or http://localhost:3000/register

### Troubleshooting related with database

Try using a different DNS server: Sometimes, DNS servers can encounter issues or have outdated records. You can try switching to a different DNS server, such as Google DNS (8.8.8.8) or Cloudflare DNS (1.1.1.1), to see if it resolves the problem.

#### Dependencies List

##### Frontend Dependencies List

- @ant-design/icons:
- @testing-library/jest-dom:
- @testing-library/react:
- @testing-library/user-event:
- antd:
- axios:
- moment:
- react:
- react-dom:
- react-redux:
- react-router-dom:
- react-scripts:
- redux:
- web-vitals:

##### Backend Dependencies List

- colors:
- cors:
- dotenv:
- express:
- moment:
- mongoose:
- morgan:
