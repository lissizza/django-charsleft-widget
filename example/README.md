# Example

To run the example application, make sure you have the required
packages installed.  You can do this using following commands :

```shell
mkvirtualenv example
pip install -r example/requirements.txt
```

This assumes you already have ``virtualenv`` and ``virtualenvwrapper``
installed and configured.

Next, you can setup the django instance using :

```shell
python example/manage.py migrate
```

And run it :
```shell
python example/manage.py runserver
```

Good luck!

