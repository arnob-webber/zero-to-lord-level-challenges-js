## Challenge 1: Unique Character Checker

**Problem:**
write a function hasUniqueChars(str) that takes a string as input and returns true if the string contains only unique **characters**, and **false** otherwise.

```javascript
hasUniqueChars("hello"); // false
hasUniqueChars("world"); // true
hasUniqueChars(""); // true
```

## Challenge 2: Array Chunking

**Problem:**
write a function chunkArray(arr, size) that splits an array into smaller arrays (chunks) of a given size. If the array can't be split evenly, the last chunk should contain the remaining elements.

```javascript
chunkArray([1, 2, 3, 4, 5], 2); // [[1, 2], [3, 4], [5]]
chunkArray([1, 2, 3, 4, 5, 6, 7], 3); // [[1, 2, 3], [4, 5, 6], [7]]
```

**hint**

- The size will always be a positive integer.
- The array may contain any type of elements.

## Challenge 3: Anagram Checker

**Problem:**
Write a function isAnagram(str1, str2) that checks if two strings are anagrams of each other. Two strings are anagrams if they contain the same characters in the same frequencies, but in a different order.

```javascript
isAnagram("listen", "silent"); // true
isAnagram("hello", "bello"); // false
```

## Challenge 4: Binary Gap

**Problem:**
given a positive integer n, write a function binaryGap(n) that returns the length of the longest sequence of consecutive zeros that is surrounded by ones in the binary representation of n.

```javascript
binaryGap(9); // 2  (binary: 1001)
binaryGap(529); // 4 (binary: 1000010001)
binaryGap(20); // 1 (binary: 10100)
binaryGap(15); // 0 (binary: 1111)
```

**hint**

-     the integer n will be a positive number.
-     the binary representation of n will have at least two '1's.

## Challenge 5: String Compression

**Problem:**
Write a function compressString(str) that compresses a string by using the counts of repeated characters. For example, the string "aabcccccaaa" would become "a2b1c5a3". If the "compressed" string would not become smaller than the original string, your function should return the original string.

```javascript
compressString("aabcccccaaa"); // "a2b1c5a3"
compressString("abcd"); // "abcd"
```

**hint**

-     the string will contain only uppercase and lowercase letters (a-z).
