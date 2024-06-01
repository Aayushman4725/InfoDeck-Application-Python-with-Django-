
# Introduction

This application provides a detail of employee and student inside the Employee list and Student list tables. The CRUD operation can only be done through the admin panel i.e adding,deleting and modifying data.




## Installation

1. **Clone this repo**

```bash
  git clone https://github.com/Aayushman4725/InfoDeck-Application-Python-with-Django-.git
```


2. **Navigate to the Project Directory:**


```bash
  cd InfoDeck-Application-Python-with-Django-
```



3. **Set Up Virtual Environment (Optional but Recommended):**
```bash
  python -m venv venv
```
Detail setup guide for virtual environment is explained in the `django.txt` file.


Activate the virtual environment:
- On Windows:

```bash
 venv\Scripts\activate
```



- On macOS and Linux:

```bash
  source venv/bin/activate
```



4. **Install Pillow:**

```bash
  pip install  pillow
```

5. **Run Migrations:**


```bash
 python manage.py migrate
```


6. **Create Superuser (Mandatory):**

```bash
 python manage.py createsuperuser
```


7. **Run the Development Server:**

```bash
  python manage.py runserver
```

8. **Access the Application:**

Open a web browser and go to `http://localhost:8000` to see your Django application running.

**To go to admin panel :** 
`http://localhost:8000/admin`
