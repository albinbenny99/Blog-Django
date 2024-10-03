Simple Blog Project
Description
The Simple Blog Project is a web-based application that allows users to create, view, and manage blog posts. Built using the Django framework, it implements basic CRUD (Create, Read, Update, Delete) functionality for blog posts, offering a user-friendly interface with additional features such as user authentication and profile management.

Features
User Authentication: Register, login, and manage user accounts.
Create Blog Posts: Authenticated users can create new blog posts.
View Blog Posts: All users can view blog posts.
Edit and Delete Blog Posts: Blog authors can edit and delete their own posts.
Profile Management: Users can update their profile information.
Responsive Design: The application is responsive and works well on different screen sizes.
Technologies Used
Backend: Django (Python)
Frontend: HTML5, CSS3, Tailwind CSS
Database: SQLite (Development environment)
Version Control: Git, GitHub
Prerequisites
Before you begin, ensure you have the following requirements:

Python 3.8+ installed on your machine.
Django framework installed.
Git installed for version control.
Installation
Follow these steps to get the project up and running on your local machine:

Clone the repository from GitHub:
git clone https://github.com/albinbenny99/Simple-Blog.git
cd Simple-Blog

Install the required Python packages:
pip install -r requirements.txt

Apply the database migrations:
python manage.py migrate

Create a superuser to access the admin panel:
python manage.py createsuperuser

Run the development server:
python manage.py runserver

Access the application in your browser at:
http://127.0.0.1:8000/

Usage
Register: Create a new user account.
Login: Log in to the application with your credentials.
Create a Blog Post: Once logged in, you can create new blog posts.
Manage Blog Posts: Edit or delete posts that you have authored.
View Profiles: View and update your user profile.
