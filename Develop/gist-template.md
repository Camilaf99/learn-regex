# Learn Fast, Learn Regex

Regular expressions or "Regex" are patterns used to match character combinations in strings. In Javascript, regex are objects. 

## Summary

A Regex pattern is made up of simple characters, for instance [a-z], /abc/, or a sum of simple and special characters, like this code: ^GET /[a-zA-Z0-9\.-_/\+%]* [1-5][0-9]{2,2} this means GET /stylesheets/style.css 200 9.089 ms - 803. 

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

Anchors match a position of the beginning of the string or line or the end of it. For example, if you want to start a new line, you always start with "^" see sample in "Summary".

### Quantifiers

Quantifiers inducate the total number of characters or expressions that you have to match. For example, "x*" means 0,1 or more times you can repeat the character or expressions; "x+" matches one or more times; "x?" matches 0 or 1 time, it can be there or not (example-https? the s can or not be there); and there is much more. ( "x{n}","x{n }","x+?", etc)

### OR Operator



### Character Classes

Character classes differentiate between letter and digits. You can specify a range of characters by using a hyphen for example, "[a-d] = [abcd]", "\s = space", "\t = horizontal line", "\d = any digit [0-9]", "\w = any alphanumeric character [6A-Za-z0-9]", "[\b] = backspace", and much more.

### Flags

Flags (g,i,m,u,s,y) are optional in regex, if you use them, they will modify a regex behavior of searching. For example "i = search is case-insensitive","g = search looks for all matches", "m = multiline mode","s = enables dotall mode that allows a . to match a newline of character","u = enaables full Unicode support","y = searches for the exacrt position in the text".

### Grouping and Capturing

Grouping groups multiple patterns as a whole and Capturing groups treat characters as a single using parentheses. 

### Bracket Expressions

Backet Expressions uses the square brackets "[]" that matches any character inside that list.

### Greedy and Lazy Match

Greedy Match will try to match the longest string, while the Greedy Match will try to match the smallest possible string. 

### Boundaries

Word Boundary matches at a position that is followed by a word character but not proceeded by a word character or vise versa. For example, "\b. matches a, , and d in abc def". 

### Back-references

Back-references refer to a previously group in the same regex. For example, when you wish to look for repeated words in some text, "\1". 

### Look-ahead and Look-behind

Lookahead lets you add a condition for what follows or what is next. Meanwhile, Lookbehind is similar but it looks behind instead of what follows.

## Author

👤 Camila Fernandez 

* https://github.com/Camilaf99?tab=repositories
