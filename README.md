# Sign Up Form

A responsive, modern sign-up form built with HTML and CSS. This project provides a clean and user-friendly interface for collecting user registration information.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Customization](#customization)
- [License](#license)

## Overview

This Sign Up Form is a front-end web application designed to capture user registration details. It features a modern two-column layout with a side image and a form section. The form collects essential user information including name, email, phone number, and password with confirmation.

## Features

- **Responsive Design**: Clean, modern layout with a side image panel
- **Form Fields**: Collects first name, last name, email, phone number, and password
- **Custom Styling**: Uses CSS custom properties (variables) for easy theme customization
- **User-Friendly Interface**: Clear labels and organized input fields
- **Professional Color Scheme**: Uses a light gray primary color (#F2F2F2) and cyan secondary color (#00D9E9)
- **Create Account Button**: Call-to-action button with custom styling

## Project Structure

```
sign-up-form/
├── README.md              # Project documentation
├── index.html             # Main HTML file with form structure
├── style.css              # Stylesheet with form styling
├── img/                   # Image assets folder
│   └── image.jpg          # Side panel image
└── LICENSE                # MIT License file
```

## Getting Started

### Prerequisites

No special installation or dependencies are required. This is a static HTML/CSS project that runs directly in any modern web browser.

- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- A text editor (optional, for modifications)

### Installation

1. **Clone the repository** (if using Git):
   ```bash
   git clone https://github.com/muhammad-asif10/sign-up-from.git
   cd sign-up-from
   ```

2. **Open the form**:
   - Double-click the `index.html` file to open it in your default browser, OR
   - Right-click on `index.html` and select "Open with" to choose a specific browser

3. **Alternatively, use a local server** (recommended for better experience):
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Python 2
   python -m SimpleHTTPServer 8000

   # Using Node.js (if installed)
   npx http-server
   ```
   Then navigate to `http://localhost:8000` in your browser.

## Usage

### Filling Out the Form

1. **First Name**: Enter your first name in the first text field
2. **Last Name**: Enter your last name in the second text field
3. **Email**: Provide a valid email address
4. **Phone Number**: Enter your contact phone number
5. **Password**: Create a secure password
6. **Confirm Password**: Re-enter your password to confirm it matches
7. **Create Account**: Click the "Create Account" button to submit the form

### Form Fields Details

| Field | Type | Purpose |
|-------|------|---------|
| First Name | Text Input | User's first name |
| Last Name | Text Input | User's last name |
| Email | Email Input | User's email address |
| Phone Number | Number Input | User's contact number |
| Password | Password Input | Secure password creation |
| Confirm Password | Password Input | Password verification |

## File Descriptions

### `index.html`

The main HTML file that defines the structure of the sign-up form. It includes:
- **Main Container**: Flex layout with side image and form sections
- **Side Image Panel**: Displays `img/image.jpg` on the left side
- **Header Section**: Welcome text and form introduction
- **Form Section**: Contains all input fields and the submit button
- **Form Fields**: 
  - First Name and Last Name (displayed side by side)
  - Email and Phone Number (displayed side by side)
  - Password and Confirm Password (displayed side by side)
  - Create Account button

### `style.css`

The stylesheet that controls the appearance and layout of the form. It includes:
- **CSS Variables**: Primary color (#F2F2F2) and secondary color (#00D9E9)
- **Global Styling**: Arial font family applied across the page
- **Layout**: Flexbox display for main container
- **Components**:
  - `.side-image`: Styles the image panel (50vw width, 20vh height)
  - `.detail`: Padding for form details container
  - `#first-name`: Specific styling for first name input
  - `#sign-up`: Button styling with cyan background and border-radius

### `img/image.jpg`

A decorative image displayed in the left panel of the form. This image contributes to the visual appeal of the sign-up experience.

### `LICENSE`

MIT License - This project is open source and free to use, modify, and distribute under the terms of the MIT License.

## Customization

### Change Colors

Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: hsl(0, 0%, 95%);      /* Light gray background */
    --secondary-color: hsl(184, 82%, 66%); /* Cyan accent color */
}
```

Replace with your preferred colors using HSL, RGB, or hex values.

### Change the Side Image

Replace `img/image.jpg` with your own image file:
1. Add your image file to the `img/` folder
2. Update the `src` attribute in the `index.html` file:
   ```html
   <img id="img" src="img/your-image.jpg" alt="Description" />
   ```

### Modify Form Fields

To add or remove fields, edit the form section in `index.html`:
1. Add new `<label>` and `<input>` tags within the `.detail` div
2. Apply corresponding styles in `style.css` as needed

### Adjust Layout Dimensions

Modify the dimensions in `style.css`:
- `.side-image` width/height for image panel size
- `main` properties for overall layout

## Development Notes

- **Current Status**: Static HTML/CSS form (no backend functionality)
- **JavaScript**: Currently not included; can be added for form validation and submission
- **Responsive Design**: Consider adding media queries for better mobile experience
- **Accessibility**: Labels are associated with inputs for better screen reader support

## Future Enhancements

- Add JavaScript for form validation
- Implement backend API for form submission
- Add mobile-responsive media queries
- Enhance accessibility features
- Add form feedback/confirmation messages
- Implement password strength indicator
- Add terms and conditions checkbox

## Contributing

This is an open-source project. Feel free to:
- Fork the repository
- Create a new branch for your changes
- Make improvements or fix bugs
- Submit a pull request with your changes

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Author**: Muhammad Asif  
**Repository**: [muhammad-asif10/sign-up-from](https://github.com/muhammad-asif10/sign-up-from)

For questions or feedback, please open an issue on GitHub.
