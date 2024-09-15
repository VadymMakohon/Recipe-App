# Recipe-App
This is a web-based Recipe Application built with Python and Django. It allows users to search for recipes based on ingredients, automatically rates recipes by difficulty level, and lets users add their own recipes. It also includes user authentication, a Django Admin dashboard, and provides data analysis on recipes.

## Preview
![Screenshot 2024-07-13 at 9 51 07 AM](https://github.com/user-attachments/assets/6ef150dc-5704-474b-a299-7ee3e9f44ad4)
![preview recipes](https://github.com/user-attachments/assets/f2cff843-7881-41f3-a18a-a393b5e576b7)
![preview chicken](https://github.com/user-attachments/assets/9f15d643-0960-43ab-aac5-cac29ac3e916)
![preview tiramisu](https://github.com/user-attachments/assets/00aee735-8006-4416-be59-0cfe00f0d5a3)

## Key Features
- User Authentication: Users can register, log in, and log out.
- Recipe Search: Search recipes based on ingredients.
- Difficulty Rating: Automatic difficulty rating for each recipe.
- Error Handling: Handles errors like invalid inputs and provides user-friendly messages.
- Recipe Details: View detailed information on each recipe.
- Add Recipes: Users can add their own recipes to the app.
- Django Admin Dashboard: Manage recipes, users, and data entries through the Django Admin interface.
- Statistics & Visualizations: View trends and data analysis on recipes and user preferences.

## Technical Requirements
- Python 3.6+ and Django 3 required.
- Handles exceptions and displays user-friendly error messages for invalid input.
- During development, the app uses an SQLite database, while in production, it connects to a locally-hosted PostgreSQL database.
- The app has an easy-to-use interface with clear instructions and forms.
- Code is properly documented, with automated tests included.
- A requirements.txt file lists all necessary modules for the project.
- Instructions for downloading and running the app locally are provided below.

## Installation Instructions
1. Clone the repository: git clone https://github.com/yourusername/recipe-app.git    cd recipe-app
2. Create a virtual environment: python3 -m venv venv source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. Install dependencies: Install all the required modules listed in requirements.txt: pip install -r requirements.txt
4. Set up the database: python manage.py migrate
5. Create a superuser for Django Admin: python manage.py createsuperuser
6. Run the development server: python manage.py runserver
7. Access the app: http://127.0.0.1:8000/
8. Access Django Admin to manage database entries through the admin dashboard, log in at http://127.0.0.1:8000/admin/

## Github repo

This is the [link](https://github.com/VadymMakohon/) to the Github repo of the project

## Sample Website

A live demo is already available via this [link](https://https://recipesapp-b0a097f75058.herokuapp.com)

## 📜 License

This repository is for educational purposes only and has an MIT License

### Show your support

Give a ⭐ if you like this website!

# Contributors

* [Vadym Makohon](https://github.com/VadymMakohon/Recipe-App)
