# Deskpass
Removing quotes JavaScript

#Store quote in string
myString = '“One only understands the things that one tames,“ said the fox.'

#Remove single, double, or curly quotation marks from string
console.log(myString.replace(/['‘’"“”]/g, ''));


