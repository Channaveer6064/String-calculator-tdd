# 🧪 Incubyte TDD String Calculator

A test-driven implementation of a String Calculator built as part of the Incubyte Software Craftsperson hiring process. The repo demonstrates clean code, readable logic, and thoughtful commit history following the Red → Green → Refactor cycle.

## ✅ Problem Statement

Create a simple `add(string)` method that returns the sum of numbers in a string.

### Requirements:
- Empty string returns 0
- Comma-separated numbers return their sum
- Newlines (`\n`) can act as delimiters
- Support for custom delimiters using syntax: `//[delimiter]\n[numbers...]`
- Negative numbers throw an error listing all negatives
- Support for multiple and multi-character delimiters (e.g. `//[*][%]`, `//[***][%%%]`)

## ✅ Key Features

- Parses and adds comma/semicolon/custom delimited numbers from strings
- Supports custom delimiters of any length (e.g., `//[***]\n1***2***3`)
- Ignores numbers greater than 1000
- Throws error for negative numbers
- Unit tested using **JUnit** following strict **TDD discipline**

## 🚀 Tech Stack

- **JavaScript (Node.js)**
- **Jest** – for test-driven development
- **Git** – with frequent commits to reflect TDD evolution


## 🧰 TDD Process Followed

- Write a failing test
- Write minimal code to pass the test
- Refactor for clarity and maintainability
- Repeat for each new feature

## 🧼 Principles Followed

- Clean Code (Uncle Bob)
- SOLID Design
- Test-first mindset

## 🧪 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/Channaveer6064/String-calculator-tdd

# Navigate into project
cd incubyte-string-calculator-tdd

# Install dependencies
npm install

# Run tests
npm test
