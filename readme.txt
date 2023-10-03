===============================================================================
                              CALCULATOR APP
===============================================================================

DESCRIPTION
-------------------------------------------------------------------------------
This repository hosts a simple web-based calculator built with Django. The app 
provides basic arithmetic functionality, allowing users to perform operations 
like addition, subtraction, multiplication, and division.

FEATURES
-------------------------------------------------------------------------------
- Basic Arithmetic Operations: Addition, Subtraction, Multiplication, Division
- Mobile-responsive design
- Elegant user interface with visual feedback

SETUP AND INSTALLATION
-------------------------------------------------------------------------------
1. **Clone the Repository**
    ```
    git clone <repository-url>
    ```

2. **Setup Virtual Environment**
    - Windows:
        ```
        python -m venv venv
        .\venv\Scripts\activate
        ```
    - Unix/MacOS:
        ```
        python3 -m venv venv
        source venv/bin/activate
        ```
3. **Install Dependencies**
    ```
    pip install -r requirements.txt
    ```
    Ensure `requirements.txt` includes:
    ```
    Django>=3.2,<4.0
    ```
4. **Run Migrations**
    ```
    python manage.py migrate
    ```
5. **Collect Static Files**
    Ensure `STATIC_ROOT` and `STATIC_URL` are configured in `settings.py`:
    ```
    python manage.py collectstatic
    ```
6. **Run the Development Server**
    ```
    python manage.py runserver
    ```
    Access the app on: [http://127.0.0.1:8000](http://127.0.0.1:8000)

7. **Admin Panel (optional)**
    Create a superuser to access the Django admin panel:
    ```
    python manage.py createsuperuser
    ```
    And access the admin panel on: [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

USAGE
-------------------------------------------------------------------------------
1. **Performing Calculations**
    - Navigate to the home page of the app.
    - Enter two numeric values into the input fields.
    - Select a desired arithmetic operation.
    - Click "Calculate".
    - View the result displayed below the calculate button.

2. **Mobile Usage**
    - Navigate using a mobile browser; the app adapts to smaller screen sizes.

CONTRIBUTING
-------------------------------------------------------------------------------
We welcome contributions and bug reporting. Feel free to open an issue or create 
a pull request!

LICENSE
-------------------------------------------------------------------------------
This project is open-source and available to everyone under the [MIT License](LICENSE).

CONTACT
-------------------------------------------------------------------------------
For more details or questions, please reach out to [your-email@example.com](mailto:your-email@example.com).

Thank you for exploring our Calculator App!
