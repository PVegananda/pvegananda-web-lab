<div align="center">
  <img src="img/logo.jpg" alt="PVegananda Web Lab logo" width="180">

  # PVegananda Web Lab

  **A clean, interactive PHP showcase for practical web experiences.**

  <p>
    <a href="https://www.php.net/"><img src="https://img.shields.io/badge/PHP-8%2B-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP 8+"></a>
    <a href="https://getbootstrap.com/"><img src="https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat-square&logo=bootstrap&logoColor=white" alt="Bootstrap 5"></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML"><img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5"></a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/CSS"><img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3"></a>
    <a href="https://github.com/PVegananda/pvegananda-web-lab"><img src="https://img.shields.io/github/stars/PVegananda/pvegananda-web-lab?style=flat-square" alt="GitHub stars"></a>
  </p>
</div>

## Overview

PVegananda Web Lab is a lightweight PHP website that brings several small,
interactive experiences together in one polished interface. It is designed
to demonstrate practical front-end structure, reusable PHP partials, and
browser-based interactions without the overhead of a full framework.

The project is intentionally easy to explore and extend. Shared navigation,
styles, scripts, and page layouts are kept in predictable locations so a new
feature can be added without duplicating the entire interface.

## What's included

- Responsive Bootstrap-based layout with reusable navigation and page partials
- A welcoming home page for the project
- A playable Snake game
- A simple age-guessing interaction
- An interactive knowledge quiz
- A records page ready to be connected to CRUD workflows
- Automatic loading for local CSS and JavaScript assets

## Project structure

```text
.
├── index.php                 # Application entry point
├── home.php                  # Home page
├── snake-game.php            # Snake game
├── age-guess.php             # Age-guessing interaction
├── knowledge-quiz.php        # Interactive quiz
├── records.php               # Records and CRUD area
├── partials/
│   ├── header.php            # Shared document head
│   ├── navigation.php        # Sidebar navigation
│   └── footer.php            # Shared document footer
├── css/
│   └── navigation.css        # Navigation styles
├── js/
│   └── navigation.js         # Navigation behavior
└── img/
    └── logo.jpg              # Project branding
```

## Getting started

### Requirements

- PHP 8.0 or newer
- A local PHP server such as PHP's built-in server, Apache, or Nginx
- A modern web browser

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/PVegananda/pvegananda-web-lab.git
   cd pvegananda-web-lab
   ```

2. Start PHP's built-in development server:

   ```bash
   php -S localhost:8000
   ```

3. Open [http://localhost:8000](http://localhost:8000) in your browser.

## Customization

Update the shared files in `partials/` to change the site-wide layout.
Page-specific content lives in the root PHP files, while visual behavior is
organized under `css/` and `js/`. This keeps the project approachable for
experimentation and makes it straightforward to add new pages or interactions.

## License

This project is available for personal and portfolio use. Add a license file
if you plan to distribute or reuse it under specific terms.

<div align="center">
  Built by <a href="https://github.com/PVegananda">PVegananda</a>
</div>
