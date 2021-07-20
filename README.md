# E-Commerce-Back-End

## Description
The **E-Commerce-Back-End** is a project from the March-August 2021 cohort from University of New Hampshire's full-stack web development course. 

Our task is to build the back end for an e-commerce site by modifying starter code. I configured a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application is not deployed, I provided walkthrough videos below that demonstrate its functionality and all of the acceptance criteria being met. 

Technologies are listed below.  

## User Story
 - AS A manager at an internet retail company
 - I WANT a back end for my e-commerce website that uses the latest technologies
 - SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
![E-Commerce-Back-End](./assets/Good-README-Generator-Walkthrough.gif)

## Technologies
 - JavaScript
 - Node.js
 - Express.js API
 - MySQL2 package
 - Sequelize package
 - dotenv package
 - Insomnia Core

## Credits 
The web development bootcamp program is offered through the University of New Hampshire Professional Development & Training and Trilogy Education Services.

March 2021 cohort instructors:
- Instructor - Benjamin Hutchins [GitHub](https://github.com/benhutchins)
- TA - Andrew Hatfield [GitHub](https://github.com/ALHatfield)

## Usage
* [GitHub Repository](https://github.com/Laura-Bullek/E-Commerce-Back-End)

## Licensing
MIT License

Copyright (c) 2021 Laura Bullek

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.