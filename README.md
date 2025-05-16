# Password Generator

A modern and secure password generator web application with a beautiful user interface. This application helps users create strong, customizable passwords with various options.

![Password Generator Screenshot](./images/screenshot.png)

## Features

- **Customizable Password Length**: Generate passwords between 1-20 characters
- **Character Options**:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special symbols (~`!@#$%^&*()_-+={[}]|:;"<,>.?/)
- **Password Strength Indicator**: Visual feedback on password strength
- **Copy to Clipboard**: One-click copy functionality with visual feedback
- **Responsive Design**: Works seamlessly on both desktop and mobile devices
- **Modern UI**: Beautiful gradient background and smooth animations

## Technology Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Google Fonts (League Spartan)

## How to Use

1. Open `index.html` in a modern web browser
2. Customize your password preferences:
   - Set desired password length using the slider
   - Select character types to include using checkboxes
3. Click "Generate Password" to create a new password
4. Click the copy icon to copy the password to your clipboard

## Password Strength Algorithm

The password strength is calculated based on the following criteria:
- Strong (Green): Contains uppercase, lowercase, and either numbers or symbols with length ≥ 8
- Medium (Yellow): Contains either uppercase or lowercase with numbers or symbols and length ≥ 6
- Weak (Red): Any other combination

## Installation

No installation required! Simply clone the repository and open `index.html` in your web browser:

```bash
git clone https://github.com/vikasyadav01234/password.git
cd password-generator
```

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## License

This project is open source and available for personal and commercial use.
