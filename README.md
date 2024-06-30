# Quadb Tech Assignment

Node.js project with PostgreSQL database

To run this project smoothly, follow the steps given below:

## Steps

1. **Download the Project:**
   - Download the zip folder from the GitHub profile.

2. **Unzip the Folder:**
   - After downloading, unzip the folder and open the terminal integrated to that folder.

3. **Install Dependencies:**
   - Run the command `npm install` to download all the dependencies listed in the `package.json` file.

4. **Edit PostgreSQL Configuration:**
   - Open the `server.js` file and edit the database connection details according to your PostgreSQL database:
     ```javascript
     const pool = new Pool({
       user: 'user_name',
       host: 'localhost',
       database: 'database_name',
       password: 'password',
       port: 5432, // Default PostgreSQL port
     });
     ```

5. **Run the Server:**
   - After entering the specific details, run the `server.js` file using the command:
     ```sh
     npm run
     ```
   - The data will be fetched from the API and stored in the PostgreSQL database.

6. **Run the Frontend:**
   - Then go to `http://localhost:3000` on browser.
   - The desired frontend and the data from the backend will be displayed there successfully.
