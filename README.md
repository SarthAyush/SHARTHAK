
************************** Features *********************************
->The system consists of two types of users: admins and students.
-> Each user should have an account.
-> The application provides signup, login and logout functionalities.
-> A book can have multiple copies so that copies of same book can be issued to multiple students.

**************************Admin Features***************************
-> Admins can view, add, update or delete the books.
-> Admins can view all the students who have an account in the system.
-> Admins can keep track of all the activities of library.
-> Admins can issue book to a student.
-> Admins can collect book from a student.
-> Admins can view all the current loans.
-> Admins can also view the past loans against which the books have been returned.
-> Admins can send the email as reminders to the students.
-> Admins can update their profile.

*****************************Student Features****************************
-> Students can view all the books in the library.
-> students can keep track of all their activities.
-> Students can view all the books which they currently possess along with status (overdue or not).
-> Students can also view the books which they have already returned.
-> Students can update their profile.


*********************Technologies used*****************************
-> Node.js
-> Express.js
-> Mongodb
-> ejs
-> Bootstrap


*************************NOTE**************************
 Admin signup page can be accessed from : `/auth/admin-signup`


in case .env file is not there then u have to add a file as ".env" in main folder and add your mongoDb databse connection sting in this variable "MONGO_URI"










