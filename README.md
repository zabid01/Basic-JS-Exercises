# Basic JS Exercises

### Exercise 1: Percentage

**Write a JavaScript function to calculate the percentage (%) of a given number.**

Test:
console.log(percentage(2000, 37.12));

Output:
742.4

------

### Exercise 2: Rotate String

**Rotate a given string in the right direction by periodically removing one letter from the end of the string and attaching it to the front.**

Test:
rotateString("cat");

Output:

cat

tca

atc

cat

HINT: Use *substring()*

------

### Exercise 3: Remove First Occurence

**Write a JavaScript function to remove the first occurrence of a given 'search string' from a string.**

Test:
console.log(remove_first_occurrence("The quick brown fox jumps over the lazy dog", 'the'));

Output:
"The quick brown fox jumps over lazy dog"

HINT: Use *indexOf()* and *slice()*

------

### Exercise 4: Alphabetical Order

**Write a JavaScript function that returns a passed string with letters in alphabetical order.**

Test:
console.log(alphabetic_order('webmaster'));

Output:
abeemrstw

HINT: Use *join()*, *split()* and *sort()*

------

### Exercise 5: Most Frequent Item

**Write a JavaScript function to find the most frequent item in a given array.**

Test:
most_frequent([3, 'a', 'a', 'a', 2, 3, 'a', 3, 'a', 2, 4, 9, 3]);

Output:
a occurs 5 times

------

### Exercise 6: FizzBuzz

**Write a JavaScript function which iterates the integers from 1 to n. For multiples of three print "Fizz" beside the number and for the multiples of five print "Buzz". For numbers which are multiples of both three and five print "FizzBuzz".**

Test:
fizzbuzz(16);

Output:

3 Fizz

5 Buzz

6 Fizz

9 Fizz

10 Buzz

12 Fizz

15 FizzBuzz

------

### Exercise 7: Guessing Game

**Write a JavaScript program where the program takes a random integer between 1 to 10, the user is then prompted to input a guess number. If the user input matches with guess number, the program will display a message "Good Work" otherwise display a message "Not matched"**

HINT: Use *Math.ceil()* and *Math.random()*

------

Source: [w3resource](http://www.w3resource.com/)
