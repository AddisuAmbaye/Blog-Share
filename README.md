# The MERN Stack Blog_share Project: F

# Installation and Setup

Here are the steps to get the backend of the MERN Stack blog-share Project up and running on your local machine:

## Prerequisites

- Node.js and npm installed on your machine.
- A MongoDB Atlas account or MongoDB installed locally.

## Steps

1. **Clone the Repository**

    Clone the backend repository from GitHub. 

    ```bash
    git clone [https://github.com/yourusername/Blog-Share.git](https://github.com/AddisuAmbaye/Blog-Share.git)
    ```

2. **Install the Dependencies**

    Navigate into the cloned project directory and install the necessary packages using npm.

    ```bash
    cd blogify-backend
    npm install
    ```

3. **Set Up Environment Variables**

    Create a new file named `.env` in the root directory and set up your environment variables. For example:

    ```bash
    PORT=9080
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

    Replace `your_mongodb_uri` with the connection string to your MongoDB database, and `your_jwt_secret` with a secret string of your choice to be used for signing JSON Web Tokens.

4. **Start the Server**

    Now, you can start the server by running the start script defined in `package.json`.

    ```bash
    npm start
    ```

    The server should start running on http://localhost:5000 or your specified PORT, and connect to the MongoDB database.

Congrats! You have successfully set up the MERN Stack Blog-Share Project on your local machine. For details on the API routes you can use, refer to the API Documentation section.

## Contributing

For contribution guidelines, refer to [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

The project is licensed under the MIT license. For more details, refer to [LICENSE.md](./LICENSE.md).
