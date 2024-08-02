# Module 13: Object-Relational Mapping (ORM) / E-commerce Back End

## Description
This is the challenge for Module 13 of the coding bootcamp. This is the back end for an e-commerce site that connects to a PostgresSQL database. The user is able to create, read, update, and delete categories, products, and tags in their database.

### User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the PostgreSQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Application
You can see how the project works in the video [here](https://drive.google.com/file/d/16lFrljs8LKdsVl8oZw7WPEKztMNUWQ0s/view?usp=sharing).

Once you start the server, you can use the API routes to GET, POST, PUT, and DELETE categories, products, and tags. Below are some examples of those actions in Postman.

GET all categories
![GET ALL](/assets/GET_all.png)

GET single product by id
![GET ONE](/assets/GET_one.png)

POST new category
![POST](/assets/POST.png)

PUT (update) category by id
![PUT](/assets/PUT.png)

DELETE tag by id
![DELETE](/assets/DELETE.png)