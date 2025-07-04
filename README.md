# Online Platform

## Overview

This is a PHP-based online education platform that allows users to browse courses, view tutor profiles, register, log in, and interact with educational content. The backend is built with PHP and MySQL, and the frontend uses HTML, CSS, and JavaScript for styling and interactivity.

---

## Features

- User registration and login
- Browse all courses and playlists
- View tutor profiles and their courses
- Bookmark playlists
- Like and comment on content
- Admin panel for managing content, playlists, and users
- Responsive design with modern UI

---

## Project Structure

```
backend - online education/
  └── project/
      ├── about.php
      ├── admin/
      ├── bookmark.php
      ├── comments.php
      ├── components/
      ├── contact.php
      ├── courses.php
      ├── css/
      ├── home.php
      ├── images/
      ├── js/
      ├── likes.php
      ├── login.php
      ├── playlist.php
      ├── profile.php
      ├── register.php
      ├── search_course.php
      ├── search_tutor.php
      ├── teachers.php
      ├── tutor_profile.php
      ├── update.php
      ├── uploaded_files/
      └── watch_video.php
```

---

## Getting Started

### Prerequisites

- PHP 7.x or higher
- MySQL
- A local server environment (XAMPP, WAMP, MAMP, etc.)

### Setup Instructions

1. **Clone the repository:**
   ```
   git clone https://github.com/SidIos25/Online-Platform.git
   ```

2. **Move the project to your server's web directory:**
   - For XAMPP: `C:\xampp\htdocs\Online-Platform\backend - online education\project\`

3. **Import the database:**
   - Open phpMyAdmin.
   - Create a new database named `course_db`.
   - Import the `course_db.sql` file located in the project folder.

4. **Configure database connection:**
   - Edit `components/connect.php` if your MySQL username or password is different from the default.

5. **Start your local server and visit:**
   ```
   http://localhost/Online-Platform/backend%20-%20online%20education/project/home.php
   ```

---

## Usage

- Register as a new user or log in with existing credentials.
- Browse courses, view playlists, and interact with content.
- Admins can log in to the admin panel to manage courses, playlists, and users.

---

## Customization

- **Styling:** Edit files in the `css/` folder.
- **Images:** Add or replace images in the `images/` folder.
- **Scripts:** Add custom JavaScript in the `js/` folder.

---

## License

This project is for educational purposes.  
Feel free to modify and use it as needed.
