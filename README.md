# 🎓 Java Learning

Welcome! This is the main navigator for my educational projects.

# 📁 JavaBasics
## Numbers and Symbols in Java.
- [Task 63 V0.1: Cyrillic Rune V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_63_V0.1) — This project concludes the series of character studies by exploring a Cyrillic symbol. It demonstrates that Java's **char** type natively supports a wide range of global characters through the Unicode standard.
- [Task 62 V0.1: Rune Decryptor V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_62_V0.1) — This project simulates the decryption of an ancient rune. It focuses on the relationship between the **char** data type and its underlying **ASCII** numeric representation, demonstrating how Java handles character encoding.
- [Task 61 V0.1: Dragon Hoard V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_61_V0.1) — This project focuses on handling numeric data that exceeds the 32-bit limit of the standard `int` type. It demonstrates how to correctly declare a 64-bit **long** variable for massive values, such as a dragon's hoard, using underscores for readability and the mandatory suffix.
- [Task 60 V0.1: Hero Inventory V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_60_V0.1) — This project simulates the creation of a base inventory for an RPG (Role-Playing Game) hero. It demonstrates how to choose and declare appropriate **numeric primitive types** in Java based on the nature and range of the data being stored.
---

## The "do-while" loop: introduction and nuances of work.
- [Task 56 V1.1: Daily Sales Tracker V1.1](https://github.com/YuriiJavaDev/JavaBasics_Task_56_V1.1) — An enhanced version of the sales tracking utility. This iteration introduces advanced flow control using an infinite loop (`while(true)`), demonstrating how to selectively process data using `continue` to skip insignificant entries (zeros) and `break` to terminate the sequence.
- [Task 56 V0.1: Daily Sales Tracker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_56_V0.1) — This application simulates a point-of-sale system that records daily transactions. It aggregates multiple sales entries into a single total. The program utilizes a sentinel-controlled loop where a negative value serves as the termination signal for the workday.
- [Task 55 V0.1: Password Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_55_V0.1) — This project simulates a secure registration form component. It focuses on string validation using a **Do-While Loop**, ensuring that the user provides a password that meets specific security requirements (minimum length of 6 characters).
- [Task 54 V0.1: Console Menu V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_54_V0.1) — This project implements a basic interactive command-line menu using a **Do-While Loop**. It allows users to perform specific actions (like printing a greeting) repeatedly without restarting the application. The program maintains an active state until the user explicitly chooses to exit. 
- [Task 53 V0.1: ATM PIN Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_53_V0.1) — This project simulates an ATM user interface for PIN-code validation. It utilizes the **Do-While Loop** to repeatedly request input from the user until a valid **four-digit positive integer** (between 1000 and 9999) is provided.
- [Task 52 V0.1: Game Bootstrapper V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_52_V0.1) — This project demonstrates the unique behavior of the **Do-While Loop** in Java. Unlike a standard `while` loop, the `do-while` structure ensures that the code block is executed **at least once** because the exit condition is checked only after the iteration is complete.
---

## The "for" loop: introduction and nuances of work.
🧩 **Nested for-loops: working with 2D grids.**
- [Task 59 V0.1: Password Finder V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_59_V0.1) — This project simulates a brute-force search for a "perfect password" consisting of two numbers. It employs **nested for-loops** to iterate through possible combinations and utilizes an early exit strategy once the target condition (sum equals 13) is met.
- [Task 58 V0.1: Asteroid Field Visualization V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_58_V0.1) — This program simulates a space shuttle's radar view of an asteroid field. It uses **nested for-loops** to generate a precise 5x7 grid of star symbols (⭐). The project demonstrates basic 2-dimensional rendering in a console environment.
- [Task 57 V0.1: Radar Coordinate System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_57_V0.1) — This project simulates a radar scanning grid by generating a 3x4 coordinate table. It utilizes **nested for-loops** to iterate through rows (i) and columns (j), outputting the precise position of each cell in an `i,j` format.

🧩 **Single-level Iterations: flow control and sequence management.**
- [Task 51 V0.1: Coordinate Tracker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_51_V0.1) — This project simulates the tracking of two objects moving in opposite directions. It utilizes an advanced **For Loop** structure where two variables are initialized, updated, and evaluated simultaneously within a single loop header.
- [Task 50 V0.1: Product Cost Calculator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_50_V0.1) — This project implements a calculation engine for a dynamic pricing model. In this scenario, the price of an item is directly proportional to its position in the sequence (e.g., the 1st item costs 1, the 2nd costs 2, etc.). It utilizes a **For Loop** to aggregate the total cost for a set number of products (N).
- [Task 49 V0.1: Train Seating V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_49_V0.1) — This project simulates the identification of even-numbered seats in a train carriage. It utilizes a **For Loop** to iterate through a range of numbers (0 to 10) and incorporates an **If Statement** with the **Modulo Operator (%)** to filter and display only even values.
- [Task 48 V0.1: New Year Countdown V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_48_V0.1) — This project simulates a festive New Year's Eve countdown. It utilizes a **For Loop** to iterate backwards from 5 to 1, demonstrating precise control over loop initialization, termination conditions, and decrementing steps.
---

## The "while" loop: introduction and nuances of its operation.
- [Task 47 V0.1: Coffee Expense Tracker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_47_V0.1) — This project implements a budget-tracking utility specifically for coffee expenses. It utilizes a **While Loop** to continuously collect user input for beverage costs. The sequence is terminated when a negative value is detected, acting as a sentinel signal.
- [Task 46 V0.1: Cinema Seats V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_46_V0.1) — This project simulates the display of available seating in a cinema row. It utilizes a **While Loop** to iterate through seat numbers starting from 2, incrementing by 2, until reaching the limit of 10.
- [Task 45 V0.1: Smartphone Unlock V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_45_V0.1) — This project simulates a smartphone security interface. It employs a **While Loop** integrated with the **Scanner class** to continuously prompt the user for a password until the predefined correct value ("java") is entered.
- [Task 44 V0.1: Spaceship Launch V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_44_V0.1) — This project simulates a spaceship ignition sequence. It utilizes a **While Loop** to perform a controlled reverse countdown from a starting value to one, followed by a launch signal.
---

## Ternary operator in Java: concise conditions and nuances regarding Clean Code.
- [Task 43 V0.1: Amusement Park Ticketing System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_43_V0.1) — This project implements a multi-tier age categorization logic for an amusement park. It utilizes **Nested Ternary Operators** to evaluate four distinct age groups within a single expression.
- [Task 42 V0.1: Dynamic Greeting System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_42_V0.1) — This project implements a simple time-aware greeting mechanism. It utilizes the **Ternary Operator** to evaluate the current hour and select between two different greeting strings ("Good morning" or "Good day").
- [Task 41 V0.1: Online Store Order Parity Checker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_41_V0.1) — This project simulates a basic order sorting mechanism for an e-commerce platform. It utilizes the **Ternary Operator** to perform a parity check on order numbers, classifying them as either "Even" or "Odd".
- [Task 40 V0.1: Sports Performance Analysis V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_40_V0.1) — This project simulates a sports timing system. It focuses on the **Ternary Operator**, a concise alternative to the standard `if-else` statement for simple value assignments based on a condition.
---

## Operator precedence and parentheses in conditions.
- [Task 39 V0.1: Bank Loan Approval Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_39_V0.1) — This project simulates a banking decision system using two distinct sets of evaluation rules. It focuses on **Complex Logical Expressions** and the strategic use of parentheses to enforce specific business requirements using the same applicant data.
- [Task 38 V0.1: Party Access Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_38_V0.1) — This project explores the **Associativity of Logical Operators**. It tests the admission logic for a private event by evaluating three mandatory conditions using the logical AND (`&&`) operator with different grouping strategies.
- [Task 37 V0.1: Concert Ticket Purchase Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_37_V0.1) — This project analyzes the impact of **Operator Grouping** on logical expressions. It compares standard Java precedence rules with custom-defined logic using parentheses to determine concert ticket eligibility.
- [Task 36 V0.1: Vacation Planner Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_36_V0.1) — This project simulates a vacation feasibility check. It focuses on the **Precedence of Logical Operators**, demonstrating how Java evaluates complex boolean expressions containing both `||` (OR) and `&&` (AND) without explicit parentheses.
---

## Boolean logical type and logical operations.
- [Task 35 V0.1: Smart Thermostat Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_35_V0.1) — This project simulates the core logic of a smart thermostat. It focuses on **Range Validation**, using logical operators to check if a numeric value resides between defined inclusive boundaries (20°C to 25°C).
- [Task 34 V0.1: Picnic Planner Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_34_V0.1) — This project simulates a decision-making algorithm for weekend planning. It focuses on **Advanced Logical Operators** to evaluate multiple boolean conditions simultaneously.
- [Task 33 V0.1: Football Match Result Recorder V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_33_V0.1) — This project simulates a basic sports scoring system. It demonstrates how to use **Relational Operators** to compare two numeric values and store the resulting truth value in a `boolean` variable.
- [Task 32 V0.1: Boolean Fundamentals V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_32_V0.1) — This project introduces the **Boolean Primitive Type** in Java. It demonstrates how to store and display logical truth values, which serve as the foundation for conditional execution and decision-making in programming.
---

## Nested "if", multi-level logic.
- [Task 31 V0.1: Loyalty Program Discount Calculator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_31_V0.1) — This project simulates a loyalty program logic. It utilizes **Nested Conditional Logic** to calculate specific discount percentages based on user demographics (age) and membership status (club card).
- [Task 30 V0.1: Conference Access Management V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_30_V0.1) — This project simulates a conference registration system. It utilizes **Complex Nested Conditionals** to perform high-level visitor filtering based on age and specialized invitation categories (VIP vs. GUEST).
- [Task 29 V0.1: Exclusive Club Entry System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_29_V0.1) — This project simulates an entry control system for an exclusive club. It utilizes **Nested Conditional Logic** to validate a user's eligibility based on two factors: minimum age and specific residency (Prague).
- [Task 28 V0.1: Secure Access System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_28_V0.1) — This project simulates a two-factor security gate. It utilizes **Nested Conditional Logic** to perform a hierarchical check of user credentials: age verification followed by a secret code validation.
---

## Conditional operator "if-else".
- [Task 27 V0.1: Time-based Greeting System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_27_V0.1) — This project simulates an adaptive greeting system. It utilizes **Multi-Branch Conditional Logic** to analyze time-of-day data and return a context-specific greeting.
- [Task 26 V0.1: Simple Login System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_26_V0.1) — This project simulates a basic security gate. It focuses on the **Single-Branch Conditional** structure (`if` without `else`) and introduces the concept of string value comparison.
- [Task 25 V0.1: Clothing Advisor V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_25_V0.1) — This project simulates a simple weather assistant. It uses conditional branching to analyze temperature data and provide appropriate clothing recommendations.
- [Task 24 V0.1: Cinema Access Control V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_24_V0.1) — This project simulates a cinema ticketing system. It introduces the fundamental concept of **Conditional Logic**, where the program executes different blocks of code based on a boolean condition (age verification).
---

## Keyboard input.
- [Task 23 V0.1: Digital Business Card V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_23_V0.1) — This project simulates a digital business card generator. It focuses on handling mixed data types (String and int) and demonstrates professional string manipulation.
- [Task 22 V0.1: Cashier System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_22_V0.1) — This project simulates a simple cashier terminal. It focuses on basic arithmetic operations and handling multiple integer inputs sequentially.
- [Task 21 V1.1: Player Registration System V1.1](https://github.com/YuriiJavaDev/JavaBasics_Task_21_V1.1) — This project is a transitional milestone in Java learning journey. While the base task requires simple console input/output, this implementation elevates the solution into an **enterprise-ready architecture**.
- [Task 21 V0.2: Player Registration System V0.2](https://github.com/YuriiJavaDev/JavaBasics_Task_21_V0.2) — This project represents the basic foundation of a Player Registration System. Added console queries for user input.
- [Task 21 V0.1: Player Registration System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_21_V0.1) — This project represents the basic foundation of a Player Registration System.
- [Task 20: Login System](https://github.com/YuriiJavaDev/JavaBasics_Task_20) — This project demonstrates how to handle user input in Java using the Scanner class to read and display a password from the keyboard.
---

## Conversion between data types.
- [Task 19: Game Score Calculator](https://github.com/YuriiJavaDev/JavaBasics_Task_19) — This project demonstrates how to parse string-based numeric data (including negative values) into integers and perform arithmetic operations on the resulting data.
- [Task 18: Movie Year Extractor](https://github.com/YuriiJavaDev/JavaBasics_Task_18) — This project demonstrates how to convert numeric data stored as a String into a primitive int type to enable mathematical operations.
- [Task 17: Flight Tracker](https://github.com/YuriiJavaDev/JavaBasics_Task_17) — This project demonstrates string concatenation in Java by combining numeric flight data with destination text to create a complete status message.
- [Task 16: Access Code Formatter](https://github.com/YuriiJavaDev/JavaBasics_Task_16) — This project demonstrates how to convert primitive numeric data types into string representations for data transmission or messaging purposes.
---

## Strings and text: String type, working with strings.
- [Task 15.1: Anagram Encoder V0.1](https://github.com/YuriiJavaDev/AnagramEncoder_V0.1) — An advanced continuation of string manipulation topics. This is project implements a complex algorithm to reverse only letters within words while preserving the exact positions of all non-letter characters. It demonstrates professional-grade coding with JUnit 5 testing, Maven lifecycle management, and efficient use of StringBuilder.
- [Task 15: String data cleaning and manipulation](https://github.com/YuriiJavaDev/JavaBasics_Task_15) — This project focuses on data normalization using the String class. It simulates a real-world scenario where user-provided data (like a city name) contains unnecessary spaces and needs to be formatted.
- [Task 14: Escaping a quote by Yurii Gagarin](https://github.com/YuriiJavaDev/JavaBasics_Task_14) — This project demonstrates the use of escaping characters in Java strings. It shows how to include special characters, such as double quotes, inside a String object literal without breaking the code structure.
- [Task 13: User Profile Creation](https://github.com/YuriiJavaDev/JavaBasics_Task_13) — This project demonstrates string concatenation in Java. It shows how to combine multiple object types (String) into a single output using the + operator.
- [Task 12: Message from the future](https://github.com/YuriiJavaDev/JavaBasics_Task_12) — This project focuses on the String class in Java. It demonstrates how to declare a variable of an object type, initialize it with a string literal containing a message "from the future", and print the stored character sequence to the console.
---

## Integers: int type, operations with int type. Determining the remainder after division "%". Increment and decrement.
- [Task 11: Hero Health Tracking](https://github.com/YuriiJavaDev/JavaBasics_Task_11) — This project simulates tracking a character's health in a game environment. It demonstrates the practical use of unary operators: increment (++) and decrement (--).
- [Task 10: Prize Distribution Logic](https://github.com/YuriiJavaDev/JavaBasics_Task_10) — This project demonstrates the use of integer division and the modulo operator (%) in Java. It simulates a scenario where a set number of prizes must be distributed equally among teams, and the remainder is calculated.
- [Task 09: Single-Line Variable Management](https://github.com/YuriiJavaDev/JavaBasics_Task_9) — This project demonstrates Java's ability to declare and initialize multiple variables of the same type in a single statement. While this approach increases compactness, it is explored here primarily for syntax understanding.
---

## Memory addressing and variables. How to declare a variable and assign a value to it.
- [Task 08: Bank Account Transactions](https://github.com/YuriiJavaDev/JavaBasics_Task_8) — This project simulates basic banking operations using integer variables. It demonstrates how to perform balance transfers between accounts and apply bonuses using fundamental arithmetic operations in Java.
- [Task 07: Memory Allocation & Concatenation](https://github.com/YuriiJavaDev/JavaBasics_Task_7) — This project focuses on understanding the memory footprint of different primitive data types in Java. It demonstrates how to combine descriptive text with actual variable values using string concatenation.
- [Task 06: String Manipulation & Immutability](https://github.com/YuriiJavaDev/JavaBasics_Task_6) — This project demonstrates how Java handles String variables and references. It explores the concept of object assignment and string immutability by creating a copy of a variable and modifying it independently.
- [Task 05: Game Character Profile](https://github.com/YuriiJavaDev/JavaBasics_Task_5) — This project demonstrates the use of various Java primitive and reference data types. The goal was to create a profile for a game character by storing different types of information (level, gold, rating, and name) and displaying them in the console.
---

## How to make comments in code.
- [Task 04: Compilation Error Analysis & Clean Code](https://github.com/YuriiJavaDev/JavaBasics_Task_4) — This project focuses on debugging a non-compilable Java program. The objective was to identify, analyze, and comment out lines that cause compilation errors or violate task constraints, ensuring the program runs without.
- [Task 03: Code Blocking & Shortcuts](https://github.com/YuriiJavaDev/JavaBasics_Task_3) — This project focuses on the use of single-line comments (//) to control code execution. The primary goal was to demonstrate how to block the execution of all commands in a Java program so that it produces no output, as per the task requirements.
---

## Console output
- [Task 02: Phrase Assembly with Console Output](https://github.com/YuriiJavaDev/JavaBasics_Task_2) — This project demonstrates the difference between System.out.print() and System.out.println() methods in Java. The goal is to assemble phrases from individual words by controlling the cursor position on the console, ensuring that words appear on the same line or move to a new one as required.
- [Task 01: Console Output Basics](https://github.com/YuriiJavaDev/JavaBasics_Task_1) — This is a foundational Java project designed to demonstrate basic console output operations. The goal of the task is to correctly use standard output streams to display mixed data types (integers and Unicode characters) on separate lines.
---

# 💾 Databases and Backend (Course 2)
- PostgreSQL integration (in progress).
- ...
- Multithreading and GitLab tasks (Petro).

# 🎨 Credits
- Social preview illustration found via open sources.
