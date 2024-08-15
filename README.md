# Business Growth Rate Calculator

This repository contains a simple Python script that calculates the growth rate of a business based on initial and final values. The tool is useful for anyone involved in business strategy, finance, or growth consulting, offering a straightforward way to measure the percentage increase or decrease in key metrics like revenue, user base, or market share.

## Features

- **Growth Rate Calculation**: Compute the growth rate as a percentage given initial and final values.
- **Error Handling**: Ensures the initial value is not zero to avoid division errors.

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/growth.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd growth
    ```
3. Run the script:
    ```bash
    python business-growth-rate.py
    ```
4. Modify the `initial_value` and `final_value` variables to calculate the growth rate for your specific case.

## Example

```python
initial_value = 100000  # Example initial revenue
final_value = 150000    # Example final revenue

growth_rate = calculate_growth_rate(initial_value, final_value)
print(f"The growth rate is {growth_rate:.2f}%")

