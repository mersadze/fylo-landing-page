# Frontend Mentor - Fylo Landing Page (Two Column Layout)

This is my solution to the [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). It helped me practice responsive layout, mobile-first design, and semantic HTML structure.

## 📑 Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

---

## 📌 Overview

### The Challenge

Users should be able to:

- View the site properly across different device screen sizes
- See hover states on all interactive elements

## 🛠 My Process

### 🧱 Built With

- Semantic **HTML5**
- **CSS3** custom properties
- **Flexbox**
- **Mobile-first** workflow
- Responsive design using media queries

### 💡 What I Learned

This project helped me:

- Improve my understanding of **mobile-first design**
- Practice clean layout using **Flexbox**
- Understand how to use relative units like `rem`, `em`, `%` instead of fixed `px` values for responsiveness
- Spot and fix layout issues using **Chrome Dev Tools**

```css
.hero-section {
  display: flex;
  flex-direction: column-reverse;
}

@media (min-width: 768px) {
  .hero-section {
    flex-direction: row;
  }
}
```

### 🔄 Continued Development

I want to get better at:

- Creating **perfectly balanced layouts** on any screen
- **Accessibility improvements** (keyboard nav, screen reader support)

### 📚 Useful Resources

- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) – Easy visual reference
- [MDN Web Docs - Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [Frontend Mentor Discord](https://discord.gg/frontendmentor) – Great for advice and feedback

---

## 👤 Author

- GitHub – [@mersadze](https://github.com/mersadze)
- Frontend Mentor – [@mersadze](https://www.frontendmentor.io/profile/mersadze)

---