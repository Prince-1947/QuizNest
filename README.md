# QuizNest
This is a web application developed in Python using the Django framework.
1. Extract the QuizNest.zip file.
2. Navigate to the project folder in the terminal.
3. Start the Django server with this command in terminal: python manage.py runserver
4. You will get an URL in the terminal, paste it on a browser.
5. You are Welcome.

If need to replace the current quiz question and answer,then do the following steps:
1. Delete the database db.sqlite3
2. Go to myproject/quiz/forms.py and change the questions in given format
3. Go to myproject/quiz/views.py and change the correct answers in given format
4. Also number of question can be edited.
5. Now navigate to the myproject folder in the terminal
6. Recreate the database with migration command step 1: python manage.py makemigrations
7. Recreate the database with migration command step 2:python manage.py migrate
8. Finally start the Django server with this command in terminal: python manage.py runserver
9. voila!!

