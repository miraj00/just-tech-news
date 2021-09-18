# just-tech-news

## Description :
```
just-tech-news is session based site. It offers techs to read others post, add post, add,edit or delete comment and upvote. 
```

* The requirement to create just-tech-news is as below :
```
- User should be allowed to create, read, update and delete a profile in the database
- Add security and authentication
- Create and manipulate posts
- Enable users to vote on posts
```
* The Client required to create front-end that fullfill following :
```
- Create and manipulate comments on post data
- Create a homepage
- Create a login and signup page
- Create a single post page
- Create a dashboard for logged-in users
```

## Languages and other components used : 
```
   * Node.js 
   * npm (node package manager) 
   * Expess.js server ( Node based web server ) 
   * MySQL (Structured Query Language) database
   * express-session, connect-seession-sequelize
   * dotenv, bcrypt 
```

## How to install : 
 ```
 To install the application in your computer follow the steps below: 

 1. Clone the repository in your computer :
    - open the command line and go to the directory where you want to clone the repository.
    - then clone the repo by typing : " git clone git@github.com:miraj00/just-tech-news.git "

 2. Install MySQL in your computer. 

 3. Install node.js on your computer by going to https://nodejs.org/en/  
  
 4. Then install below packages by typing in command line :

    - npm init -y
    - npm install express sequelize mysql2
    - npm install dotenv  
    - npm install bcrypt
    - npm i express-session connect-session-sequelize
    - npm install express-handlebars
    
5. Create files / folders such as : 
    - Create Server.js 
    - Setup .env file with database ID and Password
    - Create folders : config, db, public, utils, models, views, controllers
 
 
 7. Use " mysql -u root -p " to start MySQL Server, then enter password upon prompt 

 8. Once SQL is on, type : " source db/schema.sql; " to create database 

 9. Then You can use " exit " or " Quit " to stop the server.

 10. In command line type : " npm run seed " to seed the database if any 

 11. Then type : ' node server ' to invoke the application.

 You can go to  http://localhost:3001/  in browser and test the APP for all functions
```


## Below is the screenshot and Deployed application of the Project as per client request ## 

![Screenshot of web page](./public/assets/images/just-tech-news.JPG)


## Deployed Sites ##

[Please click here to see deployed application on Github](https://github.com/miraj00/just-tech-news)

[Please click here to see deployed application on heroku](https://whispering-caverns-29361.herokuapp.com/)

















