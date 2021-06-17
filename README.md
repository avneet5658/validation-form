# Make form validation easier and simpler

Get perfect validation of mostly used form-fields in this package.

# Installation

`npm i validation-form`

# Usage

## ES6
```
import * as validate from "validation";

validate.name("Fam@#");//returns "Name must contain only alphabets"

```
You can also import a subset of library
```
import contact from "validation";

name("Fam");//true

```
| Validation field        | Description    |
| ------------- |:-------------:|
| name(str)| Check if given string is a valid name.Must contain only alphabets |
| contact(str) | Check if given contact number is valid or not(as per India)  |
| email(str) | Valid Email or not      |
| username(str) | Valid Username or not. Must be alphanumeric     |
| password(str) | Password validation.5 required condition     |
| isImage(img.name) | Check if the file selected is image or not   |
| verifyAllfields(formObj) |   Double Check your validation at the time of submitting  |


