# HTML-Password-Generator
A simple, user-friendly html page for generating and selecting secure passwords.
* Makes use of modern browser crypto functions: window.crypto.getRandomValues
* Clicking on a generated password will select the text and automatically copy to your clipboard
* For compatibility, characters are limited to alphanumeric characters (digits, lowercase and uppercase english letters)
* To enforce password strength, each password shown must contain ALL three character classes
 
Random passwords are created at three predefined lengths: 
* **Short** (12 characters): Strong *typable* passwords
* **Medium** (24 characters): Strong *pastable* passwords
* **Long** (48 characters): Just in case you want more



![Alt text](/screenshot.png?raw=true "Screenshot")
