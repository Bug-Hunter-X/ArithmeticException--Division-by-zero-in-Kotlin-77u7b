# Kotlin ArithmeticException: Division by Zero

This repository demonstrates a common error in Kotlin: attempting to divide by zero, resulting in an `ArithmeticException`.  The example shows how to reproduce the error and how to properly handle division to prevent it.

**Bug:** The `calculate` function does not check if the divisor (`b`) is zero, leading to an exception when `b` is 0.

**Solution:** The improved `calculate` function includes a check for `b == 0`, handling this scenario gracefully.

## Usage:

1. Clone this repository.
2. Open the project in your Kotlin IDE.
3. Run the `main` function in `bug.kt` to see the exception.
4. Run the `main` function in `bugSolution.kt` to see the corrected version.