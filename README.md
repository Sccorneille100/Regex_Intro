# Regex_Intro
The goal of this exercice is to dawdle over what a common word is and

## Summary

The following code is a tutorial to know how to utilize and create a regex code. This regex is used to make a combination of word better and also with less code. jsut like this code that would allow emails

Matching Email-
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
regex a a bunch of nonsense that are being put together to create a blueprint taht would allow the user to create a combination of words.
The most common components are anchors, quantifiers, character classes, and alterations.

### Anchors
anchors indicate the position to match a string. Usually it determing the start and the end of a string. 

### Quantifiers
Quantifiers '*' specify how frequently a preceding element in a regex pattern should appear. They have influence over character or group repetition. Using specific symbols allows you to customize search parameters.

### Grouping Constructs
Grouping is denoted by by parentheses, it unifies a pattern or string to be matched in a complete block.

### Bracket Expressions
Bracket expressions are also known as character classes, and they're a fundamental component of regex functions that let you choose a set of characters from which you want to match a single character. They are inclosed in square brackets []. A basic example: [abc]

### Character Classes
Character classes let you determine specific groups of characters you would want to match. They are always closed in square brackets [].

### The OR Operator
The OR operator or | or Pipe is an oparartor that allow multiple constrings into a senstence sometimes we need to verify multiple propreties and it doesn't need to be string but more fluid.

### Flags
Flags are used to modify how a regex pattern is interpreted. For example the 'i' flag means that it is case-insensitive. The 'g' flag means global matching, or finding all occurences.

### Character Escapes
A "\" ('backslah') is a common escape tool in the coding world that allows the next code not to be executed. 
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
In our example: "\." is in several places, using the backsplash denotes that we want to find just the dot.

## Author

Sylvestre Corneille is a student at UC Berkeley extension Coding Bootcamp summer 2023. Locate me on Github:https://github.com/sccorneille100
