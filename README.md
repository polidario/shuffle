# 🔀 shuffle-array

A lightweight utility to shuffle the elements of an array in place using the Fisher–Yates algorithm.

---

## 🚀 Installation

Install via npm:

```
npm install shuffle-array
```

Or, for local development:

```
npm link
```

---

## 📦 Usage

```js
const shuffleArray = require('shuffle-array');

const items = ['apple', 'banana', 'cherry', 'date'];
const shuffled = shuffleArray(items);

console.log(shuffled); 
// → [ 'cherry', 'apple', 'date', 'banana' ] (order will vary)
```

> ⚠️ **Note:** The original array is **mutated**. If you want to preserve the original, clone it first:

```js
const shuffled = shuffleArray([...items]);
```

---

## 🧠 How It Works

This package uses the [Fisher–Yates shuffle](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle), a time-tested algorithm that ensures every possible ordering of the array is equally likely.

---

## 📄 API

### `shuffleArray(array)`

- **Parameters**:
  - `array` — An array of any type (e.g. strings, numbers, objects).
- **Returns**:
  - The same array, shuffled in place.

---

## ✅ Example Use Cases

- Randomizing quiz options
- Shuffling playlist items
- Mixing flashcards
- Creating randomized test data

---

## 🔧 Development

To test this package locally:

```
npm link
# then in another project
npm link shuffle-array
```

---

## 📜 License

MIT © 2025 Your Name
