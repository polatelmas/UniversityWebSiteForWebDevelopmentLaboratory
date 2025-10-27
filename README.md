🌟 Sivas University of Science and Technology (SUST) Website

✨ Overview

This repository contains the official institutional website for the Sivas University of Science and Technology (SUST), an academic institution focused on engineering and technological disciplines.

The website serves as a primary informational portal for prospective students, current staff, and the wider community, showcasing academic programs, campus facilities, recent news, and upcoming events.

💻 Key Features

The site is designed for clarity, accessibility, and professional presentation:

Institutional Identity: Clear display of the university's mission, contact information, and statistics.

Fully Responsive Design: Optimized layout for viewing on all devices (mobile, tablet, and desktop).

Academic Showcase: Dedicated sections for Featured Programs (e.g., Computer Science & AI, Aeronautical Engineering).

Real-Time Updates: Sections for Recent News and Upcoming Events to keep the community informed.

Interactive Elements: Utilization of modern JavaScript libraries for smooth visuals and user experience (sliders, lightboxes, counters).

Multi-Page Navigation: Structured navigation to main pages (Home, About, Contact) and sub-sections (Faculty & Staff, Campus Tour).

⚙️ Tech Stack & Dependencies

This project is built using a classic, robust, and performant web stack:

Primary Technologies: HTML5, CSS3, and Vanilla JavaScript.

CSS Framework: Bootstrap 5 (used for responsive grid and fundamental styling).

Fonts: Google Fonts (Roboto, Poppins, Raleway).

Vendor Libraries:

Bootstrap Icons: For standard iconography.

Swiper: For building touch-enabled sliders and carousels.

GLightbox: For responsive image and video lightboxes/modals.

PureCounter: For animating statistical numbers on load.

Template Base: MySchool Template by BootstrapMade.

🚀 Installation and Local Development

Since this is a static HTML/CSS/JS site, running it locally is very straightforward.

Prerequisites

You need a web server environment to serve the files, such as:

Live Server VS Code Extension

Node.js (for running simple HTTP server)

Running Locally

Clone the repository:

git clone [Your Repository URL Here]
cd [sust-website-repo]


Option A: Using VS Code Live Server (Recommended)

Open the project folder in VS Code.

Right-click on the index.html file and select "Open with Live Server".

Option B: Using Node.js HTTP Server

If you have Node.js installed, run a simple HTTP server package (like http-server):

# Install globally (if needed)
npm install -g http-server
# Run server from the root directory
http-server .


The site will typically open at http://localhost:8080.

📂 Project Structure

The file structure follows a standard template convention:

/
├── index.html        # Main homepage
├── about.html        # About Us page
├── contact.html      # Contact page
├── [other-pages].html # Additional content pages
├── assets/
│   ├── css/          # Custom CSS files (main.css)
│   ├── js/           # Custom and main JavaScript files
│   ├── img/          # All images (campus, programs, news)
│   └── vendor/       # Third-party dependencies (Bootstrap, Swiper, GLightbox, etc.)
└── README.md


🤝 Contribution & Maintenance

We welcome contributions to help keep the website information accurate and the design modern. Please follow standard fork/pull request procedures.

Fork the Project.

Create your Feature Branch (git checkout -b feature/update-news-section).

Commit your Changes (git commit -m 'Update October news items').

Open a Pull Request.