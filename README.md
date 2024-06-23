### Firebase Chat Application

This repository contains a real-time chat application built using Firebase and React. Users can sign in with Google, join chatroom, and exchange messages in real-time.

![image](https://github.com/ksvskarthik7/React-Firebase-Chatroom/assets/114343100/1573d4c8-58f4-454a-a86c-33de16289703)


![image](https://github.com/ksvskarthik7/React-Firebase-Chatroom/assets/114343100/e4bce71e-168b-4bf8-a592-b96b24c41789)



#### Features

- **Authentication**: Users can sign in securely using their Google accounts.
- **Real-time Messaging**: Messages are instantly synced across all clients in the chatroom.
- **Message Timestamps**: Each message displays the timestamp of when it was sent.
- **User Avatars**: User avatars fetched from Google accounts are displayed next to messages.
- **Responsive Design**: The application is designed to work seamlessly on desktop and mobile devices.

#### Technologies Used

- **Firebase**: Provides backend services such as authentication (using Firebase Authentication) and real-time database (using Firestore).
- **React**: Frontend library used for building the user interface and managing state.
- **React Hooks**: Used for state management and lifecycle methods within functional React components.
- **CSS**: Styled with CSS for layout and design.

#### How to Run

To run this project locally, follow these steps:

1. **Clone the Repository**
   ```
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Install Dependencies**
   ```
   npm install
   ```

3. **Set Up Firebase Project**

   - Go to the [Firebase Console](https://console.firebase.google.com/).
   - Create a new project or use an existing one.
   - Navigate to "Authentication" and enable the "Google" sign-in method.
   - Navigate to "Firestore Database" and create a new database. Start it in "test mode" for development.
   - Copy your Firebase project configuration (apiKey, authDomain, projectId, etc.) from the Firebase console.

4. **Add Firebase Configuration**
   
   In `src/App.js`, replace the `firebaseConfig` object with your Firebase project configuration:

   ```javascript
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_AUTH_DOMAIN",
     projectId: "YOUR_PROJECT_ID",
     storageBucket: "YOUR_STORAGE_BUCKET",
     messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
     appId: "YOUR_APP_ID",
     measurementId: "YOUR_MEASUREMENT_ID"
   };
   ```

5. **Run the Application**
   ```
   npm start
   ```

6. **Open in Browser**
   Open your web browser and go to `http://localhost:3000` to view the application.

#### Deployment

To deploy this application to a live server, you can use services like Firebase Hosting, Netlify, Vercel, etc. Ensure to set up Firebase hosting and deploy your application following their respective documentation.

#### Contributing

Contributions are welcome! If you have any suggestions, improvements, or feature requests, feel free to open an issue or submit a pull request.

#### License

This project is licensed under the MIT License - see the LICENSE file for details.

#### Acknowledgments

This application was built following tutorials and documentation from Firebase and React communities. Credits to the developers and maintainers of Firebase, React, and related libraries used in this project.

---

Feel free to explore, modify, and use this application according to your needs. If you encounter any issues or have questions, please reach out or refer to the documentation provided by Firebase and React. Happy chatting!
