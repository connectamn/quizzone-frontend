# Quiz Zone

## Student User

Students can prepare for upcoming exams, such as university admissions or BCS, by creating an account with email verification. After taking an exam, they receive their scores via email and can view a leaderboard based on their results. Additionally, students can enroll in various courses using their accounts.

## Admin User

Admins have the ability to add question categories, questions, answer options, and courses. They also require verification by a super admin.

## API Reference

#### Get all question

```http
  https://quizzone-server.onrender.com/question/
```

#### Get all quiz

```http
  https://quizzone-server.onrender.com/question/
```

#### Get all courses

```http
  https://quizzone-server.onrender.com/course/
```

## Tech Stack

**Client:** JavaScript, HTML, Boostrap5, CSS

**Server:** Django, Django Rest Framework, PostgreeSQL

## Features

-   Authentication with email verification
-   Get result via email
-   Leaderboard
-   Purchase Course
-   Payment System

## Run Locally

Clone the project

```zsh
  git clone of backend https://github.com/imsay3m/quizzone-server.git
```

Go to the project directory

```zsh
  cd quizzone-server
```

Install django & rest_framework

```zsh
  pip install Django
  pip install djangorestframework
```

Start the server

```zsh
  python3 manage.py runserver
```

## Screenshots

#### The Home

<img width="1676" alt="home" src="">

#### The Question Category

<img width="1680" alt="question category" src="">

#### The Question Paper

<img width="1680" alt="Question set" src="">

#### The Exam

<img width="1436" alt="exam" src="">

#### The Question

<img width="1680" alt="question" src="">

#### The Courses

<img width="1680" alt="courseBuy" src="">

#### The payment method

<img width="1680" alt="payment" src="">

#### The Admin panel

<img width="1678" alt="admin-panel" src="">

#### Course Adding Feature

<img width="1679" alt="courses" src="">

## FAQ

#### Is Bkash Nagad avilable to purchase a course?

-   Yes, SSLCommerz intigrated here. so yeah all payments methods are available.

#### Is everyone can see their profile?

-   Yes, also you can update your profile pictures in here.
