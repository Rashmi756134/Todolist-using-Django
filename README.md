
# Todolist App

## Overview

This is a simple **Todolist application** built using **Django**, **HTML**, and **Python**. The app allows users to manage their tasks by adding tasks with timings, modifying them, and deleting tasks once completed. It is a straightforward project designed to demonstrate basic functionality with Django's views, models, and templates.

## Features

- **Add Tasks**: Users can add new tasks to the list along with specific timings.
- **Modify Tasks**: Users can update or modify the details of an existing task.
- **Delete Tasks**: Tasks can be deleted once completed.
- **Responsive UI**: Simple, clean, and responsive user interface using HTML.

## Technologies Used

- **Django**: A high-level Python web framework for rapid development.
- **Python**: The backend programming language.
- **HTML**: For creating the user interface.
- **CSS**: (Optional) For styling the webpage (You can add custom styling if included).
- **SQLite**: Default database used by Django for storing the tasks.
  
## Installation

Follow the steps below to set up this project on your local machine.

### Step 1: Clone the Repository

Clone the repository using the following command:

```bash
git clone https://github.com/Rashmi756134/Todolist-using-Django.git
 ```
### Step 2: Set Up Virtual Environment

Navigate to your project directory and create a virtual environment to isolate the dependencies.
```bash
cd Todolist-using-Django 
python3 -m venv venv
```

Activate the virtual environment:

On Windows:

    venv\Scripts\activate


On Mac/Linux:

    source venv/bin/activate

### Step 3: Install Dependencies

Install the required packages listed in requirements.txt (if you have one). If not, you can install Django manually:
```bash
pip install django
```
### Step 4: Apply Database Migrations

Run the following command to apply the database migrations:
```bash
python manage.py migrate
```
### Step 5: Run the Development Server

Once everything is set up, run the development server:
```bash
python manage.py runserver
```
Visit http://127.0.0.1:8000/ in your browser to see the Todolist application in action.

## Usage

- **Add Tasks**: You can add tasks with a title and time.
- **Modify Tasks**:To edit any task, click on the task and update the details.
- **Delete Tasks**: Once a task is done, you can delete it from the list.

## Key Files:

- **models.py**: Contains the model for tasks (task name, time).
- **views.py**: Handles all views to display, add, update, and delete tasks.
- **urls.py**: Contains URL routing to link views to URLs.
- **templates/todolist/**: Contains HTML files to render the frontend.

## Future Improvements

- Implement user authentication (sign-up/login) to manage tasks for individual users.
- Add due dates and notifications for task reminders.
- Add categories or tags for tasks.
