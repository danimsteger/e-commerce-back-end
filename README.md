# E-Commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This project involved modifying starter code to create an Express.js API using Sequelize to interact with a PostgeSQL database.

This application was not deployed but a walkthrough video showing the functionality of the program can be viewed [here](https://drive.google.com/file/d/1QYB8rhpfRBxiVctOG59BfuMOoaSxOnoK/view).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

### Clone this repository

```
git clone git@github.com:danimsteger/e-commerce-back-end.git
```

### Go into this repository

```
cd e-commerce-back-end
```

### Access code of the repository

```
code .
```

### Install Necessary Dependencies on local device

```
npm install
```

## Usage

To view a video walkthrough of this application, click [here](https://drive.google.com/file/d/1QYB8rhpfRBxiVctOG59BfuMOoaSxOnoK/view?usp=sharing).

To view the program, navigate to the cloned repository. To setup the database, run the following commands:

### Navigate to PostgreSQL as user 'postgres':

Input your password for postgres if necessary.

```
psql -U postgres
```

### Setup Database and Tables:

```
\i db/schema.sql
```

### Seed Database with Data:

```
\i db/seeds.sql
```

Once the database has been created and seeded, users can run the application. Enter the following command in your terminal to invoke begin listening:

### Start Application:

```
npm start
```

From there, you can visit the local host link: [http://localhost:3001](http://localhost:3001)

You can test a variety of GET, POST, PUT, & DELETE routes for Categories, Products and Tags. All available options are shown here:

![Options of CRUD Operations you can perform with this application](/Develop/images/options.png)

A sample of what a GET request for all categories looks like is shown here:
![Sample of GET Categories](/Develop/images/categories.png)

## Credits

This project was created by Danielle Steger. To complete this project, several resources were referenced, adopted, and modified. Specifically, materials provided in Module 13 of edX Boot Camps LLC were referenced and modified. Additionally, several articles on "MDN Web Docs" and "W3Schools" were referenced. Specific articles are listed below. This project was completed with the use of Sequelize and its corresponding documentation was referenced as well.

- To validate if items in a table are integers, decimals, etc., this [article](https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/) was referenced.

- To create a default value, this [article](https://sequelize.org/docs/v6/core-concepts/model-basics/) was referenced.

## License

Distributed under the MIT License. See [LICENSE](LICENSE).
