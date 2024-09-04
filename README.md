# Bharat_Intern_Registration_Form
Registration Form App: A Node.js and Express application for user registration, using MongoDB for data storage. Features include a modern styled frontend, user registration functionality, and MongoDB integration. Ready for deployment on Render with a Procfile for process management.

# Registration Form App

A Node.js and Express application designed for user registration, featuring MongoDB for data storage. The app includes a modern styled frontend and backend integration for handling user registrations.

## Features

- **User Registration**: Allows users to register with their details.
- **MongoDB Integration**: Stores user data in MongoDB.
- **Styled Frontend**: Modern and responsive design.
- **Deployment Ready**: Configured for deployment on Render.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account
- Render account

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/registration-form.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd registration-form
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Set up environment variables:**

    Create a `.env` file in the root directory and add your MongoDB URI and port:

    ```plaintext
    MONGO_URI=mongodb+srv://<username>:<password>@cluster0.s5grp.mongodb.net/sample_mflix?retryWrites=true&w=majority
    PORT=3000
    ```

5. **Run the application locally:**

    ```bash
    npm start
    ```

    The server will start at `http://localhost:3000`.

### Deployment

1. **Create a `Procfile`** in the root directory:

    ```plaintext
    web: node app.js
    ```

2. **Push your code to GitHub.**

3. **Deploy on Render:**

    - Go to [Render](https://render.com).
    - Create a new web service.
    - Connect to your GitHub repository.
    - Render will automatically detect the `Procfile` and deploy your app.

## Contributing

Feel free to submit issues or pull requests to improve the application.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
