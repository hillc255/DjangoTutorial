=====
Polls
=====

Polls is a Django app to conduct Web-based polls. For each question,
visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "polls" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'polls',
    ]

2. Include the polls URLconf in your project urls.py like this::

    path('polls/', include('polls.urls')),

3. Run ``python manage.py migrate`` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.

Additional commands:
From Anaconda prompt - basic commands:
(base) C:\Users\Claudia\PythonProjects\[projectname]>
1. get shell commands> python manage.py shell
2. execute test cases> python manage.py test polls
3. run the server to get web pages> python manage.py runserver
4. view public web page: http://127.0.0.1:8000/polls/
5. view admin web page: http://127.0.0.1:8000/admin/polls/
6. find django source files: python -c "import django; print(django.__path__)"
7. source templates: C:\Users\Claudia\Anaconda3\Lib\site-packages\django\contrib\admin\templates\admin