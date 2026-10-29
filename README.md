# 🌐 Personal Portfolio Website

This is my **personal portfolio website**, built with **HTML**, **CSS**, and **JavaScript**.
It’s a web version of my CV — created to present my **skills**, **experience**, and **projects** in a modern, professional layout.

---

## 🚀 Features
- Clean and elegant design  
- Fully responsive layout  
- Static site with no package installation or build step
- Easy to update or extend  
- Includes sections for About, Skills, Experience, and Contact

---

## 🛠️ Built With
- **HTML5**
- **CSS3** and Tailwind CSS (loaded from a CDN)
- **JavaScript**, including particles.js (loaded from a CDN)
- Google Fonts and Font Awesome (loaded from CDNs)

---

## 📂 Project Structure

```text
MyPortfolio/
├── index.html       # Page markup, inline styles, and inline JavaScript
├── *.jpg / *.JPG    # Photos stored directly in the repository root
├── art-14-3.png     # Portrait image
└── README.md        # Project documentation
```

There is no separate `style.css` file or `images/` directory. Keep image paths and filename capitalization consistent with `index.html`, especially when hosting on a case-sensitive server.

---

## 🖥️ Local preview

With Python 3 installed, run this from the repository root:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open **http://127.0.0.1:8000/** in a browser. Stop the server with **Ctrl+C** when finished. This serves a local preview; it does not publish the site.

No npm install, build command, backend, API key, or environment file is needed. Internet access is needed for Tailwind CSS, particles.js, Google Fonts, Font Awesome, and the externally hosted image in the page; an offline preview may have missing styles, icons, animation, or imagery.

Edit `index.html` to update content, inline styles, and interactions. Keep the referenced photos beside it, then refresh the browser to see changes.

---

## 🌟 Live Demo
🔗 [View Portfolio](https://mirora95.github.io/MyPortfolio/)

> (If the link doesn’t work yet, enable GitHub Pages:  
> Go to **Settings → Pages → Branch: main → Save**)

---

## 👩‍💻 Author
**Orasta Mirdadoeva**  
💼 [LinkedIn](https://www.linkedin.com/in/orasta-mirdadoeva)  
🐙 [GitHub](https://github.com/mirora95)

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
