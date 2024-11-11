# Flight Booking Application
A full-stack application for searching and booking flights.

#Functionality and Working of our project
This Project includes the steps where the User can book and cancel their tickets.

## Prerequisites
##To install Node JS and MongoDB
- [Node.js](https://nodejs.org/) 
- [MongoDB](https://www.mongodb.com/try/download/community) 

## Installation
1. Clone the repository: `git clone https://github.com/your-username/flight-booking-app.git`
2. Navigate to the backend and frontend folders and install dependencies.
3. Configure environment variables (see below).
4. Start both the frontend and backend servers.

## Usage
Open `http://localhost:3000` in your browser. Register or log in, search for flights, and make a booking.

## API Endpoints
### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Log in a user

### Flights
- `GET /api/flights` - List available flights
- `POST /api/flights` - Add a new flight (Admin only)

#The entities in our project:
1. Customer - The Customer is the one who can book and cancel their own tickets.
2. Admin - The Admin is the one who focuses on adding flights and providing the approval for flight operators to view the application.
3. Flight Operator -  This is the one who handles the entire functionality of the application by analysing the number of bookings done.

## Features
- User registration and login
- User entering the Starting and the destination place.
- Viewing the available flights.
- As an Admin, adding flights and updating the flight information within the database.
- As a Flight Operator, they focus on analyzing the number of bookings done.

## Tech Stack
- Frontend: React, Redux, Bootstrap
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)

##Connecting the Database
- To install MongoDB compass in the system
- Then go to connecting of the String.
- Now try to make the changes within the server and then start to run your application

##Running the application
- npm start
- npm run dev
