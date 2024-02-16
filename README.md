# LAB - 29

## Django Custom User

### Author: Latherio Kidd

### Overview
Django does a great job at allowing us to get started with a solid foundation. But a foundation is just the beginning. We still need to “build the house.” One of the first things many developers choose to do is to create a custom user model. This lab demonstrates how to create a Django application from scratch with a custom user model named `CustomUser`. The application will integrate seamlessly with Django Admin, leveraging the new features and considerations of Django 5.

### Links and Resources

### Setup

#### `.env` requirements (where applicable)
- `PORT` - Port Number
- `DATABASE_URL` - URL to the running Postgres instance/db

#### How to initialize/run your application (where applicable)

```bash
python manage.py runserver
```

#### How to use your library (where applicable)

### Tests

- How do you run tests?
  - Tests can be run with the following command:
    ```bash
    python manage.py test
    ```

### Feature Tasks and Requirements
- Create a Django application `django-custom-user` from scratch that has a custom user model named `CustomUser`.
- The application should work with Django Admin.
- Use the very helpful tutorial at [LearnDjango](https://learndjango.com/), but check the Implementation Notes below about Django 5 tweak.

### Implementation Notes
- Make sure to create a custom user model before migrating data.
- **WARNING**: Django version 5 no longer supports logging out with a GET request. Refer to the demo for safe logging out in Django 5.

### User Acceptance Tests
No acceptance tests are required for this lab.

### Configuration
Refer to Lab Submission Instructions for detailed instructions.

### Stretch Goals
- Create a Django application using DjangoX.
- Style the form using Django Widget Tweaks.

---

This README provides a structured overview of your lab project, including how to set it up, run it, and the key tasks involved. Remember to replace placeholders with actual links and details specific to your project where applicable.