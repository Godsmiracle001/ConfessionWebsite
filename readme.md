# xConfess Platform

xConfess is an anonymous confession and social interaction platform built using Next.js, React, Node.js, Express, and Socket.io. It allows users to post confessions, react, comment, and engage in real-time messaging with other users.

## Key Features

-   Anonymous confessions
-   User reactions (Like, Dislike) and comments
-   Real-time messaging functionality using Socket.io
-   Secure registration and login system
-   Sleek dark-themed UI with Next.js and TailwindCSS

## Tech Stack

-   **Frontend:** Next.js, React, TailwindCSS, Framer Motion
-   **Backend:** Node.js, Express
-   **Real-time Communication:** Socket.io

## Installation Guide

### Clone the Repositories

```sh
git clone https://github.com/yourusername/xconfess-frontend.git
git clone https://github.com/yourusername/xconfess-backend.git
```

### Frontend Setup

```sh
cd xconfess-frontend
npm install
npm run dev
```

Visit: `http://localhost:3000`

### Backend Setup

```sh
cd xconfess-backend
npm install
node server.js
```

Backend URL: `http://localhost:5000`

## Folder Structure

### Frontend (xconfess-frontend)

```
/pages
  /index.js  (Landing Page)
  /register.js (Registration Page)
  /login.js (Login Page)
  /dashboard
    /index.js (Dashboard Homepage)
    /messages.js (Messaging Page)
/components
  /Navbar.js
  /MessageComponent.js
```

### Backend (xconfess-backend)

```
server.js  (Express + Socket.io Backend)
```

## Real-time Messaging

-   Built with **Socket.io** for instant message delivery.
-   Connects frontend and backend for seamless communication.

## Running the Application

1. Open two terminals.
2. Start the **backend** in Terminal 1:

```sh
cd xconfess-backend
node server.js
```

3. Start the **frontend** in Terminal 2:

```sh
cd xconfess-frontend
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Contribution

Feel free to fork this repository, create a branch, and submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License.
