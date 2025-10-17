# Passwors-strength-Checker
A responsive and interactive password strength checker built with vanilla JavaScript, HTML, and CSS. Provides real-time visual feedback, a dynamic criteria checklist, and helpful tips for creating secure passwords.
******************************************************************************************************************************************

# Password Strength Checker 🛡️

An interactive, client-side password strength assessment tool designed to provide instant feedback to users. This project helps users create stronger, more secure passwords by evaluating them against a set of criteria in real-time.



Features

* **Real-Time Analysis**: The password strength is evaluated instantly as you type.
* **Visual Strength Meter**: A color-coded progress bar provides an immediate visual representation of the password's strength (from Very Weak to Very Strong).
* **Dynamic Criteria Checklist**: An interactive checklist updates to show which requirements have been met (e.g., length, uppercase, numbers, special characters).
* **Password Visibility Toggle**: Users can easily show or hide the password text to verify their input.
* **Actionable Feedback**: Clear, text-based feedback and tips are provided to guide the user in improving their password.
* **Modern & Responsive UI**: Clean, modern interface built to be fully responsive and user-friendly on any device.
* **Zero Dependencies**: Built with pure vanilla JavaScript, HTML, and CSS—no external libraries or frameworks needed.

## Tech Stack

* **HTML5**: For the structure and content of the web page.
* **CSS3**: For styling, including the gradient background, responsive layout, and animations.
* **Vanilla JavaScript**: For all the logic, including DOM manipulation, event handling, and strength calculation.
* **Font Awesome**: For the criteria checklist icons.

## Getting Started

To run this project locally, follow these simple steps:

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd your-repo-name
    ```

3.  **Open the HTML file:**
    Simply open the `pswdstrength.html` file in your favorite web browser.

That's it! You can now start testing password strengths.

## How It Works

The strength of the password is calculated based on a scoring system. The script checks for the following five criteria:

1.  **Length**: At least 12 characters.
2.  **Uppercase Letters**: Contains one or more uppercase letters (`A-Z`).
3.  **Lowercase Letters**: Contains one or more lowercase letters (`a-z`).
4.  **Numbers**: Contains one or more numbers (`0-9`).
5.  **Special Characters**: Contains one or more special characters (e.g., `!@#$%^&*`).

Each met criterion adds 20 points to a total score. An additional bonus is given for passwords longer than the 12-character minimum. The final score determines the strength level and the color of the feedback meter.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
