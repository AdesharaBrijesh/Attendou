# Attendou

## Overview
Attendou is an online attendance management system designed using PHP to streamline the process of tracking and managing attendance for educational institutions. The project emphasizes scalability, code reusability, and ease of modification, making it suitable for various environments and future extensions.

## Features
- **Automated Attendance:** Simplifies the attendance-taking process for teachers and students.
- **Scalable Design:** Easily adaptable to different institutions with minor modifications.
- **Modular Architecture:** Facilitates the addition of new features without disrupting existing ones.
- **Responsive Web Interface:** Built with modern web technologies for an interactive user experience.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL (or any other relational database)
- **Design Pattern:** MVC (Model-View-Controller)
- **Programming Paradigm:** Object-Oriented Programming (OOP)

## Getting Started
Follow these steps to set up the project on your local machine for development and testing purposes.

### Prerequisites
- **Web Server:** Apache, Nginx, or any other compatible web server.
- **PHP:** Version 7.0 or above.
- **Database:** MySQL or any other compatible database system.

### Installation
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/AdesharaBrijesh/Attendou.git
    cd Attendou
    ```
2. **Configure the Database:**
    - Import the SQL file `database/attendance_system.sql` into your MySQL database.
    - Update the database configuration in `config/database.php` with your database credentials.

3. **Start the Server:**
    - If you are using Apache, ensure `mod_rewrite` is enabled.
    - Start your web server and navigate to the project directory.

4. **Access the Application:**
    - Open your web browser and navigate to `http://localhost/Attendou`.

## Usage

### Teacher's Interface
- **Dashboard:** View attendance summaries and manage classes.
- **Mark Attendance:** Easily mark attendance for students in each class.
- **Reports:** Generate and download attendance reports.

### Student's Interface
- **View Attendance:** Check individual attendance records.
- **Notifications:** Receive notifications for absences and important updates.

### Administration Interface
- **Manage Users:** Add, edit, or remove teachers and students.
- **System Configuration:** Update system settings and configurations.

## Contributing
We welcome contributions to enhance Attendou. Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any inquiries or support, please contact [adesharabrijesh8@gmail.com].

Thank you for using Attendou! We hope this project helps you manage attendance efficiently and effectively.
