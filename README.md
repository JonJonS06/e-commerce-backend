# E-Commerce Backend

<details>
    <summary><h2>Table of Contents</h2></summary>

- [E-Commerce Backend](#e-commerce-backend)
  - [Description](#description)
  - [License](#license)
  - [Technologies Used](#technologies-used)
  - [Screenshots](#screenshots)
  - [Walkthrough Video](#walkthrough-video)
  - [Installation](#installation)
  - [Acknowledgements](#acknowledgements)
  - [Contributors / Contact Info](#contributors--contact-info)

</details>

## Description

In this application we were tasked to create the back end for an e-commerce site by taking a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## License

[![MIT Licence](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Technologies Used

![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white) ![Sequelize](https://img.shields.io/badge/sequelize-323330?style=for-the-badge&logo=sequelize&logoColor=blue) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)

## Screenshots

Get All Categories Route ![image](Develop/Assets/get-categories-screenshot.png) Get All Products Route![image](Develop/Assets/get-products-screenshot.png) Get All Tags Route ![image](Develop/Assets/get-tags-screenshot.png)

## Walkthrough Video

[Walkthrough Demonstration on YouTube](https://youtu.be/EIAu0jYkzDs)

## Installation

First you will need to verify that you have Node.js and MySQL installed on your machine.

Next you will need to clone the repository using:

```terminal
git clone https://github.com/JonJonS06/e-commerce-backend.git
```

Next you will need to install the dependencies:

```terminal
npm init --y
```

```terminal
npm install express sequelize mysql2
```

Open MySQL shell in the terminal and enter:

```terminal
source db/schema.sql;
```

and

```terminal
use ecommerce_db;
```

Once that is complete you will "quit" to exit out of MySQL.

Now you need to seed your database using the following command:

```terminal
npm run seed
```

To start the server listening:

```terminal
npm start
```

Now you can open Insomnia on your machine and test the routes created.

## Acknowledgements

Thank you as always to our Bootcamp instructor and TA's for the instruction, guidance, and starter code.

## Contributors / Contact Info

Please feel free to contact me with any questions or suggestions at [jonjon1106@gmail.com](mailto:jonjon1106@gmail.com) or you can view my other projects at [Jonathan Strickland](https://github.com/jonjons06)

[🔼 Back to Top](#e-commerce-backend)
