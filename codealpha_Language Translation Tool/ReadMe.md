# Language Translation Tool

## Task Overview

This project is developed as part of **Internship Task 1: Language Translation Tool**.

The objective of this task is to build a simple application that allows users to:

* Enter text
* Select source and target languages
* Translate the text using a translation API
* Display the translated output clearly

This project uses the **Python `googletrans` library**, which is an unofficial Python wrapper for Google Translate.

---

## Features

* User input for text to be translated
* Language selection using language codes
* Translation using Google Translate service
* Clear display of translated text

**Optional features (future scope):**

* Copy translated text button
* Text-to-Speech functionality

---

## Prerequisites

Before running this project, ensure you have the following installed:

* **Python 3.7 or above**
* **pip (Python package manager)**
* **googletrans library**

---

## Step 1: Install Python

### Windows

1. Visit the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Download the latest stable version of Python 3.
3. Run the installer.
4. **Important:** Check the option **“Add Python to PATH”** before clicking *Install*.
5. Complete the installation.

### Verify Python Installation

Open Command Prompt and run:

```bash
python --version
```

If Python is installed correctly, it will display the installed version.

---

## Step 2: Install googletrans Library

The standard version of `googletrans` may not work correctly due to API updates. Therefore, the recommended version is:

```bash
pip install googletrans==4.0.0-rc1
```

### Verify Installation

```bash
pip show googletrans
```

---

## Step 3: Project Setup

1. Create a new Python file (e.g., `translator.py`).
2. Import the Translator class:

```python
from googletrans import Translator
```

3. Initialize the translator object:

```python
translator = Translator()
```

4. Accept user input and destination language code.
5. Call the `translate()` method and display the output.

---

## API Reference

This project is implemented by referring to the official **Python googletrans documentation**:

🔗 [https://py-googletrans.readthedocs.io/en/latest/](https://py-googletrans.readthedocs.io/en/latest/)

The documentation was used to understand:

* Supported language codes
* Translator class usage
* `translate()` method parameters

---

## Example Usage

```python
from googletrans import Translator

translator = Translator()
text = "Hello World"
result = translator.translate(text, dest='hi')
print(result.text)
```

Output:

```
नमस्ते दुनिया
```

---

## Conclusion

This project demonstrates a basic language translation tool using Python and the `googletrans` API. It fulfills all the requirements of **Internship Task 1** and can be extended further with a graphical user interface, speech features, or additional APIs.

---

## Author

**U Nithin Sathya**
