

Below are 20 advanced questions designed to elicit Python code answers requiring 3 or 4 functions to solve each problem. Each question asks for a solution with function calls, storing return values in variables, and printing the final result. The questions focus on modular programming, combining multiple functions, and problem decomposition to reinforce intermediate to advanced programming concepts.

---

### Question 1: Rectangle Perimeter with Validation and Formatting
Write Python code with three functions: one to validate if length and width are positive, returning `True` if both are, `False` otherwise; another to calculate the perimeter of a rectangle (2*(length + width)); and a third to format the result as a string ("Perimeter: X"). For inputs length=6 and width=4, validate, compute the perimeter, format the result, store it in a variable, and print it. If invalid, print "Invalid dimensions".

---

### Question 2: Sum of Even Squares with Range Check
Write Python code with three functions: one to check if a number is even, returning `True` if it is, `False` otherwise; another to square a number; and a third to check if a number is within range (0 to 100). For inputs 2, 3, and 4, check if each is in range, square the even numbers, sum the squares, store the result in a variable, and print it. If no valid even numbers, print 0.

---

### Question 3: Discounted Price with Tax Calculation
Write Python code with four functions: one to validate if a price is positive, returning `True` if it is, `False` otherwise; another to calculate a discount (15% if price > 200, else 10%); a third to calculate tax (8% of discounted price); and a fourth to compute the final price (price - discount + tax). For input price 250, validate, compute discount, tax, and final price, store the final price in a variable, and print it. If invalid, print "Invalid price".

---

### Question 4: Maximum of Four Numbers
Write Python code with three functions: one to find the minimum of two numbers; another to find the maximum of two numbers; and a third to find the maximum of four numbers using the previous functions. For inputs 8, 3, 12, and 7, find the maximum, store it in a variable, and print it.

---

### Question 5: Temperature Conversion with Range and Comfort Check
Write Python code with four functions: one to convert Celsius to Fahrenheit; another to check if a temperature is within a valid range (-50°C to 50°C), returning `True` if it is, `False` otherwise; a third to check if the Fahrenheit temperature is comfortable (60°F to 80°F); and a fourth to combine these. For input 30°C, validate, convert, check comfort, store the comfort status in a variable, and print it. If invalid, print "Invalid temperature".

---

### Question 6: Average of Positive Even Numbers
Write Python code with four functions: one to check if a number is positive; another to check if a number is even; a third to filter positive even numbers; and a fourth to compute their average. For inputs 10, -4, 6, and 3, compute the average of positive even numbers, store it in a variable, and print it. If none exist, print "No positive even numbers".

---

### Question 7: String Vowel and Consonant Count
Write Python code with three functions: one to count vowels (a, e, i, o, u) in a string; another to count consonants (non-vowel letters); and a third to combine both counts into a tuple (vowels, consonants). For input "python", compute both counts, store the tuple in a variable, and print it.

---

### Question 8: Triangle Validity and Perimeter
Write Python code with four functions: one to validate if three sides form a triangle (sum of two sides > third); another to calculate the perimeter; a third to check if all sides are positive; and a fourth to combine these. For inputs 3, 4, and 5, validate, compute the perimeter, store it in a variable, and print it. If invalid, print "Invalid triangle".

---

### Question 9: Product of Odd Numbers with Range Check
Write Python code with three functions: one to check if a number is odd; another to check if a number is within range (1 to 50); and a third to compute the product of odd numbers in range. For inputs 3, 4, 5, and 7, compute the product of valid odd numbers, store it in a variable, and print it. If none, print 1.

---

### Question 10: Circle Area with Precision Control
Write Python code with three functions: one to validate if a radius is positive; another to calculate the circle area (πr²); and a third to round the result to 2 decimal places. For input radius 4, validate, compute the area, round it, store it in a variable, and print it. If invalid, print "Invalid radius".

---

### Question 11: Quadratic Equation Root Check
Write Python code with four functions: one to validate if coefficients a, b, c are non-zero; another to calculate the discriminant (b²-4ac); a third to check if the discriminant is non-negative; and a fourth to compute one real root ((-b + √(b²-4ac))/(2a)) if valid. For inputs a=1, b=-3, c=2, validate, compute a root, store it in a variable, and print it. If invalid, print "Invalid or no real roots".

---

### Question 12: String Case and Length Analysis
Write Python code with three functions: one to count uppercase letters in a string; another to count lowercase letters; and a third to calculate the string length. For input "HeLLo", compute all three, store the results in a tuple (uppercase, lowercase, length), and print it.

---

### Question 13: Hypotenuse with Side Validation
Write Python code with four functions: one to validate if two sides are positive; another to calculate the hypotenuse (√(a²+b²)); a third to round the result to 2 decimal places; and a fourth to combine these. For inputs a=3, b=4, validate, compute the hypotenuse, round it, store it in a variable, and print it. If invalid, print "Invalid sides".

---

### Question 14: Sum of Digits in a Number
Write Python code with three functions: one to validate if a number is positive; another to extract digits from a number; and a third to sum the digits. For input 123, validate, compute the sum of digits, store it in a variable, and print it. If invalid, print "Invalid number".

---

### Question 15: Even Number Filter and Product
Write Python code with four functions: one to check if a number is even; another to validate if a number is positive; a third to filter even positive numbers; and a fourth to compute their product. For inputs 2, -4, 6, and 3, compute the product of positive even numbers, store it in a variable, and print it. If none, print 1.

---

### Question 16: String Palindrome with Cleaning
Write Python code with four functions: one to convert a string to lowercase; another to remove non-letters; a third to check if a string is a palindrome; and a fourth to combine these. For input "A man, a plan!", clean, check if palindrome, store the result in a variable, and print it.

---

### Question 17: Cylinder Volume with Validation
Write Python code with four functions: one to validate if radius and height are positive; another to calculate the circle area (πr²); a third to compute cylinder volume (area * height); and a fourth to round the result to 2 decimal places. For inputs radius=2, height=5, validate, compute volume, round it, store it in a variable, and print it. If invalid, print "Invalid dimensions".

---

### Question 18: Prime Number Check and Sum
Write Python code with four functions: one to check if a number is prime; another to validate if a number is positive; a third to filter prime numbers; and a fourth to sum them. For inputs 3, 4, 5, and 6, sum the prime numbers, store the result in a variable, and print it. If none, print 0.

---

### Question 19: Word Count in Sentence
Write Python code with three functions: one to split a sentence into words; another to count words; and a third to validate if the sentence is non-empty. For input "Hello world python", validate, count words, store the count in a variable, and print it. If invalid, print "Empty sentence".

---

### Question 20: Compound Interest with Validation
Write Python code with four functions: one to validate if principal, rate, and time are positive; another to calculate simple interest (principal * rate * time / 100); a third to calculate compound interest (principal * (1 + rate/100)^time); and a fourth to round the result to 2 decimal places. For inputs principal=1000, rate=5, time=2, validate, compute compound interest, round it, store it in a variable, and print it. If invalid, print "Invalid inputs".

---

### Instructions for Practice
- Write Python code for each question, defining 3 or 4 functions as specified, with function calls, storing return values in variables, and printing the final result.
- Ensure the Python code is modular, clear, and uses basic operations like arithmetic, comparisons, conditionals, string processing, and math functions (use Python’s `math` module for π, square root, etc.).
- Assume inputs are valid unless validation is explicitly required.
- Handle edge cases (e.g., empty lists, no valid numbers) as specified in each question.

If you want me to provide the Python code answers for any of these questions or clarify any question, let me know!

