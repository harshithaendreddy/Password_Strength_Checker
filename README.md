This project is a simple password strength checker built using HTML, CSS, and JavaScript. The web application allows users to enter a password, and it provides immediate feedback on the strength of the password based on certain criteria. Additionally, the application has an option to toggle password visibility.

Features
Password Strength Indicator: The application provides feedback on whether the password is strong or weak. The strength is determined based on criteria like length, uppercase letters, numbers, and special characters.
Toggle Password Visibility: Users can toggle between showing and hiding the password with an eye icon.
Responsive Design: The password strength checker container is centered on the screen, and the design is responsive.

Getting Started
Prerequisites
You need a modern web browser to run this password strength checker. No additional libraries or frameworks are required.

Running the Project
Clone the repository or download the files:

Clone: git clone <repository-url>
Download the files as a ZIP and extract them.
Open the HTML File:

Locate the index.html file in the project directory.
Open the index.html file in your web browser.
Files Included
index.html: The main HTML file that contains the structure of the password strength checker.
Inline CSS: The CSS styling is included in the <style> tag within the HTML file.
JavaScript: JavaScript functionality is provided in a <script> tag inside the HTML file

Usage
Open the Password Strength Checker:

Use your browser to open the index.html file.
Enter a Password:

Enter your desired password in the input field. As you type, a strength indicator will be shown below the input field.
Check Password Strength:

The password strength will be evaluated based on the following criteria:
Length is at least 8 characters.
Contains at least one uppercase letter.
Contains at least one number.
Contains at least one special character (e.g., !@#$%^&*).
If the password meets all criteria, it is marked as "Strong" with a green checkmark (✔️). Otherwise, it is marked as "Weak" with a red cross (❌).
Toggle Password Visibility:

Click the eye icon (👁️) to toggle between showing and hiding the password.
Project Structure
The password strength checker is composed of the following components:

HTML: Provides the structure of the page.

The password input field, the toggle button (👁️), and the strength message container.
CSS: Inline CSS is used to style the page and its components.

The main container is centered vertically and horizontally.
The password input and the feedback message are styled for better readability.
JavaScript: Adds interactivity to the page.

The checkPasswordStrength() function is used to evaluate the strength of the password.
Event listeners handle the password visibility toggle and the password strength evaluation.


![image](https://github.com/user-attachments/assets/bc52ec3e-78fc-415b-a405-052774110335)

