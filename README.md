# College-ERP
A college management system built using Django framework. It is designed for interactions between students and teachers. Features include attendance, marks and time table.

## Installation

Python and Django need to be installed

```bash
pip install django
```

## Usage

Go to the College-ERP folder and run

```bash
python manage.py runserver
```

Then go to the browser and enter the url **http://127.0.0.1:8000/**


## Login

The login page is common for students and teachers.  
The username is their name and password for everyone is 'project123'.  

Example usernames:  
student- 'samarth'  
teacher- 'trisila'  

You can access the django admin page at **http://127.0.0.1:8000/admin** and login with username 'admin' and the above password.

Also a new admin user can be created using

```bash
python manage.py createsuperuser
```

## Users

New students and teachers can be added through the admin page. A new user needs to be created for each. 

The admin page is used to modify all tables such as Students, Teachers, Departments, Courses, Classes etc.

**For more details regarding the system and features please refer the reports included.**

## Update (29/11/2020)

Added method to reset attendance time range in Django Admin page.

![alt_text](https://i.imgur.com/0xOWmUZ.png)

This is present in Django Admin -> Attendance (http://127.0.0.1:8000/admin/info/attendanceclass/).  
Start Date: Start Date of Attendance period  
End Date: End Date of Attendance period

This will delete all present attendance data and create new attendance objects for the given time range. 

## Screenshots

### Teacher Page

![alt text](https://imgur.com/yhnGb3V.png)

![alt text](https://imgur.com/Y7DOUrO.png)

![alt text](https://imgur.com/yIqtBJ1.png)

![alt text](https://imgur.com/eB8gs8D.png)

![alt text](https://imgur.com/BBitol2.png)

![alt text](https://imgur.com/aPTDZ3i.png)

![alt text](https://imgur.com/2Q8IjVe.png)

### Student Page

![alt text](https://imgur.com/aCigshw.png)

![alt text](https://imgur.com/HS4jENc.png)

![alt text](https://imgur.com/ZcjSl2F.png)

![alt text](https://imgur.com/y2w1IgB.png)

![alt text](https://imgur.com/Hh9ByVN.png)
