filterable Animal Collection Python CRUD application, with pymongo as the controller, Dash widgets for an
interactive view, presenting dynamic updates to client including geolocation and a Pie chart, with mongodb user
authentication.


CS340

Relevant files:
* Grazioso_Salvare_Logo.png
* ProjectTwoDashboard.ipynb
* CS 340 README Template_UPDATED.docx
* AnimalShelter.py

How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?
Write code with modularized functions, meaningful variable and function names. Use an object-oriented approach with inheritance, encapsulation, and polymorphic behavior for code readability and reduction.
Write testable code, and catch all errors and write test conditions.

How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?
In choosing the correct database platform, it's important to take into consideration the clients needs. Is the data overall non-relational? In this case, MongoDb is excellent and provides
aggregate pipeline functionality to create filtered queries. In addition, having a good working knowledge of how the different components of the Model-View-Controller functionality.

We used DASH with Python for the view, we used Python with Pymongo for the controller, and we used Mongodb for the model database. In each case I had to read up on docs and examples to get all the components working together.

What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?
By creating a fullstack application for the company, while also taking into account security, optimization and query speed, size of the database, we can create the fastest possible queries that meet the company's needs.
From the database, to the browser we can provide the company with way to aggregate massive Big Databases which can help achieve business goals.

