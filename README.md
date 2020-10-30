# JS Cheat Sheet

## String Methods

1 Returns the character at the specified index (position)
    ```.charAt(index)```
2 Returns the Unicode of the character at the specified index
    ```.charCodeAt(index)```
3 Joins two or more strings, and returns a new joined strings
    ```.concat(str1,[...])```
4 Checks whether a string ends with specified string/characters
    ```.endsWith(searchVal,[length])```
5 Converts Unicode values to characters
    ```.fromCharCode(n1,[...])```
6 Checks whether a string contains the specified string/characters
    ```.includes(searchVal,[start])```
7 Returns the position of the first found occurrence of a specified value in a string
    ```.indexOf(searchVal,[start])```
8 Returns the position of the last found occurrence of a specified value in a string
    ```.lastIndexOf(searchVal,[start])```
9 Compares two strings in the current locale
    ```.localeCompare(str)```
10 Searches a string for a match against a regular expression, and returns the matches
    ```.match(regex)```
11 Returns a new string with a specified number of copies of an existing string
    ```.repeat(count)```
12 Searches a string for a specified value, or a regular expression, and returns a new string where the specified values are replaced
    ```.replace(searchVal,newVal)```
13 Searches a string for a specified value, or regular expression, and returns the position of the match
    ```.search(searchVal)```
14 Extracts a part of a string and returns a new string
    ```.slice(start,[end])```
15 Splits a string into an array of substrings
    ```.split([separator],[limit])```
16 Checks whether a string begins with specified characters
    ```.startsWith(searchVal,[start])```
17 Extracts the characters from a string, beginning at a specified start position, and through the specified number of character
    ```.substr(start,[length])```
18 Extracts the characters from a string, between two specified indices
    ```.substring(start,[end])```
19 Converts a string to lowercase letters, according to the host's locale
    ```.toLocaleLowerCase()```
20 Converts a string to uppercase letters, according to the host's locale
    ```.toLocaleUpperCase()```
21 Converts a string to lowercase letters
```.toLowerCase()```
22 Returns the value of a String object
    ```.toString()```
23 Converts a string to uppercase letters
    ```.toUpperCase()```
24 Removes whitespace from both ends of a string
    ```.trim()```
25 Returns the primitive value of a String object
    ```.valueOf()```
