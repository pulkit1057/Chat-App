
# EchoChat

**EchoChat** is a real-time public chat application built using **Flutter**, **Dart**, and **Firebase**. It allows users to chat publicly with others, with integrated authentication and notification features for seamless communication. The app is designed to offer a fast, reliable, and engaging messaging experience.

## Features

- **Public Chat**: Users can chat with everyone in a public space.
- **Authentication**: User sign-up and login functionality to ensure secure access.
- **Real-Time Notifications**: Get notified instantly when someone sends a new message.
- **Cross-Platform Support**: Available on Android devices, built with Flutter for easy scalability to other platforms.

## Screenshots

(Include some screenshots of the app’s UI to give users a visual overview)

## Technologies Used

- **Flutter**: Cross-platform UI toolkit for building natively compiled applications.
- **Dart**: Programming language optimized for building mobile, desktop, server, and web applications.
- **Firebase**: Backend services for authentication, real-time database, and notifications.

## Installation and Setup

To run this project locally, follow these steps:

1. Clone the repository:

   \`\`\`bash
   git clone https://github.com/your-username/EchoChat.git
   \`\`\`

2. Navigate to the project directory:

   \`\`\`bash
   cd EchoChat
   \`\`\`

3. Install the dependencies:

   \`\`\`bash
   flutter pub get
   \`\`\`

4. Set up Firebase:

   - Create a Firebase project.
   - Enable Firebase Authentication, Firestore Database, and Cloud Messaging.
   - Download the \`google-services.json\` file and place it in the \`android/app\` directory.

5. Run the app:

   \`\`\`bash
   flutter run
   \`\`\`

## Firebase Setup

Ensure that the Firebase project has the following:

- **Authentication**: Email/Password authentication is enabled.
- **Firestore Database**: Set up Firestore for storing messages in real-time.
- **Cloud Messaging**: For sending push notifications when a new message arrives.

## Future Improvements

- **Private Messaging**: Enable users to chat privately with one another.
- **User Profiles**: Add user profile functionality with avatars and bio.
- **Media Sharing**: Allow users to share images and files in the chat.

## Contributing

Feel free to contribute by submitting a pull request. Before contributing, please ensure your code follows the project's coding standards.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
