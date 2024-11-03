# FinanceTracker

A web application for tracking personal finances built with Django and PyMongo. FinanceTracker allows users to manage their income, expenses, and budgets efficiently.

## Features

- User authentication (sign up, log in, log out)
- Add, edit, and delete income and expense records
- Categorize transactions for better analysis
- View financial summaries and trends
- Responsive design for mobile and desktop

## Tech Stack

- **Backend**: Django
- **Database**: MongoDB (via PyMongo)
- **Frontend**: HTML, CSS, JavaScript (optional frameworks like Bootstrap)
- **Environment**: Python 3.x

## Installation

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- pip
- MongoDB

### Clone the Repository

```
git clone https://github.com/nirmal8988/financetracker.git
cd financetracker
python -m venv myenv
myenv\scripts\activate
pip install django==3.2
pip install djongo
pip install pymongo==3.12.1
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
