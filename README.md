# CBTP G-8: Death Certificate Generator

A web-based application designed for local Kebele administration to generate, record, and print official death certificates. 

## Features
* User-friendly form to input deceased details (Name, DOB, DOD, Parents' names, etc.).
* Photo upload functionality for the memorial section.
* Dynamically generated, print-ready certificate layout.
* CSS styled to look like an official document (including stamp placeholders).

## Technologies Used
* **Frontend:** HTML5, CSS3
* **Backend:** PHP
* **Database:** MySQL (MariaDB via XAMPP)
* **Server Environment:** Apache (XAMPP)

## How to Run Locally
1. Install [XAMPP](https://www.apachefriends.org/).
2. Clone this repository into your `htdocs` folder:
   `git clone https://github.com/work-out16/project-cbtp.git`
3. Open XAMPP Control Panel and start **Apache** and **MySQL**.
4. Open `http://localhost/phpmyadmin` and create a database named `ginjo`. Import the `Database.sql` file provided in the project.
5. Navigate to `http://localhost/project-cbtp/Death_certificate/death_certificate.php` in your browser.

## Author
* **work-out16** - *Initial work*
