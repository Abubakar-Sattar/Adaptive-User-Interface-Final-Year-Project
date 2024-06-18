# Adaptive User Interface Web App

This project is an Adaptive User Interface Web Application created using Django. It incorporates a machine learning algorithm to dynamically change the layout and UI of the website based on the user's age and gender.

## Features

- **Adaptive Layout and UI**: The application personalizes the user experience by adjusting the website's layout and UI elements according to the user's age and gender.
- **Django Framework**: Utilizes the robust Django framework for backend development.
- **Machine Learning Integration**: Implements a machine learning algorithm to predict and adapt the UI for each user.
- **User Authentication**: Secure user authentication system.
- **Responsive Design**: Ensures compatibility with various devices and screen sizes.

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x
- pip (Python package installer)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Abubakar-Sattar/Adaptive-User-Interface-Final-Year-Project.git
   cd Adaptive-User-Interface-Final-Year-Project

2. **Create a virtual environment**:

    ```bash
    python -m venv venv

3. **Activate the virtual environment**:

    Activate the virtual environment:
  
    **On Windows**:
    ```bash
    
    venv\Scripts\activate
    ```
    **On macOS/Linux**:
    ```bash
    
    source venv/bin/activate
    ```
        
4. **Install the required packages**:

    ```bash
    
    pip install -r requirements.txt
    Apply migrations:
    ```
       
    ```bash
  
    python manage.py migrate
    Create a superuser:
    ```

    ```bash
    
    python manage.py createsuperuser
    Run the development server:
    ```

    ```bash
    
    python manage.py runserver
    ```
**Access the application**:
Open your web browser and go to http://127.0.0.1:8000/.

Project Structure
```sql

Adaptive-User-Interface-Final-Year-Project/
├── adaptive_ui/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   └── templates/
│       └── adaptive_ui/
│           ├── base.html
│           ├── home.html
│           └── ...
├── adaptive_ui_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── ...
├── machine_learning/
│   ├── model.py
│   ├── preprocess.py
│   └── ...
├── static/
│   └── ...
├── manage.py
├── requirements.txt
└── README.md
```
**Key Components**

adaptive_ui/: Contains the Django app for the adaptive UI.
adaptive_ui_project/: Contains the project settings and configurations.
machine_learning/: Contains the machine learning model and preprocessing scripts.
static/: Contains static files like CSS, JavaScript, and images.

**Contributing**
Contributions are welcome! Please create a pull request or open an issue to discuss any changes.
