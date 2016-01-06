You will need to install scipy, matplotlib, django, beautifulsoup and
reportlab to run this software.  On Debian and Ubuntu, you can run:

apt-get install python-scipy python-matplotlib
apt-get install python-django python-beautifulsoup
apt-get install python-reportlab python-reportlab-accel


Then install the pyeq2 fitting code with the command:

pip install pyeq2

I personally had to apt-get install python-pip to do so.


You can then cd to the project's top-level directory and
run the django development server with the command:

python manage.py runserver

and open the url http://127.0.0.1:8000/ in a browser.
