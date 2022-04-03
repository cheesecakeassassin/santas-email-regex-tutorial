# Santa's Email Regex Tutorial

Regex or Regular Expressions can look scary to the untrained eye. I for one always ran away from them until I took a closer look and learned that they weren't all so bad! I'd like to take you step-by-step and show you the way of the regex so you won't be frightened next time you see one. Let's get started!

## Summary

There are so many different uses for regex but for this gist I will focus solely on the regex for matching an email. A regex in short is a string of characters that assist in finding patterns in text. It is essential to programming. Here's an example of the email regex we will be discussing:

```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```
Come along for the ride as we dissect this beast!

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

Anchors are found in the beginning of a regex ```^``` as they are found at the end ```$```. These two symbols do exactly that. The carot marks the beginning and the dollar sign marks the end of the regex as can be seen in the email regex.

### Quantifiers

A quantifier is used at the end of the email regex: ```([a-z\.]{2,6})```. What we are specifically looking at is the ```{2,6}```. What this signifies is that the final part of the email string(after the .) should be 2 to 6 characters that are a-z or contain a period.

### Character Classes



### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

## Author

My name is Sebastian Santa, I am an aspiring future software developer, follow my journey at https://github.com/cheesecakeassassin
