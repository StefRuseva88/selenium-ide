# Selenium IDE
### This is a test project for Front-End Test Automation July 2024 Course @ SoftUni

[![Google Chrome](https://img.shields.io/badge/tested%20on-Google%20Chrome-4285F4.svg)](https://www.google.com/chrome/)
[![Mozilla Firefox](https://img.shields.io/badge/tested%20on-Mozilla%20Firefox-FF7139.svg)](https://www.mozilla.org/firefox/)
[![Selenium IDE](https://img.shields.io/badge/tested%20with-Selenium%20IDE-FF6C37.svg)](https://www.selenium.dev/selenium-ide/)

## Getting Started
This project demonstrates my skills in using Selenium IDE, a record-and-playback tool, to quickly create and execute UI tests without needing to write code manually. Selenium IDE allows for easy test case creation and provides a way to export these tests into different programming languages if further customization is required.

### Prerequisites
- Selenium IDE for creating and managing test scripts.
- Chrome or Firefox with Selenium IDE installed for browser compatibility.
- Developer Tools: Use for copying text assertions and debugging.

### Key Features:
- Creating automated tests through recording user interactions with the browser.
- Exporting test scripts in different formats, such as C# with WebDriver code.
- Running automated tests directly from the browser to quickly verify web functionalities.
- Integrating with GitHub Actions for continuous testing and reporting.

### Running Tests
To run these tests, import the scripts into Selenium IDE and execute. Tests are organized by functionality, allowing targeted validation.

### Notes
- Adjust Chrome security settings for smooth testing when using hardcoded credentials.
- For Firefox, the Google Password Manager interference is minimized.
  
## Project Sections

### Number Calculator
This test suite covers the following validations:
- **Input Validation**: Ensures numeric-only input fields, checks for error messages on invalid inputs, and verifies handling of empty fields.
- **Operation Selection**: Confirms all mathematical operations (Sum, Subtract, Multiply, Divide) are selectable and assertable.
- **Calculation**: Validates correctness of calculation results across operations.
- **Reset Functionality**: Tests the reset button’s ability to clear inputs and selections.
- **Edge Cases**: Handles divide-by-zero, negative numbers, decimals, and spacing issues.

### CURA Health Care Service
This test suite covers the following validations:
- **Footer Verification**: Confirms the footer text and element presence.
- **Login and Logout**: Validates login with proper credentials and log-out redirection.
- **Appointment Booking**: Tests appointment form with field selections, submission, and confirmation page verification.

### Saucedemo
This test suite covers the following validations:
- **Login with Invalid User and Retry**: Implements conditional login retry after invalid credentials.
- **Add to Cart**: Logs in, adds an item, and verifies cart contents.
- **Remove from Cart**: Validates item removal after adding to the cart.
   
## Additional Resources
- [Selenium IDE Commands Reference](https://www.selenium.dev/selenium-ide/docs/en/api/commands)

### Important Browser Settings
For testing with Chrome:
- **Password Breach Warnings**: Disable temporarily in Chrome’s Privacy & Security settings by selecting “Standard protection.”
- **Script Pause for Manual Pop-Up Handling**: Use pauses for handling pop-ups.
  
## Contributing
Contributions are welcome! If you have any improvements or bug fixes, feel free to open a pull request.

## License
This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, please open an issue in the repository.

---
### Happy Testing! 🚀
