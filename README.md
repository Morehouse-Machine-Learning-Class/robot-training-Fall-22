# CVAT Login Credentials For Super User

username = admin
password = root
email = zachare.lofton@morehouse.edu

## How to Make New Super User

```terminal
$ docker exec -it cvat_server bash -ic 'python manage.py createsuperuser'
```

After entering the above command, enter a username, password and email, and your new account should be set up on (this link)[http://localhost:8080].
