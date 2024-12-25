# wtshop - Online Shop

**wtshop** is a modern and user-friendly online shop built with Django. It offers an easy-to-navigate interface where users can browse products. This project is designed to be a fully functioning e-commerce platform with a simple and attractive design.

## Features
- **Product Listings**: Browse products with images, descriptions, and prices.

## Tech Stack
- **Backend**: Django
- **Frontend**: HTML, CSS (Bootstrap)
- **Database**: SQLite (can be swapped with PostgreSQL in production)
- **Environment Variables**: Managed with `django-environ`
- **Authentication**: Django's built-in authentication system

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/havrilovalex/wtshop.git
```

### 2. Set Up the Virtual Environment
```bash
cd wtshop
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
### 4. Set Up Environment Variables
Create a `.env` file in the root of your project and add your secret key and other settings:
```bash
DJANGO_SECRET_KEY=your-secret-key
DJANGO_DEBUG=True
DJANGO_ALLOWED_HOSTS=your-hosts
```
### 5. Run Migrations
python manage.py migrate

### 6. Start the Development Server
python manage.py runserver

Visit http://127.0.0.1:8000/ to view shop in action!

## Usage

- **Admin Panel**: Access the Django admin panel at `/admin` (use the admin credentials you set during migration).
- **Product Management**: Admin can add/edit products, manage categories, and view orders from the admin dashboard.

## Screenshots
Here are a few screenshots of the app in action:


## License
Distributed under the License. See LICENSE for more information.

---

Made with ❤️ by **Havrilov Alex**