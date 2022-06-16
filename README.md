# PHP-Laravel-App-2021
This was a collaborative project that allows users to create their own accounts to register for jobs. This was inspired by websites such as LinkedIn.

![image](https://user-images.githubusercontent.com/62003762/173732010-346ad1fa-47ec-4e8f-9328-0245dd51114b.png)

# Login
The website ensures the user is logged into an existing account in the databae.
![image](https://user-images.githubusercontent.com/62003762/174056125-5c379fa4-740a-4619-81ff-fa7397bbdc6b.png)

# Home Page
Here, the user is logged in as an administrator. They are able to access of number of different pages on the site including exculsive pages for administrators.
![image](https://user-images.githubusercontent.com/62003762/174056542-4d71d6dc-3453-43a7-950f-a92622e225d1.png)

# Manage Job Posts
Administrators can create, update, and delete job posts for all users to view. For regular users, they would see an 'Apply' button next to each job post.
![image](https://user-images.githubusercontent.com/62003762/174057207-6f11ba5c-8c4e-4632-a3c3-27dca2ebf030.png)

# E-Portfolio
Users are able to edit their E-Portfolio so other users, such as employers, can view their information. Here is an example.
![image](https://user-images.githubusercontent.com/62003762/174057808-bbf5605e-9b13-4b03-abf0-a3bd263b6d45.png)

# Group Message Forums
Users can join group forums to collaborate in different subjects. Here, AlexCarrillo, a user, created 5 different forums that can be accessed by clicking on their corresponding 'View' button.
![image](https://user-images.githubusercontent.com/62003762/174058239-66a80c73-b43b-48f2-be0e-775bf94f9b98.png)

In a group forum, users can view messages sent by other user. At the bottom of the page, the user is able to input text and click the 'Add Reply' button to send a message in the group forum.
![image](https://user-images.githubusercontent.com/62003762/174058649-dd55fb0c-f755-4886-bb48-4b826663b98d.png)

# Data Access Object
A Rest controller was implemented which contained multiple methods that called upon a Security Service class. In this method, if there are jobs in the database, then a success message will be sent in JSON format.
![image](https://user-images.githubusercontent.com/62003762/174059492-756f9202-0522-43d8-8b17-72adbfa3944d.png)

The Security Service class methods create an instance of the SecuirtyDAO class, which contains methods needed to perform various requests with SQL statements. Here is an example of a method in the DAO class used to find all the jobs in the database.
![image](https://user-images.githubusercontent.com/62003762/174060994-0553fcac-53fb-42b0-a221-9d4b2cd918ca.png)

