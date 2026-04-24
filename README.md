# Login-Form-96

A clean glassmorphism login form built with HTML, CSS and a small amount of JavaScript (for progressive enhancement). This repository contains a responsive login UI that uses a blurred background image and iconography for a modern look-and-feel.


## Preview

![Login Form Screenshot](./Screenshot%202024-08-06%20090457.png)


## Features

- Simple, lightweight HTML + CSS layout
- Glassmorphism style with backdrop blur and translucent border
- Icon support via Ionicons CDN
- Responsive centre-aligned form that works on desktop and mobile


## Files

- `index.html` — markup for the login page
- `style.css` — styling for layout, glass effect and form interactions
- `Screenshot 2024-08-06 090457.png` — preview screenshot used in this README
- `mountain-peak-rises-majestically-nature-landscape-generative-ai.jpg` — background image


## How to run

1. Clone the repository or download the ZIP.

   git clone https://github.com/BinaryVortex/Login-Form-96.git

2. Open `index.html` in your browser (no server required):

   - Double-click `index.html`, or
   - Run a simple HTTP server if you prefer (example with Python):
     - Python 3: `python -m http.server 8000`
     - Then open `http://localhost:8000` in your browser.


## How to customize

- Background: Replace `mountain-peak-rises-majestically-nature-landscape-generative-ai.jpg` with any image and adjust `background-position`/`background-size` in `style.css`.
- Fonts: The project uses the Poppins font imported from Google Fonts. Change the import at the top of `style.css` to switch fonts.
- Icons: Ionicons are loaded from a CDN in `index.html`. You can remove or swap them with other icon libraries (Font Awesome, Remix Icon, etc.).
- Inputs & Validation: The current markup uses `required` attributes for inputs. Add JavaScript for client-side validation, or wire the form `action` to your authentication endpoint.


## Accessibility & Improvements

- Add `label` `for` attributes and matching `id` values to inputs to improve accessibility.
- Provide visible focus styles for keyboard users.
- Use semantic form controls and ARIA attributes where appropriate.


## Notes

- This repository contains only the front-end UI for a login form. It does not implement server-side authentication — do not use this alone to authenticate users in production.


## Contributing

Contributions are welcome. Feel free to open issues or submit pull requests to improve styling, accessibility, or add examples.


## License

No license specified. If you want to make this project open-source, consider adding an OSI-approved license such as MIT.
