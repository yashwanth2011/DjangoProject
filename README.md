# DjangoProject
Navigate to the code directory on your Desktop and create a helloworld directory with the following commands.
Create a new virtual environment called .venv, activate it, and install Django with Pip
Now we’ll use the Django startproject command to make a new project called django_project.
The .venv directory was created with our virtual environment but Django has added a django_project directory and a manage.py file.
The manage.py file is not part of django_project but is used to execute various Django commands such as running the local web server or creating a new app.
The next step is therefore to create our first view. Start by updating the views.py file.
Moving along we need to configure our URLs. In your text editor, create a new file called urls.py within the pages app
However, to create a static webpage (not linked to a database) we can hardcode the data into a view so the model is not needed.The next step is therefore to create our first view. Start by updating the views.py file.
We’ve created a function called homePageView that accepts the request object and returns a response with the string “Hello, World!”.
Run python manage.py runserver to start development server.
