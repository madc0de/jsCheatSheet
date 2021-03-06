# JS Cheat Sheet

## String Methods

1. ```.charAt(index) // Returns the character at the specified index (position)```
2. ```.charCodeAt(index) // Returns the Unicode of the character at the specified index```
3. ```.concat(str1,[...]) // Joins two or more strings, and returns a new joined strings```
4. ```.endsWith(searchVal,[length]) // Checks whether a string ends with specified string/characters```
5. ```.fromCharCode(n1,[...]) // Converts Unicode values to characters```
6. ```.includes(searchVal,[start]) // Checks whether a string contains the specified string/characters```
7. ```.indexOf(searchVal,[start]) // Returns the position of the first found occurrence of a specified value in a string```
8. ```.lastIndexOf(searchVal,[start]) // Returns the position of the last found occurrence of a specified value in a string```
9. ```.localeCompare(str) // Compares two strings in the current locale```
10. ```.match(regex) // Searches a string for a match against a regular expression, and returns the matches```
11. ```.repeat(count) // Returns a new string with a specified number of copies of an existing string```
12. ```.replace(searchVal,newVal) // Searches a string for a specified value, or a regular expression, and returns a new string where the specified values are replaced```
13. ```.search(searchVal) // Searches a string for a specified value, or regular expression, and returns the position of the match```
14. ```.slice(start,[end]) // Extracts a part of a string and returns a new string```
15. ```.split([separator],[limit]) // Splits a string into an array of substrings```
16. ```.startsWith(searchVal,[start]) // Checks whether a string begins with specified characters```
17. ```.substr(start,[length]) // Extracts the characters from a string, beginning at a specified start position, and through the specified number of character```
18. ```.substring(start,[end]) // Extracts the characters from a string, between two specified indices```
19. ```.toLocaleLowerCase() // Converts a string to lowercase letters, according to the host's locale```
20. ```.toLocaleUpperCase() // Converts a string to uppercase letters, according to the host's locale```
21. ```.toLowerCase() // Converts a string to lowercase letters```
22. ```.toString() // Returns the value of a String object```
23. ```.toUpperCase() // Converts a string to uppercase letters```
24. ```.trim() // Removes whitespace from both ends of a string```
25. ```.valueOf() // Returns the primitive value of a String object```

## Array

1. ```.concat(arr1,[...]) // Joins two or more arrays, and returns a copy of the joined arrays```
2. ```.copyWithin(target,[start],[end]) // Copies array elements within the array, to and from specified positions```
3. ```.entries() // Returns a key/value pair Array Iteration Object```
4. ```.every(function(currentval,[index],[arr]),[thisVal]) // Checks if every element in an array pass a test```
5. ```.fill(val,[start],[end]) // Fill the elements in an array with a static value```
6. ```.filter(function(currentval,[index],[arr]),[thisVal]) //	Creates a new array with every element in an array that pass a test```
7. ```.find(function(currentval,[index],[arr]),[thisVal]) // Returns the value of the first element in an array that pass a test```
8. ```.findIndex(function(currentval,[index],[arr]),[thisVal]) // Returns the index of the first element in an array that pass a test```
9. ```.forEach(function(currentval,[index],[arr]),[thisVal]) // Calls a function for each array element```
10. ```.from(obj,[mapFunc],[thisVal]) // Creates an array from an object```
11. ```.includes(element,[start]) // Check if an array contains the specified element```
12. ```.indexOf(element,[start]) // Search the array for an element and returns its position```
13. ```.isArray(obj) // Checks whether an object is an array```
14. ```.join([seperator]) // Joins all elements of an array into a string```
15. ```.keys() // Returns a Array Iteration Object, containing the keys of the original array```
16. ```.lastIndexOf(element,[start]) // Search the array for an element, starting at the end, and returns its position```
17. ```.map(function(currentval,[index],[arr]),[thisVal]) // Creates a new array with the result of calling a function for each array element```
18. ```.pop() // Removes the last element of an array, and returns that element```
19. ```.push(item1,[...]) // Adds new elements to the end of an array, and returns the new length```
20. ```.reduce(function(total,currentval,[index],[arr]),[initVal]) // Reduce the values of an array to a single value (going left-to-right)```
21. ```.reduceRight(function(total,currentval,[index],[arr]),[initVal]) // Reduce the values of an array to a single value (going right-to-left)```
22. ```.reverse() // Reverses the order of the elements in an array```
23. ```.shift() // Removes the first element of an array, and returns that element```
24. ```.slice([start],[end]) // Selects a part of an array, and returns the new array```
25. ```.some(function(currentval,[index],[arr]),[thisVal]) // Checks if any of the elements in an array pass a test```
26. ```.sort([compareFunc]) // Sorts the elements of an array```
27. ```.splice(index,[quantity],[item1,...]) // Adds/Removes elements from an array```
28. ```.toString() // Converts an array to a string, and returns the result```
29. ```.unshift(item1,...) // Adds new elements to the beginning of an array, and returns the new length```
30. ```.valueOf() // Returns the primitive value of an array```
