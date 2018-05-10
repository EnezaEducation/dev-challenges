# You speak PHP, LARAVEL, MySQL
PHP & Laravel are at the core of the Eneza's system. 

As a back end developer, you'll be working on all aspects of the core system and so a solid understanding of PHP,
Laravel & MySQL is required

Though this task may seem simplistic, it will help us gauge your understanding of some core aspects of the different 
technologies we use.

## Description
We are an Educational System, so off course the challenge will be in relation to that.

We offer educational content to different sets of users. 
An ongoing challenge we have is to ensure that our content structures and management are scalable.

To access our content, a student has to select a specific course they want to study.
The course has a list of subjects that the student can study and each subject has a set of content they can take.
For simplicity in this challenge, the content that can be accessed is quizzes and tutorials. A quiz has a number of
multiple choice questions. A tutorial is just text content that can be read in prose form. Questions can be re-used in 
other quizzes. Quizzes and tutorials can be re-used in other courses.

### Requirements
- Create a REST API that can be used to Create, Read, Update & Delete (CRUD) courses, subjects and content.
- The API should implement OAuth authentication
- It should be possible for a developer to register and get access to the API through their assigned OAuth credentials. This
can be implemented by creating a simple sign up form that returns the required OAuth access credentials 
- All the code you write should follow [SOLID](https://laracasts.com/series/solid-principles-in-php/episodes/1) principles
- All the code you write should have adequate automated tests (Unit & Integration/Acceptance tests) using PHPUnit

### Technology
You are required to build your solution using PHP, LARAVEL 5 & MySQL 5.7

### How to submit
To submit your application, you should create a publicly accessible github repo with all the code you've worked on
In your github repo, create a README.md file that has instructions on how to setup the application and start using it.
We should be able to use it without having to contact you to clarify what to do.

Ensure you have seed data included that we can use to test. Have at least 2 courses, 3 subjects per course, 2 tutorials
in a course and 2 quizzes in a course.