# 🔐 React Login & Signup Toggle Form

A modern, high-fidelity Login and Signup interface built with **React** and **CSS**. This project features a professional purple gradient design and a dynamic toggle system that updates the UI based on the user's selection.

---

## 🚀 Features

*   **Dynamic Toggle:** Smoothly switch between "Sign Up" and "Login" modes.
*   **Conditional Rendering:** 
    *   The **Name** field automatically hides when in "Login" mode.
    *   The **Lost Password** link only appears in "Login" mode.
*   **Interactive UI:** Buttons change color (active vs. inactive/gray) to provide clear user feedback.
*   **Perfect Centering:** Uses CSS Flexbox to ensure the form is perfectly centered on all screen sizes.
*   **Modern Styling:** Includes a linear gradient background and custom input icons.

---

## 🛠️ Tech Stack

*   **Framework:** React.js
*   **Styling:** CSS3 (Flexbox & Transitions)
*   **Assets:** Custom Icon PNGs (User, Email, Password)

---

## 📂 Project Structure

```text
src/
├── Assets/              # Input icons (person.png, email.png, etc.)
├── Components/
│   ├── LoginSignup.jsx  # Component logic & State management
│   └── LoginSignup.css  # Layout & Theme styling
└── App.js               # Main Application entry
