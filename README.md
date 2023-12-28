# E-Commerce Back End

  
  ![Badge for GitHub repo top language](https://img.shields.io/github/languages/top/dpprdgls/ORM-E-Commerce-Back-End?style=flat&logo=appveyor) ![Badge for GitHub last commit](https://img.shields.io/github/last-commit/dpprdgls/ORM-E-Commerce-Back-End?style=flat&logo=appveyor)
  

  ## Description

  *The purpose, the motivation, the execution:*

This application was created to allow internet retailers to utilize a MySQL database and keep an up to date record of specific categories, products, and tags that relate to the sale and inventory of their business. This application uses Sequelize to interact with the MySQL database by providing an object-relational-map that sequalize can depend on rather than being limited only to SQL queries. This helps to separate the application code into more managable pieces of code that can be reused and helps to isolate any bugs. 





  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
    
    ## Installation
    
    *Steps required to install project and how to get the development environment running:*
  
    You can clone the repository to you local hard drive. Open the project in VS Code, if you do not have VS code you must install it. Navigate to the project folder within the terminal and run `npm init -y` to initialize your node environment and create a package.json where the project will be stored. Next use the terminal to execute the command `npm i` to install the project dependencies. 
    
    After all dependencies have been installed you will need to create your .env file within the root directory of your repository. This will contain your environmental variables specifying the database name, your MySQL username, and your MySQL password. This will need to be completed before running the application, and will allow the connection.js file to utilize your environmental variables which will keep sensiitive login information safe. 
    
     To create the database for the project you will need to navigate to the project file containing the schema.sql file. Once there you will need to open a MySQL shell and run the command `source schema.sql`. Once the database is created you will need to navigate to the root directory to seed the database with the following command: `npm run seed`. After this command is sucessfully executed you can run the command `npm start` to start the application.  
    
    ## Usage

    ![Usage Gif](/img/usage_1.gif)
    ![Usage Gif](/img/usage_2.gif)
   


    *Instructions and examples for use:*
    
    Once the application is started, the user can utilize an api platform such as Postman or Insomnia to hit the api enpoints and execute the various functions within the aapplication. A demonstration of the applications functionality is shown below.

     [Video Link](https://drive.google.com/file/d/1WqHg_ubBNRyKjvcjGtLcWfZm6CwHN9EU/view)
    
    ## License
    
    This project is covered under the MIT License license.
  ---

  ## Questions? 

  <img src="https://avatars.githubusercontent.com/u/74167696?v=4" alt="dpprdgls" width="40%" />

  For any questions or concerns, feel free to contact me using the information below:
  
  GitHub: [@dpprdgls](https://api.github.com/users/dpprdgls)

  