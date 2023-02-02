# Lab1_202001216
Find the submission of Lab1 - Date(02/02/2023) in README file.

IT314-Software Engineering Lab-1
Identifying Functional and Non-Functional Requirements


Q.1. Identify FRs and NFRs:

->List of the some basic functionality of the system:
  New user registration/ Sign Up: Any member of the institute if he/she wants to access facilities of the library has to register on LIS. After successful registration   he/she will be provided password and User ID which will be used for any access from LIS.

  User login: Registered members can login into LIS by entering User ID and password which was provided at the time of registration. In case of login failure the user   will be asked  to enter details again with an error message. Also there will be an option to reset password which can be done by password reset link mailed to the     registered email id of that user. If a user is unable to verify him, his/her account will be blocked by LIS. After login the user will land into Homepage where he     can access many features of the system. He needs to contact with the administrator to make it active again.

  Admin Login: There will be an option of admin login who has control of this LIS, and can directly add, delete, update in the database of the system about new books     purchase, take off of some books.

  Search book: Anyone from the institute can search for books/resources in this system to check its availability. Searching can be done based on the category, author     name, publisher, subject etc. 

  Book Issue: Only registered members of LIS can issue books/resources from the library for a finite time if the book is available and not currently issued by any       other. Also registered members can not issue more than a certain number of books at same time. This limit will be different for different type(role) of members.       Staff/faculty can issue a maximum of 12 books and students of the institute can issue a maximum of 5 books.
  When the issuing process of the book is completed, the user account and LIS database will update it and add a record of book issuing.

  Return book: Finite time for book issue can be set by admin staff suppose 15 days as limit. Members who have issued the book have to return it within the time period   of 15 days. After successful return of a book, the user account and database will be updated. If a registered member fails to return the book within the time period   user will be penalized and that also will be reflected in the user account.

  New Arrival: Using this functionality anyone can see the latest books/resources which are coming to the library in the last week.

-> List of the some non functional requirement of the system:
  Performance: LIS can be accessible at any time 24x7. System should be able to manage traffic of at least 100 users at the same time. Searching algo should be           optimal so that delay can be minimized.

  Security: Databases should not store any password in plain text, also personal details of every user should be stored in encrypted form in the database. LIS can’t     run outside the Institute LAN.	

  Maintainability

  Database consistency

  Design Constraints: The system has to be developed as a web application using recent HTML 5, and should be able to run on any browser.


Q.2. Identify scope, features and non-functional aspects of the following problem.

-> Scope: 
This application is for those people who are unabe to hearing.
Since the application involves Artificial Inteligence which regularly learn itself and provide better user expirience and user friendlyness to the uses.
Low latencty application which can works on real time and use of AI provide the application ability to handle large data in a speedy fashion with smooth learning and interface.
User has to carry mobile with him or near to him as there is no point of provide output as sound.
          
-> Features:
Appication can identify different everyday sounds like car sound, babies crying, and other households and give immidiate allert to the user by providing sound above 35dB with visual allert.
Input of this application can be voice or touch, so the application can identify which type of sound is producing in surroundings and using AI. But output should be preferable to visual/vibration allert.
There should be option for emergency contact, so that in any critical situation he can contact to doctor/ any person if the user has not responded to that allert.

-> Non Functional aspects:
Security: Personal data of user must be protected and should have high encryption in database.
Performance: Application has to reflex allert on any sound efffect imidiately with 0 delay. Application should not be crashed in any critic condition.
Portability
Scalibility: Since 5% of the world population (approx 466 milion) people sufferes from this, application must be able to handle all the user without any difficulties and delay.
 
  
