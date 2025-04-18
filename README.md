# JobTracker - Job Tracking App
- Developed a comprehensive job tracking web app with user authentication via **JWT tokens** and **HTTP-only cookies**. Utilized **React Query** for efficient **data caching** and included **pagination** for seamless navigation. Implemented a **RESTful API** for backend communication.
- Enabled **user account management**, including **profile picture upload**, **job modification**, and **sorting** functions. Implemented **data visualization** with **interactive charts**. **Deployed** securely on **Render** for cloud-based access.
- **Technologies Used:** [MongoDB](https://www.mongodb.com/), [Express.js](https://expressjs.com/), [React.js](https://react.dev/), [Node.js](https://nodejs.org/en), [Vite](https://vitejs.dev/), [Render](https://render.com/)
  
#### Complete App

[JobTracker](https://jobify-mern-project-ugah.onrender.com)

### Usage
1. Clone the repository
   
   ```sh
     https://github.com/Chetana1911/JobTracker.git
   ```

2. Install dependencies

   ```sh
   cd jobify-main
   ```


3. There are two parts of this project: client and server.

   For Server
     ```sh
     cd server
     npm install
     ```
     If you see something like Server is listening on port 5000, you're good!

     For Client -  In a new terminal or after installing server dependencies:
      
     ```sh
      npm install
     ```

  
5. Set up environment variables: To run the application locally or deploy it elsewhere, you need to set up the following environment variables in a `.env` file at the root of the project. Here's how to fill in each variable:

    - `NODE_ENV`: Set the environment to either `development` or `production`.
    - `PORT`: Define the port number on which the server will run. Here default is `5100`.
    - `MONGO_URL`: Provide the connection string to your MongoDB database. Replace `<username>`, `<password>`, and `<dbname>` with your MongoDB credentials.
    - `JWT_SECRET`: Choose a secret key for JSON Web Token (JWT) encryption.
    - `JWT_EXPIRES_IN`: Set the expiration time for JWT tokens.
    - `CLOUD_NAME`: Your cloud storage provider's name (e.g., Cloudinary).
    - `CLOUD_API_KEY`: Your cloud storage API key.
    - `CLOUD_API_SECRET`: Your cloud storage API secret.
    
    Here's an example `.env` file:
    
    ```plaintext
    NODE_ENV=development
    PORT=5100
    MONGO_URL=mongodb+srv://<username>:<password>@cluster0.a3mftk7.mongodb.net/<dbname>?retryWrites=true&w=majority&appName=Cluster0
    JWT_SECRET=your_secret_key
    JWT_EXPIRES_IN=1d
    CLOUD_NAME=your_cloud_name
    CLOUD_API_KEY=your_cloud_api_key
    CLOUD_API_SECRET=your_cloud_api_secret
    ```
6. Run the application:Run Backend
     ```sh
    npm start
     ```
     If you see something like Server is listening on port 5000, you're good!
7. Run Frontend
      Open a new terminal, go to the client folder:
     ```sh
     npm run dev
     ```
     This will launch the frontend on http://localhost:5173 (default Vite port).

