

## ⚙️ Implementation Details:
- **Setup**: The project was built using **Vite** for a fast and modern development experience.
- **Components**: The `LoginForm` component is a functional component that uses `useState` to manage email and password inputs. It handles form submission with an `onSubmit` event, logging the input values to the console and displaying an alert (`"Logged in!"`).
- **Styling**: Styles are implemented using **CSS modules** (`LoginForm.module.css` and `App.module.css`) to ensure scoped, modular styling. The original `style.css` was adapted to maintain the same look and feel.
- **JSX Conversion**: The provided `index.html` was converted to valid JSX within `LoginForm.jsx` and `App.jsx`, following React best practices.
- **No UI Libraries**: The solution uses plain React and CSS, with no external UI libraries like Bootstrap or MUI.
- **Form Handling**: The form submission triggers a `console.log` of the input values and an alert, as real login logic was not required.

To run the project locally:
1. Clone the repository: `git clone https://github.com/Atanurag/bugflows-react-challenge.git`
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`
4. Open `http://localhost:5173` to view the application.



Deadline: Within **24 hours** of receiving this challenge.

---

## 🛠️ Approach Notes:
- **Tool Choice**: Chose Vite over Create React App for faster build times and a modern development experience.
- **Modularity**: Used CSS modules to scope styles to components, preventing conflicts and improving maintainability.
- **Error Handling**: Ensured the form is controlled with `useState` for robust input management.
- **Version Control**: Resolved Git issues (e.g., unrelated histories) by merging or force-pushing as needed to align local and remote repositories.

Good luck, and thank you for the opportunity!
