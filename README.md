
# RegexRead

# Regex Matching an Email

A regular expression shows a sequence of characters for the search pattern. Regex is used to validate passwords, url and html tags and emails.

Here is an example of a Regex

```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/.
```

The essential ingredients of a Regex are as follows:

## ([a-z0-9_\.-]+)

This upholds the username part of the email address. Starting off the code saying the username can contain a-z, numbers 0-9, characters "_\.-+ and 

The "+" symbol makes a previous character be within the username

## @([\da-z\.-]+)

Domain component of the email.  These days examples are either @gmail, or @yahoo.com

When users @ symbol glues the username with domain section. "\d" is for digits, a-z for letters and \.- for the special characters listed

+ symbol needs the previous connection to operate


## .([a-z\.]{2,6})

This domain component element finishes the email address normally seen as a ".com"

The . glues the domain from the finish, the a-z creates a space for letters, the \. gives special characters a place, and the {2,6} makes 2 characters minimum 6 maximum for the component.

Regex must contain ^ to begin, which shows the expression has began. Than to finish the expressoin add a $ to end.


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

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Donovan Fletcher link
 
 https://github.com/FletcherFitness22/RegexRead
