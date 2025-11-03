<h1 align="center">Web Technologies Project</h1>

<p align="center">
  <!-- Frontend -->
  <img src="https://img.shields.io/badge/HTML-5-orange.svg" alt="HTML">
  <img src="https://img.shields.io/badge/CSS-3-blue.svg" alt="CSS">
  <img src="https://img.shields.io/badge/JavaScript-ES6-yellow.svg" alt="JavaScript">

  <!-- Backend -->
  <img src="https://img.shields.io/badge/PHP-7.4-777BB4.svg" alt="PHP">
  <img src="https://img.shields.io/badge/Laravel-Framework-red.svg" alt="Laravel">

  <!-- Database -->
  <img src="https://img.shields.io/badge/SQL-MySQL-blue.svg" alt="MySQL">

  <!-- Architettura -->
  <img src="https://img.shields.io/badge/Architecture-MVC-orange.svg" alt="MVC">
</p>




<p>
<i>Implementation of a platform for managing listings, users, messaging, and booking requests.</i>
</p>

<hr>



<h2>Website Structure</h2>

<p>
The website is organized into four navigation levels, all accessible through a shared navbar.  
After login, the user is redirected to the homepage of their corresponding level.  
Logging out always returns the user to Level 1.
</p>

<ul>
  <li><b>Level 1:</b> Public pages (homepage, catalog preview, basic info)</li>
  <li><b>Level 2:</b> Registered users (basic features, messaging access)</li>
  <li><b>Level 3:</b> Locatario (tenant) functionalities (filters, booking, messaging)</li>
  <li><b>Level 4:</b> Locatore (landlord) or Admin functionalities (managing listings, viewing requests)</li>
</ul>

<p>
A complete navigation scheme was created to describe transitions between levels and components.
</p>

<hr>



<h2>✅ Adopted Solutions</h2>

<h3>1. User Homepage Management</h3>
<p>
We implemented a shared homepage template for all logged-in users and differentiated its features through conditional checks based on user type (locatore or locatario).  
The header and footer were modularized and included via a base layout for all pages.  
A carousel with 3 slides dynamically adapts its content depending on whether the user is logged in or browsing as a guest.
</p>

<h3>2. Listing Management (Locatore)</h3>
<p>
Landlords can add, edit, or delete their listings from a dedicated page.  
Listing details include a section for viewing booking requests, accepting or rejecting them, viewing requester data, or contacting the user via messaging.
</p>

<h3>3. Catalog Management</h3>
<p>
We kept a single page for the catalog and adapted its behavior using conditional logic:  
</p>

<ul>
  <li>Guests can browse listings but cannot open details.</li>
  <li>Locatori and Admins can view listings but not open details.</li>
  <li>Locatari can open listing details, filter results, send messages to the landlord, or submit a booking request.</li>
</ul>

<h3>4. Admin Statistics</h3>
<p>
The statistics page includes filters such as listing type and date range to refine the displayed data.
</p>

<hr>

<p align="center"><i>Project created as part of the Web Technologies and Databases coursework.</i></p>

<h2>Authors</h2>

* Michele Vigliotta
* Filippo Montagnoli
* Marco Pasquale Martino
