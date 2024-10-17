# Challenge: Temperature Converter in Go

## Objective

Create a command-line application in Go that converts temperatures between Celsius and Fahrenheit. This challenge will help you practice your Go programming skills, as well as your understanding of basic input handling and mathematical operations.

## Requirements

1. The program should prompt the user to choose a conversion option:
   - 1: Celsius to Fahrenheit
   - 2: Fahrenheit to Celsius

2. Based on the user's choice:
   - If the user selects option 1, the program should ask for a temperature in Celsius, convert it to Fahrenheit, and display the result.
   - If the user selects option 2, the program should ask for a temperature in Fahrenheit, convert it to Celsius, and display the result.
   
3. Implement error handling:
   - Ensure that the program handles invalid input gracefully (e.g., non-numeric values or out-of-range numbers).
   - Display appropriate error messages for invalid options or input.

4. Organize your code:
   - Create a separate package (e.g., `auxiliary`) for the conversion functions:
     - `CelsToFir(celsius float32) float32`: Converts Celsius to Fahrenheit.
     - `FirToCels(fahrenheit float32) float32`: Converts Fahrenheit to Celsius.


## Bonus Challenge

- Add functionality to convert temperatures between Kelvin and Celsius.
- Implement unit tests for the conversion functions in your auxiliary package.




