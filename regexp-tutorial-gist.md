# REGEXP TUTORIAL

> <img src="https://img.shields.io/badge/license-MIT-orange.svg">

>  
# License 
    
> This project is licensed under MIT
    
# Description

> Regular expressions, or "regexps" for short, are a powerful tool for searching and manipulating text. They allow you to describe patterns in text and find matches based on those patterns. Regexps are used in a wide range of applications, from text editors and command-line tools to programming languages and web applications.
    
# Table of Contents


*[Anchors](#anchors)
*[Quantifiers](#quantifiers)
*[Grouping Constructs](#groupingConstructs)
*[Bracket Expressions](#bracketExpressions)
*[Character Classes](#characterClasses)
*[The OR Operator](#theOrOperator)
*[Flags](#flags)
*[Character Escapes](#characterEscapes)

* [License](#license)

# Anchors
> Anchors are used to specify where in the text a match should occur. The two most common anchors are "^" and "$". The "^" anchor matches the start of the string, while the "$" anchor matches the end of the string. For example, the regexp "^hello" would match any string that starts with "hello", while the regexp "world$" would match any string that ends with "world".
# Quantifiers
> Quantifiers are used to specify how many times a pattern should match. The most common quantifiers are "", "+", and "?". The "" quantifier matches zero or more occurrences of the preceding pattern, the "+" quantifier matches one or more occurrences of the preceding pattern, and the "?" quantifier matches zero or one occurrences of the preceding pattern. For example, the regexp "a*" would match any string that contains zero or more "a" characters, while the regexp "a+" would match any string that contains one or more "a" characters.
# Grouping Constructs
> Grouping constructs are used to group parts of a regexp together so that they can be treated as a single unit. The most common grouping construct is the parentheses "()". For example, the regexp "(ab)+" would match any string that contains one or more occurrences of the pattern "ab".
# Bracket Expressions
> Bracket expressions are used to match a single character from a set of characters. The most common bracket expression is the square brackets "[]". For example, the regexp "[abc]" would match any string that contains either an "a", a "b", or a "c" character.
# Character Classes
> Character classes are used to match a single character from a predefined set of characters. Some common character classes include "\d" (matches any digit), "\w" (matches any word character), and "\s" (matches any whitespace character). For example, the regexp "\d+" would match any string that contains one or more digits.
# The OR Operator
> The OR operator, represented by the "|" symbol, is used to match either one pattern or another. For example, the regexp "hello|world" would match any string that contains either the pattern "hello" or the pattern "world".
# Flags
> Flags are used to modify how a regexp is matched. Some common flags include "i" (case-insensitive matching), "g" (global matching), and "m" (multiline matching). For example, the regexp "/hello/i" would match any string that contains the pattern "hello", regardless of whether it's capitalized or not.
# Character Escapes
> Character escapes are used to match special characters that would otherwise be interpreted as part of the regexp syntax. The most common escape character is the backslash "". For example, the regexp "+" would match any string that contains a "+" character, while the regexp "$" would match any string that contains a "$" character.
# Questions
## If you have questions, then please email me at Christophergdale@gmail.com