<img src="screenshot/login.png"/>

Django login custom error message

<img src="screenshot/loginerror.png"/>

<h1>Prerequisites</h1>

Install virtual environment:
On macOS and Linux:

<pre>
$ virtualenv -p python3 env
$ cd env
$ source bin/activate
$ pip install django
</pre>

<h1>How to run</h1>

1. Clone the repository:
<pre>git clone https://github.com/mikailaydogdu/simple-django-login.git</pre>

2. Run migrations:
<pre>python manage.py migrate</pre>

3. Create a user:
<pre>python manage.py createsuperuser</pre>

4. Run the server:
<pre>python manage.py runserver</pre>

5. And open 127.0.0.1:8000/login in your web browser.
