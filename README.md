
In the assignment 1 , I have used C++ to take name a input and returned a random ID , Name and the date and time of Request ![WhatsApp Image 2021-12-08 at 23 05 59 (1)](https://user-images.githubusercontent.com/95737916/145256229-deac0b33-ebd2-4732-97b6-15e6c24a2912.jpeg)



In assignment 2 , I have taken some users and their corrosponding events with Mysql . The .sql and the .docx file contains the queries and the Csv file contains the values on user and events databases.

In assignment 3, I have build a rest api with MySQL database.Run npm install first in this directory the run nodemon. I have used node.js express.js stack to make this rest api.
Adding user to database
![Screenshot from 2022-01-11 22-49-16](https://user-images.githubusercontent.com/95737916/148991433-bb7f8abb-1ae4-4d65-86b0-516fcb52f01d.png)
Adding event to database
![Screenshot from 2022-01-11 22-50-03](https://user-images.githubusercontent.com/95737916/148991465-61f5baea-eaca-4471-822d-694382a4fc99.png)


In assignment 5, I have to add user, items and book items per user so that there is no overlap of booking.I have used the API stack of Node.js , express.js and below are my execution of Rest api.

![Screenshot from 2022-01-12 17-31-18](https://user-images.githubusercontent.com/95737916/149137576-a49d6b08-0676-4ef5-a12d-b5760af6270d.png)

![Screenshot from 2022-01-12 17-31-34](https://user-images.githubusercontent.com/95737916/149137726-656ac68f-c45a-4cca-a092-a8f0b01ac45a.png)

![Screenshot from 2022-01-12 17-32-45](https://user-images.githubusercontent.com/95737916/149137749-da6a5a22-15c7-4e96-b8ca-a4e932cf96b7.png)

![Screenshot from 2022-01-12 17-33-21](https://user-images.githubusercontent.com/95737916/149137768-0779557a-6f20-4bd9-8b2d-f69443ffa343.png)

![Screenshot from 2022-01-12 17-33-29](https://user-images.githubusercontent.com/95737916/149137776-9c27eac1-8c8c-4dfe-89f3-aee133e98ce4.png)



In assignment 7, Some users and items are taken now we have to see a user can book a item following the criteria that a user can book a definite item for once, multiple user can't book the same item for 7 days and a user can book multiple items any time. Now here is the output 

![Output pic](https://user-images.githubusercontent.com/95737916/147390330-86a5d593-0dd5-4792-ad2e-8830222c165b.jpeg)

Capstone project:
Internal Event Management System:

Introduction: In this management system, I have made an event booking calendar system so that each user can book their events for a particular day or a span of days

Prerequisites: To make this system, basic knowledge about programming and data structure in javascript, a basic introduction to react.js for frontend and node.js, and express js for backend is required. As well as knowledge of MySQL for the database management system is needed.

Details:
Database: The database has two tables for user and events.The user table contains columns as userID(uid), email, gender, and password. The events columns contain tables as eventID(id),userID(which is a foreign key from the user table), event name, description about the event, Start Date and End Date. The end date can be left blank while booking event . The program will take the end date as the start date.

Restful API: The stack used for the rest API is Node.js and Express.JS with MySQL database. Now a user can’t sign up with the same email address and can only see his own events after he/she logs in. This is done to protect the privacy of the user. Only the host can see all the users and their event details but not the password.

Frontend: The frontend contains two pages. Registration or Login page and event booking page. The frontend is created using react.js. Below we can see the two pages


![Screenshot from 2022-01-11 19-35-44](https://user-images.githubusercontent.com/95737916/148964263-40380b72-0f23-4944-ac8e-363e31f07b49.png)


![Screenshot from 2022-01-11 19-38-04](https://user-images.githubusercontent.com/95737916/148964272-7982d875-47b4-4a83-ae52-e4f5aec7d8f6.png)






Setup: Now let’s come to set up. 


Disable your google chrome web security or you can’t run both files in your own computer.
Run : google-chrome --disable-web-security --user-data-dir="dir of your google chrome app" run in terminal

![Screenshot from 2022-01-11 19-46-57](https://user-images.githubusercontent.com/95737916/148964079-9ca743b7-24d2-4cdc-ba0a-bca6dc0a1bb1.png)


In for rest api(can find in folder rest api), in file new.js change the details about your database.
You can see the function await connection, change the password (normally it is null or ‘’ but if you have a password for your MySQL) and the database name(if you want a different database).
![Screenshot from 2022-01-11 19-43-08](https://user-images.githubusercontent.com/95737916/148964243-1d25c6eb-0037-467a-958e-f763d7137bad.png)


Finally,first, run npm install in both folders as due to cloning node modules may not be loaded then run npm start in saikat1 folder and nodemon new.js in rest api folder. When the web opens go to localhost: PORT/auth.
					Enjoy!!
