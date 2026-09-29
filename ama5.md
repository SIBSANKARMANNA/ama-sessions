## What is Middleware?

Middleware is a layer between the request and response that can process or modify them before they reach the view or after the view returns a response.

## What is SECRET_KEY?

SECRET_KEY is a secret value used by Django for security-related operations, such as signing sessions, CSRF tokens, and password-reset links.

## What is MessageMiddleware?

MessageMiddleware enables Django's messages framework, which lets you show temporary messages to users, such as "Login successful" or "Invalid password".

## What is XSS?

XSS (Cross-Site Scripting) is a security attack where an attacker injects malicious JavaScript into a web page that other users can execute.

Django helps prevent XSS by escaping HTML in templates by default.

## What is ALLOWED_HOSTS?

ALLOWED_HOSTS is a Django setting that specifies which host/domain names are allowed to access your application.

Example:
ALLOWED_HOSTS = ["localhost", "127.0.0.1"]

## What is UTF-8?

UTF-8 is a character encoding that represents text using bytes. It supports almost all characters and languages.

## What is a Model in Django?

A Model is a Python class that represents data in the database.

Example:

class Student(models.Model):
    name = models.CharField(max_length=100)

Django uses the model to create, read, update, and delete database data through the ORM.

## What are WSGI and ASGI?

WSGI is an interface used to run Django applications with traditional synchronous HTTP requests.

ASGI is the newer interface that supports asynchronous operations, WebSockets, and long-running connections.

## What is Aggregation in Django?

Aggregation is used to perform calculations on a group of database records, such as COUNT, SUM, AVG, MAX, and MIN.

## Which middleware protects against Clickjacking?

Django uses XFrameOptionsMiddleware to protect against clickjacking.