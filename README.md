# Notes

**Database**

`By default, the configuration uses SQLite. If we want to use another database, install the appropriate database bindings and change the following keys in the DATABASES 'default' item to match the database connection settings`

**ENGINE** – Either 'django.db.backends.sqlite3', 'django.db.backends.postgresql', 'django.db.backends.mysql', or 'django.db.backends.oracle'.


**NAME** – The name of your database. If you’re using SQLite, the database will be a file on your computer; in that case, NAME should be the full absolute path, including filename, of that file. The default value, BASE_DIR / 'db.sqlite3', will store the file in your project directory.
If you are not using SQLite as your database, additional settings such as USER, PASSWORD, and HOST must be added.

