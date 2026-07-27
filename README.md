# My Portfolio

A personal portfolio website with a login page, project showcase, and embedded YouTube video demos — built with plain HTML, CSS, and JavaScript, and deployed via GitHub Pages.

🔗 **Live site:** https://claviopoernama.github.io/building-portfolio/

## Features

- **Login page** – glassmorphism-style sign-in screen (`index.html`)
- **Dashboard** – profile section, project cards, and embedded video demos (`dashboard.html`)
- **Responsive design** – adapts to mobile, tablet, and desktop screens
- **No frameworks** – pure HTML/CSS/JS, easy to read and customize

## Folder Structure

```
portfolio/
│
├── index.html          # Login page
├── dashboard.html       # Profile + projects + videos
├── styles.css            # Shared styles
├── README.md
└── assets/                # Images, profile photo, icons
```

## Tech Stack

- HTML5
- CSS3 (custom properties, glassmorphism, flexbox/grid, responsive media queries)
- Vanilla JavaScript
- [Font Awesome](https://fontawesome.com/) for icons
- GitHub Pages for hosting

## Running Locally

1. Clone the repo:
   ```
   git clone https://github.com/claviopoernama/building-portfolio.git
   ```
2. Open the folder in VS Code (or any editor).
3. Open `index.html` in your browser, or right-click → **Open with Live Server**.
4. Log in with:
   - Username: `admin`
   - Password: `123456`

> Note: Login credentials are hard-coded client-side for demo purposes only — this is not a secure authentication system.

## Customization

- Edit profile info, project cards, and video links directly in `dashboard.html`.
- Update colors, fonts, and layout in `styles.css`.
- Add a profile photo by placing an image in `assets/` and updating the `<img>` tag in `dashboard.html`.

## Deployment

Deployed via **GitHub Pages**:
1. Push changes to the `main` branch.
2. GitHub → repo **Settings** → **Pages** → set branch to `main`.
3. Site goes live at `https://claviopoernama.github.io/building-portfolio/`.

## Author

**Clavio Poernama**
