# Firebase Obscure Error Reporting
This repository demonstrates a common issue with Firebase: unhelpful error messages when encountering configuration problems or security rule violations.  The `firebaseBug.js` file shows how easily a small mistake (like a missing API key or incorrect data structure) can lead to ambiguous error messages.  The solution, `firebaseBugSolution.js`, illustrates how to improve error handling and provide more context to the user, making debugging significantly easier.

## Setup:
1.  Clone this repository.
2.  Install Firebase:
    ```bash
    npm install firebase
    ```
3.  Replace placeholders in `firebaseConfig` with your actual Firebase project configuration.
4.  Run the code.