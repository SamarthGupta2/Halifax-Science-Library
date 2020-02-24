# Halifax Science Library - MySQL, MongoDB, PHP Application
Technology Used: MySQL, MongoDB, Python, Bash scripts, PHP, HTML5, CSS3

The project focussed on updating the existing database of Halifax Science Library which had the following immediate plans:
- Sell library items and record information about these sales(transactions)
- Record data about all articles in a magazine
- Record data about monthly expenses

Developed an EER diagram to understand the requirements, entities and the relationships between them. All entities and relationships were normalized to 3NF. 

Imported the existing raw data in JSON format by cleaning and loading into MongoDB using bash scripts and python which was further processed to load data into newly created MySQL tables. 

Developed a PHP web application to allow users access the newly designed database for the library employees to perform various tasks:
- Show tables
- Add new articles
- Add new transactions
- Cancel transactions
