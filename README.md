# Portfolio Website

## Overview
A responsive single-page portfolio website built to showcase web development, UI/UX, and 3D integration skills. This project fulfills internship requirements for a modern, interactive, and visually appealing portfolio with a mandatory 3D model.

## Features
- **Hero Section:** Name, role, 3D spinning cube with profile photo, call-to-action button
- **About Section:** Introduction and profile picture
- **Projects Section:** 5 projects with images, descriptions, and links
- **Certificates Section:** Responsive gallery of certificates
- **Contact Section:** Validated contact form
- **3D Model Integration:** Interactive 3D cube using Three.js and OrbitControls
- **Modern UI:** Glassmorphism, responsive design, and accessibility

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **3D Library:** Three.js (via CDN)
- **Other Tools:** OrbitControls, FontLoader, TextGeometry (Three.js examples)

## Folder Structure
```
/portfolio
  ├── css/
  │     └── styles.css
  ├── js/
  │     └── script.js
  ├── images/
  │     ├── profile.jpg
  │     ├── project1.jpg
  │     ├── project2.jpg
  │     ├── project3.jpg
  │     ├── project4.jpg
  │     ├── project5.jpg
  │     ├── certificate1.jpg ... certificate8.jpg
  ├── index.html
  └── README.md
```

## 3D Model Integration
- **Method:** Three.js (CDN)
- **Location:** Hero section
- **Description:** Interactive spinning 3D cube with your profile photo as the texture. Users can rotate/zoom the cube using OrbitControls.
- **How it works:**
  - Three.js and OrbitControls are loaded via CDN in `index.html`.
  - The cube is created and textured in `js/script.js`.
  - OrbitControls allow user interaction with the cube.

## Setup Instructions
1. **Clone or download the repository.**
2. **Ensure your folder structure matches the above.**
3. **Add your images:**
   - `images/profile.jpg` (your photo)
   - `images/project1.jpg` ... `project5.jpg` (project images)
   - `images/certificate1.jpg` ... (certificate images)
4. **Start a local server:**
   ```sh
   python3 -m http.server 8000
   ```
5. **Open your browser at:**
   [http://localhost:8000](http://localhost:8000)
6. **Do a hard refresh** if you update images or scripts.

## Deployment
- You can deploy this site to GitHub Pages, Vercel, or Netlify.
- Make sure all images are included in the `images` folder.
- No build step is required; it is a static site.

## Accessibility & Code Quality
- Semantic HTML and alt attributes for all images
- Responsive design for all devices
- Well-commented and modular code

## Contact Information
- **Email:** [dhanraj.t1616@gmail.com](mailto:dhanraj.t1616@gmail.com)
- **Phone:** +91 8106518591
- **LinkedIn:** [Thipirishetty Dhanraj](https://www.linkedin.com/in/thipirishetty-dhanraj/)
- **GitHub:** [dhanraj1912](https://github.com/dhanraj1912)

## Credits
- [Three.js](https://threejs.org/) for 3D rendering
- [unpkg CDN](https://unpkg.com/) for reliable script delivery

---
