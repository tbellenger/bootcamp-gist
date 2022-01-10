# Regex Tutorial on Hex code

This tutorial breaks down a regex expression that matches a hex code. It shows the different individual parts of the expression, what they do and how, when combined they are able to match a hex code. 

## Summary

In this gist I will be looking at a hex code regex and how it works. The regex expression to match a hex code  is `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors are used to match positions before, after or between characters. In the above example of a regex expression to match a hex code anchors are used at the start of the expression `^` to match the start of the string and `$` at the end of the expression which matches to the end of the string.

### Quantifiers
Quantifiers specify how many matches are required in the regular expression. In the above exmaple of a regex expression to matcha a hex code, quantifiers are used to limit the hex code to either 6 or 3 characters using `{6}` following the first character group and `{3}` following the second character group.

### OR Operator
OR Operator specifies a choice between different options in the regular expression. In the above example of a regex express to match a hex code, OR operator is used between the character groups and their quantifiers. The `|` that separates the character groups and quantifiers `[a-f0-9]{6}|[a-f0-9]{3}` means that either of these character group and quantifiers may be matched. 

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Tom Bellenger is a Berkely Coding Bootcamp student. His Github can be found at https://github.com/tbellenger.
