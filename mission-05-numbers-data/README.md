# Mission 5: Numbers and Data

## 1. Task / objective

Understand decimal, binary and hexadecimal number systems, perform number conversions, verify results using Python, build a number converter and learn how computers store text.

## 2. Work completed

### Task 5.1 — Convert Numbers by Hand

**1. Decimal 13 to Binary**

13 ÷ 2 = 6 remainder 1  
6 ÷ 2 = 3 remainder 0  
3 ÷ 2 = 1 remainder 1  
1 ÷ 2 = 0 remainder 1  

Answer: `1101`

**2. Decimal 25 to Binary**

25 ÷ 2 = 12 remainder 1  
12 ÷ 2 = 6 remainder 0  
6 ÷ 2 = 3 remainder 0  
3 ÷ 2 = 1 remainder 1  
1 ÷ 2 = 0 remainder 1  

Answer: `11001`

**3. Binary 1010 to Decimal**

= 1×8 + 0×4 + 1×2 + 0×1

Answer: `10`

**4. Binary 1101 to Decimal**

= 1×8 + 1×4 + 0×2 + 1×1

Answer: `13`

**5. Hexadecimal A to Decimal**

A = 10

Answer: `10`

**6. Hexadecimal 1F to Decimal**

= 1×16 + 15×1

Answer: `31`

**7. Binary 1111 to Hexadecimal**

1111 in binary = 15 in decimal.

15 in hexadecimal = F.

Answer: `F`

### Task 5.2 — Verify Using Python

| Conversion | Python expression | Result |
|---|---|---|
| Decimal 13 to binary | `bin(13)` | `0b1101` |
| Decimal 25 to binary | `bin(25)` | `0b11001` |
| Binary 1010 to decimal | `int("1010", 2)` | `10` |
| Binary 1101 to decimal | `int("1101", 2)` | `13` |
| Decimal 13 to hexadecimal | `hex(13)` | `0xd` |
| Decimal 25 to hexadecimal | `hex(25)` | `0x19` |
| Hexadecimal A to decimal | `int("A", 16)` | `10` |
| Hexadecimal 1F to decimal | `int("1F", 16)` | `31` |

The Python results match my manual calculations.

### Task 5.3 — Build a Small Number Converter

- Created a file named `number_converter.py`.
- Used `input()` to accept a decimal number.
- Used `int()` to convert the input into an integer.
- Used `bin()` to convert the number into binary.
- Used `hex()` to convert the number into hexadecimal.
- Displayed the converted results using `print()`.

**Test results:**

| Decimal input | Binary output | Hexadecimal output |
|---|---|---|
| 10 | 1010 | A |
| 13 | 1101 | D |
| 25 | 11001 | 19 |

### Task 5.4 — How Is Text Stored?

**ASCII decimal codes:**

- Uppercase A = 65
- Lowercase a = 97

**My understanding:**

- Computers store text using character encoding.
- ASCII represents a basic set of characters.
- UTF-8 supports a much wider range of characters.
- The rupee symbol (₹) is an example of a character outside basic ASCII.
- Encoding helps computers represent text using numbers.

## 3. Commands / tools used

- `python3`: Runs Python programs.
- `python3 number_converter.py`: Executes the number converter.
- `bin()`: Converts an integer into binary.
- `hex()`: Converts an integer into hexadecimal.
- `int()`: Converts a value into an integer.
- `input()`: Accepts input from the user.
- `print()`: Displays output.
- VS Code: Used to create and edit files.
- Terminal: Used to execute Python programs.

## 4. My understanding

- Decimal uses base 10.
- Binary uses base 2.
- Hexadecimal uses base 16.
- Computers represent information using 0s and 1s.
- Eight bits make one byte.
- Python provides built-in functions for number conversion.
- ASCII and UTF-8 are character encoding standards.
- Number systems help computers represent data.

## 5. Difficulties faced

- Initially, I was confused about decimal-to-binary conversion.
- Understanding hexadecimal values was challenging.
- I needed help understanding Python conversion functions.

## 6. How I resolved them

- Practised conversions step by step.
- Used Python to verify manual calculations.
- Created and tested a number converter.
- Studied ASCII and UTF-8 encoding.

## 7. Evidence / files

- README.md
- number_converter.py
- Manual conversion calculations
- Python verification results
- Three number converter test outputs
- Text encoding notes

## 8. Commit details

- Commit message: Build number converter and practise data representation.
- Commit status: Pending.
- Push status: Pending.