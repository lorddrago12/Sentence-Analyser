# 📝 Sentence Analyser

A lightweight JavaScript utility that provides detailed linguistic analysis of any sentence or string — counting vowels, consonants, punctuation, and words with zero dependencies.

---

## ✨ Features

| Function | Description |
|---|---|
| `getVowelCount(sentence)` | Counts all vowel characters (`a, e, i, o, u`) |
| `getConsonantCount(sentence)` | Counts all consonant characters |
| `getPunctuationCount(sentence)` | Counts punctuation marks (`.,!?;:-()[]{}\"'–`) |
| `getWordCount(sentence)` | Counts total words (handles extra whitespace) |

---

## 📦 Installation

No installation required. Simply copy the functions into your JavaScript project or include the script file.

```bash
# Clone the repository
git clone https://github.com/your-username/sentence-analyser.git

cd sentence-analyser
```

---

## 🚀 Usage

```js
// Vowel Count
const vowelCount = getVowelCount("Apples are tasty fruits");
console.log(`Vowel Count: ${vowelCount}`); // Vowel Count: 7

// Consonant Count
const consonantCount = getConsonantCount("Coding is fun");
console.log(`Consonant Count: ${consonantCount}`); // Consonant Count: 7

// Punctuation Count
const punctuationCount = getPunctuationCount("WHAT?!?!?!?!?");
console.log(`Punctuation Count: ${punctuationCount}`); // Punctuation Count: 9

// Word Count
const wordCount = getWordCount("I love freeCodeCamp");
console.log(`Word Count: ${wordCount}`); // Word Count: 3
```

---

## 🔍 Function Reference

### `getVowelCount(sentence)`

Returns the number of vowel characters in a sentence. Case-insensitive.

```js
getVowelCount("Hello World"); // → 3
```

**Parameters:**
- `sentence` *(string)* — The input string to analyse.

**Returns:** `number` — Total vowel count.

---

### `getConsonantCount(sentence)`

Returns the number of consonant characters in a sentence. Case-insensitive.

```js
getConsonantCount("Hello World"); // → 7
```

**Parameters:**
- `sentence` *(string)* — The input string to analyse.

**Returns:** `number` — Total consonant count.

---

### `getPunctuationCount(sentence)`

Returns the number of punctuation characters. Recognises: `. , ! ? ; : - ( ) [ ] { } " ' –`

```js
getPunctuationCount("Wait, really?!"); // → 3
```

**Parameters:**
- `sentence` *(string)* — The input string to analyse.

**Returns:** `number` — Total punctuation count.

---

### `getWordCount(sentence)`

Returns the number of words in a sentence. Safely handles empty strings and extra whitespace.

```js
getWordCount("  Hello   World  "); // → 2
getWordCount("");                  // → 0
```

**Parameters:**
- `sentence` *(string)* — The input string to analyse.

**Returns:** `number` — Total word count.

---

## 🧪 Example Output

```
Vowel Count: 7
Consonant Count: 7
Punctuation Count: 9
Word Count: 3
```

---

## 🛠️ Built With

- **Vanilla JavaScript** — No frameworks, no dependencies.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Open a pull request

---
