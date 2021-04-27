# Employee Directory

[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

## Table of Contents

* [Installation](#Installation)
* [Usage](#Usage)
* [License](#License)
* [Testing](#Test)

## Description

This application allows the user to view, search and sort employee information in a table format. The application uses React components to render the html and it makes an AJAX call to the [Random Person API](https://randomuser.me/) to get the random employee data.

## Installation
There are many packages to install which can be viewed in the package.json. Please view it and remove any you do not need, then run the following command in your terminal.

```bash
npm i
``` 

## License

This project's code is allowed to be "set free" using [The Unlicense](https://unlicense.org/).  This link provides all the details for the license.

## Test
Upon loading the application, you will see a generated list of random employees. Simply scroll and view the rendered employees, or narrow down your search by entering a search query in the "Search" bar in the top right corner. The results returned by the search are only relevant to the first name of the employee. As you type, the list will narrow down. If you wish to sort the employees, simply click the "Sort" button next to the first name table field, and it will sort the employees by first name alphabetically. To re-render the entire employee table, you may either delete the search query in the search bar or click the title of the page to refresh.

## Link to Deployed Application
https://gavin56.github.io/employee-directory/

## Images
<img src="https://github.com/Gavin56/images/blob/main/employee-directory-main.png?raw=true" width=600px>
<img src="https://github.com/Gavin56/images/blob/main/employee-directory-sorted.png?raw=true" width=600px>
<img src="https://github.com/Gavin56/images/blob/main/employee-directory-searched.png?raw=true" width=600px>
