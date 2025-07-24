The Online Auction System is a web-based platform developed using the MERN stack (MongoDB, Express.js, React, Node.js) that facilitates secure and transparent online bidding. 
It allows users to list products for auction, place real-time bids, and track auction status until closure. 
The system automates auction ending times and supports competitive bidding with ease of access and user-friendly interfaces.

Project Objectives
To develop a full-stack web application that enables item listings with starting bids.
To implement real-time bidding functionality with auto-bid support.
To automatically manage auction durations and closure.
To ensure secure user authentication and role-based access (Seller/Buyer/Admin).
To create an intuitive interface for buyers and sellers to interact seamlessly.
To promote digital transformation in traditional auction processes.

# MERN Stack Online Auction System

This is a full-stack web application built with the MERN stack (MongoDB, Express.js, React, Node.js) to create a secure, transparent, and user-friendly online auction platform. It allows users to list products, place bids in real-time, and track auction progress seamlessly. The system is designed to automate auction management and promote a digital-first approach to traditional auctioning.

## Table of Contents

- [Project Objectives](#project-objectives)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Objectives

- To develop a full-stack web application that enables item listings with starting bids.
- To implement real-time bidding functionality with auto-bid support.
- To automatically manage auction durations and closure.
- To ensure secure user authentication and role-based access (Seller/Buyer/Admin).
- To create an intuitive interface for buyers and sellers to interact seamlessly.
- To promote digital transformation in traditional auction processes.

## Key Features

- **Real-Time Bidding**: Place and view bids instantly without needing to refresh the page, powered by WebSockets.
- **User Role Management**: Distinct roles for Buyers, Sellers, and Administrators, each with a specific set of permissions.
- **Secure Authentication**: Secure user registration and login system using JWT (JSON Web Tokens).
- **Automated Auction Lifecycle**: Auctions automatically start and end based on scheduled times, with winners notified upon closure.
- **Product Listings**: Sellers can easily create and manage their product listings, including descriptions, images, and starting bids.
- **Bidding History**: Users can track the complete bidding history for any item.
- **Responsive User Interface**: A clean, intuitive, and responsive design that works across desktops, tablets, and mobile devices.

## Tech Stack

### Frontend
- **React**: A JavaScript library for building dynamic user interfaces.
- **React Router**: For client-side routing and navigation.
- **Socket.IO Client**: For real-time, bidirectional communication.
- **Tailwind CSS**: A utility-first CSS framework for modern styling.
- **Axios**: For making HTTP requests to the backend API.

### Backend
- **Node.js**: A JavaScript runtime for building the server.
- **Express.js**: A web application framework for creating the RESTful API.
- **MongoDB**: A NoSQL database for storing user data, products, and bids.
- **Mongoose**: An Object Data Modeling (ODM) library for MongoDB.
- **Socket.IO**: Enables real-time server-side communication for the bidding engine.
- **JWT (jsonwebtoken)**: For generating and verifying user authentication tokens.
- **Bcrypt.js**: For hashing user passwords before storing them in the database.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js (v14 or newer)
- npm (Node Package Manager)
- MongoDB (a local instance or a cloud-hosted one like MongoDB Atlas)

### Backend Setup

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Navigate to the backend directory:**
    ```bash
    cd <project-folder>/backend
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```
4.  **Create a `.env` file** in the `backend` root and add the following variables:
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_super_secret_jwt_key
    PORT=5000
    ```
5.  **Start the backend server:**
    ```bash
    npm start
    ```
    The API server will be running at `http://localhost:5000`.

### Frontend Setup

1.  **Open a new terminal** and navigate to the frontend directory:
    ```bash
    cd <project-folder>/frontend
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    ```
3.  **Start the React development server:**
    ```bash
    npm start
    ```
    The application will be accessible at `http://localhost:3000`.

## Usage

Once both servers are running, you can use the application:
1.  **Register** for a new account as either a Buyer or a Seller.
2.  **Login** to access your dashboard.
3.  **Sellers** can list new items for auction.
4.  **Buyers** can browse listings and place bids on active auctions.
5.  The system will automatically close the auction when the time expires and declare a winner.

## Contributing

Contributions are welcome! If you have ideas for improvements or find any bugs, please feel free to fork the repository and submit a pull request.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/NewFeature`).
3.  Commit your Changes (`git commit -m 'Add some NewFeature'`).
4.  Push to the Branch (`git push origin feature/NewFeature`).
5.  Open a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.


