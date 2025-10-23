# greenden_tailwind_css

A responsive multipage website built using HTML and Tailwind CSS, designed for a fictional plant store called Greenden.
The site includes three main pages — Home, Products, and Contact — with smooth navigation and a clean, modern UI.
Features
Responsive Design — Works seamlessly on all devices (desktop, tablet, mobile).
Home Page — Welcomes users with a modern hero section and brand intro.
Products Page — Displays plant products in a clean, grid-based layout.
Contact Page — Simple contact form for inquiries.
Tailwind CSS — Fast and efficient styling with utility-first classes.
Navbar Navigation — Smooth navigation between pages.

Tech Stack
HTML5
Tailwind CSS (via CDN or local setup)

📁 Folder Structure
Greenden/
├── index.html          # Home Page
├── products.html       # Products Page
├── contact.html        # Contact Page
├── /assets             # Images and icons
└── /css
    └── tailwind.css    # Tailwind CSS file (optional if using CDN)

Setup & Usage
Clone this repository:
git clone https://github.com/jaisreerajkumar/greenden_tailwind_css

Navigate to the project folder:
cd greenden

Open the website:
Simply open index.html in your browser.
Install dependencies:
npm install
Build your Tailwind CSS:
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch

Navigation
Page	Description
Home	Introduction to Greenden with hero section and highlights
Products	Grid display of available plants and products
Contact	Contact form for customer messages
Cu can update brand colors and spacing easily in tailwind.config.js.e placeholder images in /assets with your own.

Modify text and links directly in each .html
