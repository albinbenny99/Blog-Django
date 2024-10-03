# Simple Blog Project

## Description
The **Simple Blog Project** is a web-based application that allows users to create, view, and manage blog posts. Built using Django, this project implements basic CRUD (Create, Read, Update, Delete) functionality for blogs, providing a user-friendly interface with features like user authentication and profile management.

## Features
- **User Authentication**: Register, login, and manage user accounts.
- **Create Blog Posts**: Authenticated users can create new blog posts.
- **View Blog Posts**: All users can view blog posts.
- **Edit and Delete Blog Posts**: Blog authors can edit and delete their own posts.
- **Profile Management**: Users can update their profiles.
- **Responsive Design**: The application is responsive and works well on different screen sizes.

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML5, CSS3, Tailwind CSS
- **Database**: SQLite (Development)
- **Version Control**: Git, GitHub

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.8+ installed on your machine.
- Django framework installed.
- Git installed for version control.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/albinbenny99/Simple-Blog.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd Simple-Blog
    ```
3. **Install the required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```
4. **Apply database migrations**:
    ```bash
    python manage.py migrate
    ```
5. **Create a superuser to access the admin panel**:
    ```bash
    python manage.py createsuperuser
    ```
6. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

## Usage
1. **Register**: Create a new user account.
2. **Login**: Login to the application with your credentials.
3. **Create a Blog Post**: After logging in, you can create new blog posts.
4. **Manage Blog Posts**: You can edit or delete posts that you have created.
5. **View Profiles**: View or update your user profile.

## Access the Application
Once the development server is running, access the application in your browser at:
