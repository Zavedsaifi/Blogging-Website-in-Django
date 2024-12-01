# Blogging-Website-in-Django
A simple and functional blogging platform built with Django. Users can register, log in, create, edit, and delete blog posts, offering an intuitive interface for managing their content.

# Features
  **User Authentication**:
    Register, login, and logout functionality.
  **Blog Management**:
     Create, edit, and delete blog posts.
     View all posts by users.
 **Responsive Design**:
     Clean and user-friendly UI for desktop and mobile devices.
   
# Tech Stack
  **Backend**: Django (Python)
  **Frontend**: HTML, CSS, Bootstrap
  **Database**: SQLite (default Django DB, can switch to PostgreSQL or MySQL)
  **Authentication**: Django's built-in authentication system
  
# Setup Instructions
1. **Clone the Repository**
        git clone https://github.com/Zavedsaifi/django-blogging-website.git
        cd django-blogging-website
2. **Create a Virtual Environment**
        python -m venv venv
        source venv/bin/activate  # On Windows: venv\Scripts\activate     
3.  **Install Dependencies**
        pip install -r requirements.txt
4. **Apply Migrations**
        python manage.py makemigrations
        python manage.py migrate
5. **Run the Development Server**
        python manage.py runserver
The website will be available at http://127.0.0.1:8000.

# How It Works
1.**User Management**
    Users can register for an account.
    Registered users can log in to manage their blog posts.
2. **Blog Operations**
    **Create**: Add new blog posts with a title and content.
    **Edit**: Update existing posts.
    **Delete**: Remove posts created by the user.
    **View**: Display all blog posts.
    
# Folder Structure

django-blogging-website/
├── blogging/               # Main Django application folder
│   ├── migrations/         # Database migrations
│   ├── templates/          # HTML templates
│   ├── static/             # Static files (CSS, JS)
│   ├── views.py            # Application views
│   ├── models.py           # Database models
│   ├── urls.py             # Application URL routing
│   └── forms.py            # Django forms for the application
├── myproject/              # Project settings folder
│   ├── settings.py         # Project settings
│   ├── urls.py             # Project-wide URL routing
│   └── wsgi.py             # WSGI entry point
├── db.sqlite3              # SQLite database file
├── manage.py               # Django project management script
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

# Features in Detail
1.**User Authentication**
**Register**:
  Users can create accounts using the registration page.
**Login/Logout**:
  Django's built-in authentication for secure user login/logout.
2.**Blog Post Management**
**Create**:
  Users can add blog posts through a form.
**Edit/Delete**:
  Only post authors can edit or delete their blogs.
**View Blogs**:
  All posts are visible on the homepage.
3. **Responsive UI**
  Designed with Bootstrap for mobile and desktop compatibility.
  
# Screenshots
  Homepage
  Blog Editor

# Future Enhancements
  Add search functionality for blog posts.
  Enable categories/tags for posts.
  Add comment functionality.
  Implement rich-text editors for blog content.
  Deploy on a cloud platform (Heroku, AWS, or DigitalOcean).

# Acknowledgments
  Django Documentation: https://docs.djangoproject.com/
  Bootstrap: https://getbootstrap.com/
