# Audit Report: Fibonacci Program

## 1. Program Details

* **File Name:** `fibonacci.py`
* **Language:** Python
* **Purpose:** Generate a Fibonacci series for a specified number of terms.

## 2. Concepts Reviewed

* User input using `input()`.
* Type conversion using `int()`.
* Variables and multiple assignment.
* `for` loop.
* Addition.
* Output using `print()`.

## 3. Code Review

The program initializes two variables, `a` and `b`, to `0` and `1`. It prints the current value of `a` and updates both variables to generate the next Fibonacci numbers.

## 4. Expected Behaviour

The Fibonacci sequence begins:

`0, 1, 1, 2, 3, 5, 8, 13, ...`

The program should print the requested number of terms for a valid non-negative integer input.

## 5. Limitations

* Negative input is not explicitly validated.
* Non-integer input may cause an error.
* Runtime testing has not been performed.

## 6. Recommendations

* Add input validation.
* Test with `0`, `1`, and larger positive integers.
* Verify that the number of printed terms matches the input.

## 7. Audit Conclusion

The program demonstrates sequence generation, loops, arithmetic operations, and variable updates in Python.

**Audit Status:** Code reviewed; runtime testing pending.
