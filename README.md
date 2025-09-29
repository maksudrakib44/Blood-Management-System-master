# Blood Management System

A web-based system built for managing blood donations and hospital requests.  
This project was developed as part of the University’s IDP II course.  

---

## Motivation
Managing blood donations, tracking donors, and handling hospital requests is crucial in times of need.  
This system makes it easier to:

- Allow donors to register and donate blood  
- Let hospitals request specific blood groups  
- Maintain stock/inventory of blood units  
- Keep all data organized via a relational database  

---

## Features
- Donor registration, login, and profile management  
- Hospital user registration and login  
- Hospitals can request blood of specific groups  
- Inventory / stock management for blood units  
- View and manage donation records  
- Deletion / editing of records (where applicable)  
- Stored in a MySQL database  

---

## Architecture & Technologies
- **Backend / Server-side**: PHP  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: MySQL  

**File Structure:**
- `.php` scripts for pages and logic  
- `.html` pages for layouts / static parts  
- `css/` directory for styles  
- `sql/` folder for database scripts  
- `image/` (or similar) folder for images  

---

## Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/maksudrakib44/Blood-Management-System-master.git
````

2. Create a MySQL database (e.g., `blood_management`) and import the provided SQL dump from the `sql/` folder.

3. Adjust the database connection settings in your PHP config (host, user, password, db name).

4. Place the project under your web server’s root (e.g., `htdocs` in XAMPP or `www` in WAMP).

5. Start Apache / PHP server and navigate to:

   ```
   http://localhost/Blood-Management-System-master/
   ```

6. Use the registration/login pages to begin using the system.

---

## Usage

* **For Donors**: sign up, login, and donate blood
* **For Hospitals**: request specific blood groups
* **Admin / Inventory**: monitor stock levels, view all donations and requests

---

## Contributing

If you'd like to contribute:

1. Fork the project
2. Create a new branch (`git checkout -b feature/SomeFeature`)
3. Make your changes & test
4. Submit a Pull Request with a clear description

Please ensure code is clean, documented, and tested.



## Contributors

| Name | Role / Contribution |
|------|--------------------|
| **Md. Maksudul Haque** | Lead Developer / Setup & Documentation |
| [**Pranto Bapary**](https://github.com/Pranto-Bapary) | Feature Development, UI, Testing |
