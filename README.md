# Description
verify-regix is module who use to verify specific condition in string

# Usage 
* npm i verify-regex
* import  * as verifyRegex from 'verify-regex';
* verifyRegex.isValidEmail('johndoe@gmail'); return false

# Exemples
* verifyRegex.isValidEmail('johndoe@gmail.com'); return true
* verifyRegex.isValidEmail('johndoe@gmail.com'); return true
* verifyRegex.isBetween(5, 4, 8); return true
* verifyRegex.isBetween(7, 4, 5); return false
* verifyRegex.isInteger('55'); return true
* verifyRegex.isInteger(55); return true
* verifyRegex.isInteger('fm55'); return false


# functions

    1. isValidEmail : Check if the email is compliant and returns a boolean
    2. isBetween : Check if a word is within a range and returns a boolean
    3. isSolidPassword : Check if a password is solid and returns a boolean. Minimum eight characters, at least one uppercase letter, one lowercase letter, one number and one special character.
    4. isInteger : Check if a param is integer and returns a boolean

