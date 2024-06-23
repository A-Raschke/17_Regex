# Matching an Email by Regex

This tutorial covers using an email regex and explains each component. 

## Summary

Regex is a tool used to match email addresses. It uses a string as a parameter to check if they contain the desired specifications. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

### Anchors
```
The two anchors are ^ and $
^ is used for the beginning of a string
$ is used at the end of a string
```

### Quantifiers
```
Quantifiers are used to set the minimum and maximum times a character can occur
+ One or more times
{} used to limit the match between a range. For example:
{3-6} Any number within the range 3 and 6
```

### Grouping Constructs
```
[a-z] Capturing any lowercase letter from a-z
[0-9] Capturing any number from 0-9
. Any character besides a new line
```

### Bracket Expressions
```
Using brackets [] to enclose a range of characters we want to match with
[a-z] Capturing any lowercase letter from a-z
[0-9]Capturing any number from 0-9
```

### Character Classes
```
Used to match a character by it's class
\d{4} would indicate a digit four times
```

### The OR Operator
```
The OR operator | is not used in regex
```

### Flags
```
No flags are used
```

### Character Escapes
```
Used to match a specific character
For example \* would represent an asterisk,
```

<script src="https://gist.github.com/A-Raschke/fb1aa0820204c3b2d1a1ec410605eeb9.js"></script>

## Author

This was created by Adam Raschke. 
https://github.com/A-Raschke