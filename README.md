# One-Time Password (OTP) Generator

## Overview

This is a simple Java application that generates a random One-Time Password (OTP) of a specified length using Java's `Random` class. The OTP is composed of numeric digits (0-9) and can be easily customized for different length requirements.

## Features

- Generate OTPs of variable length
- Uses Java's `Random` class for randomization
- Simple and straightforward implementation
- Easily configurable OTP length

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- A Java IDE or text editor

## How to Run

1. Ensure you have Java installed on your system
2. Compile the Java file:
   ```
   javac OTPGenerator.java
   ```
3. Run the application:
   ```
   java OTPGenerator
   ```

## Customization

To change the OTP length, modify the `otpLength` variable in the `main` method:

```java
int otpLength = 6; // Change this value to generate OTPs of different lengths
```

## Example Output

```
Generating OTP using Random class...
Your OTP is: 123456
```

## Note on Randomness

This implementation uses `java.util.Random`, which provides pseudorandom number generation. For cryptographically secure random number generation, consider using `java.security.SecureRandom` instead.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
