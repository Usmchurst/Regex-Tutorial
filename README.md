# Regex-Tutorial
Regex is what's called a regular expression. A regular expression is a group or sequence of charachters that is used in programming to define a research pattern of look for anything in coding from phone numbers to text. It comes from the mathmatical concept of regular sets. Its often used to define a search pattern in a body of text. This tutorial is to describe what the regular expressions are in addition to what they are used for, why they are used, their components, and what it does when being used.

# Summary

Here is a Sample of a Regex that would be vary hard to comprehend, however this is what an expression looks like that can be used to verify that a user input is a valid email address:
`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

You are probably looking like "that the bleep is this" im sure you do as when I first looked at this i thought the same thing howevet when I get dont with this tutorial you will be looking at saying to yourself oh yeah I got this. 

# Table of Contents

Anchors
Bracket Expressions
Quantifiers
Grouping constructs
The OR Operator
Characher Escapes 
Charachter classes
FlagsAdvanced Regex Categories
Resources

# Regex Components

in a regex its considered a litteral so the patterns must always be wrapped in slash charachters (/). looking at the following Regex you can observe this pattern.
/^[a-z0-9_-]{3,16}$/
In Javascript there are tow different ways that you could write create a regex object. First there is the example above and the second is the constuctor function that uses quotaion marks.

Anchors

The ^ and the $ charachters are both whats known as anchors.

