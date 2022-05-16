# Regex-Tutorial
Regex is what's called a regular expression. A regular expression is a group or sequence of charachters that is used in programming to define a research pattern of look for anything in coding from phone numbers to text. It comes from the mathmatical concept of regular sets. Its often used to define a search pattern in a body of text. This tutorial is to describe what the regular expressions are in addition to what they are used for, why they are used, their components, and what it does when being used.

# Summary

Here is a Sample of a Regex that would be vary hard to comprehend, however this is what an expression looks like that can be used to verify that a user input is a valid email address:
`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

You are probably looking like "that the bleep is this" im sure you do as when I first looked at this i thought the same thing howevet when I get dont with this tutorial you will be looking at saying to yourself oh yeah I got this. 

# Table of Contents

[#Anchors]
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

# Anchors

The ^ and the $ charachters are both whats known as anchors.
The ^ tells the system what its reading is a string and it starts in the beginning of the regex. The last part or the end is the $ and it signifies the end point of said string of charachters. As you see the charachters in the Email Regex above the begining and the end.

Bracket Expressions

The bracket expression is anyting inside of the square brackets [] that you want to match. They are also known as bracket expressions, and positive charachter group because they outline the charachters we want to include. 
For example, [abc] will look for a string that includes a or b or c, regardless of the length of the string. So all of the following examples would match: "aaa", "bin" "court", "abracadabra", and "bca".

Quantifiers

Now we are going to the last requirement for the regex. There is no minimum or maximun number of charachters the regex is lookgin for when it comes to this. Qantifiers match as many particular occurence of patterns as possible. This is why they say that quantifiers greedy. 
These charachters include *, +, ?, {} these charachters matches patterns zero or more times. the character {n} matches the n the exact number of times. {n,} matches the pattern at least n number of times. Lastly {n,x} matches the pattern from a minimum of a number of times to a maximum of x number of times. They can be ,ade lazy by adding a ? symbol after, its meant to match a few occurences as possible. 

# Grouping Constructors

You can group a section of a regex by using parentheses (). Each of these section of expressions within parenthesis is known as a subexpression. Breaking them up is called grouping constructs. the following example is as follows below.  
(abc):(xyz)
The first subexpression is lookign for the part of the string that matches 'abc' exactly. The second part of the expression is lookign for the 'xyz'. in the middle you have the :. With the colon there and no brackets the have a different meaning. But with brackets the subexpressions are told to do otherwise.




