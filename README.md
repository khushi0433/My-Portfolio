# project  overview

DevForge Portfolio is my personal full-stack developer portfolio website, designed to showcase my skills, projects, and ways to get in touch. Built with React on the frontend and Django on the backend, it offers a modern, clean, and fully responsive design. It features an animated particles background, smooth section transitions, and an interactive contact form with a star rating system — all wrapped in a sleek dark theme with emerald accents.

🚀 Features
Responsive Design: Looks great on all screen sizes, from mobile to desktop

Animated UI: Smooth animations and transitions powered by Framer Motion

Interactive Particles Background: Dynamic animated background with tsParticles

Project Showcase: Filterable gallery displaying frontend, backend, and full-stack projects

Contact Form: Fully functional form with validation and backend integration

Review System: Visitors can leave a star rating and write optional reviews

Dark Theme: Stylish dark mode with emerald green highlights for a modern feel

API Integration: RESTful backend API for projects and form submissions

🛠️ Technologies Used
Frontend
React

React Router

Tailwind CSS

Framer Motion

React tsParticles

Lucide React (icons)

React Toastify (notifications)

Axios (API calls)

Backend
Django

Django REST Framework

MySQL

Django CORS Headers

Pillow (image processing)

📁 Project Structure
plaintext
Copy
Edit
portfolio/
├── frontend/                # React frontend code
│   ├── public/
│   └── src/
│       ├── components/      # React components like Navbar, Hero, Contact, etc.
│       ├── App.jsx          # Main React component
│       ├── index.jsx        # Entry point
│       └── index.css        # Global styles (Tailwind)
├── backend/                 # Django backend code
│   ├── portfolio/           # Django app with models, serializers, views, and URLs
│   ├── portfolio_backend/   # Django project settings
│   └── manage.py            # Django management commands
└── README.md                # Project documentation
⚙️ Installation and Setup
Prerequisites
Node.js and npm installed

Python 3.8+

MySQL database server

Frontend Setup
bash
Copy
Edit
# Clone the repository
git clone https://github.com/khushi0433/devforge-portfolio.git
cd devforge-portfolio/frontend

# Install dependencies
npm install

# Run the development server
npm start
Backend Setup
bash
Copy
Edit
cd ../backend

# Create and activate a Python virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install Python dependencies
pip install -r requirements.txt

# Create MySQL database (use your MySQL credentials)
mysql -u root -p
CREATE DATABASE portfolio_db;
exit;

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Run backend server
python manage.py runserver
🖥️ Usage
Access the Django admin dashboard at http://localhost:8000/admin/ to manage projects and contact messages.

API endpoints:

GET /api/projects/ - List all projects

GET /api/projects/?category=frontend - Filter projects by category

POST /api/contact/ - Submit contact form data


🤝 Contributing
I welcome contributions, bug reports, and feature requests! Feel free to open an issue or submit a pull request on GitHub.

📞 Contact
Khushi Baloch
Email: fatimahbaloch917@gmail.com
GitHub: https://github.com/khushi0433

Thank you for checking out my portfolio! If you have any questions or want to connect, feel free to reach out.
