# Regular expression Tutorial

## Description

A regular expression in short known as regex, is a sequence of characters that defines a specific search pattern.
A pattern consists of one or more character literals, operators, or constructs. Regular expressions is used to find
patterns of characters within a string, find and replace a character or sequence of characters within a string and validation of user input.

## Summary

Regular expressions basically allow us to search for specific pattens of text and they can look extremely complicated. You can create a regular expression just for a search pattern within a text or can be used to find usernames, emails, hex values, URLs, or HTML tags.Regex are widely used in all popular languages like, Java, Python, JavaScript, PHP etc. For validating an email address, we can use below expression.

/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

This is a search pattern meant for basic Email validation. It is wrapped in forward slashes (/) at th beginning and end of the expression. Within those forward slashes, you will find the components of a regex: anchors, quantifiers, grouping constructs, bracket expressions, character classes, OR operators, flags, and character escapes.

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

The characters ^ and $ are both considered to be anchors. From the example, after the first forward slash, you will find ^ and $ just before the forward slash at the end of the expression. The ^ anchor signifies a string that begins with the characters that follow it. The $ anchor signifies a string that ends with the characters that precede it. Just as with the ^ character, it can be preceded by an exact string or a range of possible matches.

### Quantifiers

Quantifiers set the limits of the string that your regex matches a range of numbers between two curly bracket {}. From the example, {2,6} states that each section of the string needs to be a minimum length of 2 characters and a maximum length of 6 characters.

### Grouping Constructs

There are multiple parts of a string with different section fulfilling different requirements. We use grouping constructs to break up these sections. Regex are generally broken up into sections using parentheses (). From the example, ([a-z0-9_.-]+),([\da-z.-]+),([a-z.]{2,6}) these are the three separate sections.

### Bracket Expressions

A bracket expression is anything inside a set of sqaure brackets([]), represents a range of characters that we want to match. From the example, [a-z0-9_.-] the string that contains any combination of lowercase letters starting from 'a' to 'z', numbers from 0 to 9, an underscore or hyphen or a period. This pattern doesnot require to meet all of them, it can meet any of them in any order.

### Character Classes

A character class in a regex is a set of characters, that any one of the character can occur in an input string to fullfill a match.The bracket expressions which explained before are considered as character classes.From the email example,

A period(.)—Matches any character except the newline character (\n)
(\d)—Matches any Arabic numeral digit. This class is equivalent to the bracket expression [0-9].

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
