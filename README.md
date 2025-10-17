# CAPTCHA Solver Web Page

This project provides a simple, dark-themed web page for solving a CAPTCHA. It features a responsive design, user input field, and a "Verify" button with a subtle hover animation. The solver logic is implemented in client-side JavaScript to demonstrate a success or failure state based on a hardcoded CAPTCHA value.

## Features

*   **Dark Theme:** Visually appealing interface with light text on a dark background.
*   **Responsive Design:** Adapts to various screen sizes using Tailwind CSS.
*   **CAPTCHA Display:** Shows the provided CAPTCHA image (`image.png`).
*   **User Input:** Allows users to enter the CAPTCHA text.
*   **Interactive Verify Button:** A circular button with a hover scale and glow animation.
*   **Client-side Logic:** Verifies the CAPTCHA input and displays immediate feedback (success/failure).

## Setup and Running

This is a single-file web application, requiring no complex build steps or server setup.

1.  **Save the files:**
    *   Save the `index.html` content into a file named `index.html`.
    *   Ensure the CAPTCHA image, `image.png`, is in the **same directory** as `index.html`.
    *   (Optional but recommended) Save `README.md` and `LICENSE` in the same directory.

2.  **Open in browser:** Simply open the `index.html` file with your web browser (e.g., Chrome, Firefox, Edge). You can do this by:
    *   Double-clicking the `index.html` file.
    *   Right-clicking `index.html` and selecting "Open with..." your preferred browser.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS (CDN):** For utility-first styling and responsive design.
*   **JavaScript:** For interactive elements and CAPTCHA verification logic.

## CAPTCHA Value

The expected CAPTCHA text for this demonstration is `V4XBG` (case-insensitive), as derived from the provided `image.png`.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.