# Project Title: E-commerce-Back-End


## Description:
 This is a back end applicatin for an e-commerce site. It uses an Express.js API. It is configured to use Sequelize to interact with a MySQL database.


 ## Installation:
 This application runs through Node.js. It needs MySQL2 and sequelize packages to connect the Express.js API to a MySQL database. These are installed using `npm i mysql2` and `npm i sequelize` commands. The dotenv package is employed to use environment variables and to store sensitive data, scuh as the MySQL username, password, and database name. It is installed using `npm i dotenv` command.

 ## Usage:
   The application can be invoked by following the `mysql -u root -p` command at the project root and entering the password when prompted. On the mysql prompt, a `source schema.sql` command is used to create a database and `quit` command is used to exit the mysql prompt. After creating the models(categories, products and tags) and routes, `npm run seed` is run to seed data to the database. The server is started using either `node server.js` or `npm start` commands. The insomnia core is opened to test API GET, POST, PUT, and DELETE routes, which request to display models' data in JSON format, create, update, and delete data in the database, respectively.

   Follow the walkthrough videos for its potential applications. 
   
   ### Walkthrough video 1: Running the application. 
   

   https://drive.google.com/file/d/1QyChr8I6dub7PJY_IpryvbpyBibVDtNX/view?usp=share_link



   ### Walkthrough Video 2: Routing the categories. 
   
   
   https://drive.google.com/file/d/1Ook9TD-Udmd8tH7fudNl9H7_h5QRr0wF/view?usp=share_link



   ### Walkthrough Video 3: Routing the products and tags. 
   
   
   https://drive.google.com/file/d/18Ec_MBjGhJDUirJmbTEZfHehPt1I0VKJ/view?usp=share_link


## License:

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg) 


Read more about the MIT licence here: https://opensource.org/licenses/MIT.



## Credits:
  Thanks to Xander Rapstine (https://github.com/Xandromus) for providing rescources for this project.


## Questions?
  ### Reach me here: 
   My GitHub profile:   [veerak21](https://github.com/veerak21),

   My E-mail: pv.kallu@gmail.com.

