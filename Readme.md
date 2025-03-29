
# Blog Application

This is a full-stack blog application built using Django for the backend and a modern frontend framework. The application supports user authentication, CRUD operations for blog posts, and responsive design for an optimal user experience on both desktop and mobile devices.

---

## Features

### User Authentication
- Users can sign up and log in using their email and password.
- Only logged-in users can create, edit, and delete blogs.

### Blog Management
- Create, view, update, and delete blog posts.
- Blogs include a title and content.
- Published blogs are viewable by everyone, including unauthenticated users.

### Public Blog Listing
- A public page displays all blogs with pagination.

### Database
- Blogs and users are stored in a SQL database (SQLite).

### Responsive Design
- Fully responsive design, optimized for both desktop and mobile devices.

---

## Technologies Used

### Backend
- **Django**: Handles authentication, APIs, and blog CRUD operations.
- **SQLite**: Lightweight SQL database for data persistence.

### Frontend
- **React**: Frontend framework for building user interfaces.
- **CSS**: Used for styling and ensuring responsiveness.
- **Axios/Fetch**: Handles API communication between the frontend and backend.

### Deployment
- **PythonAnywhere**: Cloud hosting platform for deployment.

---

## Installation and Setup

### Prerequisites
- Python (>= 3.8)
- Node.js and npm
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/anjgotnochill/blog-app.git
   cd blog-app
   ```

2. Set up the backend:
   ```bash
   cd backend
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```

3. Set up the frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. Access the application:
   - Frontend: `http://localhost:3000`
   - Backend: `http://localhost:8000`

---

## Deployment
The application is deployed on PythonAnywhere. You can access it at:
[https://anjalip01.pythonanywhere.com/](https://anjalip01.pythonanywhere.com/)

---

## Application Walkthrough

### Features Demonstrated
1. **Signup/Login**:
   - New users can create accounts.
   - Existing users can log in to manage blogs.

2. **Blog CRUD Operations**:
   - Create, update, and delete blogs as a logged-in user.
   - View all published blogs on the public listing page.

3. **Pagination**:
   - Blog listing is paginated to ensure easy navigation.

4. **Responsive Design**:
   - Application works seamlessly on both mobile and desktop devices.

---

## Repository Structure
```
blog-app/
├── backend/          # Django backend files
│   ├── manage.py     # Django management script
│   ├── blog/         # Blog app with models, views, and APIs
│   └── db.sqlite3    # SQLite database file
├── frontend/         # React frontend files
│   ├── public/       # Static assets
│   └── src/          # React components
└── README.md         # Project documentation
```

## Author
**Anjali Patel**

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.
