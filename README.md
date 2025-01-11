# CurrencyConverter_CPP

A simple C++ program to convert an amount in Indian Rupees (INR) into its equivalent values in other major currencies: United States Dollar (USD), Euro (EUR), and British Pound (GBP).

## Features

- Accepts an input amount in INR.
- Converts the input amount into:
  - USD (United States Dollar)
  - EUR (Euro)
  - GBP (British Pound)
- Uses predefined exchange rates for simplicity.
- Easy to use and understand for beginners learning C++.

## How It Works

1. The program prompts the user to enter an amount in INR.
2. It calculates the equivalent amounts in USD, EUR, and GBP using the following exchange rates:
   - 1 INR = 0.012 USD
   - 1 INR = 0.011 EUR
   - 1 INR = 0.0091 GBP
3. The results are displayed with two decimal precision.

---

## Getting Started

### Prerequisites

- A C++ compiler (e.g., GCC, MinGW, or any IDE like Code::Blocks, Visual Studio, etc.).

### Compilation

1. Clone this repository:
   ```bash
   git clone https://github.com/abjaiyad/CurrencyConverter_CPP.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CurrencyConverter_CPP
   ```
3. Compile the program:
   ```bash
   g++ CurrencyConverter.cpp -o CurrencyConverter
   ```

### Running the Program

After successful compilation, run the program:
```bash
./CurrencyConverter
```
Enter an amount in INR when prompted, and the program will display the equivalent amounts in USD, EUR, and GBP.

---

## Example

### Input:
```
Enter Amount in INR: 1000
```

### Output:
```
Amount in INR: 1000.00
Equivalent USD: 12.00
Equivalent EUR: 11.00
Equivalent GBP: 9.10
```

---

## File Structure

- `CurrencyConverter.cpp` - The main program file.

---

## Contributing

Contributions are welcome! Feel free to fork this repository, make your changes, and submit a pull request.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Author

**Amad Bin Jaiyad**  
- GitHub: [abjaiyad](https://github.com/abjaiyad)
