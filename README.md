# coreapitest
This is a demo project for https://github.com/tomchristie/django-rest-framework/issues/4401

# What is the issue?

- REST-API mounted under `/api/v1/`
- Resolved `url` property in corejson does not include the `/api/v1/`-Prefix

# Relevant files within this project

- [coreapitest/urls.py](coreapitest/urls.py)
- [demo/views.py](demo/views.py)
