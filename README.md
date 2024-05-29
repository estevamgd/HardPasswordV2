## Hard Password Generator

This Python application generates strong and secure passwords using a unique mathematical function.

**Features:**

* **Secure password generation:** Utilizes a customizable function to transform user input into a complex, randomly generated password.
* **User-friendly interface:** Features masked password inputs, clear feedback via snackbars, and easy copy functionality.
* **Customizable algorithm:** Allows users to adjust the coefficients of the function to personalize the password generation process.

**Usage:**

1. **Install dependencies:** 
   ```bash
   pip install flet pyperclip
   ```
2. **Run the script:** 
   ```bash
   python main.py
   ```

**How it Works:**

The application uses a custom function that combines user-input numbers with three customizable coefficients (terms) to generate a secure password. The function performs operations like squaring, multiplying, and adding the input numbers, resulting in a unique password.

**Customization:**

* **Coefficients (Terms):** Users can adjust the three terms (Term 1, Term 2, Term 3) to personalize the password generation algorithm.
* **Input Numbers:** Users can input any sequence of numbers to be transformed into a password.

**Security:**

The application utilizes a mathematical function to generate a password, ensuring randomness and complexity. The generated passwords are not stored or transmitted, making the process secure.

**Note:** This is a basic implementation and should not be used for critical security applications.

**Future Features:**

- [ ] **Save function and password:** Allow users to save the generated function and password to a text file for later retrieval.
- [ ] **Save user settings:** Store the user's preferred function coefficients for the next session.
- [ ] **Version 3: Website:** Create a web-based version of the password generator for wider accessibility.

**Contributions:**

Contributions are welcome! Please feel free to submit issues or pull requests for improvements and enhancements.


