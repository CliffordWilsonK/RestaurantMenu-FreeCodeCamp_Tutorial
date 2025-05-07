# 🍽️ Restaurant Menu App (Django)

A web-based restaurant menu application built using **Django**. This app was created as part of a tutorial to learn how to build dynamic web applications using Python and Django. It allows restaurant owners or staff to manage their menu—adding, editing, deleting, and displaying items across categories.

## 📚 Tutorial Source

This project was developed by following the tutorial:  
**Django Crash Course - Python Web Framework(#)**  
*https://www.youtube.com/watch?v=0roB7wZMLqI*

## ✨ Features

- 📝 Create, Read, Update, and Delete (CRUD) menu items
- 📂 Categorize menu items (e.g., Appetizers, Main Course, Desserts, Drinks)
- 💸 Price listing and formatting
- 📱 Responsive layout using Django templates + CSS
- 🔍 Optional filtering/search functionality (if implemented)
- 🛠️ Admin interface for easy data management

## 🧰 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** Django Templates, HTML5, CSS3 
- **Database:** SQLite3
- **Admin:** Django Admin Panel


## 🚀 Getting Started

### Prerequisites

- Python 3.x
- pip (Python package manager)
- Virtualenv (optional but recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/CliffordWilsonK/RestaurantMenu-FreeCodeCamp_Tutorial.git

````

2. **Create and activate a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```bash
   python manage.py migrate
   ```

5. **Create superuser (optional)**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**

   ```bash
   python manage.py runserver
   ```

7. **Open in browser**
   Visit `http://127.0.0.1:8000/`

## 🧪 Sample Usage

* Visit the homepage to see a list of all menu items.
* Use the admin panel (`/admin`) to manage items and categories.
* Add new items via the UI or admin panel.
* Edit/delete items as needed.

## 📸 Screenshots

*(Add screenshots here if available)*

## 📁 Requirements

Include a `requirements.txt` generated with:

```bash
pip freeze > requirements.txt
```

## 💡 Lessons Learned

This project helped me understand:

* Django’s MVC (Model-View-Template) architecture
* How to create models and interact with the ORM
* URL routing and views
* Template inheritance and dynamic rendering
* Using the Django admin interface effectively

## 🔧 Future Improvements

* Add image uploads for menu items
* Implement search/filter by category or price
* Integrate Django REST Framework for API access
* Add user authentication and authorization

## 🤝 Acknowledgements

Big thanks to the tutorial author for guiding through this project.
*(List the name of the tutorial creator or YouTube channel, if applicable)*

---

**Built with ❤️ using Django.**

```

