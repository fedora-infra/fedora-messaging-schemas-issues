This repository does not contain code, only issues.

Estimating the code quality by dividing the number of issues by the amount of
code will therefore give a `ZeroDivisionError`.

Some useful links:
- Documentation on [message schemas](https://fedora-messaging.readthedocs.io/en/stable/messages.html)
- [CookieCutter template](https://github.com/fedora-infra/cookiecutter-message-schemas) for message schemas
- A library to [convert SQLAlchemy models to jsonschemas](https://pypi.org/project/alchemyjsonschema/) that may be useful when porting a SQLAlchemy-based app.
