# regexExplination 

Regex or regular expression is a set of characters that can define specific search patterns in text. It is mostly used as a way to pattern match in programing. 

## Summary

I will be explaining how to match an email using a regular expression with this code below.

^([a-zA-Z0-9._%-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,6})*$

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

## Regex Components

### Anchors

The ^ and $ will match any string that starts with ^ and ends eith $

### Quantifiers

* specifies how many instances of a group, character, or character class must be present in the input for a match to be found.

### OR Operator

you can use | to match characters or expression of either the left or right of the | operator. As well as using [] but without capturing the characters inside the brackets. 

### Character Classes

A set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string. \d matches with a single digit. \w matches a word character. \s matches a whitespace character. And . matches any character.

### Flags

An optional parameter to a regex that modifies its behavior of searching. Different types of flags would be the gobal flag g and the multiline flag m. 

### Grouping and Capturing

Capturing groups are a way to treat multiple characters as a single unit. They are created by placing the characters to be grouped inside a set of ()

### Bracket Expressions

a matching list expression or a non-matching list expression. It consists of one or more expressions: ordinary characters, collating elements, collating symbols, equivalence classes, character classes, or range expressions.
For example [abc] or [a-c] 

### Greedy and Lazy Match

'Greedy' means match longest possible string. 'Lazy' means match shortest possible string. 
* matches any character and ? matches to the shortest possible string. 

### Boundaries

In regular expressions, \b anchors the regex at a word boundary or the position between a word and a non-word character, or vice versa. 

### Back-references

back-references are regular expression commands which refer to a previous part of the matched regular expression. Back-references are specified with backslash and a single digit for example: \1

## Author

This was created by Jared Pennington and my github profile is below.
(https://github.com/jaredpennington)