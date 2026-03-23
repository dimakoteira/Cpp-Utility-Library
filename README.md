# Cpp-Utility-Library
A collection of reusable C++ header-only libraries for String manipulation, Input Validation, and general Utility functions
C++ Utility Library 🛠️
A comprehensive collection of reusable C++ classes designed to simplify string manipulation, input validation, and general utility tasks. These classes are built with an Object-Oriented approach, providing both static and instance-based methods.

📁 Library Components
1. clsString 🔤
This class provides advanced tools for handling and transforming strings. It includes features that go beyond the standard string library.

Case Transformation: Convert strings or the first letter of each word to uppercase/lowercase.

Counting & Analysis: Count words, specific letters, capital letters, small letters, and vowels.

Splitting & Joining: Split strings into a std::vector<string> based on a delimiter and join them back.

Cleaning: Remove punctuations and extra spaces.

Reversing & Replacing: Reverse word order and replace specific words within a string.

Property Support: Uses __declspec(property) for easy access to the string value (Visual Studio specific).

2. clsInputValidate ✅
A robust class dedicated to ensuring user input is safe and within expected ranges. It handles common std::cin failures automatically.

Type-Safe Reading: Methods to read int, short, float, and double with built-in error handling for invalid characters.

Range Validation: Check if a number or a date (using clsDate) falls within a specific range.

Read Between: Force the user to enter a number between two values, providing a custom error message until a valid input is received.

Date Validation: Basic checks for date validity.

3. clsUtil ⚙️
A "Swiss Army Knife" for common programming logic, such as randomization, encryption, and formatting.

Randomization: Generate random numbers, characters, words, and professional-looking license keys (e.g., XXXX-XXXX-XXXX).

Array Operations: Fill arrays with random numbers/words and shuffle them.

Encryption: Simple Caesar-cipher-like encryption and decryption using a numeric key.

Number to Text: A sophisticated method to convert large numeric values (up to billions) into their English text equivalent (e.g., 123 -> "one hundred twenty three").

Generics: Template-based swap function to work with any data type.
4. clsDate:The clsDate library is a comprehensive system designed to handle date and time operations with high precision. It goes beyond basic display features, acting as a complete computational engine for temporal logic in C++.
🚀 How to Include
Since these are header-only libraries, you can simply include the files in your project:
#include "clsString.h"
#include "clsInputValidate.h"
#include "clsUtil.h"
#include "clsDate.h"
