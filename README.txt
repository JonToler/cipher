cipher: A drupal project

CONTENTS OF THIS FILE
---------------------

 * About cipher
 * Installation profiles
 * Specs
 * Developing for Drupal
 * Known Bugs
 * Support and Contact details
 * Technologies Used
 * Licensing

 ABOUT BOOKSTORE
---------------

The Cipher is a design concept project for week 2 at epicodus.
Its is a practice in using custom DRUPAL 7 modules, php, REGEX, and modulus expressions. The cipher is a modified caesarean cipher, which takes in the users inputted phrase and returns it encrypted.

INSTALLATION
-------------
1. Go to http://localhost:8888/MAMP/ and under the "Tools" menu, select "phpMyAdmin"

2. Please select the from here if the DataBase for 'cipher' is not present then please import the database.
  Importing the database: the database can be found under bookstore/sites/db-backup/cipher.sql.zip

3. from http://localhost:8888/MAMP/?language=English select 'my website' from the menu bar, which will navigate you to the cipher.

SPECS
-----

Using the cipher module the user is prompted to enter in infomation into three fields.
User: Enters a shift value of 42 into the text box, types in the direction 'right', and the phrase 'The answer is 42!'

Output: will shift all the alpha characters 42 spaces to the right, which will give the output encoded phrase: "jxu qdimuh yi 42!" because this cipher only encrypts alpha characters. 


Known Bugs
----------
NA

Support and Contact details
---------------------------

Jon Toler: tolerjonathan@gmail.com.

Technologies Used
-----------------

Drupal 7, Atom, MYSQL

License

This webpage is licensed under the GPL license.

Copyright (c) 2016 Jon Toler
