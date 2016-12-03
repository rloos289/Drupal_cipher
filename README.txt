# Cipher

#### _allows to encrypt messages, 12/2/16_

#### By _**Ryan Loos**_

## Setup/Installation Requirements

* _Clone this repository to your desktop_
* _import the database located in cipher/sites/db-backup into mySQL_
* _create an account in phpMyAdmin with the username: cipher and password: cipher, and give it full access to the database_
* _Open MAMP and under preferences > Web server direct the document root to the cipher folder_
* _On your browser, go to localhost:8888_
* _log in with username: cipher and password: cipher_

## Behavior Driven Development

|Behavior|Input|Output|
|--------|:---:|-----:|
|users can input a phrase, direction, and offset number that will produce the corresponding phrase|"hi", right, 2 |"jk"|
|users can choose any number and cipher will cycle through the alphabet the correct number of times to get the correct letter  |"hi", right, 47 |"cd"|
|users can go to the left instead of the right |"hi", left, 2 |"fg"|

## Support and contact details

* _Ryan Loos @ rloos289@gmail.com_

## Technologies Used

* PHP
* Drupal 7.5.2

### License

*This webpage is licensed under the GPL license.*

Copyright (c) 2016 **Ryan Loos**
