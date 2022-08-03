# Online-Examination-System WebApp Using Django Framework


![Logo](./Student%20information%20system.jpg)

this online exam system project in Python Django focuses mainly on dealing with student’s examinations. Also, the system displays all the available course and their question sets. In addition, the system allows managing question set by entering questions, options, and answers. This project is divided into three categories: Student, Teacher, and Admin Panel. In an overview of this web application, a student can simply register and start using it. Here, the system displays all the exams for the student. And the student can proceed to attend their examinations. All the exams are of MCQ type. After submission of answers, the student can view his/her marks with their number of attempts under respective courses. The system also counts the number of attempts a student takes in order to complete the exam.

## Teacher Panel
Talking about the teacher panel, each and every user needs approval from the administration in order to activate their accounts. Once after getting approval, he/she can access the system and manage courses with their question sets. For adding courses, the teacher has to enter the course name, total questions, and marks. Similarly, the same goes for the management of questions. He/she has to select a course, enter questions, total marks, and four options with the correct answer. For the rest, the teacher has a limit up to this point of accessing the system, but he/she can view the total number of students.

## Admin Panel
On the other hand, an admin has full control of the system. An admin manages the flow of the system, unlike every other user. The user can have an overview of each data. The admin has the right to approve/decline the teacher’s account. After approving the request, he/she can set up the salary of the teachers. Just like the teacher’s role, an admin can easily manage courses and question sets. Additionally, the admin can view each student’s total obtained marks from each course. All the steps are similar to the above in terms of managing the course and question sets. Besides, the admin can manage their students, teachers, and teacher’s salary record. In this way, these roles help in maintaining the proper flow of the system. And all the answers are checked by the system automatically.

Last but not least, a clean and simple dashboard is presented with various color combinations for greater user experience while using this Online Exam Management System Project in Python Django Framework. For its UI elements, a free open-source CSS framework; Bootstrap is on board with some Vanilla CSS too. Presenting a new Online Examination System Project in Python Django which includes an admin panel with student and teacher that contains all the essential features to follow up, and a knowledgeable resource for learning purposes.

[Watch Full Video]()

## Available Features:

- Student Panel
- Teacher Panel
- Admin Panel
- Attend Online Examinations
- Multiple Choice Question Sets
- Course Management
- Question Management
- Manage Teacher’s Account Request
- View Total Student Marks
- Counts Examination Attempts
- Set up Teacher’s Salary

## File Stucrure

```shell
├── Ecommerce-WebApp (Current Directory)
    ├── exam
    ├── onlinexam
    ├── templates
    ├── db.sqlite3
    ├── manage.py
    ├── requirements.txt
    └── static
        
```



## How to Install and Run this project?

### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

**3. Install Requirements from 'requirements.txt'**
```
$  pip install -r requirements.txt
```

**4. make database migrations**
```python
python manage.py migrate
```

**5. Login Credentials**

Create Super User (HOD)
```
$  python manage.py createsuperuser
```
Then Add Email, Username and Password

**6. Now Run Server**

Command for Windows:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

## Screenshots

![Admin Page](./1.PNG)
![Stuff Page](./3.PNG)
![student Page](./4.PNG)



## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.




## Authors
- [@naemazam](https://github.com/naemazam?tab=repositories)

## License

[MIT](https://choosealicense.com/licenses/mit/)



