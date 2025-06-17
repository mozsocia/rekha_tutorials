Below are 10 beginner-friendly pseudocode examples for practicing Python function creation, following a consistent pattern similar to the first example you liked (function definition, function call, storing return value in a variable, and printing the variable). To make them distinct and avoid simple copying, I've varied the function logic, included unique operations, and occasionally used multiple functions (two or three) in a single example. I've also placed function definitions in different orders (sometimes before the main program, sometimes after, or mixed when multiple functions are used) to add variety. The examples remain beginner-level but are designed to require thoughtful conversion to Python.

---

### Example 1: Triple and Add One
**Pseudocode:**
```
// Main program
value = 4


FUNCTION triple_and_add_one(num)
    temp = num * 3
    result = temp + 1
    RETURN result
END FUNCTION

result = triple_and_add_one(value)
PRINT result
```

---

### Example 2: Check Odd and Double
**Pseudocode:**
```
FUNCTION is_odd(num)
    IF num MOD 2 = 1 THEN
        RETURN true
    ELSE
        RETURN false
    END IF
END FUNCTION

FUNCTION double_if_odd(num)
    IF is_odd(num) THEN
        RETURN num * 2
    ELSE
        RETURN num
    END IF
END FUNCTION

// Main program
input_num = 7
answer = double_if_odd(input_num)
PRINT answer
```

---

### Example 3: Square and Subtract
**Pseudocode:**
```
// Main program
base = 5


FUNCTION square_and_subtract(num)
    squared = num * num
    result = squared - num
    RETURN result
END FUNCTION

output = square_and_subtract(base)
PRINT output
```

---

### Example 4: Max of Three Numbers
**Pseudocode:**
```
FUNCTION max_of_two(a, b)
    IF a > b THEN
        RETURN a
    ELSE
        RETURN b
    END IF
END FUNCTION

// Main program
num1 = 8
num2 = 3
num3 = 6
temp = max_of_two(num1, num2)
result = max_of_two(temp, num3)
PRINT result
```

---

### Example 5: Half if Even
**Pseudocode:**
```
FUNCTION is_even(num)
    IF num MOD 2 = 0 THEN
        RETURN true
    ELSE
        RETURN false
    END IF
END FUNCTION

FUNCTION half_if_even(num)
    IF is_even(num) THEN
        RETURN num / 2
    ELSE
        RETURN num
    END IF
END FUNCTION

// Main program
number = 10
answer = half_if_even(number)
PRINT answer


```

---

### Example 6: Multiply and Add Five
**Pseudocode:**
```
// Main program
x = 3
y = 4


FUNCTION multiply_and_add_five(a, b)
    product = a * b
    result = product + 5
    RETURN result
END FUNCTION

total = multiply_and_add_five(x, y)
PRINT total
```

---

### Example 7: Check Range and Adjust
**Pseudocode:**
```
FUNCTION in_range(num)
    IF num >= 1 AND num <= 10 THEN
        RETURN true
    ELSE
        RETURN false
    END IF
END FUNCTION

FUNCTION adjust_if_in_range(num)
    IF in_range(num) THEN
        RETURN num + 2
    ELSE
        RETURN num - 2
    END IF
END FUNCTION

// Main program
value = 6
result = adjust_if_in_range(value)
PRINT result
```

---

### Example 8: Cube and Compare
**Pseudocode:**
```

FUNCTION cube_number(num)
    RETURN num * num * num
END FUNCTION

FUNCTION cube_and_compare(num)
    cubed = cube_number(num)
    IF cubed > 10 THEN
        RETURN cubed
    ELSE
        RETURN 10
    END IF
END FUNCTION

// Main program
input_num = 2
answer = cube_and_compare(input_num)
PRINT answer

```

---

### Example 9: Divide and Round Up
**Pseudocode:**
```
FUNCTION divide_numbers(a, b)
    quotient = a / b
    IF quotient MOD 1 = 0 THEN
        RETURN quotient
    ELSE
        RETURN quotient + 1
    END IF
END FUNCTION

// Main program
numerator = 17
denominator = 4
result = divide_numbers(numerator, denominator)
PRINT result
```

---

### Example 10: Triple, Subtract, and Check Positive
**Pseudocode:**
```
FUNCTION triple_number(num)
    RETURN num * 3
END FUNCTION

FUNCTION is_positive(num)
    IF num > 0 THEN
        RETURN true
    ELSE
        RETURN false
    END IF
END FUNCTION

// Main program
value = 3
tripled = triple_number(value)
adjusted = tripled - 1
final_result = is_positive(adjusted)
PRINT final_result
```

---

### Instructions for Practice
- **Convert to Python**: Write Python code for each example, ensuring:
  - Functions are defined with the same logic as the pseudocode.
  - Function calls use the specified inputs.
  - Return values are stored in variables.
  - The variable is printed.
- **Notes**:
  - For Example 9, assume the denominator is non-zero to avoid division errors.
  - For division operations (e.g., Example 5, Example 9), Python's division (`/`) returns a float, so consider using integer division (`//`) or rounding as needed.
  - For modulo (`MOD`) operations, use Python's `%` operator.
  - For logical conditions (e.g., `AND`), use Python's `and` operator.
- **Testing**: Run your Python code to verify the output matches the expected behavior.
- **Variety**: The function definitions are placed differently (before or after the main program) to practice flexibility. Multiple functions in some examples (e.g., Examples 2, 4, 5, 7, 8, 10) require understanding function dependencies.

If you need help converting any specific example to Python, want to see a sample solution, or have questions about implementing the logic, let me know!
