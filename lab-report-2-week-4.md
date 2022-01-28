# Week 4 Lab Report

## Code Change 1:

![1-1](codechange1-1.png)

### Link to file: 
[test-issue-1.md](https://github.com/idonotknowwhatiamdoing/markdown-parse/blob/bfe7abee1421bcb19304fc2b560400433a221c66/test-issue-1.md)
```
(link)
```

### Symptom: 
```
-1
-1
-1
-1
-1
-1
```

### Summary:
Instead of a properly formatted link with square brackets and parentheses, the failure-inducing input only had a set of parentheses. Because the index for the square brackets ```[``` and ```]``` could not be found, the index variable returned ```-1``` in an infinite loop.

## Code Change 2: 

## Code Change 3: 
