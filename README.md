Markdown
# Nike Modern Single-Page Application (SPA)

A high-performance, responsive single-page e-commerce web application built for Nike. It features a clean light-mode luxury aesthetic, a glassmorphism sticky navigation header, live product searching, interactive sizing controls, dynamic checkout simulation, and integrated product enquiry and support forms.

---

## 📁 Project Structure

Ensure your project root folder follows this exact directory structure so that styles and scripts link and load properly:

```text
nike-project/
│
├── css/
│   └── style.css          # Centralized modern light-mode stylesheet with glassmorphism & animations
│
├── index.html             # Complete single-page application (Home, About, Products, Enquiry, Contact)
├── logo.png               # Brand logo image file
├── running.png            # Hero section banner and product image asset
├── tshirt.png             # Product asset
├── hoodie.png             # Product asset
├── bag.png                # Product asset
├── cap.png                # Product asset
├── shorts.png             # Product asset
├── socks.png              # Product asset
└── jacket.png             # Product asset
✨ Key Features & Design Elements
Cinematic Light-Mode Aesthetic: Designed with a crisp white/light background palette, subtle shadows, and high-contrast Nike Orange (#ff3e00) accents.

Glassmorphism Navigation Header: A sticky, backdrop-blurred navigation bar that keeps your menu links and live search bar accessible as users scroll.

Smooth Page Scrolling: Single-page architecture where clicking top navigation buttons smoothly glides the viewport directly to the requested section (#home, #about, #products, #enquiry, #contact).

Live Product Search Filter: Instantaneous client-side filtering that hides or shows product cards in real time as you type into the search box.

Interactive E-Commerce Flow:

Select custom product sizes (Small, Medium, Large, or specific shoe/sock sizes) via dropdown menus.

Click "Buy Now" to transition smoothly from the catalog grid to an interactive shipping address form.

Submit the form to generate a unique randomized Order ID (e.g., NK-482910).

Customer Enquiries & Direct Contact: Fully styled forms allowing users to submit product questions or direct support messages with embedded location mapping.

🚀 Getting Started & Installation
Clone or Download all project files into a single local folder, ensuring the css/ subfolder contains style.css.

Confirm that your image asset files (running.png, tshirt.png, logo.png, etc.) are placed correctly in the root folder.

Open index.html in any modern web browser (Google Chrome, Microsoft Edge, Safari, or Firefox) to run and test the application locally.

🛠️ Built With
HTML5: Semantic markup, form controls, and accessible structure.

CSS3: Flexbox and Grid layouts, CSS custom variables, backdrop filters, and custom cubic-bezier transitions.

JavaScript (Vanilla): Dynamic view state toggling, live keyword search logic, and automated order tracking ID generators.

📄 License
© 2026 Nike, Inc. All Rights Reserved

references

Nike, Inc. (2026). Nike Official Website: Innovation, Sustainability, and Sportswear Collections. Available at: https://www.nike.com [Accessed: September 2026].

Mozilla Developer Network (MDN) (2026). HTML5 Semantic Elements and Document Structure. MDN Web Docs. Available at: https://developer.mozilla.org [Accessed: September 2026].

Mozilla Developer Network (MDN) (2026). CSS Grid Layout, Flexbox, and Backdrop Filter Properties. MDN Web Docs. Available at: https://developer.mozilla.org [Accessed: September 2026].

W3Schools (2026). JavaScript DOM Manipulation and Event Handling Reference. W3Schools Online Web Tutorials. Available at: https://www.w3schools.com [Accessed: September 2026]
[README(2).txt](https://github.com/user-attachments/files/30991483/README.2.txt)
# Nike Official Website Project

## Project Overview
This project is a responsive, multi-page website for a Nike commercial platform, designed for educational purposes. It features product listings, secure enquiry channels, customer contact options, and a dynamic checkout flow.

## Project Structure
The project follows a standard web development directory structure:
- / (root)
    - index.html (Homepage)
    - about.html (About Us page)
    - products.html (Products catalog & checkout)
    - enquiry.html (Enquiry form)
    - contact.html (Contact information & Google Maps)
- /css
    - style.css (Global stylesheet with blue color theme)
- /images
    - (Store your branding and product images here)

## Features
- **Homepage**: Introduces the brand with a clear call-to-action.
- **Product Catalog**: Displays 4 featured products with quantity selectors, size charts, and a "Buy Now" checkout system.
- **Dynamic Checkout**: Collects shipping addresses and generates a unique Order ID upon successful submission.
- **Contact & Enquiry**: Interactive forms and embedded Google Maps for store location.
- **Responsive Theme**: A deep blue color palette designed for a professional aesthetic.

## Deployment Notes
- Ensure all images are placed in the `/images` folder to match the image paths in the HTML files.
- The `style.css` file must be located in the `/css` folder for the styles to load correctly.
- This project uses standard HTML5, CSS3, and native JavaScript. No external libraries or complex frameworks are required.

## How to Run
1. Download or clone the project folder.
2. Open the `index.html` file in any modern web browser.
3. Use the navigation menu to move between pages.
