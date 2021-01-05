# Session Auth
This is a simple project to demonstrate how to implement session authentication in a Django and React application. This project will show how to send your session cookie and CSRF token along with your request in order to properly access API endpoints that require you to be authenticated.

In order to test out this project, follow these steps:
- clone the repository
- in the frontend folder, run: npm install, this will install the required frontend packages
- in the frontend folder, run: npm run build, this will make a build folder and copy it into the backend folder
- in the backend folder, run: python3 -m venv venv
- then activate the virtual environment
- in the backend folder, run: pip install -r requirements.txt
- go to backend/session_auth/settings.py, and under DATABASES, set the PASSWORD field to your database password