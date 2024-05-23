# Contact Form Project

A simple contact form built using HTML, CSS, JavaScript, and PHP. This form allows users to send their messages, which are then emailed to a specified email address.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [File Structure](#file-structure)



## Features

- Responsive contact form with basic validation.
- Backend processing using PHP to send form data via email.
- Clean and simple design with CSS.

## Technologies Used

- HTML
- CSS
- JavaScript
- PHP

## Setup Instructions

### Local Development

1. **Install XAMPP**:
   Download and install XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).

2. **Start XAMPP**:
   Open the XAMPP Control Panel and start the Apache and MySQL modules.

3. **Move Project to XAMPP Directory**:
   Copy the project files to the `htdocs` directory inside the XAMPP installation folder (e.g., `C:\xampp\htdocs\contact_form` on Windows or `/Applications/XAMPP/htdocs/contact_form` on macOS).

4. **Open in Browser**:
   Open your web browser and navigate to `http://localhost/message` to view the contact form.

### Deployment on a Live Server

1. Choose a Hosting Provider:
   Select a web hosting provider that supports PHP (e.g., Bluehost, SiteGround, HostGator).

2. Upload Files:
   Use the hosting provider's file manager or an FTP client (like FileZilla) to upload your project files to the server.

3. Set File Permissions:
   Ensure PHP files have the correct permissions (typically `644` for files and `755` for directories).

4. Configure Database (if required):
   If your form saves data to a database, set up the database on your live server and update the PHP scripts with the correct database credentials.

5. **Test Live Site**:
   Visit your domain in a web browser and test the contact form to ensure everything works correctly.

## File Structure

/contact_form
├── index.html
├── style.css
├── script.js
├── message.php
└── README.md
