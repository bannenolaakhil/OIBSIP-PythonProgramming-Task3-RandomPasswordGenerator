
# 🔐 Random Password Generator

## 📌 Project Overview

The Random Password Generator is a Python-based desktop application that generates secure, random passwords based on user preferences. Users can choose the password length and character types to create strong passwords.

This project was developed as part of a Python Programming Internship to practice Python programming, GUI development, input validation, and password security.

## ✨ Features

- Generate random passwords with a minimum length of 8 characters.
- Include uppercase letters, lowercase letters, numbers, and symbols.
- Allow users to select different character types.
- Validate password length and character selections.
- Use Python's `secrets` module for secure password generation.
- Display password strength as Weak, Medium, or Strong.
- Copy generated passwords to the clipboard.
- Maintain the last five generated passwords during the current session.
- Exclude ambiguous characters such as `0`, `O`, `1`, `l`, and `I`.
- Provide a user-friendly graphical interface.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **GUI Framework:** Tkinter
- **Security Module:** `secrets`
- **String Handling:** `string`

## 📋 Requirements

- Python 3.9 or later recommended.
- Tkinter installed with Python.

No third-party Python packages are required.

## 📂 Project Structure

```text
Random-Password-Generator/
├── password_generator.py
└── README.md
```

## 🚀 Installation and Execution

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
```

### Step 2: Open the Project Folder

```bash
cd Random-Password-Generator
```

### Step 3: Run the Application

```bash
python password_generator.py
```

On some systems, use:

```bash
python3 password_generator.py
```

### Step 4: Generate a Password

1. Enter the desired password length.
2. Select the character types you want to include.
3. Click **Generate Password**.
4. Check the displayed password strength.
5. Click **Copy** to copy the password to your clipboard.

## 🔒 Security

The application uses Python's `secrets` module to generate passwords suitable for security-sensitive use. Password strength indicators are estimates and do not guarantee that a password is impossible to guess.

Avoid sharing generated passwords or storing sensitive passwords in publicly accessible repositories.

## 🎯 Learning Outcomes

- Understanding secure random password generation.
- Working with Python strings and character sets.
- Building desktop applications using Tkinter.
- Implementing input validation and error handling.
- Understanding basic password security principles.
- Working with clipboard functionality.

## 👨‍💻 Project Information

- **Project Name:** Random Password Generator
- **Domain:** Python Programming
- **Project Type:** Internship Project
- **Status:** Completed

## 📄 License

This project is intended for educational and learning purposes. Add an appropriate open-source license before redistributing it.
