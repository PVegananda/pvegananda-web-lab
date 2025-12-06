<div align="center">

  <!-- Banner -->
  <div style="
      width: 100%;
      padding: 45px 0;
      background: linear-gradient(135deg, #1e1e2e, #35355e);
      border-radius: 14px;
      color: #ffffff;
      font-family: Arial, sans-serif;
  ">
      <h1 style="font-size: 40px; margin-bottom: 8px;">🛠️ SIMPLE PHP Template</h1>
      <p style="font-size: 18px; opacity: 0.9;">
          Lightweight PHP Website Boilerplate / Template for Rapid Development
      </p>
  </div>

  <br />

  <!-- Badges -->
  <img src="https://img.shields.io/badge/Language-PHP-777BB4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Web-lightgrey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Template%20Boilerplate-blue?style=for-the-badge" />

</div>

<br/><br/>

<h2>📌 Project Overview</h2>
<p>
The <strong>SIMPLE_PHP_TEMPLATE</strong> repository is a minimalistic yet robust starting point for building PHP-based web projects.  
It provides a clean directory structure, reusable components (such as header/footer or navigation includes), and base files for quick setup — allowing developers to focus on core logic instead of repetitive boilerplate.  
This template is ideal for small to medium websites, prototypes, learning projects, or as a base for more complex web applications.
</p>

<h2>🧩 What This Template Offers</h2>
<ul>
  <li>Standard directory/file structure for PHP web projects</li>
  <li>Reusable include files — e.g. header, footer, navigation, config files</li>
  <li>Separation of concerns: content, layout, and configuration separated for cleaner code</li>
  <li>Support for dynamic page titles and metadata via configuration — easy to maintain across multiple pages</li>
  <li>Optional integration with a database or form processing (if needed)</li>
  <li>Lightweight — no heavy frameworks, easy to understand and extend</li>
</ul>

<br/>

<h2>📁 Recommended Directory Structure (Example)</h2>
<pre>
/ (root)
  ├── assets/           ← CSS, JS, images, etc.
  ├── includes/         ← header.php, footer.php, nav.php, config.php, etc.
  ├── pages/            ← individual page PHP files (home.php, about.php, etc.)
  ├── index.php         ← main entry (could route to pages or include header/footer)
  └── README.html (or .md)
</pre>

*(Actual structure may vary — adjust as per your files.)*

<br/>

<h2>📥 1. Setup & Installation</h2>
<ol>
  <li>Clone the repository:</li>
</ol>
<pre>
git clone https://github.com/PVegananda/SIMPLE_PHP_TEMPLATE
cd SIMPLE_PHP_TEMPLATE
</pre>
<ol start="2">
  <li>Copy project folder into your web server root — e.g. <code>htdocs/</code> (XAMPP), <code>www/</code> (WAMP/Laragon) or your hosting directory.</li>
  <li>If using a database — configure your DB connection (host, user, password, db name) in the config file (e.g. <code>includes/config.php</code>).</li>
  <li>Open the site in your browser — e.g. <code>http://localhost/SIMPLE_PHP_TEMPLATE/</code></li>
</ol>

<br/>

<h2>🌐 Usage & How to Build Your Website</h2>
<ol>
  <li>Create a new PHP file inside the pages folder (e.g. <code>pages/about.php</code>)</li>
  <li>At the top of your page file, include the config and header files:</li>
  <pre>
<?php
include '../includes/config.php';
include '../includes/header.php';
// page content here
include '../includes/footer.php';
?>
  </pre>
  <li>Adjust navigation if needed (e.g. for active menu highlighting)</li>
  <li>Add CSS/JS or other assets under <code>assets/</code> and link from header or footer</li>
  <li>If you need forms or database — add your logic, using the existing config for DB connection</li>
</ol>

<br/>

<h2>✨ Why Use This Template</h2>
<ul>
  <li>Speeds up project start — no need to write boilerplate again and again</li>
  <li>Encourages organized structure & clean separation of layout and logic</li>
  <li>Easy to customize and expand — ideal for learning or building small web apps</li>
  <li>Lightweight and dependency-free — good if you don’t want a full framework</li>
</ul>

<br/>

<h2>🔧 Recommended Environment</h2>
<ul>
  <li>PHP 7.x or 8.x</li>
  <li>Apache / Nginx (with PHP support) — e.g. via XAMPP, WAMP, Laragon, or web hosting</li>
  <li>A text editor or IDE — e.g. VS Code, Sublime Text, PHPStorm</li>
</ul>

<br/>

<h2>📄 License</h2>
<p>This template is free to use, modify, and build upon — perfect for educational, personal, or small-scale commercial use.</p>

<br/>

<div align="center">
  <h3>🚀 Start your PHP project quickly — with structure, clarity, and simplicity!</h3>
</div>
