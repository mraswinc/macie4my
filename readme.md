# Amazon Macie Custom Identifier for MY!

This is a guide how to create Custom Identifier for Amazon Macie to detect Malaysian IC! 

# Steps for Malaysia IC
## Create Custom Identifier
![Screenshot for Custom Identifier](https://github.com/mraswinc/macie4my/blob/d6f3cca82eb28a1c50daa384c147bad0cddc6b61/MacieCustomMYIC.png)

Regex:
```
((([[1-9]{2})(0[1-9]|1[0-2])(0[1-9]|[12][0-9]|3[01]))-([0-9]{2})-([0-9]{4}))|(([[1-9]{2})(0[1-9]|1[0-2])(0[1-9]|[12][0-9]|3[01]))([0-9]{2})([0-9]{4})
```
**Use your own Regex format if you wanted to test or foolproof it further. This is just a sample

## Test It 
Key in sample IC:
```
911221-10-5050 
911231105050 
570831-18-4050 
790430105899 
```
