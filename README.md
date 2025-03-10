# Personal Expense Tracker
![Expense Tracker UI](https://github-production-user-asset-6210df.s3.amazonaws.com/102463335/277596025-f31d97f4-4841-44cb-b2af-62286c60a0c9.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250310%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250310T091248Z&X-Amz-Expires=300&X-Amz-Signature=130e421dfb1cb1499b7fc4be76d7c39f89d5471fbe455fe1c0fab67e0f097194&X-Amz-SignedHeaders=host)
![forecast Expense UI ](https://github-production-user-asset-6210df.s3.amazonaws.com/102463335/277673170-c1188567-39c5-4cc1-8916-24f3d3712ee8.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250310%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250310T091345Z&X-Amz-Expires=300&X-Amz-Signature=f5b69aeb2b1a31f4830579fd74f09189dff941ef2aa2c4f3c9b00f4fb02b7dde&X-Amz-SignedHeaders=host)

![forecast Expense UI 2](https://github-production-user-asset-6210df.s3.amazonaws.com/102463335/277673219-a2088949-c4f6-4d18-ba23-308ce3ad19f4.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250310%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250310T091455Z&X-Amz-Expires=300&X-Amz-Signature=b867c8a66f3aef23dc272920285f91f6f2e3f1649c9b731f97e6ece61d49cc81&X-Amz-SignedHeaders=host)
![report ui Expensewise](https://github-production-user-asset-6210df.s3.amazonaws.com/102463335/277673330-c3271340-d3ea-4171-9618-04c8c0a98759.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20250310%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20250310T091525Z&X-Amz-Expires=300&X-Amz-Signature=d2081dd857f221ed1bc2a955c8f23213bff384e07bc27a10e03f5ec30a07919b&X-Amz-SignedHeaders=host)

## Overview

This is a personal expense tracker web application built using Django. It allows users to log their expenses, categorize them, and provides automated expense categorization and future expense prediction features. This README.md file provides instructions for setting up and running the application on your local machine, as well as some additional information about its features and usage.

## Features

- **Expense Logging**: Easily log your daily expenses, including the date, description, amount, and category.

- **Automated Expense Categorization**: The application uses machine learning algorithms to automatically categorize expenses based on their descriptions. This makes it easier to track and manage your spending.

- **Future Expense Prediction**: The application provides predictions for future expenses based on your spending history. This can help you plan your budget more effectively.

- **User Authentication**: Users can create accounts and log in to securely manage their expenses.

## Setup

To run this application locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/personal-expense-tracker.git
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - **Windows**:

     ```bash
     venv\Scripts\activate
     ```

   - **macOS and Linux**:

     ```bash
     source venv/bin/activate
     ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Apply database migrations:

   ```bash
   python manage.py migrate
   ```

6. Create a superuser account to access the admin panel:

   ```bash
   python manage.py createsuperuser
   ```

7. Start the development server:

   ```bash
   python manage.py runserver
   ```

8. Open your web browser and go to `http://localhost:8000` to access the application.

## Usage

1. Create a new account or log in using your superuser account.

2. Start logging your expenses by clicking the "Add Expense" button.

3. Fill in the expense details, including the date, description, amount, and category. You can also leave the category empty, and the application will attempt to automatically categorize it.

4. View your expense history, categorized expenses, and future expense predictions on the dashboard.

5. To access the admin panel, go to `http://localhost:8000/admin/` and log in with your superuser credentials. From the admin panel, you can manage users, categories, and view the database.

## Acknowledgments

- Thanks to the Django community for creating such a powerful web framework.

- The automated expense categorization and prediction features are powered by machine learning models, which were trained using various open-source libraries and datasets.

Feel free to customize and enhance this expense tracker according to your needs. Happy budgeting!
