# School Management System in PHP using CodeIgniter

A comprehensive School Management System built with PHP and the CodeIgniter web framework. This project is designed to manage all aspects of a school, including students, teachers, parents, classes, attendance, exams, and more.

## Features

- **User Roles:** Admin, Teacher, Student, Parent
- **Authentication:** Secure login for all user types
- **Student Management:** Add, edit, view, and delete student records
- **Teacher Management:** Manage teacher profiles and assignments
- **Parent Management:** Parent profiles linked to students
- **Class Management:** Create and manage classes and sections
- **Attendance:** Daily attendance tracking for students
- **Exams & Grades:** Exam scheduling, marks entry, and grade reports
- **Multi-language Support:** Easily switch between languages
- **Notifications:** Email and SMS notifications (Clickatell, Twilio integration)
- **Responsive UI:** Built with Bootstrap for mobile and desktop
- **Reports:** Generate various academic and administrative reports
- **Settings:** System configuration, session management, and more

## Technologies Used

- **Backend:** PHP (CodeIgniter Framework)
- **Frontend:** HTML, CSS (Bootstrap), JavaScript, jQuery
- **Database:** MySQL
- **Other:** AJAX, Multi-language, Email & SMS APIs

## Installation

1. Clone the repository:


2. Import the `schooligniter.sql` file from the `DATABASE FILE` folder into your MySQL database.
3. Configure your database settings in `application/config/database.php`.
4. Make sure your PHP version is 5.6 (recommended).
5. Start your local server (XAMPP/WAMP) and access the project via `http://localhost/School-Management-System`.

## Admin Login

- **Email:** admin@mail.com
- **Password:** Password@123

## Project Structure

- `application/controllers/` - All controllers (Admin, Teacher, Student, Parent, etc.)
- `application/models/` - Database models (CRUD, Email, SMS, etc.)
- `application/views/` - Views for backend and frontend
- `assets/` - CSS, JS, images, fonts
- `uploads/` - Uploaded files and images

## Screenshots & Modules

| Image | Name | Work | Features |
|-------|------|------|----------|
| ![Dashboard](uploads/logo.png) | Dashboard | Main admin dashboard | Overview, stats, quick links |
| ![User](uploads/user.jpg) | User Management | Manage students, teachers, parents | Add, edit, delete, view profiles |
| ![Admin](uploads/admin_image/1.png) | Admin Panel | System settings, session, language | Configuration, multi-language |
| ![Inbox](assets/images/inbox.png) | Notifications | Email & SMS notifications | Clickatell, Twilio integration |
| ![Loader](assets/images/loader-1.gif) | UI/UX | Responsive design, loaders | Bootstrap, custom CSS |

> Replace the image paths with actual screenshots of your website for better presentation.

## License

This project is open-source and free to use for educational purposes.

---

**Developed by Manjeet Developer, Fullstack LPU**

---

Feel free to contribute, report issues, or suggest features!
