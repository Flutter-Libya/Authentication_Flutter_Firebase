# Flutter Authentication Application

This is a Flutter project that utilizes Firebase for user authentication. The application supports user login with email and password, while also providing users with a way to sign out.

## Project Structure

The application consists of several components including:

1. **Firebase Initialization:** Firebase is initialized in the `main.dart` file, which serves as the entry point of the application.

2. **Authentication Page:** `AuthPage` checks the user's authentication status. If the user is logged in, they're directed to the `HomePage`. Otherwise, they're directed to the `LoginPage`.

3. **Login Page:** `LoginPage` is where users can enter their email and password to log in. It uses Firebase's `signInWithEmailAndPassword` method for authentication.

4. **Home Page:** After successful login, the user is redirected to the `HomePage`, which displays the email of the logged-in user. It also includes a button for signing out.

5. **Custom Components:** These include `MyButton` (a custom styled button), `MyTextField` (a custom text field with consistent styling), and `SquareTile` (a custom widget for displaying images).

## Screenshots

Here are some screenshots of the application:

<img src="Simulator Screen Shot - iPhone 14 Plus - 2023-05-25 at 15.46.33.png" width="200">

<img src="Simulator Screen Shot - iPhone 14 Plus - 2023-05-25 at 15.46.49.png" width="200">

<img src="Simulator Screen Shot - iPhone 14 Plus - 2023-05-25 at 15.47.06.png" width="200">

