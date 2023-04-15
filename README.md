# Regex Tutorial

Welcome to our regex tutorial! Regex is a powerful tool for pattern matching and text manipulation. In this tutorial, we will cover the fundamentals of regex, including key concepts, syntax, and practical examples. Whether you're a beginner or an experienced developer, this tutorial will provide you with a solid foundation to understand and effectively use regex in your projects. Let's get started!

## Summary

In this tutorial, we will be focusing on a common regex pattern: email validation. We will explain how to use regex to validate email addresses in your code. Here's an example of a simple regex pattern for email validation:

 ^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$

This regex pattern ensures that an email address must start with one or more alphanumeric characters, followed by the "@" symbol, then one or more alphanumeric characters, followed by a dot ".", and ends with two or more alphabetic characters. We will discuss each component of this pattern in detail and provide practical examples of how to use it for email validation in different programming languages.

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

Anchors in regex are special characters that allow you to specify the position of a pattern within a string. They do not match any characters themselves, but rather define the beginning or end of a line, word, or string. 

### Quantifiers

Quantifiers are used to specify the number of occurrences or repetitions of a preceding character or group. For example, * (zero or more), + (one or more), ? (zero or one), {} (exact number), {,} (minimum number), and {,} (range of occurrences).

### OR Operator

The OR operator in regex, denoted by the pipe symbol '(|)', allows you to specify multiple alternatives for a single position in a pattern. It allows you to create a logical OR condition, where any of the alternatives can match for the pattern to be considered a match.Here's how it works:

Syntax: 'pattern1|pattern2'

### Character Classes
Character classes in regex are special constructs that allow you to define a set of characters that can match a single character at a specific position in a string. They are denoted by square brackets ('[]') and are used to specify a range or a set of characters that are allowed or not allowed to match at a particular position in a pattern. Here's how they work:

Syntax:

'[characters]' - Matches any single character that is listed within the square brackets.
'[^characters]' - Matches any single character that is NOT listed within the square brackets.

### Flags

Flags, also known as modifiers or options, are additional settings that can be applied to a regular expression (regex) pattern to modify its behavior during matching or processing. Flags are usually appended to the end of a regex pattern and are denoted by a letter or a combination of letters, preceded by a backslash '\'.

### Grouping and Capturing

Grouping and capturing are important concepts in regex that allow you to organize and extract parts of a matched pattern. They provide a way to group and isolate specific portions of text data for further processing or manipulation. In regex, grouping is done using parentheses '(' and ')', and capturing allows you to capture and store the matched content of a group for later use.

### Bracket Expressions

Bracket expressions, also known as character classes, are a powerful feature in regex that allow you to define a set of characters that can match a single character at a specific position in a string. They are enclosed in square brackets '[ ]' and can specify a list of characters or ranges of characters that can be matched. For example, '[abc]' matches any of the characters "a", "b", or "c". You can also use special characters within bracket expressions to represent common character classes like digits, letters, whitespace, and more. Bracket expressions are widely used for tasks such as validating input, extracting specific characters, and filtering or manipulating text data. Understanding how to use bracket expressions effectively can enhance your regex skills and make your patterns more precise and efficient.

### Greedy and Lazy Match

Greedy and lazy matching are important concepts in regular expressions that affect how matches are made in a pattern.

Greedy matching is the default behavior, where the engine tries to match as much of the input string as possible. Example: '<.*>' matches from the first '<' to the last '>'.

Lazy matching, denoted by adding a '?' after a quantifier, matches as little as possible while still allowing the pattern to match. Example: '<.*?>' matches from the first '<' to the next character.

Understanding the difference between greedy and lazy matching is crucial for creating precise and efficient regex patterns when dealing with repetitive elements in the input string.

### Boundaries

Boundaries, or anchors, are special characters in regex that represent specific positions in a string. They include '^' for the start of a line or string, '$' for the end of a line or string, '\b' for word boundaries, and '\B' for non-word boundaries. Boundaries help ensure matches occur at desired positions, such as the beginning or end of a line, or between words in a string.

### Back-references

Back-references in regex allow you to refer to previously matched subpatterns within a pattern using '\1', '\2', etc. They are useful for capturing repeated occurrences of the same pattern or referencing previously matched subpatterns within a larger pattern.

### Look-ahead and Look-behind

Look-ahead and look-behind are advanced features in regex denoted by '(?=...)' for look-ahead and '(?<=...)' for look-behind. They allow you to assert conditions before or after a pattern without including them in the final match. They are useful for creating complex and precise regex patterns for advanced text manipulation tasks.

## Author

* Luis Garcia repository: [GitHub](https://github.com/LuisFGarciaN)
* Luis Garcia: [email](mailto:luisluisfgarcia096@gmail.com).
* [GitHubGis] :(https://gist.github.com/LuisFGarciaN/8b327da70ade1f5c717b6473de4836a4)