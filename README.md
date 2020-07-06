This repository does not contain code, only issues.

Estimating the code quality by dividing the number of issues by the amount of
code will therefore give a `ZeroDivisionError`.


**Some useful links**:
- Documentation on [message schemas](https://fedora-messaging.readthedocs.io/en/stable/messages.html)
- [CookieCutter template](https://github.com/fedora-infra/cookiecutter-message-schemas) for message schemas
- A library to [convert SQLAlchemy models to jsonschemas](https://pypi.org/project/alchemyjsonschema/) that may be useful when porting a SQLAlchemy-based app.


**Definition of Done**:
- Check if the application is converted to fedora-messaging, if not, port it
- Create a new repo on the same server (Github or Pagure) for the messages, called `<app-name>-messages`
- Write the schemas, with 100% test coverage
- Publish an early version on PyPI (version < 1.0.0)
- Add the schemas to the application, replacing the `fedora_messaging.api.Message` classes
- Make sure the application's unit tests still pass
