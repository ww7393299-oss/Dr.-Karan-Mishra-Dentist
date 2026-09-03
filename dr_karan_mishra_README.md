# Dr. Karan Mishra — Advanced Dental Care Website

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Responsive-Yes-brightgreen?style=for-the-badge" alt="Responsive">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
</p>

<p align="center">
  <b>A professional, fully responsive single-page dental clinic website with a clean red & white medical theme.</b>
</p>

<p align="center">
  <a href="#live-demo">🚀 Live Demo</a> •
  <a href="#features">✨ Features</a> •
  <a href="#screenshots">📸 Screenshots</a> •
  <a href="#customization">🎨 Customize</a> •
  <a href="#deployment">🚀 Deploy</a>
</p>

---

## 🦷 About The Project

**Dr. Karan Mishra — Advanced Dental Care** is a modern, professional, and fully responsive single-page website designed for dental clinics and healthcare professionals. Built entirely with **HTML5**, **CSS3**, and **vanilla JavaScript** — no frameworks, no dependencies (except Google Fonts & Font Awesome CDN).

This template is perfect for dentists, dental surgeons, orthodontists, prosthodontists, and multi-specialty dental clinics looking to establish a strong online presence.

### 🌟 Key Highlights
- ⚡ **Zero dependencies** — Pure HTML/CSS/JS
- 📱 **Fully responsive** — Perfect on mobile, tablet, and desktop
- 🎨 **Clean red & white medical theme** — Professional healthcare aesthetic
- 📅 **Online appointment booking form** — Patients can book directly
- 🦷 **Services showcase** — 8 dental treatments with hover cards
- 👨‍⚕️ **Doctor profile section** — Credentials, expertise, and bio
- 📸 **Before/After gallery** — Showcase treatment results
- ✨ **Smooth scroll animations** and hover effects

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Hero Section** | Eye-catching banner with experience badge, stats counter, and dual CTA buttons |
| **About Clinic** | Clinic introduction with feature highlights, quote box, and dual images |
| **Doctor Profile** | Full profile card with photo, B.D.S./M.D.S. credentials, expertise grid, and CTA |
| **Services/Treatments** | 8 service cards with hover effects — Implants, Root Canal, Cosmetic Dentistry, Fillings, Braces, Child Dentistry, Laser Dentistry, Full Mouth Rehab |
| **Why Choose Us** | Dark-themed feature grid highlighting Expert Dentist, Advanced Tech, Patient First, Sterile Environment, Affordable Care, Flexible Timing |
| **Before/After Gallery** | Transformation showcase with overlay badges |
| **Appointment CTA** | Bold red call-to-action banner |
| **Contact Form** | Full booking form with name, phone, email, treatment selection, date picker, and message |
| **Sticky Navigation** — Transparent navbar with smooth anchor links |
| **Mobile Menu** | Full-screen hamburger menu for mobile devices |
| **Scroll Animations** | Elements fade in smoothly as you scroll down the page |

---

## 📸 Screenshots

> *Add your own screenshots here by replacing the links below*

<p align="center">
  <img src="screenshots/hero.png" width="80%" alt="Hero Section">
  <br><br>
  <img src="screenshots/services.png" width="80%" alt="Services Section">
  <br><br>
  <img src="screenshots/contact.png" width="80%" alt="Contact Form">
</p>

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties (variables), Flexbox, CSS Grid, animations
- **JavaScript (ES6+)** — DOM manipulation, scroll events, form handling
- **Google Fonts** — Poppins
- **Font Awesome 6** — Icons

---

## 🚀 Getting Started

### Prerequisites

You only need a modern web browser. No build tools, no npm, no bundler required!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/dr-karan-mishra-dental.git
   cd dr-karan-mishra-dental
   ```

2. **Open in browser**
   ```bash
   # Simply open the HTML file
   open index.html

   # Or serve locally (optional)
   npx serve .
   ```

> 💡 **Tip:** For the best development experience, use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code.

---

## 🎨 Customization Guide

### 1. Change Doctor Name
Search and replace all instances of **"Dr. Karan Mishra"** with the actual doctor's name.

### 2. Update Contact Details
Find these sections and update:
- Phone number: `+91 12345 67890`
- Email: `dr.karanmishra@email.com`
- Clinic Address: `123 Dental Care Lane, Main Road`
- Working hours

### 3. Replace Images
All images are loaded from Unsplash via URL. Replace them with your own clinic/doctor photos:
```html
<img src="YOUR_IMAGE_URL" alt="Description">
```

### 4. Update Services
Find the `<div class="services-grid">` section and edit treatment names, descriptions, and icons.

### 5. Update Doctor Credentials
Edit the doctor profile section with actual:
- Degrees (B.D.S., M.D.S., etc.)
- Specialization
- Years of experience
- Areas of expertise
- Bio

### 6. Change Brand Colors
Edit the CSS variables at the top of the `<style>` tag:
```css
:root {
  --primary: #c41e3a;      /* Primary red accent */
  --primary-dark: #a01830; /* Darker red for hover */
  --dark: #1a1a2e;         /* Dark text color */
  --light-gray: #f8f9fa;   /* Light background */
}
```

### 7. Add Your Social Links
Update the social media links in the footer:
```html
<a href="YOUR_FACEBOOK_URL"><i class="fab fa-facebook-f"></i></a>
<a href="YOUR_INSTAGRAM_URL"><i class="fab fa-instagram"></i></a>
<a href="YOUR_WHATSAPP_URL"><i class="fab fa-whatsapp"></i></a>
```

---

## 🚀 Deployment

### GitHub Pages (Recommended — Free)

1. Go to your repository **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Select the `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://YOUR_USERNAME.github.io/dr-karan-mishra-dental/`

### Netlify (Drag & Drop)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site is live instantly!

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

---

## 📁 Project Structure

```
dr-karan-mishra-dental/
├── index.html          # Main HTML file (single page)
├── README.md           # This file
├── LICENSE             # MIT License
└── screenshots/        # Add your screenshots here
    ├── hero.png
    ├── services.png
    └── contact.png
```

> **Note:** This is a single-file website. All HTML, CSS, and JavaScript are contained in `index.html` for simplicity. You can split them into separate files if you prefer.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or find a bug, feel free to:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use it for personal or commercial projects.

```
MIT License

Copyright (c) 2024 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 📞 Contact

**Dr. Karan Mishra — Advanced Dental Care**  
📍 123 Dental Care Lane, Main Road, Near City Center  
📞 [+91 12345 67890](tel:+911234567890)  
📧 [dr.karanmishra@email.com](mailto:dr.karanmishra@email.com)  
🌐 [www.drkaranmishra.com](https://www.drkaranmishra.com)

<p align="center">
  Made with ❤️ for healthier smiles
</p>

---

<p align="center">
  <b>⭐ Star this repo if you found it helpful!</b>
</p>
