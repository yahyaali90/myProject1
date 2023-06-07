PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm> pip install virtualenv APPLICATION_DEVELPOMENT\Assignment\ecomm> virtualenv env
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm> cd .\env\
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env> cd .\Scripts\
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env\Scripts> activate
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env\Scripts> pip list
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env\Scripts> activate.bat
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env\Scripts> ./activate.bat

PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env\Scripts> workspace activate

PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env\Scripts> cd..
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env> .\Scripts\activate
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env> pip list
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env> pip install django
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env> pip install pillow
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\env> cd..
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm> django-admin startproject ec
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm> cd .\ec\
PS D:\documents\PERSONNEL\SCHOLORSHIP\NANKAI\STUDIES\SEMISTER_2\WEB APPLICATION_DEVELPOMENT\Assignment\ecomm\ec> python manage.py runserver

Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).

You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.
May 22, 2023 - 23:10:26
Django version 4.2.1, using settings 'ec.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

[22/May/2023 23:13:22] "GET / HTTP/1.1" 200 10731
[22/May/2023 23:13:22] "GET /static/admin/css/fonts.css HTTP/1.1" 404 1816
Not Found: /favicon.ico
[22/May/2023 23:13:22] "GET /favicon.ico HTTP/1.1" 404 2106