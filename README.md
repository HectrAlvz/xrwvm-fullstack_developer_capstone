# coding-project-template

## Full Stack Application Development Project
### Module 1 - Application - Static Pages

This project was executed locally. If you wish to use the cloud-based virtual lab environment from `https://www.edx.org/`, please follow these steps:

1. **Initial Setup**:
   - Open the file `server/djangoproj/settings.py` in the editor.
   - Set the `ALLOWED_HOSTS` and `CSRF_TRUSTED_ORIGINS` variables to reflect your Django app's root URL. Please do not include the `/` at the end.

```bash
ALLOWED_HOSTS=['localhost','<your application URL here>']
CSRF_TRUSTED_ORIGINS=['<your application URL here>']
```