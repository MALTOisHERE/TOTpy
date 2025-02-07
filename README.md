
# <img src="https://github.com/user-attachments/assets/7dcc8137-433f-453f-8ec1-0f3bce2e3728" alt="logo2" width="150">

**TOTpy** is a lightweight and interactive authentication interface that demonstrates the implementation of **Time-Based One-Time Password (TOTP)** Multi-Factor Authentication (MFA). It’s designed as a learning tool or a starting point for integrating TOTP-based MFA into your applications.


## Features

- **TOTP MFA Implementation**: Secure authentication using time-based one-time passwords.
- **User Authentication**: Supports user login, signup, and logout functionality.
- **Flask-Based**: Built with Python and Flask for simplicity and flexibility.
- **Environment Configuration**: Easy setup using a `.env` file for sensitive configurations.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.7 or higher
- `pip` (Python package manager)


## Getting Started

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/MALTOisHERE/TOTpy.git
cd TOTpy
```
### 2. Install Dependencies

Install the required Python packages using pip:

```bash
pip install -r requirements.txt
```
### 3. Configure the Environment

Create a ```.env``` file in the root directory of the project and add your Flask secret key:

```env
SECRET_KEY=your_secret_key_here
```

Replace ```your_secret_key_here``` with a strong, random string. This key is used to securely sign session cookies and other sensitive data.

### 4. Run the Application

Start the Flask development server:

```bash
python main.py
```
or

```bash
python3 main.py
```

The application should now be running at ```http://127.0.0.1:5000/```.


## Project Structure

```
TOTpy/
├── main.py                # Entry point for the Flask application
├── requirements.txt       # List of Python dependencies
├── .env                   # Environment variables (e.g., secret key)
├── static/                # Static files (CSS, JS, images)
│   └── ...
├── templates/             # HTML templates
│   └── ...
└── README.md              # Project documentation
```




