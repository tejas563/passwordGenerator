# Password Generator
A simple and customizable password generator built using React.js. The application allows users to generate secure passwords with adjustable length and options to include numbers and special characters.

## Features
Generate passwords of customizable length (from 6 to 100 characters).
Option to include numbers and special characters.
One-click password copy to clipboard functionality.
Dynamic password generation based on the selected settings.

## Hooks Used
useState: For managing the state of the password length, number inclusion, character inclusion, and the generated password.
useCallback: To memoize the password generation and copy functions for performance optimization.
useRef: To reference the password input for copying the password to the clipboard.
useEffect: To trigger password generation whenever the length, number inclusion, or character inclusion settings change.

