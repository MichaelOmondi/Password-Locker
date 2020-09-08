## Password-Locker

This project was generated by Michael Omondi in Moringa school in the year 2020

# Author 

Michael Omondi

# Description

This is a an application which helps one to generate passwords and even manage user's password.

## Behaviour Driven Development
*Run the command run.py
| Given | When | Then |
| :---------------- | :---------------: | ------------------: |
| User Opens the application on the terminal | User runs the command ```$ run.py```| Welcome to Password Locker Application... <br>* CN ---  Create New Account * HA ---  Have An Account |
|User Selects  CN| User inputs username and password| Hello ```username```, Your have succesfully created your username! Your password is: ```password```|
|User Selects HA  | User Enters password and username he signed up with| Abbreviations menu to help you navigate through the application|
| User wants to Store new credentials in the application| User Enters ```CC```|Enter Account, username, password<br>choose ```tp``` to enter your password or ```gp``` for the application to generate a password for you |
|User wants to Display all stored credentials |User Enters ```DC```|A list of all credentials that has been stored or ``` Oooooops!! You don't have any credentials saved yet``` |
|User wants to Find a stored credential based on account name|User Enters ```FC```| Enter the Account Name you want to search for and returns the account details|
|User wants to Delete an existing credential that he doesn't want anymore|User Enters ```D```|Enter the account name of the Credentials you want to delete and returns true if the account has been deleted and false if the account doesn't exixt|
|User wants to Exit the application|User Enters ```EXT```| The application exits|


# Known bugs

There are no known bugs in this project 

# Technolgy used

Python.

# Support and contact details

In case of any query, you can reach me via e-mil at:

omondimike11@gmail.com

# License

MIT copyright license Copyright (c) 2020 Michael Omondi

