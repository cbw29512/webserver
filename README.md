# webserver
https://ruslanspivak.com/lsbaws-part2/

You can also test the server on the command line using the ‘curl’ utility:

$ curl -v http://localhost:8888/hello

run servers:

pyramid $ python3 webserver.py pyramidapp:app
flask $ python3 webserver.py flaskapp:app
django $ python3 webserver.py djangoapp:app
WSGI $ python3 webserver.py wsgiapp:app