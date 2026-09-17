# MD Oyasim Raja - Robotics & AI Engineer Portfolio

Welcome to the source code of my personal portfolio website! This repository contains the full HTML, CSS, and JavaScript source for my professional portfolio, highlighting my experience, technical skills, and projects in the field of AI, Robotics, and Sim-to-Real development.

## 🚀 Live Demo
*(Your GitHub Pages URL will go here once deployed, e.g., https://oyasimraja1316.github.io/My_portfolio/)*

## 🛠️ Technologies Used
- **HTML5 & CSS3**
- **Vanilla JavaScript**
- **Bootstrap 5** (Layout and Grid)
- **Vendor Libraries:** AOS (Animations), GLightbox (Image/Video Popups), Swiper (Carousels), Typed.js (Typing effects)

---

## 💻 Running the Portfolio Locally

You don't need any complex build steps or Node.js to run this locally! It is pure frontend code.

1. Clone or download this repository.
2. Open the folder in your terminal.
3. Start a simple local server. If you have Python installed, you can use:
   ```bash
   python3 -m http.server 8000
   ```
4. Open your web browser and visit `http://localhost:8000`.

*(Alternatively, you can just double-click the `index.html` file to open it directly in your browser!)*

---

## 🌐 Deploying to GitHub Pages (For Free)

If you fork this repository and want to host your own version of it for free using GitHub Pages, follow these steps:

### Step 1: Push to GitHub
If you haven't already, initialize git, commit your files, and push them to a new repository on your GitHub account:

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub.com.
2. Click on the **Settings** tab (the gear icon near the top right).
3. On the left sidebar, scroll down and click on **Pages**.
4. Under the "Build and deployment" section, find the **Source** dropdown and select `Deploy from a branch`.
5. Under the **Branch** dropdown, select your `main` (or `master`) branch, leave the folder as `/root`, and click **Save**.

Wait about 1-2 minutes, refresh the page, and GitHub will provide you with a live link to your website!

---

## 📝 Customization Guide

If you are using this as a base for your own portfolio, here is what you need to edit:
- **`index.html`:** This is the main file. Search for the text you want to change (like names, skills, and about paragraphs) and replace it. 
- **Adding Images:** Drop your images into the `assets/img/` folder and update the file paths (`src="..."`) in the HTML file.
- **Videos:** The portfolio supports inline video popups! Just link a YouTube, Vimeo, or local `.mp4` file in the lightbox anchor tag (`href="..."`).

## 📄 Credits
The layout and structure of this portfolio are heavily customized from the free open-source "iPortfolio" Bootstrap template. All vendor libraries (Bootstrap, AOS, GLightbox, Isotope, Swiper, Typed.js, Boxicons) are included in `assets/vendor/` under their respective open-source licenses.
