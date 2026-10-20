# 🛍️ RedStore – Responsive E-commerce Website

A clean, modern, and fully responsive **front-end e-commerce landing page** for a sports and fitness apparel brand. Built with plain **HTML, CSS, and JavaScript** – no frameworks, no build tools, no dependencies to install.

> Give your workout a new style! 💪

---

## ✨ Features

- **Hero section** with a call-to-action and gradient background
- **Featured categories** showcase
- **Featured & Latest Products** grids with star ratings and hover animations
- **Exclusive offer banner** highlighting a promoted product
- **Customer testimonials** with lift-on-hover cards
- **Brand logos** strip with grayscale-to-color hover effect
- **Multi-column footer** with app download links, useful links, and social links
- **Mobile-friendly navigation** with a toggle (hamburger) menu
- **Responsive layout** built with Flexbox that adapts to desktop, tablet, and mobile screens

---

## 🧰 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic markup |
| CSS3 | Styling, Flexbox layout, transitions, media queries |
| JavaScript (Vanilla) | Mobile menu toggle |
| [Google Fonts – Poppins](https://fonts.google.com/specimen/Poppins) | Typography |
| [Font Awesome 4.7](https://fontawesome.com/v4/) | Rating stars and quote icons |

---

## 📁 Project Structure

```
.
├── index.html      # Page markup and content
├── style.css       # All styles, including responsive media queries
├── index.js        # Mobile menu toggle logic
└── images/         # Logos, product images, banners, icons
```
## 📱 Responsive Behavior

| Screen width | Behavior |
|---|---|
| > 800px | Full horizontal navigation bar |
| ≤ 800px | Navigation collapses into a hamburger menu that slides open and closed |
| ≤ 600px | Columns stack vertically and content is center-aligned |

---

## 🎨 Customization

- **Brand color:** The accent color `#ff523b` is used for buttons, ratings, and highlights in `style.css`. Search and replace it to re-theme the site.
- **Products:** Duplicate or edit the `.col-4` blocks in `index.html` to add or change products, names, ratings, and prices.
- **Font:** Change the Google Fonts link in the `<head>` and the `font-family` in `body` to use a different typeface.
- **Navigation links:** The `href` values in the nav and buttons are currently empty placeholders. Point them to your own pages or sections.

---

## 🗺️ Roadmap / Ideas

- [ ] Separate pages for Products, About, Contact, and Account
- [ ] Product details page
- [ ] Working shopping cart (add, remove, update quantity)
- [ ] Product filtering and sorting
- [ ] Search functionality
- [ ] Checkout flow and backend integration

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repo and open a pull request.

---

## 🙌 Acknowledgements

- Fonts by [Google Fonts](https://fonts.google.com/)
- Icons by [Font Awesome](https://fontawesome.com/)
