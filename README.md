this project, it's a breakthrough in the flask framework which is micro framework easy and fast , in this project i gained very good knowledge within the basics , first by starting with the key concepts like routing which is the process of mapping the URL with the function we previously implement to help us to make a specific logic for this URL using the decorator app.route() i also notice that we can handle both request using the methods key word inside app.route() to make the function able to handle both post and get request , (get for fetch website ) and post for submit data on the server.

now before continue of explaining what i learnt , i will talk about this project and what it dose , this project it's a simple login sign-up page which allow the user to store and keep his notes and also the ability to delete any one of them , all of this using sqlalchemy.

now I will explain the flow of how i built this project, ( by using a guide from youtube ( Tech With Tim) with video title " Python Website Full Tutorial - Flask, Authentication, Databases & More" with this link "https://www.youtube.com/watch?v=dam0GPOAvVI" ) at first we start with building the structure of website , static for java script and CSS files and templates for dynamic HTML file and finally we created models for specify the database schema for the user information and for his notes, then we make auth.py which have the logic of login and logout and sign_up , we used here some validation logic to ensure that the data is valid and as required , also for toast or notation we used flash function , also we include remember feature not make the user everytime enter his data , and finally in this section we ensure that the database inseration in signup is correct and how intended to be , in views.py we make the home page logic , and inseration and delete note , the delete note we used java script code to ensure to put for each node a unique id to just delete it as required, finally in init.py we create from it the database and two blueprint for views and auth , and we ensure that the session is secure using " app.config['SECRET_KEY'] = 'secret' " now for templeats , i create for HTML files which base home login sign_up , base is a the basic temple which all other HTML will overwrite using jinja blocks and it contains nave bar just shows the content according to the status of the user if he logged in or not , other is standard HTML .


https://github.com/user-attachments/assets/e0ffa751-0b57-41dd-b29d-fb8c46f5722e



![image](https://github.com/user-attachments/assets/e8ec5754-2fe1-4b65-9756-d20584d15d63)
![image](https://github.com/user-attachments/assets/dad40070-197a-4951-b587-bb4badeca7d7)
![image](https://github.com/user-attachments/assets/48f47193-7b8c-47be-a230-bdcc22778172)
