# Regex Tutorial

This is going to be a breakdown on regex functions and descibing what it does.
## Summary

The specifics of one particular regex will be covered in this course. [a-z0-9_-] is the regular expression (abbreviated as regex). This expression using brackets will look for anything enclosed by them. We have the characters a-z0-9 -, which we shall explain to you here, inside the brackets. A-Z refers to the entire alphabet from letter A through letter Z since hyphens indicate a range between letters or integers. Take note of the lowercase letters that are used. This indicates that while we are within that range, we will look for lowercase letters. The next regex is 0-9, which refers to all numbers from 0 to 9. Anything containing a lowercase letter or a number from 1 to 9 will match this regex. The hyphen and underscore come last.

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

### Anchors
The symbol ^ is an instance of an anchor. This marks the beginning of a string.
### Quantifiers
Quantifiers specify (or quantify) the minimum number of a character that must be present in a string in order for it to match the regex.
### Grouping Constructs
Using grouping constructs, a regex query can return a number of subsets of data that are related to one another.
### Bracket Expressions
A bracket expression uses regex to simply search everything included in the brackets. Every lowercase letter between a and z for example [a-z0-9] would result in a match, along with any existing numbers.
### Character Classes
To distinguish between several sets of characters, there exist character classes.
### The OR Operator
The | symbol indicates the OR operator, which allows you to regex between already chosen options.
### Flags
Flags are modifiers that allow you to affect the engine which you search with. 
## Author

My name is Ian M and my GitHub is https://github.com/IanMosur06
