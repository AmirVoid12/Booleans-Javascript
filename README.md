# 🎯 Booleans-Javascript

![License](https://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Tests](https://img.shields.io/badge/tests-passing-brightgreen.svg?style=for-the-badge)

## 📖 Overview

A comprehensive collection of JavaScript Boolean operation modules designed to simplify complex boolean logic operations. Each module is carefully crafted to provide efficient, readable, and maintainable solutions for boolean algebra problems.

## 🗂️ Project Structure

```
Booleans-Javascript/
├── 📁 BasicOperations/
│   ├── AND.js
│   ├── OR.js
│   └── NOT.js
├── 📁 CompoundOperations/
│   ├── NAND.js
│   ├── NOR.js
│   └── XOR.js
├── 📁 ConditionalLogic/
│   ├── IF_THEN.js
│   ├── IMPLIES.js
│   └── IFF.js
├── 📁 TruthTables/
│   ├── TableGenerator.js
│   ├── Validator.js
│   └── Formatter.js
├── 📁 BooleanAlgebra/
│   ├── Simplifier.js
│   ├── Normalizer.js
│   └── Evaluator.js
└── 📁 Utils/
    ├── Parser.js
    ├── Formatter.js
    └── Validator.js
```

## ⚡ Features

- **Basic Operations**: Core boolean operations (AND, OR, NOT)
- **Compound Operations**: Advanced boolean functions (NAND, NOR, XOR)
- **Conditional Logic**: Implements logical implications and bi-conditionals
- **Truth Tables**: Generate and validate truth tables
- **Boolean Algebra**: Simplify and normalize boolean expressions
- **Utility Functions**: Parse and format boolean expressions

## 🚀 Quick Start

```javascript
// Import a module
const { AND } = require('./BasicOperations/AND');
const { OR } = require('./BasicOperations/OR');

// Basic usage
console.log(AND(true, true));  // Output: true
console.log(OR(false, true));  // Output: true
```

## 📦 Installation

```bash
npm install booleans-javascript
```

## 📚 Module Examples

### Basic Operations
```javascript
const { AND, OR, NOT } = require('./BasicOperations');

// AND operation
console.log(AND(true, false));  // false

// OR operation
console.log(OR(true, false));   // true

// NOT operation
console.log(NOT(true));         // false
```

### Compound Operations
```javascript
const { NAND, NOR, XOR } = require('./CompoundOperations');

// XOR operation
console.log(XOR(true, true));   // false
console.log(XOR(true, false));  // true
```

## 🧪 Testing

Each module includes comprehensive test cases:

```bash
npm test
```

## 📊 Performance

| Operation | Time Complexity | Space Complexity |
|-----------|----------------|------------------|
| Basic     | O(1)           | O(1)            |
| Compound  | O(1)           | O(1)            |
| Truth Table| O(2^n)        | O(2^n)          |

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/Booleans-Javascript?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/yourusername/Booleans-Javascript?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/yourusername/Booleans-Javascript?style=for-the-badge)

## 🔍 Keywords

`javascript`, `boolean-algebra`, `logic-operations`, `truth-tables`, `boolean-expressions`, `node-modules`, `npm-package`

---

<div align="center">
  <p>Made with ❤️ for the JavaScript community</p>
  <img src="https://komarev.com/ghpvc/?username=yourusername&color=blue&style=flat-square" alt="Profile views">
</div>
