Artifact Overview
The artifact I selected for the databases category is the Salvare Search for Rescue Web App. I created this project during the CS340 Client/Server Development course. It is a web application built in Python using the Dash framework and the MongoDB database. The app helps animal shelters organize and search through their dog records to identify good candidates for rescue training. The database uses a CSV file of shelter dogs that gets imported into MongoDB. The application can be run in Jupyter Notebook or the computer terminal using a browser.

Why This Artifact Was Chosen
I chose this artifact for my ePortfolio because it shows strong database and web development skills. It uses a real-world data structure, connects to a non-relational database, and follows the Model View Controller (MVC) design pattern. The MVC pattern helps separate the different parts of the app. The model handles the data using MongoDB and Python. The view uses Dash to show the user what they see on the screen. The controller uses PyMongo to update and pull data from the database.
This artifact also includes RESTful API practices, which are very common in professional software development. I improved the code by recreating the project in a Windows environment. Originally, it was built using Apporto, which is a Linux platform. I followed the original documentation to rebuild the project and updated it with new steps for using Windows. I also had to update parts of the code to work with newer versions of PyMongo and MongoDB.

Meeting Course Outcomes
Yes, I met the course outcomes I planned for this enhancement. My goal was to improve my skills in using databases, following secure coding practices, and documenting my work clearly. I now better understand how to set up a database connection, validate user input, and use version changes in database tools. I also learned to organize and format my code to make it easier to read and maintain. I do not have any changes to my outcome plans right now.



Reflection on Enhancing the Artifact
Improving this project taught me a lot about working in different operating systems. Since the original app was built in a remote Linux lab, I had to set up Python, Dash, and MongoDB from scratch on my personal Windows machine. It was hard to match everything exactly, especially since newer software versions required changes to the original code. I had to modify the Create method in the CRUD module to match PyMongo version 4.0.
This process improved my ability to solve technical problems on my own. I also learned how to write clear instructions and update project documentation so others can follow it. I used Python best practices, like in-line comments, clean formatting, and proper naming for functions and variables. I also worked hard to make sure every part of the app followed security-minded programming, like checking inputs and controlling access to the database.
Overall, this project shows how I can build a working database application, improve it to work in new environments, and document everything clearly for future use. It fits well in my ePortfolio and proves my growth in using databases in real-world applications.
Below is a screenshot of the controller logic for dropdown filters and database interaction.
 


This screenshot compares the original and enhanced versions of the 'Create' method using PyMongo v3 and v4.
 

Here is a view of the live dashboard created for the Salvare Search for Rescue Web App.
 
<img width="468" height="637" alt="image" src="https://github.com/user-attachments/assets/40f3b6fd-1a4d-4ba0-bb91-67e12e0925e9" />
