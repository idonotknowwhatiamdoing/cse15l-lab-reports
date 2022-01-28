# Week 4 Lab Report

## Code Change 1:

![1-1](codechange1-1.png)

### Link to file: 
[test-issue-1.md](https://github.com/idonotknowwhatiamdoing/markdown-parse/blob/bfe7abee1421bcb19304fc2b560400433a221c66/test-issue-1.md)
```
(link.com)
```

### Symptom: 
```
-1
[link.com]
```

### Summary:
Instead of a properly formatted link with square brackets and parentheses, the failure-inducing input only had a set of parentheses. Because the index for the square bracket ```[``` could not be found, the index returned ```-1```. The output should be nothing because the formatting was incorrect. By checking for the existence of square brackets in the added ```if``` statement, we can fix this issue. 

## Code Change 2: 

## Code Change 3: 

![3-1](codechange3-1.png)

### Link to file: 
[test-issue-3.md](https://github.com/idonotknowwhatiamdoing/markdown-parse/blob/bfe7abee1421bcb19304fc2b560400433a221c66/test-issue-3.md)
```
[Here is a link] and some text (url.com)
```
### Symptom: 
```
[and some text (url.com]
```
### Summary:
In our original code, we assumed that the formatting would always be correct and that the opening parenthesis ```(``` would always come after the closing bracket ```]```. When this is not true, the link is formatted incorrectly. In our solution, we check to see if the ```char``` directly after ```]``` is ```(```, and if not, we then ```break```.