

# String Manipulation in C

This C program performs several common string operations including:

* Reversing a string
* Checking if a string is a palindrome (ignoring case and non-alphanumeric characters)
* Concatenating two strings
* Counting the number of words in a string

---

## Features

* Reverse any input string in place
* Palindrome check is case-insensitive and ignores spaces and punctuation
* Concatenate two user-provided strings assuming sufficient buffer space
* Count words accurately even if multiple spaces or punctuation are present

---

## How to Use

1. Clone the repository or download the source code file `string_manipulation.c`.

2. Compile the program with a C compiler:

   ```bash
   gcc string_manipulation.c -o string_manipulation
   ```

3. Run the executable:

   ```bash
   ./string_manipulation
   ```

4. Follow the prompts to input strings for each operation:

   * Reverse a string
   * Check if a string is palindrome
   * Concatenate two strings
   * Count the number of words in a string

---

## Sample Run

```
Enter a string to reverse: Hello World!
Reversed string: !dlroW olleH

Enter a string to check palindrome: A man, a plan, a canal, Panama
The string is a palindrome.

Enter first string for concatenation: Hello 
Enter second string for concatenation: World!
Concatenated string: Hello World!

Enter a string to count words: This is a sample sentence.
Word count: 5
```

---

## Code Overview

* `reverseString(char str[])`: Reverses a string in-place.
* `isPalindrome(const char str[])`: Checks if the input string is a palindrome ignoring case and non-alphanumeric characters.
* `concatenate(char str1[], const char str2[])`: Concatenates `str2` to the end of `str1`. Assumes `str1` has enough space.
* `wordCount(const char str[])`: Counts words separated by spaces in the input string.
* `main()`: Interactively takes input and calls the above functions to demonstrate their functionality.

---

## Requirements

* Standard C compiler (supports C99 or later)
* Standard C library

---


