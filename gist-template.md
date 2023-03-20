# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

Anchors serve the purpose of finding patterns behind strings. The most widely used anchors are the caret `^` and the dollar sign `$`.

The caret `^` matches with the beginning of a line.

The dollar sign `$` matches with the end of a line.

Example:

`^45` matches any line that start with the word "45", for example: Applying `^45` to "45B" will only match "45" since it is at the beginnning of the string.

`$goodbye` matches any line that ends with the word "goodbye"

### Quantifiers

Quantifiers serve the purpose of only allowing a pre-determined number of occurrences of characters within a string. The most widely used quantifiers are `+`, `*` and `?`.

`+` matches one or more occurences of the preceding character.

`*` matches zero or more occurences of the preceding character.

`?` matches zero or one occurence of the preceding character.

Example:

`z+` matches one or more occurences of the character "z".

`z*` matches zero or more occurences of the character "z".

`z?` matches zero or one occurences of the character "z".

### OR Operator

The OR operator in regular expressions is denoted by the `|` character and is used to match either of two patterns which are seperated by that character.

`hello|world` matches any string that contains either "world" or "hello

Example:

`apple|orange` matches either "apple" or "orange".

### Character Classes

Character classes server the purpose of matching a set of characters. Some commonly used character classes are `[a-z]`, `[A-Z]`, and `[0-9]`.

`[a-z]` matches any lowercase letter from "a" to "z".

`[A-Z]` matches any uppercase letter from "A" to "Z".

`[0-9]` matches any digit from 0 to 9.

Example:

`[aeiou]` matches any vowel.

### Flags

Flags serve the purpose of modifying the behavior of a specfic regex pattern. The most widely used flas are `i` which means case-insensitive, `g` which means global, and `m` which means multiline.

`i` makes the pattern case-insensitive.

`g` matches all occurrences of the pattern, not just the first one.

`m` matches the pattern across multiple lines.

Example:

`/hello/i` matches "hello", "Hello", "hElLo", etc.

`/world/g` matches all occurrences of "world" in the string.

### Grouping and Capturing

Grouping and capturing serves the purpose of grouping patterns together and capture the matched text for it to be used later. Groups are written with parentheses `()`.

Example:

`(hello)+` matches one or more occurrences of "hello".

`(hello)(world)` matches "hello" followed by "world" and captures both as separate groups.

### Bracket Expressions


### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
