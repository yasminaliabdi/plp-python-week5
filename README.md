# Week 5 Assignment: Password Generator & Your Own Module

## Files

- **password_generator.py** - Uses the `random` and `string` modules to generate random passwords. Creates an 8-character and a 12-character password.
- **helpers.py** - A custom module with two functions: `tables_needed()` (calculates how many tables are needed) and `welcome()` (returns a greeting). Includes a `__main__` block for testing.
- **main.py** - Imports `helpers` and uses both functions to print output.

## How to Run

1. Run `password_generator.py` to generate random passwords.
2. Run `main.py` to see the helpers module in action.
3. Run `helpers.py` on its own to see the `__main__` block.

## Reflection

The `if __name__ == "__main__":` block is useful because it lets a file run code only when executed directly, not when imported. This means `helpers.py` can be tested on its own without affecting `main.py`.