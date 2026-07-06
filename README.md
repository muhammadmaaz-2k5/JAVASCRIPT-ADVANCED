# 🚀 JavaScript Advanced Course

Welcome to the **JavaScript Advanced** repository. This repository documents the journey of learning JavaScript from fundamental concepts to advanced topics. Each section includes conceptual notes and practical code examples.

---

## 📂 Repository Directory Structure

```text
JAVASCRIPT-ADVANCED/
├── Lecture1/               # Introduction to JavaScript & Environment Setup
│   ├── 1. ECMAvsJS.md      # Conceptual differences (ECMAScript vs JS)
│   └── code.js             # Basic script execution demo
├── Lecture2/               # Variable Declarations
│   ├── Variables.md        # Comparison of var, let, and const
│   ├── var.js              # Examples of function/global-scoped var
│   ├── let.js              # Examples of block-scoped let
│   └── const.js            # Examples of constants and initialization
├── Lecture3/               # Primitive Data Types
│   ├── Primtives.md        # Overview of 7 primitive types
│   └── primitives.js       # Code demonstration of types and typeof operator
└── Lecture4/               # Reference Data Types
    ├── Refference.md       # Notes on Objects, Arrays, and Functions
    ├── object.js           # Object manipulation (dot & bracket notation)
    ├── arrays.js           # Working with arrays in JavaScript
    ├── functions.js        # Basic function syntax and parameters
    └── calculating.js      # Return statements and calculations
```

---

## 📝 Lecture Overviews

### 📑 [Lecture 1: ECMAScript vs JavaScript](./Lecture1/1. ECMAvsJS.md)
* Learn the relationship between **ECMAScript** (the standard specification) and **JavaScript** (the actual programming language implementation).
* Understand JavaScript engines (like Chrome's **V8** engine) and runtime environments (like **Node.js**).
* Explore running JavaScript code in both browser developer consoles and standalone environments.

### 📑 [Lecture 2: Variables (var, let, const)](./Lecture2/Variables.md)
* Understand the evolution of variable declaration in JavaScript (Pre-ES6 vs Post-ES6).
* Key differences covered:
  | Feature | `var` | `let` | `const` |
  | :--- | :--- | :--- | :--- |
  | **Redeclaration** | ✅ Allowed | ❌ Not Allowed | ❌ Not Allowed |
  | **Reassignment** | ✅ Allowed | ✅ Allowed | ❌ Not Allowed |
  | **Scope** | Global / Function | Block Scope | Block Scope |
  | **Initialization** | Not Required | Not Required | ⚠️ Required at declaration |

### 📑 [Lecture 3: Primitive Types](./Lecture3/Primtives.md)
* JavaScript values are categorized into **Primitive** and **Reference** types.
* Explore the 7 Primitive types:
  1. `String` (Textual data)
  2. `Number` (Integers & decimals)
  3. `Boolean` (True/False values)
  4. `null` (Intentional empty reference)
  5. `undefined` (Declared but unassigned value)
  6. `BigInt` (Extremely large numbers)
  7. `Symbol` (Unique identifiers)
* Use the `typeof` operator to inspect variable types.

### 📑 [Lecture 4: Reference Types](./Lecture4/Refference.md)
* Deep dive into complex data structures:
  * **Objects**: Storing key-value pairs. Learn about dot (`person.age`) and bracket (`person['name']`) notation.
  * **Arrays**: Storing ordered lists of items.
  * **Functions**: Creating reusable blocks of logic, accepting parameters, and returning calculated values.

---

## ⚙️ How to Run the Code

To run any of the JavaScript files locally, make sure you have [Node.js](https://nodejs.org/) installed, navigate to the folder, and run:

```bash
# Navigate to the lecture directory
cd Lecture4

# Run the JavaScript file
node calculating.js
```
