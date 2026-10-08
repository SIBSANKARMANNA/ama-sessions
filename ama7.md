# What are messages in Django?
- Django messages are used to show temporary notifications to users.

# What is git revert?
- git revert undoes a previous commit by creating a new commit.

# What is session middleware?
- SessionMiddleware enables Django to store and retrieve user session data between requests.

# What is an atomic transaction?
- An atomic transaction means all database operations succeed together, or all of them are rolled back.


# How do you run a custom management command file using manage.py in Django?
```
app/
└── management/
    └── commands/
        └── import_data.py

```
- python manage.py import_data


# What is a view in Django?
- A view contains the logic that handles a request and returns a response.


# What is the collectstatic command?
- collectstatic collects static files from different apps into one directory, usually for production deployment.


# Why do we need async and await?
- async and await allow Python to perform asynchronous operations without unnecessarily blocking while waiting.

# Why should we not use DEBUG=True in production?
- Because DEBUG=True can expose sensitive information, such as detailed error messages, file paths, and configuration details.

# What is the difference between select_related() and related_name?
- select_related() is used to optimize database queries by fetching related objects using a SQL JOIN.
- related_name defines the reverse name used to access related objects.