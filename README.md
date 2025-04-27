# Grovia-N

<p align="center">
  <a href="https://getbootstrap.com/"><img src="https://img.shields.io/badge/Built%20with-Bootstrap-blue.svg" alt="Bootstrap Badge"></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/Styled%20with-TailwindCSS-38B2AC.svg" alt="Tailwind CSS Badge"></a>
  <a href="https://www.npmjs.com/package/canvas-confetti"><img src="https://img.shields.io/badge/Animation-CanvasConfetti-ff69b4.svg" alt="Confetti Badge"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License Badge"></a>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen.svg" alt="Active Badge">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-red.svg" alt="Love Badge">
</p>

---

**Grovia-N** is a sleek, modern web application designed to provide secure access to a server through a user-friendly interface.  
Built with **HTML**, **JavaScript**, **Bootstrap**, and **Tailwind CSS**, it features a dynamic particle animation background, a responsive access request form, and real-time server link updates from a JSON file.

👉 Hosted at [github.com/quark365/Grovia-N](https://github.com/quark365/Grovia-N).

👉 **Live Demo**: [https://quark365.github.io/Grovia-N/](https://quark365.github.io/Grovia-N/)

---

## ✨ Features

- **Responsive Form**: Submit access requests with name, email, and message fields, integrated via [Formsubmit.co](https://formsubmit.co/).
- **Dynamic Particle Animation**: Interactive background responding to mouse movement.
- **Real-Time Link Updates**: Automatically fetches and displays the latest server link from `link.json` every 10 seconds.
- **Modern Styling**: Combines Bootstrap and Tailwind CSS for a polished, gradient-themed UI with hover effects.
- **Success Feedback**: Displays a confirmation message with a confetti animation upon form submission.
- **Accessibility**: Optimized for all screen sizes with a mobile-friendly responsive design.

---

## 🗂️ File Structure

```
Grovia-N/
├── index.html        # Main HTML file with form and particle animation
├── link.json         # JSON file containing the server URL
└── README.md         # Project documentation
```

---

## ⚙️ Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge)
- Internet access to load CDN-hosted libraries (Bootstrap, Tailwind CSS, canvas-confetti)
- (Optional) A local server for development (e.g., VS Code Live Server extension)

---

## 🚀 How to Clone and Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/quark365/Grovia-N.git
   cd Grovia-N
   ```

2. **Serve the Application Locally:**

   - **Option 1:** Open `index.html` directly in your browser.
     > ⚠️ Some browsers may block fetching `link.json` due to CORS if opened without a server.
   
   - **Option 2:** Use a local server:
     ```bash
     npx http-server
     ```
     Then navigate to `http://localhost:8080` in your browser.

   (You can also use **Live Server** extension in Visual Studio Code.)

3. **Or Visit the Live Demo:**

   👉 [https://quark365.github.io/Grovia-N/](https://quark365.github.io/Grovia-N/)

4. **Interact with Grovia-N:**
   - View the real-time server link at the top.
   - Fill out the form and submit an access request.
   - Enjoy the confetti animation on success!

---

## 💬 Usage

- **Access Request Form**: Enter your name, email, and message to submit an access request through [Formsubmit.co](https://formsubmit.co/).
- **Server Link Display**: Displays the current server link, updated every 10 seconds from `link.json`.
- **Interactive Background**: Move your mouse to interact with the dynamic particle animation.

---

## 📦 Dependencies

Grovia-N uses the following CDN-hosted libraries:

- [Bootstrap 5.3.3](https://getbootstrap.com/) — Responsive layout and form components
- [Tailwind CSS 2.2.19](https://tailwindcss.com/) — Utility-first CSS framework
- [canvas-confetti 1.6.0](https://www.npmjs.com/package/canvas-confetti) — Confetti animation on successful form submission

_No local installation needed — all dependencies are loaded via CDN._

---

## 🤝 Contributing

We welcome contributions! 🚀

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your fork:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a Pull Request.

Please ensure your code is clean, documented, and tested thoroughly before submitting.

---

## 📜 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).  
See the [LICENSE](https://github.com/quark365/Grovia-N/blob/main/LICENSE) file for full details.

---

## 📬 Contact

For questions, suggestions, or feedback:

- Open an issue [here](https://github.com/quark365/Grovia-N/issues)
- Or contact the maintainer at [quark365](https://github.com/quark365)

---

Built with ❤️ by the **Moon Knight Team** for **secure server access**.

---
