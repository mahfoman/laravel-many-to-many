## Laravel many to many relationship Demo with users table

This is simple one controller and one model but two tables ( doctor and patient both with users table and pivot table ) many to many demo project. Here eloquent ORM belongsToMany relationships is used 
and in controller DoctorController.php following methods are created

- Index ( listing all the doctors with patients )
- create ( creating doctors and patients data )
- edit ( editing doctors and patients )
- delete ( deleting doctors and patients )


Two migration files are also created for users and doctor_patient table inside migration folder. 

## Here following are not used 

- html forms 
- validations 
- Resource routes

Laravel 10.43.0 on php 8.1.0 is used for this demo project

## How to use

- Clone or download the project
- composer install
- copying .env from .env.example [ cp .env.example .env ]
- creating a mysql database and update the name in .env file
- Setting APP_KEY value in .env by - php artisan key:generate
- seeding data [ php artisan migrate ]
- running the project [php artisan serve]
- browsing to http://localhost:8000/doctors to see the output


## License
Feel free to use and re-use any way you want.

---

## You can check more tutorials and posts in my site [LaravelCodeSnippet.com](https://laravelcodesnippets.com)

## Most viewed Links in Laravelcodesnippets.com

- [Building mini ecommerce in Laravel](https://laravelcodesnippets.com/communities/projects/topics/mini-ecommerce/posts/113)
- [Building mini issue trackcer with vue3 spa, authentication and authorization in Laravel](https://laravelcodesnippets.com/communities/projects/topics/mini-issue-tracker/posts/159)

## Available for freelance work
Feel free to reach me at [mahfoozurrahman.com](https://www.mahfoozurrahman.com)
