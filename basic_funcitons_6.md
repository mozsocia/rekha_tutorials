

# 20 Additional Advanced Python Exercises

Below are 20 advanced Python programming questions designed to reinforce modular programming, function composition, and problem decomposition. Each question requires 3 or 4 functions, function calls, storing return values in variables, and printing the final result. The problems focus on intermediate to advanced concepts, including arithmetic, string processing, list operations, and the use of Python’s `math` module where needed.

---

### Question 1: Area of Triangle with Heron's Formula
Write Python code with three functions: one to validate if three sides are positive and form a triangle (sum of two sides > third); another to calculate the semi-perimeter (s = (a + b + c)/2); and a third to compute the area using Heron's formula (√(s(s-a)(s-b)(s-c))). For inputs a=3, b=4, c=5, validate, compute the area, store it in a variable, and print it rounded to 2 decimal places. If invalid, print "Invalid triangle".

---

### Question 2: Sum of Odd Digits in a Number
Write Python code with three functions: one to validate if a number is positive; another to extract digits from a number; and a third to sum only the odd digits. For input 1357, validate, compute the sum of odd digits, store it in a variable, and print it. If invalid, print "Invalid number".

---

### Question 3: String Word Length Average
Write Python code with four functions: one to validate if a string is non-empty; another to split a string into words; a third to compute the average length of words; and a fourth to round the result to 2 decimal places. For input "Python is fun", validate, compute the average word length, store it in a variable, and print it. If invalid, print "Empty string".

---

### Question 4: Factorial Sum of Digits
Write Python code with three functions: one to compute the factorial of a number; another to validate if the number is non-negative; and a third to sum the digits of the factorial. For input n=5, validate, compute the factorial, sum its digits, store the result in a variable, and print it. If invalid, print "Invalid number".

---

### Question 5: Pythagorean Triple Check
Write Python code with four functions: one to validate if three numbers are positive; another to check if they form a Pythagorean triple (a² + b² = c²); a third to sort the numbers to ensure c is the largest; and a fourth to combine these. For inputs a=3, b=4, c=5, validate, check if they form a Pythagorean triple, store the result in a variable, and print it. If invalid, print "Invalid numbers".

---

### Question 6: Longest Word in Sentence
Write Python code with three functions: one to validate if a sentence is non-empty; another to split the sentence into words; and a third to find the longest word (return the first one in case of ties). For input "The quick brown fox", validate, find the longest word, store it in a variable, and print it. If invalid, print "Empty sentence".

---

### Question 7: Sum of Prime Factors
Write Python code with four functions: one to check if a number is prime; another to validate if a number is positive; a third to find all prime factors of a number; and a fourth to sum them. For input n=28, validate, compute the sum of prime factors, store it in a variable, and print it. If invalid, print "Invalid number".

---

### Question 8: String Character Frequency
Write Python code with three functions: one to convert a string to lowercase; another to count the frequency of a specific character; and a third to return a dictionary of all character frequencies. For input "Hello" and character 'l', compute the frequency of 'l', store it in a variable, and print it.

---

### Question 9: Cube Sum of First N Numbers
Write Python code with three functions: one to validate if a number n is positive; another to compute the cube of a number; and a third to sum the cubes of the first n numbers. For input n=3, validate, compute the sum of cubes (1³ + 2³ + 3³), store it in a variable, and print it. If invalid, print "Invalid number".

---

### Question 10: Reverse Words in Sentence
Write Python code with four functions: one to validate if a sentence is non-empty; another to split the sentence into words; a third to reverse each word; and a fourth to join the reversed words. For input "Hello World", validate, reverse each word, store the result in a variable, and print it. If invalid, print "Empty sentence".

---

### Question 11: GCD and LCM of Two Numbers
Write Python code with four functions: one to validate if two numbers are positive; another to compute the GCD using the Euclidean algorithm; a third to compute the LCM using GCD (a*b/GCD); and a fourth to combine these. For inputs a=12, b=18, validate, compute the LCM, store it in a variable, and print it. If invalid, print "Invalid numbers".

---

### Question 12: String Anagram Check
Write Python code with four functions: one to convert a string to lowercase; another to remove non-letters; a third to check if two strings are anagrams (same letters, same frequency); and a fourth to combine these. For inputs "Listen" and "Silent", check if they are anagrams, store the result in a variable, and print it.

---

### Question 13: Sum of Squares of Even Digits
Write Python code with three functions: one to validate if a number is positive; another to extract even digits; and a third to sum their squares. For input 246, validate, compute the sum of squares of even digits, store it in a variable, and print it. If invalid, print "Invalid number".

---

### Question 14: Distance Between Two Points
Write Python code with four functions: one to validate if coordinates (x1, y1, x2, y2) are numbers; another to calculate the Euclidean distance (√((x2-x1)² + (y2-y1)²)); a third to round the result to 2 decimal places; and a fourth to combine these. For inputs x1=0, y1=0, x2=3, y2=4, compute the distance, store it in a variable, and print it. If invalid, print "Invalid coordinates".

---

### Question 15: Count Words Starting with Vowel
Write Python code with four functions: one to validate if a sentence is non-empty; another to split the sentence into words; a third to check if a word starts with a vowel (a, e, i, o, u); and a fourth to count such words. For input "Apple is orange", validate, count words starting with a vowel, store the result in a variable, and print it. If invalid, print "Empty sentence".

---

### Question 16: Binomial Coefficient
Write Python code with four functions: one to validate if n and k are non-negative and k ≤ n; another to compute the factorial of a number; a third to compute the binomial coefficient (n!/(k!(n-k)!)); and a fourth to combine these. For inputs n=5, k=2, validate, compute the binomial coefficient, store it in a variable, and print it. If invalid, print "Invalid inputs".

---

### Question 17: Sum of ASCII Values in String
Write Python code with three functions: one to validate if a string is non-empty; another to compute the ASCII value of a character; and a third to sum the ASCII values of all characters. For input "abc", validate, compute the sum of ASCII values, store it in a variable, and print it. If invalid, print "Empty string".

---

### Question 18: Perfect Number Check
Write Python code with four functions: one to validate if a number is positive; another to find all proper divisors of a number; a third to check if the sum of proper divisors equals the number (perfect number); and a fourth to combine these. For input n=28, validate, check if it’s a perfect number, store the result in a variable, and print it. If invalid, print "Invalid number".

---

### Question 19: String Title Case with Vowel Check
Write Python code with four functions: one to validate if a string is non-empty; another to convert a string to title case; a third to count vowels in the string; and a fourth to combine these into a tuple (title_case_string, vowel_count). For input "hello world", validate, compute the title case and vowel count, store the tuple in a variable, and print it. If invalid, print "Empty string".

---

### Question 20: Weighted Average with Validation
Write Python code with four functions: one to validate if a list of numbers and weights are positive and of equal length; another to compute the product of each number and its weight; a third to compute the weighted average (sum of products / sum of weights); and a fourth to round the result to 2 decimal places. For inputs numbers=[10, 20, 30], weights=[1, 2, 3], validate, compute the weighted average, store it in a variable, and print it. If invalid, print "Invalid inputs".

---

### Instructions for Practice
- Write Python code for each question, defining 3 or 4 functions as specified, with function calls, storing return values in variables, and printing the final result.
- Ensure the Python code is modular, clear, and uses basic operations like arithmetic, comparisons, conditionals, string processing, and math functions (use Python’s `math` module for π, square root, etc.).
- Assume inputs are valid unless validation is explicitly required.
- Handle edge cases (e.g., empty lists, no valid numbers) as specified in each question.

