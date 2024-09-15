# Admin Dashboard

## Overview

This is a **Sales Dashboard** that provides insights into user data, customer data, sales performance, and geographical data of users. It helps visualize which products sell the most and gives daily, monthly, and breakdown reports of sales. The dashboard also includes data on the geographical locations of users and product distribution.

## Features

- **Sales Insights**: View sales data with daily, monthly, and breakdown reports.
- **User Data**: Access detailed user information, including geographical location and user engagement.
- **Product Data**: Analyze product sales trends to understand which products perform better.
- **Customer Data**: Detailed data on customers and their purchasing behavior.
- **Performance Metrics**: Visual representation of sales performance and trends.
- **Interactive Graphs**: Data visualization using Nivo charts to display user data, product trends, and sales insights.

## Tech Stack

- **Frontend**:
  - **React.js**: For building the user interface.
  - **Material UI**: For pre-built components and responsive design.
  - **Nivo Charts**: For creating interactive graphs and charts.
  
- **Backend**:
  - **Node.js**: Server-side JavaScript runtime.
  - **Express.js**: Web framework for creating APIs and handling backend logic.

- **State Management**:
  - **@reduxjs/toolkit**: For managing application state.
  - **@reduxjs/toolkit/query/react**: For handling API data fetching and caching.

- **Database**:
  - **MongoDB**: NoSQL database for managing user, sales, and product data.

## Installation

To run this project locally, follow these steps:

### Prerequisites

- **Node.js**: Ensure you have Node.js installed on your system.
- **MongoDB**: Install MongoDB or use a cloud-based MongoDB instance (e.g., MongoDB Atlas).

### Clone the Repository

```bash
git clone https://github.com/your-username/admin-dashboard.git
cd admin-dashboard
cd server
npm install
cd client
npm install
```
Create a .env file in the server directory and add your environment variables
Start the backend server:
```bash
nodemon index.js
```
Start the Client:
```bash
npm start 
```
### Screenshots
![image](https://github.com/user-attachments/assets/4fca58c6-697c-4616-b1f4-ac7c3f1f4d24)



