# todolist

## Installation

### Cloning from GitHub Repository

To get started with the todolist Django Web App, you can clone the repository from GitHub using the following steps:
 
1. **Clone the repository**:

   ```bash
   https://github.com/ParimaSA/todolist.git
   ```

2. **Install the GTK Installer** (To use weasyprint):

   [GTK Installer](https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases/download/2022-01-04/gtk3-runtime-3.24.31-2022-01-04-ts-win64.exe)

3. **Navigate to the project folder**:

   ```bash
   cd todolist
   ```

4. **Create and activate a virtual environment** (optional but recommended):

   ```bash
   python -m venv myworld
   source myworld/bin/activate  # On Windows use: myworld\Scripts\activate.bat
   ```

5. **Install project dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

7. **Run database migrations**:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

8. **Create a superuser account (for admin access)**:

    ```bash
    python manage.py createsuperuser
    ```

8. **Start the development server**:

    ```bash
    python manage.py runserver
    ```

9. **Open your web browser and go to** [http://localhost:8000](http://localhost:8000) **to access the todolist Django Web App**.

## Features

The todolist Django Web App offers the following features:

- **Task Management**: Easily add, edit, and delete tasks.
- **Task Prioritization**: Assign priority levels to tasks.
- **Task Categorization**: Divide tasks into different categories.
- **Task Reminder**: Send Email to users for specific tasks (with Celery).
- **User Authentication**: Secure account management (signin, signup, forgot password).
- **Admin Dashboard**: Access admin dashboard [http://localhost:8000/todo-admin/](http://localhost:8000/todo-admin/) to manage users and tasks.
- **Profile Management**: View/Change user details.
- **Export Task Details**: Download PDF / CSV file of your tasks.
- **Dark Mode**: Trigger Dark theme for an awesome experience.



## References

- https://github.com/divanov11/Django-To-Do-list-with-user-authentication/tree/master/base/templates/base

- https://github.com/NAHIAN-19/Todo-List-Django