---
Title: '.lastIndexOf()' 
Description: 'Searches a string for a specified value, and returns the position of the match.'
Subjects:
  - 'Computer Science'
  - 'Programming'
Tags:
  - '.lastIndexOf'
  - 'String Method'
  - 'JavaScript'
CatalogContent:
  - 'Learn how to use the .lastIndexOf method in JavaScript.'
---

The **`.lastIndexOf()`** method is a string method in JavaScript which searches a string for a specified value, and returns the position of the match. It searches the string from the end to the beginning, and returns the index within the string of the last occurrence of the specified value, or -1 if the value is not found.

## Syntax

```
str.lastIndexOf(searchValue[, fromIndex])
```

The `searchValue` parameter is required and is the value to search for. The `fromIndex` parameter is optional and is the index at which to start searching backwards in the string.

## Example

```javascript
let str = 'The quick brown fox jumps over the lazy dog';
let lastPos = str.lastIndexOf('the');
console.log(lastPos); // 31
```

This example searches the string `str` for the value `the` and returns the index of the last occurrence of `the`, which is 31
