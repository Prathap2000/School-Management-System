# Kavery School Management System

Welcome to the Kavery School Management System, a DBMS mini-project developed for VTU. This system helps manage various aspects of a school including faculty information, administration tasks, and more.

## Getting Started

To get started with the project, follow these instructions:

### Prerequisites

1. **XAMPP**: Install XAMPP which includes Apache and MySQL servers.
   - Download XAMPP from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)
   - Start the Apache and MySQL servers from the XAMPP control panel.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Kavery-School-Management-System.git
   ```

2. Place the project folder `Kavery-School-Management-System` in the `htdocs` directory of your XAMPP installation. Typically located at:
   - For Windows: `C:\xampp\htdocs`
   - For macOS: `/Applications/XAMPP/htdocs`
   - For Linux: `/opt/lampp/htdocs`

3. Import the database:
   - Create a new database named `kavery_school` in phpMyAdmin (`http://localhost/phpmyadmin`).
   - Import the provided SQL file `kavery_school.sql` into the `kavery_school` database to create tables and populate initial data.

4. Configure database connection:
   - Edit the `connect.php` file to update the database connection details (`hostname`, `username`, `password`, `dbname`) if they differ from default XAMPP settings.

### Usage

- Access the application by navigating to `http://localhost/Kavery-School-Management-System` in your web browser.

### Structure

- `index.html`: Main page of the project.
- `web.css`: CSS file for styling.
- `about.html`: Displays information about the project.
- `addfaculty.html`: Form to add faculty members to the database.
- `admin.html`: Provides functionalities to create and delete records.
- `connect.php`: PHP script to establish database connection.
- `contact.html`: Displays contact information.
- `delete.php`: PHP script to delete records from the database.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- This project was developed as a DBMS mini-project for VTU.

---

Feel free to customize the sections further based on additional features or acknowledgments relevant to your project. Adjust the URLs and paths according to your local environment settings.
