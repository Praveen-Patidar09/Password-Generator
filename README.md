Password Generator
A responsive and secure Password Generator application built with React, Tailwind CSS, and Vite. This project focuses on implementing React hooks to manage application state and optimize performance.

Features
Customizable Length: Easily adjust the password length (6–100 characters) using a slider.

Security Toggles: Options to include or exclude numbers and special characters.

One-Click Copy: Quickly copy the generated password to your clipboard.

Dynamic Generation: Real-time password generation based on user preferences.

Tech Stack
Frontend: React, Tailwind CSS

Build Tool: Vite

Hooks Used:

useState - For managing password state and user preferences.

useCallback - To memoize the generation function for performance optimization.

useEffect - To trigger password regeneration when dependencies change.

useRef - For DOM manipulation to enable the copy-to-clipboard functionality.