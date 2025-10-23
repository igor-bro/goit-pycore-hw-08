# 📚 Address Book Application — Python OOP Project

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![OOP](https://img.shields.io/badge/-Object_Oriented-FF6B6B?logo=code&logoColor=white)
![CLI](https://img.shields.io/badge/-Command_Line-4B8BBE?logo=terminal&logoColor=white)
![Pickle](https://img.shields.io/badge/-Pickle-32CD32?logo=python&logoColor=white)
![Data Persistence](https://img.shields.io/badge/-Data_Persistence-FF6B6B?logo=database&logoColor=white)

## 📖 Description

A comprehensive Address Book application built with Python using Object-Oriented Programming principles. This project demonstrates advanced Python skills including classes, inheritance, data persistence, and user interface design.

**Key Highlights:**

- 🏗️ Clean OOP architecture with proper class hierarchy
- 💾 Automatic data persistence using Pickle serialization
- 📱 Command-line interface with intuitive commands
- 🔍 Advanced search and filtering capabilities
- 📊 Contact management with birthday tracking
- ⚡ Fast and efficient data operations
- 🛡️ Input validation and error handling

## 🚀 Technologies

### Core Python Stack

- **Python 3.8+** - Core programming language
- **OOP Concepts** - Classes, inheritance, polymorphism, encapsulation
- **Pickle** - Data serialization and persistence
- **Collections** - UserDict for custom dictionary behavior
- **Datetime** - Date handling and birthday calculations

### Architecture & Design

- **Decorators** - Error handling and input validation
- **Modular Design** - Separated concerns across multiple files
- **CLI Interface** - Command-line user interaction
- **Data Validation** - Input validation and error management
- **File I/O** - Persistent data storage and retrieval

## ✨ Features

### 📊 Contact Management

- **Add Contacts** - Create new contacts with name and phone
- **Edit Contacts** - Modify existing contact information
- **Delete Contacts** - Remove contacts with confirmation
- **Search Contacts** - Find contacts by name or phone
- **List Contacts** - Display all contacts with details
- **Phone Management** - Add, edit, and remove phone numbers

### 🎂 Birthday Features

- **Birthday Tracking** - Store and manage birthday information
- **Upcoming Birthdays** - Find birthdays in the next week
- **Date Validation** - Proper date format validation (DD.MM.YYYY)
- **Age Calculation** - Automatic age calculation

### 🔧 Technical Features

- **Data Persistence** - Automatic save/load with Pickle
- **Input Validation** - Phone number and date format validation
- **Error Handling** - Graceful error handling with decorators
- **Cross-platform** - Works on Windows, macOS, and Linux
- **Memory Efficient** - Optimized data structures and operations

## 📸 Screenshots

```
👋 Welcome to the assistant bot!
📝 Enter a command: add John 1234567890
✅ Contact John added successfully.

📝 Enter a command: add-birthday John 15.03.1990
✅ Birthday added for John.

📝 Enter a command: birthdays
📅 Upcoming birthdays in the next week:
- John: 15.03.1990 (in 5 days)

📝 Enter a command: all
📋 All contacts:
- John: 1234567890, Birthday: 15.03.1990
```

## ⚙️ Installation & Usage

### Quick Start

1. **Clone the repository:**

```bash
git clone https://github.com/igor-bro/goit-pycore-hw-08.git
cd goit-pycore-hw-08
```

2. **Run the application:**

```bash
python main.py
```

### Available Commands

- `add <name> <phone>` — Add new contact or phone number
- `change <name> <old> <new>` — Change phone number
- `delete <name>` — Delete contact
- `phone <name>` — Show contact's phone numbers
- `add-birthday <name> <DD.MM.YYYY>` — Add birthday
- `show-birthday <name>` — Show birthday
- `birthdays` — Show upcoming birthdays (next week)
- `all` — Show all contacts
- `help` — Show available commands
- `exit` or `close` — Save and exit

## 🎯 Key Learning Outcomes

### Object-Oriented Programming

- **Class Design** - Proper class hierarchy and inheritance
- **Encapsulation** - Data hiding and access control
- **Polymorphism** - Method overriding and overloading
- **Abstraction** - Interface design and implementation
- **Composition** - Object relationships and dependencies

### Python Advanced Features

- **Decorators** - Function modification and error handling
- **Data Serialization** - Pickle for data persistence
- **Collections** - Custom dictionary behavior with UserDict
- **Exception Handling** - Proper error management
- **File Operations** - Reading and writing data files

### Software Architecture

- **Modular Design** - Separated concerns across files
- **Error Handling** - Graceful error management
- **Data Validation** - Input validation and sanitization
- **User Interface** - Command-line interface design
- **Data Persistence** - Automatic save/load functionality

## 🏗️ Project Structure

```
goit-pycore-hw-08/
├── address_book.py    # Core classes: Field, Name, Phone, Birthday, Record, AddressBook
├── storage.py         # Data persistence: save_book() and load_book() with Pickle
├── handlers.py         # Command handlers: add, change, delete, birthdays, etc.
├── decorators.py       # Error handling decorators
├── main.py            # Main CLI loop and command parser
├── requirements.txt   # Project dependencies
└── README.md          # Project documentation
```

### Class Hierarchy

- **Field** - Base class for all data fields
- **Name** - Contact name field
- **Phone** - Phone number field with validation
- **Birthday** - Birthday field with date validation
- **Record** - Individual contact record
- **AddressBook** - Main container for all contacts

## 🧪 Testing

The project includes comprehensive error handling and input validation:

- **Phone Validation** - 10-digit phone number requirement
- **Date Validation** - DD.MM.YYYY format validation
- **Input Validation** - Command parameter validation
- **Error Handling** - Graceful error messages

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐️ Star this repository if you found it helpful!
