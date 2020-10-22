# Assignment 14

You will make a few methods for this assignment and it is fine if you just use one class.

Create the (`static`) methods in `Main.java` and run each of the tests in `main` (just copy and paste from below). Check that your test outputs match mine.

## Part 1
Given an "out" string length 4, such as "\<\<\>\>", and a word, return a new string where the word is in the middle of the out string, e.g. "\<\<word\>\>". Note: use str.substring(i, j) to extract the String starting at index i and going up to but not including index j.

### Sample Outputs

```
makeOutWord("<<>>", "Yay") → "<<Yay>>"
makeOutWord("<<>>", "WooHoo") → "<<WooHoo>>"
makeOutWord("[[]]", "word") → "[[word]]"
```

## Part 2

Given two strings, append them together (known as "concatenation") and return the result. However, if the strings are different lengths, omit chars from the longer string so it is the same length as the shorter string. So "Hello" and "Hi" yield "loHi". The strings may be any length.

### Sample Outputs

```
minCat("Hello", "Hi") → "loHi"
minCat("Hello", "java") → "ellojava"
minCat("java", "Hello") → "javaello"
minCat("abc", "x") → "cx"
minCat("", "Hello") → ""
```

### Grading

As always, your program will be graded on its functionality according to the project specifications and proper code style.

