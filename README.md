# SpendMap – Personal Finance Tracker

SpendMap is a personal finance tracking web application that helps users manage their income and expenses in one place. It provides a dashboard to review financial activity, track spending by category, and understand where money is going.

## Features

- User authentication with signup and login
- Add and manage income and expense transactions
- Dashboard with a summary of income and expenses
- Category-wise expense tracking
- Date-based transaction filtering
- Export financial data to Excel

## Tech Stack

- **Frontend:** React, Vite, JavaScript, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB or access to a MongoDB database

### Installation

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project folder:

   ```bash
   cd spendmap
   ```

3. Install backend dependencies:

   ```bash
   cd backend
   npm install
   ```

4. Install frontend dependencies:

   ```bash
   cd ../frontend
   npm install
   ```

### Environment Variables

Create the required `.env` files for the backend and frontend. Configure the database connection, authentication secret, and frontend API URL according to your project settings.

Do not upload `.env` files or sensitive credentials to GitHub.

### Running the Application

Start the backend and frontend in separate terminals using the development scripts specified in their respective `package.json` files.

## What I Learned

While building SpendMap, I gained practical experience with React, REST APIs, Express.js, MongoDB, user authentication, and managing financial transaction data across the frontend and backend.

## Future Improvements

- Add more detailed spending visualizations
- Improve transaction filtering and dashboard insights
- Introduce additional ways to analyze spending patterns

---

**SpendMap** is a personal project built to practice full-stack web development and create a useful tool for managing everyday finances.