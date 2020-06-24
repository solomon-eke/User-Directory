# User Directory

This application is an employee directory created with React and utilizing the Random User Generator API. Tha application's UI is broken up into multiple componenets. Upon page load, a user is presented with a list of 100 "employees". The user can sort the employees by first or last name, and can filter employees by last name. The application is reactive, updating state with every search letter entry, filtering out any employees who's last name does not match the search, and returning employees when search items are deleted.

User Story:

As a user, I want to be able to view my entire employee directory at once so that I have quick access to their information.

## Table of Contents

1. [Technologies](#technologies)
2. [Usage](#usage)
3. [License](#license)

## Technologies

<p id="technologies"></p>

- React
- Random User Generator API
- Bootstrap
- React-moment

## Usage

<p id='usage'></p>

- Navigate to https://solomon-eke.github.io/User-Directory/
- Press the "Last Name" or "First Name" buttons to sort employees in ascending or descending order
- In the search box, enter in any combination of letters to see if any employees' last names match the query.
- For the filtered results, names including the search will are included, e.g. an employee with the last name "Martinez" will reamin in the table if "ine" is searched
- Simply delete a search to retrieve all of the employees again

## License

<p id='license'></p>

<img alt='licenseBadge' src='https://img.shields.io/badge/License-MIT License-BLUE'>
  
- MIT License
