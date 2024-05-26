# Rentify - Where Renting Meets Simplicity

## Introduction

Rentify is a real estate platform designed to help property owners find the correct tenants and assist tenants in finding the right house based on their key requirements. As the world recovers from the pandemic, there is a high demand for real estate, especially in densely populated cities with many IT offices. Rentify aims to simplify the renting process by providing a seamless user experience for both property owners and tenants.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: Mongoose, JWT, bcryptjs, dotenv, etc,.

## Getting Started

### Prerequisites

- Node.js
- npm 
- MongoDB  compass (Local or Atlas)
- Git
- Github

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ShashankRV1/Project_Rentify
   cd Rentify_MERN_Project
   ```

2. **Backend Setup:**

   - Navigate to the backend directory:

     ```bash
     cd rentify-backend
     ```

   - Install backend dependencies:

     ```bash
     npm install
     ```

   - Create a `.env` file in the backend directory and add the following:

     ```env
     JWT_SECRET=your_secret_key_here
     MONGO_URI=your_mongodb_connection_string_here
     ```

   - Start the backend server:

     ```bash
     npm start
     ```

3. **Frontend Setup:**

   - Navigate to the frontend directory:

     ```bash
     cd ../rentify-frontend
     ```

   - Install frontend dependencies:

     ```bash
     npm install
     ```

   - Start the frontend development server:

     ```bash
     npm start
     ```

4. **Access the Application:**
   - The frontend application should now be running at `http://localhost:3000`.
   - The backend server should be running at `http://localhost:3001`.


## Navigation Options

- **Trip List**: Users can view a list of their past and upcoming trips.
- **Wish List**: Users can create and view a list of properties they are interested in.
- **Property List**: Sellers can view and manage the list of properties they have posted.
- **Reservation List**: Users can view and manage their reservations.
- **Become A Host**: Users can sign up to become a host and start listing properties.
- **Log Out**: Users can log out of their account.

## Submission Format

- Ensure the code is well-documented.
- Provide a video demo of the application.
- Include instructions for running the project locally in the README file.
- Include screenshots of the application in the README file.

## Contributing

If you would like to contribute to Rentify, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
