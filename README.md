# GyojiApp
Gyoji Application Repository

Gyoji App
---------
About: 
    - The application is being developed to set daily targets and focus the user on completing those tasks before launching "Time Waster" apps.
    - The player will gain experience points according to their skill level.

Structure:
    1. manage.py to do all App realated tasks.
    
    2. Backend - 
        - Gyoji_Backend (primary app)
            = Gyoji_Backend will have all the code require on the backend side. 
            = The application is being made using Python Django framework.
            = Below are current specs of libraries:
                --pip -> 24.0
                --Django -> 5.0.14
                --djangorestframework -> 3.16.0
                --djangorestframework_simplejwt -> 5.5.0
                --mssql-django -> 1.5
                --PyJWT -> 2.9.0
                --pyodbc -> 5.2.0
        - MasterApp 
            = This app will have all the componets required for this app.
            = It has:
                -- "helpers" which will contain main api response model, token authentication, serializers & functions which would help services in performing their tasks.
                -- "services" which will be called by views.py to process the data and do all the db functionality.

    
    3. Frontend - 
        - Gyoji_Frontend will have all the code require on the frontend side.