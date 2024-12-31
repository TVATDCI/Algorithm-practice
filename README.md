# Algorithm Practice

This repository contains a collection of algorithm challenges designed to help you improve your JavaScript skills. Each challenge includes a brief description and an example to illustrate the expected output. Whether you are a beginner or an experienced developer, these challenges will help you practice and enhance your problem-solving abilities.

## CHALLENGE 1: REVERSE A STRING

```javascript
// Return a string in reverse
// Example:
reverseString("hello") === "olleh";
```

**Explanation:** This challenge requires you to write a function that takes a string as input and returns the string in reverse order. For example, if the input is "hello", the output should be "olleh".

## CHALLENGE 2: VALIDATE A PALINDROME

```javascript
// Return true if palindrome and false if not
// Example:
isPalindrome("racecar") === true;
isPalindrome("hello") === false;
```

**Explanation:** A palindrome is a word, phrase, number, or other sequence of characters that reads the same forward and backward (ignoring spaces, punctuation, and capitalization). This challenge requires you to write a function that checks if a given string is a palindrome.

## CHALLENGE 3: REVERSE AN INTEGER

```javascript
// Return an integer in reverse
// Example:
reverseInt(521) === 125;
```

**Explanation:** This challenge requires you to write a function that takes an integer as input and returns the integer with its digits reversed. For example, if the input is 521, the output should be 125.

## CHALLENGE 4: CAPITALIZE LETTERS

```javascript
// Return a string with the first letter of every word capitalized
// Example:
capitalizeLetters("i love javascript") === "I Love Javascript";
```

**Explanation:** This challenge requires you to write a function that takes a string as input and returns the string with the first letter of each word capitalized. For example, if the input is "i love javascript", the output should be "I Love Javascript".

## CHALLENGE 5: MAX CHARACTER

```javascript
// Return the character that is most common in a string
// Example:
maxCharacter("javascript") === "a";
```

**Explanation:** This challenge requires you to write a function that takes a string as input and returns the character that appears most frequently in the string. For example, if the input is "javascript", the output should be "a".

## CHALLENGE 6: FIZZBUZZ

```javascript
// Write a program that prints all the numbers from 1 to 100. For multiples of 3, instead of the number, print "Fizz", for multiples of 5 print "Buzz". For numbers which are multiples of both 3 and 5, print "FizzBuzz".
```

**Explanation:** FizzBuzz is a classic programming challenge that requires you to write a program that prints the numbers from 1 to 100. However, for multiples of 3, you should print "Fizz" instead of the number, for multiples of 5, you should print "Buzz", and for multiples of both 3 and 5, you should print "FizzBuzz".

## CHALLENGE 7: LONGEST WORD

```javascript
// Return the longest word of a string
// SOLUTION 1 - Return a single longest word
// SOLUTION 2 - Return an array and include multiple words if they have the same length
// SOLUTION 3 - Only return an array if multiple words, otherwise return a string
// Example:
longestWord("Hi there, my name is Brad") === "there,";
longestWord("My name is Brad") === ["name", "brad"];
longestWord("Brad") === "brad";
```

**Explanation:** This challenge requires you to write a function that takes a string as input and returns the longest word in the string. If there are multiple words with the same length, you can return an array of those words.

## CHALLENGE 8: ARRAY CHUNKING

```javascript
// Split an array into chunked arrays of a specific length
// Example:
chunkArray([1, 2, 3, 4, 5, 6, 7], 3) === [[1, 2, 3], [4, 5, 6], [7]];
chunkArray([1, 2, 3, 4, 5, 6, 7], 2) === [[1, 2], [3, 4], [5, 6], [7]];
```

**Explanation:** This challenge requires you to write a function that takes an array and a chunk size as input and splits the array into smaller arrays (chunks) of the specified size. For example, if the input array is [1, 2, 3, 4, 5, 6, 7] and the chunk size is 3, the output should be [[1, 2, 3], [4, 5, 6], [7]].

## CHALLENGE 9: FLATTEN ARRAY

```javascript
// Take an array of arrays and flatten to a single array
// Example:
[[1, 2], [3, 4], [5, 6], [7]] === [1, 2, 3, 4, 5, 6, 7];
```

**Explanation:** This challenge requires you to write a function that takes an array of arrays as input and flattens it into a single array. For example, if the input is [[1, 2], [3, 4], [5, 6], [7]], the output should be [1, 2, 3, 4, 5, 6, 7].

## CHALLENGE 10: ANAGRAM

```javascript
// Return true if anagram and false if not
// Example:
'ex. 'elbow' === 'below'
'ex. 'Dormitory' === 'dirty room##'
```

**Explanation:** An anagram is a word or phrase formed by rearranging the letters of another word or phrase. This challenge requires you to write a function that takes two strings as input and returns true if they are anagrams of each other, and false otherwise.

## CHALLENGE 11: ADD ALL NUMBERS

```javascript
// Return a sum of all parameters entered regardless of the amount of numbers
// Example:
addAll(2, 5, 6, 7) === 20;
```

**Explanation:** This challenge requires you to write a function that takes any number of arguments and returns their sum. For example, if the input is 2, 5, 6, 7, the output should be 20.

## CHALLENGE 12: SUM ALL PRIMES

```javascript
// Pass in a number to loop up to and add all of the prime numbers. A prime number is a whole number greater than 1 whose only factors are 1 and itself
// Example:
sumAllPrimes(10) === 17;
```

**Explanation:** A prime number is a whole number greater than 1 whose only factors are 1 and itself. This challenge requires you to write a function that takes a number as input and returns the sum of all prime numbers up to that number. For example, if the input is 10, the output should be 17 (2 + 3 + 5 + 7).

## CHALLENGE 13: SEEK AND DESTROY

```javascript
// Remove from the array whatever is in the following arguments. Return the leftover numbers in an array
// Example:
seekAndDestroy([2, 3, 4, 6, 6, "hello"], 2, 6) === [3, 4, "hello"];
```

**Explanation:** This challenge requires you to write a function that takes an array and additional arguments, and removes all elements from the array that match any of the additional arguments. For example, if the input is [2, 3, 4, 6, 6, "hello"], 2, 6, the output should be [3, 4, "hello"].

## CHALLENGE 14: EVEN & ODD SUMS

```javascript
// Take in an array and return an array of the sums of even and odd numbers
// Example:
evenOddSums([50, 60, 60, 45, 71]) === [170, 116];
```

**Explanation:** This challenge requires you to write a function that takes an array as input and returns an array with two elements: the sum of all even numbers and the sum of all odd numbers. For example, if the input is [50, 60, 60, 45, 71], the output should be [170, 116].
