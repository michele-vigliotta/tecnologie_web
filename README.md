<h1 align="center">Web Technologies (Tecnologie Web) Course Project</h1>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-orange.svg" alt="HTML">
  <img src="https://img.shields.io/badge/CSS-3-1572B6.svg" alt="CSS">
  <img src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E.svg" alt="JavaScript">
  <img src="https://img.shields.io/badge/PHP-7.4-777BB4.svg" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel-Framework-FF2D20.svg" alt="Laravel">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1.svg" alt="MySQL">
  <img src="https://img.shields.io/badge/MVC-Architecture-orange.svg" alt="MVC">
</p>

<p align="center">
  <i>Platform for managing listings, user roles, messaging, and booking requests.</i>
</p>

<hr>

<p align="center">
  <img src="home_view.png" width="900">
</p>

<h2>Website Structure</h2>

<p>
The website is organized into four navigation levels, all accessible through a shared navbar.  
After login, users are redirected to the homepage corresponding to their assigned level.
</p>

<ul>
  <li><b>Level 1:</b> Public pages (homepage, catalog preview)</li>
  <li><b>Level 2:</b> Registered users (basic features, messaging)</li>
  <li><b>Level 3:</b> Locatario (tenant): filters, bookings, messaging</li>
  <li><b>Level 4:</b> Locatore / Admin: listing management, booking requests</li>
</ul>

<h2>Adopted Solutions</h2>

<ul>
  <li><b>User Homepage:</b> single template with conditional rendering based on user type; modular header/footer; dynamic carousel</li>
  <li><b>Listing Management (Locatore):</b> add/edit/delete listings; view requests; accept/reject; contact users</li>
  <li><b>Catalog:</b> single page with behavior adapted to each role (guest, tenant, landlord, admin)</li>
  <li><b>Admin Statistics:</b> filtered data by listing type and date range</li>
</ul>

<h2>Tech Stack</h2>

<ul>
  <li><b>Frontend:</b> HTML5, CSS3, JavaScript (ES6)</li>
  <li><b>Backend:</b> PHP 7.4, Laravel</li>
  <li><b>Database:</b> MySQL (6-table relational model)</li>
  <li><b>Architecture:</b> MVC</li>
</ul>

<h2>Authors</h2>

<ul>
  <li>Michele Vigliotta</li>
  <li>Filippo Montagnoli</li>
  <li>Marco Pasquale Martino</li>
</ul>

<hr>

<p align="center"><i>University project developed for the Web Technologies course.</i></p>
