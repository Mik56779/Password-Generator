# Password-Generator
Password Generator in Javascript with bootstrap

**Strong Password Generator App**

**Description:**

The Strong Password Generator app is a web-based application that allows users to generate strong and secure passwords. It offers various options for customizing the password, including length and the inclusion of uppercase letters, lowercase letters, numbers, and special characters. The app also provides a password strength meter, giving users an idea of how strong their generated password is. The passwords generated are cryptographically secure and are unique each time the generator is used.

**Features:**

1. Generate Strong Passwords: Users can specify the desired password length and choose to include uppercase letters, lowercase letters, numbers, and special characters to create strong and secure passwords.

2. Password Strength Meter: The app provides a visual password strength meter that indicates how strong the generated password is. The strength meter shows a value between 0 and 100, with higher values representing stronger passwords.

3. Real-time Password Strength Feedback: As users customize the password options, the password strength meter updates in real-time to show the strength of the password based on the selected criteria.

4. Firebase Integration: The app is integrated with Firebase to store the generated passwords. Each time a password is generated, it is saved with a timestamp in Firestore, ensuring that each generated password is unique and can be retrieved later if needed.

**Usage:**

1. Access the App: Open the Strong Password Generator app in your web browser by navigating to the URL where the app is hosted.

2. Customize Password Options: Choose the desired password length using the input field, and check or uncheck the checkboxes for including uppercase letters, lowercase letters, numbers, and special characters as per your preferences.

3. Generate Password: Click the "Generate Password" button to generate a strong password based on your selected options. The generated password will appear below the button.

4. Password Strength Meter: The password strength meter will automatically update to show the strength of the generated password. A higher percentage indicates a stronger password.

5. Save Generated Password: The app automatically saves each generated password to the Firebase Firestore. You can access and retrieve your generated passwords later.

**Requirements:**

- Web browser (Google Chrome, Mozilla Firefox, Safari, etc.)
- Internet connection (for Firebase integration)

**Firebase Setup:**

To use the app with Firebase integration, you need to create a Firebase project and get the configuration details. Replace the placeholder values in the provided script tag with your actual Firebase configuration.

**Limitations:**

- The app requires an internet connection to use Firebase for storing generated passwords.

**Contributing:**

We welcome contributions to improve the Strong Password Generator app. If you find any bugs or have suggestions for new features, please feel free to open an issue or submit a pull request on the GitHub repository.

**License:**

The Strong Password Generator app is licensed under the MIT License. See the LICENSE file in the repository for more details.

**Authors:**

- [Mike Kalange](https://github.com/Mik56779) - App Developer

**Acknowledgments:**

- Special thanks to the developers of Firebase for providing a secure and reliable database solution.
- Thanks to the open-source community for creating and maintaining libraries and tools used in this app.

**Contact:**

For any inquiries or support related to the Strong Password Generator app, you can contact us at [mike:mikekalange@gmail.com).
