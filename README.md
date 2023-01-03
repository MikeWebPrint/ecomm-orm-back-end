# E-commerce Back End

  ![https://img.shields.io/badge/License-MIT-blue](https://img.shields.io/badge/License-MIT-blue)

  ## Description
  
  This project is a simple e-commerce back end.  It takes a working Express.js API and configures it to use Sequelize to interact with a MySQL database.
  
  ## Author
  
  The author for this project is [Mike Johnson](https://github.com/mikewebprint)
  
  ## Table of Contents
  
  - [Installation](#installation)
  - [Usage](#usage)
  - [Credits](#credits)
  - [License](#license)
  - [How to Contribute](#contributions)
  - [Tests](#tests)
  
  ## Installation
  
  This project requires first initializing a MYSQL database through the db/schema.sql. After performing an npm install of the project dependencies,  enter npm run seed to seed the provided data, tnen npm run watch (nodemon globally installed, you may need to install that separately). This starts the localhost server. The api endpoints can then be tested through Insomnia or a similar program.
  
  ## Usage
  
  Other developers may use this as an example of an existing simple ecommerce site's api. Video of the project being used can be viewed here: [https://drive.google.com/file/d/1b03xwSDpKkg5mn7zILn-A05BXo3MhWcs/view](https://drive.google.com/file/d/1b03xwSDpKkg5mn7zILn-A05BXo3MhWcs/view).
  
  ## Credits
  
  Much of the code in this project was starter code.  While I applied the rest of the code in this repo, much is adapted from other class project code, modified to fit the data models.  Credit does go to my tutor Trinh Nguyen for feedback to help me over some roadblocks and classmate Lynn Sadler for helping me find a breaking error.
  
  ## License
  
  MIT
  
  ## Features
  
  This project has api routes for products, categories, and tags. Categories have a one-to-many relationship to products. Products and tags have many-to-many relationships. Each route handles the four CRUD functions through their respective HTTP methods.
  
  ## Contributions
  
  Contributions and/or review of the project can be offered at the repository here: [https://github.com/mikewebprint/ecomm-orm-back-end](https://github.com/mikewebprint/ecomm-orm-back-end)
  
  ## Tests
  
  Testing for this project would be appropriate to ensure that the CRUD operations are working properly for products, categories, and tags, and that tags and categories are properly applied to products, and vice versa.

