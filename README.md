# Random Number Generator

The Random Number Generator is a simple npm package that provides a convenient way to generate random numbers. It is useful for various applications that require randomization, such as simulations, games, statistical analysis, and more.

## Installation

Use npm to install the Random Number Generator package:

```shell
   `npm i nandha_random_number_generator`
```

## Usage

To use the Random Number Generator in your project, follow these steps:

1. Import the package into your JavaScript file:

```javascript
const { generateRandomNumber } = require("random-number-generator");
```

2. Generate a random number using the `generateRandomNumber` function:

```javascript
const randomNumber = generateRandomNumber(min, max);
```

- `min` (optional): The minimum value of the random number. Default is 0.
- `max` (optional): The maximum value of the random number. Default is 1.

3. Use the generated random number in your application as needed.

Here's a simple example of generating a random number:

```javascript
const { generateRandomNumber } = require("random-number-generator");

const randomNumber = generateRandomNumber(1, 10);
console.log(randomNumber);
```

This will output a random number between 1 and 10.

## Features

- Generate random numbers within a specified range.
- Customizable minimum and maximum values for the random number.
- Easy to integrate into your projects.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request or open an issue.

## Acknowledgements

This package was inspired by the need for a simple and reliable random number generator for JavaScript projects. Special thanks to the contributors and the open-source community for their valuable contributions and support.

## Contact

For any inquiries or questions, please contact nandhakumarchinnasami@gmail.com
