# 🔐 Random Password Generator

## 📌 Project Overview
The Random Password Generator is a Python-based application that generates secure random passwords based on user preferences. Users can customize password length and select different character types.

## ✨ Features
* Generate passwords with a minimum length of 8 characters.
* Include uppercase letters, lowercase letters, numbers, and symbols.
* Validate password length and character selections.
* Use Python's `secrets` module for secure password generation.
* Display password strength: Weak, Medium, or Strong.
* Copy generated passwords to the clipboard.
* Maintain the last five generated passwords during the current session.
* Exclude ambiguous characters such as `0`, `O`, `1`, `l`, and `I`.

## 🛠️ Technologies Used
* Python 3
* Tkinter
* `secrets` module
* `string` module

## 📋 Requirements
* Python 3.9 or later recommended.
* Tkinter installed with Python.

## 🚀 How to Run
1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run the application:

   ```bash
   python password_generator.py
