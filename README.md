# 📝 Simple Blog API

A simple blog API built using Django REST Framework (DRF) that allows users to create, read, update, and delete blog posts.

## 🚀 Features
- Create, Read, Update, and Delete (CRUD) blog posts.
- API authentication using Django's built-in user model.
- Pagination for listing blog posts.

## 🛠️ Technologies Used
- Python
- Django & Django REST Framework (DRF)
- SQLite (default) or PostgreSQL
- Django CORS Headers (for frontend communication)

## 📂 Project Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/Simple-Blog-API.git
cd Simple-Blog-API
**### 2️⃣ Create a virtual environment**
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
**### 3️⃣ Install dependencies **
pip install -r requirements.txt

**4️⃣ Apply migrations & create superuser **
python manage.py migrate
python manage.py createsuperuser
**5️⃣ Run the server**
python manage.py runserver

Your API is now running at http://127.0.0.1:8000/

🔥 API Endpoints
Method	Endpoint	Description
GET	/api/posts/	List all blog posts
POST	/api/posts/	Create a new post
GET	/api/posts/{id}/	Retrieve a single post
PUT	/api/posts/{id}/	Update an existing post
DELETE	/api/posts/{id}/	Delete a post
