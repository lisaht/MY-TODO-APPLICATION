# Django Project Initialization Guide

This guide will walk you through the process of initializing a Django project so that you will be able to set up a basic Django project structure and get started with your development.

## Step 1: Create a Virtual Environment

To create a virtual environment, open your terminal or command prompt and run the following command. Make sure you are doing this in your project directory:

```shell
python -m venv env
```

This will create a new virtual environment named "env" in your project directory.

To activate the virtual environment, run the appropriate command for your operating system:

- For Windows:

```shell
env\Scripts\activate
```

- For macOS/Linux:

```shell
source env/bin/activate
```

Add the "env" folder to your `.gitignore` so that it won't be commited to GitHub
  > env/

## Step 2: Install Django

With your virtual environment activated, you can now install Django. Run the following command:

```shell
pip install django
```

## Step 3: Create a Django Project

To create a new Django project, in the terminal or command prompt, run the following command:

```shell
django-admin startproject projectname
```

Replace "projectname" with the desired name for your project, e.g `todo_api`. This command will create a new directory with the specified project name and generate the initial project structure.

## Step 4: Verify the Project Setup

After creating the project, navigate into the project directory:

```shell
cd projectname
```

You should see the following files and directories:

- `manage.py`: A command-line utility for various Django management tasks.
- `projectname/`: The project package containing project-specific settings and configurations.

## Step 5: Run the Development Server

To ensure that your project is set up correctly, run the following command:

```shell
python manage.py runserver
```

This will start the Django development server. Open your web browser and visit `http://localhost:8000/`. If everything is working correctly, you should see the Django default landing page.

To stop the development server, press `Ctrl + C` in the terminal or command prompt.

## Conclusion

Congratulations! You have successfully initialized a Django project. You can now start building your web application by defining models, views, and templates.

Remember to consult the [documentation](https://docs.djangoproject.com/) and explore the numerous Django features to make the most out of your development experience. Happy coding!
