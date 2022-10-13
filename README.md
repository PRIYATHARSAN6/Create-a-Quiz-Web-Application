# Create-a-Quiz-Web-Application

It is an online quiz platform that allows teachers to create quizzes and let students try them in their comfort zones.

***
### Introduction 
we develop a quiz application using Python Django. Let’s see what all functionalities we developing in this project (for two roles – Teacher and Student).

  #### Student
  * Sign up (register)
  * Login
  * Quiz page (with timer)
  * Result page (with score, time taken, percentage score, total questions, correct answers, wrong answers)

  #### Teacher
  * Login
  * Sign up
  * Add Question
  * Quiz Page
  * Result Page

  #### Teacher
  1 Create an account as a teacher ,
  2 After login can view a dashboard with all the available quizes ,
  3 Add new questions to the existing quize ,
  4 Create new quizes and add questions ,
  5 Review created quizes ,
  6 Delete quizes .
  #### Student
  1 Create an account as a student ,
  2 After login can view a dashboard with all the available quizes ,
  3 Attempt any quiz ,
  4 View grades of all the attempted quizes . 
  
### Project Prerequisites Are
  * HTML: to display content on web page
  * CSS: to style HTML document
  * Python: Programming language
  * Django: Python framework
  
 *** 
### How to Run the Project 
  * Install Python 
  * Install `Django 4.1.2`
  
  ```
  pip install Django
  ```
  * Download the poroject to your local machine 
  * Open a terminal from the project directory and run the below commands
  
  ```
  pip install mysql-connector-python-rf
  pip install pymysql
  pip install django-widget-tweaks
  ```
   * Open `settings.py` and add `widget-tweaks` to `INSTALLED_APPS` as below;

  ```python
  INSTALLED_APPS += [
    'widget_tweaks',
  ]
  ```
 * Create a php MySQL Database as `quizdb`
 * Run the following commands to do the database migrations

 ```
 python manage.py makemigrations
 python manage.py migrate
```
 * Run the server
 
 ```
 python manage.py runserver
 ```
 * Now you can view the project using the below URL
