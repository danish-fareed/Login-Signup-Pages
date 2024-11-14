# Login/Signup Page

This is a simple Login and Signup web page created using HTML, CSS, and JavaScript. It features form validation and toggling between the Login and Signup forms without reloading the page.

## Features

- **Login Form**: Allows users to log in with email and password.
- **Signup Form**: Allows new users to sign up by entering their name, email, password, and confirming their password.
- **Form Validation**: Validates email format, checks password length, and ensures passwords match.
- **Smooth Toggle**: Switches between Login and Signup forms with a smooth transition.

## Technologies Used

- **HTML**: For the structure of the page.
- **CSS**: For styling, including a gradient background and responsive design.
- **JavaScript**: For form validation and toggling between the forms.

## How to Use

1. **Login**:
   - Enter your email and password.
   - Password must be at least 8 characters long.
   - Click the "Login" button to proceed. If validation passes, a success message will appear.

2. **Sign Up**:
   - Click on the "Sign up" link to switch to the Signup form.
   - Enter your full name, email, password, and confirm the password.
   - Password must be at least 8 characters and both password fields must match.
   - Click the "Sign Up" button to complete registration. If validation passes, a success message will appear.


## Customization

You can customize the page according to your needs:

- **Styling**: Modify the `style.css` to change colors, fonts, or layout.
- **Form Validation**: The form validation logic is in `script.js`. You can enhance it as needed.
- **Backend Integration**: Currently, form submission is only handled client-side. For server-side integration, you can use an AJAX request or any backend API.

## Screenshots

### Login Page
![Login Page](screenshots/login.png)

### Signup Page
![Signup Page](screenshots/signup.png)

## Future Enhancements

- Integrate with a backend service for actual user authentication.
- Add additional form validation checks like email uniqueness.
- Improve accessibility (e.g., add ARIA roles and better keyboard navigation).
- Enhance the user interface with animations or icons.

## License

This project is open-source and available under the MIT License.

