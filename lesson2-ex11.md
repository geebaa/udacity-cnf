How to get the exercise 11 of lesson-2 working on Windows 10
=============================================================

Step-1   Prerequisite python3 and pip 
=====================================
    python3 -V
    Python 3.9.5
    
    pip --version
    pip 21.1.1

Step-2  clone the repo  
=======================
    git clone git@github.com:udacity/nd064_course_1.git
    cd .\nd064_course_1\exercises\python-helloworld\

Step-3  install virtual environment package  
===========================================

    pip install virtualenv

Step-4  create virtual environment  
===================================

    python3 -m venv venv

Step-5  Activate virtual environment  
===================================

    .\venv\Scripts\activate

Step-6  Install flask  
=====================

    pip install Flask

step-7 Set the environment for "flask run"
==========================================
    setx FLASK_APP "app.py"

step-8  run the app using
==========================================

    flask run

step-9
======
visit "http://localhost:5000/" from the browser
