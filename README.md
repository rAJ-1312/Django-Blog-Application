# Django Blog Web Application
![blog-app-cover](https://github.com/rAJ-1312/Django-Blog-Application/blob/main/screenshots/ss1.png?raw=true)


This Blogging web application project is purely made with Django as the backend and Bootstrap as the frontend.

## Installation Instructions

If you want to work with this project or create a version of it make sure to follow the steps below!

 Make sure to install ` Python 3 `, ` pip ` and ` virtualenv `   
1. Create a project folder
   
    ```bash
        $ mkdir project
        $ cd project
    ```
2. Create a python 3 virtualenv, and activate the environment to install requirements.
    ```bash
        $ python3 -m venv env
        $ source env/bin/activate
    ``` 
3. Install the project dependencies from `requirements.txt`
    ```
        (env)$ pip install -r requirements.txt
    ```
4. Clone the repository
   
    ```bash
        (env)$ git clone https://github.com/rAJ-1312/Django-Blog-Application.git
        (env)$ cd Django-Blog-Application
    ```

You have now successfully set up the project on your environment.

## How to run  the project?

Make sure you are in `env` and then do the following each at a time.

```bash
(env)$ python manage.py makemigrations
(env)$ python manage.py makemigrations mysite
(env)$ python manage.py makemigrations users
(env)$ python manage.py migrate
(env)$ python manage.py createsuperuser
(env)$ python manage.py runserver
```

## Features

### Blog list View
List all blog posts with Title, Author Name, Date Posted, Image, and some body part with Read More button.

### Blog Detail View
View the complete blog post when clicked on the Title.

### Recent Posts
List all the post which are created recently with Image thumb and Title.

### Filter
List all blog posts with the username you clicked.

### Pagination

<p align="center">
  <img align="center" src="screenshots/ss2.png?raw=true" alt="OOPS" width="700">
</p>
<p align="center">
  To limit with a certain number of posts in each page.
</p>



### Login/Register

<p align="center">
  <img align="center" src="screenshots/ss3.png?raw=true" alt="OOPS" width="700">
</p>
<p align="center">
  Users can Login/Register to the Blog App.
</p>



### Create Blog Post
Users can create blog posts from the front end with title and contenet.

### Edit Profile
Users can edit Profile Image, First Name, Last Name, Email id, username, password.

## Tech Stacks

* **Language:**  Python 3.10
* **Framework:** Django 3.1.5

## Latest Fixes

1. Added Pagination to show limited posts in one page.
2. Dynamic Title Tag for Blog Details

## How you can contribute to this project?

1. Fork this project to your GitHub account
2. Clone the repository to your local machine and follow the above Installation instructions.
3. Find an issue or feature and work on it.
4. Make a pull request.
