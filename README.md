# Ex02 Django ORM Web Application
## Date: 22.04.2025

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).


## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM:
```
from django.db import models
class Student(models.Model):
    user=models.CharField(max_length=100,primary_key=True)
    password=models.CharField(max_length=100)
    email=models.EmailField()
    phone=models.CharField(max_length=100)
    profile=models.ImageField(upload_to='profile/')
    address=models.TextField()
```
## OUTPUT
![image](https://github.com/user-attachments/assets/5aed8e3e-5359-4823-85ef-1b8e55fc80a7)


## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
