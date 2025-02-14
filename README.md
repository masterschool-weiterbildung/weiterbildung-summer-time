# Sum Generator

## Overview
This Python script continuously prompts the user to enter numbers and sums them until the cumulative total exceeds 1000. It utilizes a generator function for efficient handling of user input and sum calculation.

## Features
- Uses a generator to yield user-inputted values.
- Stops input collection once the cumulative sum exceeds 1000.
- Provides a clean function to calculate and display the final sum.

## Constant
```python
LESS_THAN_ONE_THOUSAND = 1000
```
Defines the threshold at which input collection stops.

## Functions
### `value_generator() -> int`
- A generator function that continuously prompts the user for input.
- Yields values until the cumulative sum exceeds `LESS_THAN_ONE_THOUSAND`.

### `calculate_the_sum() -> int`
- Calls `value_generator` and computes the total sum of the entered values.
- Returns the final sum.

### `main() -> None`
- Calls `calculate_the_sum` and prints the final sum.

## Usage
Run the script in a Python environment:
```sh
python sum_generator.py
```
The script will prompt for user input:
```sh
Enter your number: 200
Enter your number: 500
Enter your number: 400
Final sum: 1100
```
