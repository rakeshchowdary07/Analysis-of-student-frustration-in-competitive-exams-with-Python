# Analysis of student frustration in competitive exams with Python
    collage major project

## Aim
 - The importance of a student’s affective component in learning has led ITS to include students’ affective states such as frustration, boredom, confusion, flow, curiosity, and anxiety in their learner models. In this research work, we focus on the response to students’ frustration.

## Software Requirements
    - Operating system : Windows xp,7,8,10.
    - python 3
    - Server    : Wamp Server

## Hardware Requirements
    - Processor : Pentium IV 2.4 GHz.
    - Ram : 512 Mb.

## Required Packages installation with required verison
    - open cmd
    - type cd C://Programfiles(x86)\\python36-32//Scripts or change your current working directory to the path where you installed you python scripts and then enter following commads
    - pip install --user django==1.11.5
    - pip install --user mysqlclient==1.3.12
    - pip install --user pillow
    - pip install --user opencv-python==3.1.0.5
    
## Execution
    - Clone the code into you device.
    - run wamp server, in browser [go to](http://localhost/phpmyadmin/), create a database named fustration and import the fustration.SQL file . or after running wamp serser, go to icon tray click on wamp server icon, go to MySQL and then click on MySQL console, A sql command promt console will open. now copy paste text from fustration.SQL in sql command promt.
    - from CMD go to the directory you cloned in which manage.py file is there. now type python manage.py runserver. An url will be displayed, go to that url in browser.
    
