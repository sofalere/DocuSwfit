# Take the Notes

This simple yet powerful notes app, built using Express, JavaScript, and MongoDB with Mongoose, allows multiple users to seamlessly create, edit, and manage their notes. The application prioritizes security by employing bcrypt to hash passwords, ensuring user data integrity.

## Features:

- **User Authentication:** Secure user authentication system to protect individual accounts.
  
- **Password Hashing:** Passwords are hashed using bcrypt, enhancing security.

- **Note Management:** Create, edit, and delete notes with an intuitive user interface.

- **Multiple Users:** Designed to support multiple users, each with their own set of personalized notes.

## Installation:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/notes-app.git

2. **Navigate to the project directory:**
    ```bash
    cd notes-app
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Set up your MongoDB connection in the `utils/config.js` file.**

5. **Run the application:**
    ```bash
    npm start
    ```

5. **Open your browser and visit [http://localhost:3000](http://localhost:3000) to start using the Notes App.**

## Dependencies:
- [Express](https://expressjs.com/): Web application framework for Node.js.
- [bcrypt](https://www.npmjs.com/package/bcrypt): Library for hashing passwords.
- [Mongoose](https://mongoosejs.com/): MongoDB object modeling for Node.js.

## Usage:
1. Register a new account.
2. Log in with your credentials.
3. Start creating and managing your notes effortlessly.

Feel free to explore and contribute to make this Notes App even more robust and user-friendly. If you encounter any issues or have suggestions, please [open an issue](https://github.com/your-username/notes-app/issues). Happy noting!
