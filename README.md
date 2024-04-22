# Even Odd Number Checker

This Go program checks whether numbers in a list are even or odd.

## Overview

This program demonstrates a simple function to determine whether numbers in a given list are even or odd. It uses a loop to iterate over the list of numbers and uses the modulus operator (`%`) to check if each number is divisible by 2. If the remainder is 0, the number is even; otherwise, it is odd.

## How to Use

1. Clone the repository:

   ```sh
   git clone https://github.com/prasiddha007/goEvenOdd.git
   ```

2. Navigate to the project directory:

   ```sh
   cd goEvenOdd
   ```

3. Run the program:

   ```sh
   go run main.go
   ```

## Example

Input:
```go
numberList := []int{0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
```

Output:
```
0 is Even
1 is odd
2 is Even
3 is odd
4 is Even
5 is odd
6 is Even
7 is odd
8 is Even
9 is odd
10 is Even
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
