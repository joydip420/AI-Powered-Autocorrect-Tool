# AI-Powered Autocorrect Tool

An AI-powered Natural Language Processing (NLP) application that automatically detects and corrects common spelling, grammar, capitalization, and punctuation errors in English text.

The project combines **PySpellChecker** for spelling correction with a **T5 Transformer model** for grammar correction and provides an interactive **Gradio** interface for users.

---

## 📌 Project Overview

The **AI-Powered Autocorrect Tool** is an NLP-based text correction system designed to improve the quality and readability of user-written text.

The system processes the input text through multiple correction stages:

1. Spelling correction
2. Grammar correction using a T5 Transformer
3. Capitalization correction
4. Punctuation correction
5. Correction analysis and statistics

The application also identifies whether the input required correction and calculates a correction score based on the similarity between the original and corrected text.

---

## 🎯 Objective

The main objective of this project is to develop an intelligent autocorrection system that can:

- Detect spelling mistakes.
- Correct grammatical errors.
- Fix capitalization issues.
- Add missing punctuation.
- Analyze the corrections performed.
- Provide correction statistics.
- Identify text that does not require correction.
- Provide alternative correction suggestions.
- Provide an easy-to-use interactive interface.

---

## ✨ Features

### 🔤 Spelling Correction

The system uses **PySpellChecker** to detect and correct spelling mistakes.

**Example:**

```text
Input:
I hav a beutiful hous.

Output:
I have a beautiful house.
