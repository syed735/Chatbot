# Medical Chatbot

Welcome to Medical Chatbot! This web application is designed to provide users with a platform to chat about diabetes, get information, and support. The application includes user authentication features such as login and signup.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

Medical Chatbot is a Django-based web application that allows users to chat and get information about diabetes. Whether you need information about symptoms, treatment options, or lifestyle tips, this chatbot is here to help.

## Features

- **User Authentication:** Secure login and signup functionality.
- **Chat Interface:** Users can chat with the bot to get information about diabetes.
- **User Profile:** Manage your profile and view chat history.

## Tech Stack

- **Backend:** Django
- **Frontend:** HTML, CSS, JavaScript (Bootstrap for styling)
- **Database:** MySQL (using PyMySQL)
- **Chatbot Framework:** Integrate a chatbot framework like Rasa or Dialogflow (if applicable)

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- [Python](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installation/)
- [MySQL](https://dev.mysql.com/downloads/installer/)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Syed735/Chatbot.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Chatbot
    ```

3. Create a virtual environment:
    ```sh
    python -m venv venv
    ```

4. Activate the virtual environment:
    - On Windows:
      ```sh
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```sh
      source venv/bin/activate
      ```

5. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

6. Set up the MySQL database:
    - Create a database in MySQL:
      ```sql
      CREATE DATABASE Chatbot;
      ```
    - Update the database settings in `settings.py`:
      ```python
      DATABASES = {
          'default': {
              'ENGINE': 'django.db.backends.mysql',
              'NAME': 'Chatbot',
              'USER': 'your_mysql_username',
              'PASSWORD': 'your_mysql_password',
              'HOST': 'localhost',
              'PORT': '3306',
          }
      }
      ```

7. Apply the migrations:
    ```sh
    python manage.py migrate
    ```

8. Create a superuser to access the admin panel:
    ```sh
    python manage.py createsuperuser
    ```

9. Run the development server:
    ```sh
    python manage.py runserver
    ```

    The application will be available at `http://127.0.0.1:8000`.

## Usage

1. **Sign Up:** Create a new account by providing your details.
2. **Log In:** Access your account using your credentials.
3. **Chat:** Use the chat interface to get information about diabetes.
4. **Manage Profile:** View and update your profile and chat history.

## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

Please make sure to update tests as appropriate.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Syed Sufiyan - sufiyanahmedsyed388@gmail.com

Project Link: https://github.com/yourusername/Chatbot

---


