# TASK MANAGEEMNT SYSTEM

This project is done using a python framework called django. This project aims at a task management project where users can create account, sign in and create their respective tasks. They can also edit other's tasks, but can't delete. Only the owners of the task can delete such a task. We have used MySQL as the SQL client.

## TEAM MEMBERS
[ARJUN SHIJU](https://github.com/Godly-arj)

[ALLEN JUDE](https://github.com/ajallen14)

[JOE SUNIL](https://github.com/kuttanerror)

[ALEN T L](https://github.com/ALENTL)

## [Link to product walkthrough](https://youtu.be/te3z8I1s5Uk)

Click on the above heading, it will redirect to youtube to the product walk through

## How it works

<ol>

<li><strong>Explanation</strong></li>

The project has its backend done using Django. We have used *django-admin startproject task_manager* to create the project. We have 4 apps in the project namely *labels*, *statuses*, *tasks* and *uses*.

The tasks app is used to list all the tasks and get the post from the user and query them into the database. Label app is used to provide label to the task. Statuses app is used to show the status of the respective task. Either completed or incomplete. The user can add more status in the status section. Users app is used to manage all the users in the system. As of now every user can update each and every tasks. From the next release we are planning to focus more on users and their activity control.

<li><strong>[Video Content](https://youtu.be/zj7c3AN5rrs)</strong></li>

</ol>


## Libraries Used
[Django](https://djangoproject.com)

[MariaDB](https://mariadb.org)

## How To Configure
<ol>
    <li>Install python from https://python.org</li>
    <li>Create a virual environment using *python -m venv env*</li>
    <li>Install required modules by using the command <strong>pip install -r requirements.txt</strong></li>
</ol>

## How to Run
After configuring the project, you can run the app by using *python manage.py runserver*