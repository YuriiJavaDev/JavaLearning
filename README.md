# 🎓 Java Learning

Welcome! This is the main navigator for my educational projects.

# 📁 JavaBasics
## Throws exceptions.
- [Task 177 System Log Analyzer V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_177_V0.1) — This project demonstrates the handling of `IOException` during file operations in Java. It simulates a log analysis utility that delegates the responsibility of handling input/output errors to the caller using the `throws` keyword.
- [Task 176 Secret Document Access V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_176_V0.1) — This project demonstrates the use of the `throws` keyword in Java to delegate exception handling. Instead of catching a `FileNotFoundException` locally, the method declares it in its signature, passing the responsibility of error management to the calling method.
---

## The finally `block` and the `throw` statement: Termination and exception throwing.
- [Task 175 User Registration Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_175_V0.1) — This project demonstrates the combined use of manual exception throwing and the `finally` block. It simulates a user registration system where the username must not be empty. The `finally` block is used to ensure that the validation status is reported regardless of whether the registration was successful or failed due to an exception.
- [Task 174 Critical Resource Manager V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_174_V0.1) — This project illustrates the behavior of the `finally` block when an exception occurs but is not caught by a `catch` block. It proves that the Java Virtual Machine guarantees the execution of the `finally` block before the program terminates due to a fatal error, which is essential for resource cleanup.
- [Task 173 Game Score Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_173_V0.1) — This project demonstrates how to manually throw exceptions in Java using the `throw` keyword. It ensures that game scores remain positive by triggering an `IllegalArgumentException` when an invalid value is processed.
- [Task 172 Cleaning Robot Manager V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_172_V0.1) — This project demonstrates the usage of the `finally` block in Java. In software development, certain actions (like closing a database connection or sending a final status report) must occur regardless of whether an error occurred. This simulation uses a cleaning robot to show how the `finally` block guarantees execution of completion messages.
---

## Try-catch syntax.
- [Task 171 Mission Control System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_171_V0.1) — This project demonstrates the resilience of a Java application when facing critical runtime errors. In a mission-critical system, an error like division by zero should not halt the entire process. By using a `try-catch` block, we ensure that the exception is handled gracefully, allowing the program to proceed to its final logical conclusion.
- [Task 170 Team Score Calculator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_170_V0.1) — This project focuses on retrieving detailed exception information in Java. When a system error results in an empty player list (`numberOfPlayers = 0`), dividing the total score by zero triggers an `ArithmeticException`. Instead of a generic message, this task demonstrates how to use the `e.getMessage()` method to obtain the exact technical reason for the failure as defined by the Java Virtual Machine.
- [Task 169 RPG Inventory System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_169_V0.1) — This project demonstrates the `ArrayIndexOutOfBoundsException` in Java. It simulates an RPG inventory where a player attempts to access an item slot that does not exist. This helps in understanding how to handle errors when working with fixed-size data structures like arrays.
- [Task 168 Smart Robot Explorer V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_168_V0.1) — This project demonstrates how to handle one of the most common runtime exception in Java: the `ArithmeticException`. It occurs when the application attempts to divide an integer by zero. This simulation helps understand how `try-catch` blocks ensure the reliability of software in unpredictable environments, such as a robot with failing sensors.
---

## Introduction to Exception Handling.
- [Task 167 Secret Agent Database V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_167_V0.1) — This project demonstrates one of the most common runtime errors in Java: the `NullPointerException`. It occurs when the application attempts to use an object reference that has not been initialized (contains `null`). This simulation helps understand why null-checks are essential in production code.
- [Task 166 Registration Input Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_166_V0.1) — This project simulates a common data-entry error where a user provides non-numeric text in a field expected to contain an integer (e.g., age). It focuses on Java's response to invalid format conversion through the `Integer.parseInt()` method.
- [Task 165 Gem Collector Inventory V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_165_V0.1) — This project explores how Java manages memory and array boundaries. In many programming languages, accessing an index outside an array's range might return garbage data, but Java's strict type safety and runtime checks prevent this by throwing a specific exception.
- [Task 164 Galactic Energy Divider V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_164_V0.1) — This project explores Java's behavior when encountering illegal mathematical operations. Specifically, it demonstrates what happens when an integer is divided by zero. This is a crucial lesson in exception handling and defensive programming for any Java developer.
---

## Advanced Switch Expressions.
- [Task 163 Student Grading System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_163_V0.1) — This project showcases the advanced capabilities of **Switch Expressions** introduced in Java 14. Specifically, it demonstrates how to group multiple constants within a single `case` label using a comma-separated list. This approach significantly simplifies the logic when several inputs should result in the same output.
- [Task 162 Modern Task Planner V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_162_V0.1) — This project demonstrates the transition from legacy `switch` statements to modern **Switch Expressions**. By using the arrow syntax, we reduce boilerplate code and ensure that each case returns a value directly to a variable, which is a key pattern in functional-style Java programming.
- [Task 161 Drone Control System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_161_V0.1) — This project demonstrates the use of **Switch Expressions** with `String` objects. It simulates a drone's command processing unit where incoming text commands are mapped to specific operational statuses. The modern arrow (`->`) syntax is used to ensure code conciseness and safety.
- [Task 160 HTTP Response Handler V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_160_V0.1) — This project demonstrates the use of the modern **Switch Expression** (introduced in Java 14). Unlike the traditional switch statement, the expression form is more concise, eliminates the risk of "fall-through" bugs by removing the need for `break`, and allows for direct variable assignment.
---

## Enumeration: enum.
- [Task 159 Celestial Navigation System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_159_V0.1) — This project simulates a spacecraft navigation module. It demonstrates the use of built-in Java `enum` methods to handle constant data. We explore how to retrieve the string name of a constant, its position (index) in the declaration list, and how to dynamically convert a string back into an enum constant.
- [Task 158 Weekday Iterator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_158_V0.1) — This project demonstrates how to retrieve and iterate through all constants defined in a Java `enum`. By using the built-in `values()` method, we can programmatically access the entire set of days in a week, which is a fundamental requirement for building task schedulers and calendar applications.
- [Task 157 Seasonal Message Generator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_157_V0.1) — This project demonstrates the synergy between Java `enum` types and the `switch` statement. By using an enum as the switch selector, we create a highly readable and type-safe branching logic that delivers personalized messages based on the current season.
- [Task 156 Traffic Signal State Model V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_156_V0.1) — This project demonstrates the use of Java `enum` to model a real-world system: a traffic light. Enums provide a type-safe way to represent a fixed set of constants, making the code more readable and preventing invalid values from being assigned to state variables.
---

## Classic Switch: Syntax and Examples.
- [Task 155 Smartwatch Calculator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_155_V0.1) — This project implements a lightweight calculator designed for a smartwatch interface. It processes two integer inputs and a mathematical operator, demonstrating how to use the `switch` statement with the `char` data type to branch logic based on symbols.
- [Task 154 Seasonal Activity Planner V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_154_V0.1) — This project demonstrates how to group multiple `case` statements in a `switch` block to execute the same logic for different inputs. The application identifies the season based on a numeric month input (1-12), showcasing efficient multi-condition handling.
- [Task 153 Robot Control Interface V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_153_V0.1) — This project demonstrates the application of the `switch` statement for string comparisons. It simulates a basic command-line interface for a robot, where specific text inputs trigger corresponding actions, showcasing how to handle multiple logical branches efficiently.
- [Task 152 Office Day Navigator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_152_V0.1) — This project demonstrates the use of the `switch` statement in Java. It serves as an efficient alternative to multiple `if-else-if` conditions when dealing with a single variable that can take several discrete values. The application maps numeric input to the corresponding day of the week.
---

## Type inference and constants in Java.
- [Task 151 Constant Protection Mechanism V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_151_V0.1) — This project demonstrates the strict enforcement of the `final` modifier in Java. By attempting to reassign a value to a constant, we observe how the Java compiler prevents modifications, ensuring that critical parameters like server capacity remain fixed.
- [Task 150 Global Constants and Static Access V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_150_V0.1) — This project demonstrates how to create a globally accessible constant in Java. By combining `public`, `static`, and `final` modifiers, we create a value that belongs to the class itself, remains immutable, and can be accessed from any other part of the application without instantiating the class.
- [Task 149 Constants in Java V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_149_V0.1) — This project demonstrates how to define immutable values in Java using the `final` modifier. By declaring a variable as `final`, we ensure that its value remains constant throughout the execution of the program, which is critical for system-wide parameters like calendar rules.
- [Task 148 Local Variable Type Inference V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_148_V0.1) — This project explores the `var` keyword introduced in Java 10. While it allows the compiler to infer the data type based on the assigned value, its use is a subject of debate regarding code clarity and long-term maintenance.
---

## Wrapper types in Java.
- [Task 147 Sensor Data NaN Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_147_V0.1) — An educational project focused on handling special floating-point values in Java. It demonstrates how to parse a "NaN" string into a double and verify it using built-in utility methods, which is crucial for processing telemetry and sensor data where invalid readings may occur.
- [Task 146 Price Wrapper Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_146_V0.1) — An educational project exploring the transition between primitive types and their corresponding wrapper classes. It focuses on Autoboxing and Unboxing, which are essential when working with Java Collections or APIs that require objects instead of primitives.
- [Task 145 Character Type Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_145_V0.1) — An educational project demonstrating character validation techniques in Java. It specifically focuses on identifying whether a given character belongs to the numeric digit category using the built-in utility methods of the Character wrapper class.
- [Task 144 Player Score Converter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_144_V0.1) — An educational project focused on parsing numerical data from strings. This is a common task when handling user input or reading data from text files where numeric values are initially represented as text.
---

## StringBuilder and StringBuffer.
- [Task 143 Advanced Text Editor V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_143_V0.1) — This project demonstrates professional-grade text editing using `StringBuilder`. It covers the removal of specific fragments and the replacement of key terms, showcasing how to modify content efficiently without reallocating memory for new string objects.
- [Task 142 Cryptographic Text Reverser V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_142_V0.1) — An educational project demonstrating the power of the `StringBuilder.reverse()` method. This tool is essential for tasks requiring character order inversion, such as palindrome checking or simple cryptographic decoding.
- [Task 141 Precision Text Inserter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_141_V0.1) — This project focuses on the mutable nature of `StringBuilder`, specifically utilizing the `insert()` method. This technique allows for adding content at any specific index within a string buffer, which is highly efficient for dynamic text generation like personalized chat-bot greetings.
- [Task 140 Dynamic String Builder V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_140_V0.1) — An educational project focused on efficient string manipulation using the `StringBuilder` class. This approach is highly optimized for scenarios where strings are built incrementally, preventing unnecessary memory allocation.
---

## String comparison: equals, equalsIgnoreCase, compareTo.
- [Task 139 Registration Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_139_V0.1) — This project simulates a registration validation system. It demonstrates how to verify if two email addresses are identical regardless of casing and how to check if a specific domain or keyword exists within a registration message.
- [Task 138 Lexicographical String Comparator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_138_V0.1) — An educational project that explores how Java compares strings alphabetically (lexicographically). By using the `compareTo()` method, we can determine the relative order of strings, which is essential for sorting algorithms and data organization.
- [Task 137 Case-Insensitive Comparison V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_137_V0.1) — An educational project demonstrating how to identify file types and extensions by analyzing string prefixes and suffixes. This technique is commonly used in file management systems and data processing pipelines.
- [Task 136 Case-Insensitive Comparison V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_136_V0.1) — A fundamental educational project demonstrating how to compare two strings in Java while ignoring their case (uppercase vs. lowercase). This is essential for creating user-friendly interfaces where "Admin" and "admin" should be treated as the same identity.
- [Task 135 Secure Login Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_135_V0.1) — An educational project demonstrating the difference between case-sensitive and case-insensitive string comparison in Java. This simulation mirrors real-world login procedures where emails are flexible but passwords are strict.
---

## Basic String methods.
- [Task 134 Product Filter System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_134_V0.1) — An educational project demonstrating conditional string processing. It checks if a product name meets specific criteria (starts with 'E') and generates a 3-character abbreviation if the condition is met.
- [Task 133 Dynamic String Surgeon V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_133_V0.1) — An advanced look at substring extraction. Instead of hardcoding indices, this project demonstrates how to programmatically find the start and end positions of a fragment, making the code resilient to changes in the source string.
- [Task 132 Substring Search Locator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_132_V0.1) — An educational project demonstrating how to find the position of a specific word within a string using the `indexOf()` method. This is a fundamental operation for search engines and text processing applications.
- [Task 131 Secret Character Extraction V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_131_V0.1) — An educational project focused on string manipulation. It demonstrates how to retrieve a specific character from a string using its index, highlighting that Java uses zero-based indexing.
---

## String formatting.
- [Task 130 Localized Result Formatter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_130_V0.1) — An educational project demonstrating how to handle internationalization (i18n) in Java. It specifically focuses on using `Locale` with `String.format()` to display decimal numbers according to regional standards (using a comma instead of a dot).
- [Task 129 Warehouse Inventory Reporter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_129_V0.1) — This project demonstrates advanced string formatting techniques in Java to create structured, table-like console output. It focuses on field width specification and text alignment for professional reporting.
- [Task 128 Financial Price Formatter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_128_V0.1) — An educational project focused on the precision of financial data display. It demonstrates how to use Java's formatting tools to round and display floating-point numbers with exactly two decimal places.
- [Task 127 User Dossier Formatter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_127_V0.1) — An educational project demonstrating the power of `String.format()` for creating uniform and readable data strings in Java. This approach is essential for administrative panels and reporting systems.
---

## Character escaping.
- [Task 126 Unicode Emoji Output V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_126_V0.1) — This project demonstrates how to output special characters and emojis using their exact Unicode sequences (`\uXXXX`). This ensures consistent rendering across different environments and systems.
- [Task 125 Formatted Slogan Output V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_125_V0.1) — An educational project focused on complex string formatting using escape sequences. It demonstrates how to include double quotes within a string and how to use tabs for visual alignment.
- [Task 124 Multi-line Text Output V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_124_V0.1) — An educational project demonstrating how to use the newline escape sequence (`\n`) to output multiple lines of text using a single output command, adhering to code conventions.
- [Task 123 Java Path Escaping Demo V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_123_V0.1) — A simple educational project illustrating how to handle backslashes in Java strings. Backslashes are special characters used for escaping, so to print a literal backslash, it must be escaped with another backslash.
---

## Access modifiers, variable scope.
- [Task 122 School Student Registry V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_122_V0.1) — This project illustrates the core OOP principle of **Encapsulation**. It demonstrates how to protect sensitive data using access modifiers while providing controlled ways to interact with it.
- [Task 121 Box Factory Management V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_121_V0.1) — This project demonstrates the use of the `this` keyword in Java to resolve naming conflicts between instance variables and method parameters. 
The implementation follows a strict decoupled architecture with meaningful class naming to ensure that each component's purpose is clear.
- [Task 120 Secure Bank Account Demo V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_120_V0.1) — This project demonstrates strict **encapsulation** — one of the core principles of object-oriented programming. The account balance is completely hidden from external code (private field). Any modification of the balance is possible **only** through a controlled public method.
- [Task 119 Football Village Registry System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_119_V0.1) — This project simulates an open village registry. It serves as a demonstration of **Public Field Access** within a professional N-Tier architecture. The system allows direct modification of a model's data while maintaining a strict pipeline for validation and formatting.
---

## Passing parameters by value and by reference.
- [Task 118 Football Magical Container Enchantment V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_118_V0.1) — This project demonstrates the nuances of Java's "Pass-by-Value" mechanism for object references. It proves that while a method can successfully modify the fields of a passed object, it cannot reassign the original caller's reference to a new object instance.
- [Task 117 Football Team Lineup Manager V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_117_V0.1) — This project simulates a real-time team`s lineup management tool for a football manager. It demonstrates the fundamental algorithm for swapping two values within an array reference, ensuring that positional changes made in the logic layer persist throughout the application's lifecycle.
- [Task 116 Bonus List Swap Experiment V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_116_V0.1) — This project explores Java's memory model, specifically focusing on how object references are passed to methods. It demonstrates that while method calls can modify the internal state of an object (like an array's elements), reassigning the reference itself inside the method has no effect on the original caller's reference.
- [Task 115 Robot Trajectory Reset V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_115_V0.1) — This project simulates a robot control system that manages movement trajectories. It specifically demonstrates how Java handles array references, allowing a method to permanently modify the state of an array defined in a different layer of the application.
---

## Return values.
- [Task 114 Student Grade Calculator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_114_V0.1) — This project simulates an automated teacher's assistant tool. It processes an array of exam results, calculates the total sum of grades using an iterative approach, and displays the result through a decoupled architectural pipeline.
- [Task 113 Sports Results Analyzer V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_113_V0.1) — This project implements a professional sports score analysis tool. It utilizes a layered architecture to determine the highest score among participants while maintaining strict separation between data entry, comparison logic, and output formatting.
- [Task 112 Quiz Show Application V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_112_V0.1) — This project demonstrates a strict unidirectional data pipeline. It ensures absolute separation of concerns: the data layer only provides data, the logic layer only performs calculations, and the formatting layer only manages visual appearance.
- [Task 111 AI Assistant Greeting V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_111_V0.1) — This project implements the core logic for an intelligent assistant's personalized greeting feature. It focuses on the effective use of return values to transfer processed data between architectural layers, allowing for flexible message handling.
---

## Declaration and invocation of methods, parameters.
- [Task 110 Shape Designer Tool V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_110_V0.1) — This project provides a professional tool for engineers and designers to quickly verify rectangular object parameters. It demonstrates the reuse of static methods with different arguments and showcases clean architectural separation into specialized packages.
- [Task 109 HR Profile Manager V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_109_V0.1) — This project simulates an automated system for managing employee records in an HR department. It demonstrates advanced code organization by separating responsibilities into different packages and classes, following the Single Responsibility Principle.
- [Task 108 Store Cashier Automation V0.1 V0.2](https://github.com/YuriiJavaDev/JavaBasics_Task_108_V0.1_V0.2) — This project demonstrates two evolutionary steps of a store cashier automation system. Version 1 provides a quick, direct calculation, while Version 2 introduces functional decomposition by separating data calculation from the presentation layer.
- [Task 107 Personal Greeter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_107_V0.1) — This project simulates a personal greeting feature for an interactive application. It focuses on creating a specialized function that addresses users by their name, demonstrating how to implement static methods with parameters to enhance user interaction.
---

## Array of counters and totalizers.
- [Task 106 Random Number Distribution V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_106_V0.1) — This project simulates a statistical analysis of a random number generator. It generates 50 integers in the range of 1 to 10 and calculates how many times each specific digit appears. This demonstrates the use of frequency arrays to visualize data distribution and probability patterns.
- [Task 105 Student Grade Analysis System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_105_V0.1) — This project simulates an academic grading system that processes scores across four different subjects for a group of students. It calculates the aggregate score for each individual and identifies the top performer using search algorithms, providing a clear and readable statistical report.
- [Task 104 Number Classification System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_104_V0.1) — This project implements a numerical analysis tool that classifies integers into three categories: positive, negative, and zero. It processes a raw data sequence and generates a statistical summary using a mapped integer array, demonstrating basic data filtering and aggregation techniques.
- [Task 103 Customer Purchase Aggregator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_103_V0.1) — This project automates the calculation of total expenditures for a group of 4 clients. It processes a complex 2D data structure representing daily transactions and aggregates them into a consolidated report. This simulation mirrors real-world billing systems where multiple entries must be summed per user account.
- [Task 102 Letter Frequency Counter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_102_V0.1) — This project implements a frequency analysis tool for a specific set of characters ('a', 'b', 'c'). It processes a character array and uses a separate integer array to track how many times each character appears, demonstrating efficient data categorization logic.
---

## Arrays class: sort, fill, copyOf, equals.
- [Task 101 Game Security Access Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_101_V0.1) — This project simulates a security validation system for a gaming environment. It compares two separate integer sequences (main and backup access codes) to ensure they are perfectly identical. The implementation highlights the importance of deep equality checks in Java to verify array contents rather than memory addresses.
- [Task 100 Meteorological Data Extraction V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_100_V0.1) — This project simulates a weather station data processing unit. It handles a sequence of daily temperature readings and extracts a specific "mid-day" subset for reporting purposes. The implementation demonstrates how to isolate data ranges within arrays efficiently using standard Java utility methods.
- [Task 99 Warehouse Management System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_99_V0.1) — This project simulates the initialization of a warehouse storage grid. Instead of manual entry, it uses automated batch processing to set the initial state of all storage cells to "Empty". This ensures that the system starts with a clean and verified configuration before any inventory is added.
- [Task 98 Athletic Race Results V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_98_V0.1) — This project automates the organization of athletic competition results. It takes raw timing data from participants and sorts them from the fastest (lowest number) to the slowest (highest number) using Java's standard utility methods, ensuring official results are presented in a clear, ascending sequence.
---

## Two-dimensional arrays.
- [Task 97 Environmental Sensor Grid V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_97_V0.1) — This project simulates an ecological monitoring system. It organizes sensor readings into a $2 \times 5$ matrix and implements a specific formatting logic to present the data as a clean, readable table. The primary technical focus is on managing whitespace and line breaks during 2D array traversal.
- [Task 96 Warehouse Inventory Automation V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_96_V0.1) — This project automates the population of an inventory grid for a warehouse system. It utilizes nested `for` loops to iterate through a 3x4 matrix, filling it with sequential numbers from 1 to 12. It also includes a visualization module to display the resulting grid in the console.
- [Task 95 Digital Billboard Grid V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_95_V0.1) — This project simulates a digital information board represented by a 3x2 grid. The objective is to place a specific message in the final panel (bottom-right corner) and verify its coordinates by rendering the entire grid structure to the console.
- [Task 94 Theater Seating System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_94_V0.1) — This project simulates a seat-numbering system for a small theater hall with 2 rows and 3 seats per row. It introduces the concept of two-dimensional arrays, where data is organized into rows and columns, requiring two indices for access.
---

## Basic operations with one-dimensional arrays.
- [Task 93 Edge-to-Center Palindrome Check V0.2](https://github.com/YuriiJavaDev/JavaBasics_Task_93_V0.2) — This project implements the "Two Pointers" algorithm to verify if a character array is a palindrome. It avoids creating additional memory structures by comparing elements from the start and end of the array, progressively moving toward the center.
- [Task 93 Palindrome Checker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_93_V0.1) — This project implements a palindrome check for character arrays. A palindrome is a sequence that reads the same forwards and backwards. This specific task demonstrates the **Array Reversal and Comparison** strategy.
- [Task 92 Array Fill Demonstration V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_92_V0.1) — This project demonstrates the process of initializing an array and populating all its elements with a single constant value. It highlights the efficiency of using loops for bulk data assignment compared to manual entry.
- [Task 91 Smart Home Temperature Analysis V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_91_V0.1) — This project simulates a data processing module for a "Smart Home" system. It implements an algorithm to find the maximum value within a set of temperature readings. This pattern is fundamental for monitoring peak loads, overheating, or any threshold-based alerts.
- [Task 90 Shopping Cart Calculator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_90_V0.1) — This project simulates a basic checkout system for an online store. It focuses on initializing an array with predefined item prices and performing a mathematical summation of its contents to determine the total cost. 
- [Task 89 Movie Reverser V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_89_V0.1) — This project demonstrates how to collect user-provided strings into an array and retrieve them in reverse order. It highlights the use of the `Scanner` class for interactive input and the logic of accessing array elements from the highest index down to the lowest.
- [Task 88 Galactic Defender Leaderboard V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_88_V0.1) — This project simulates a high score table for the "Galactic Defender" game. It focuses on **Array Literals**, a concise way to initialize and populate an array simultaneously, and demonstrates how to output data line-by-line for a leaderboard format.
---

## Introduction to Arrays.
- [Task 87 Quarterly Array Mapping V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_87_V0.1) — This project explores advanced indexing techniques by dividing a 120-element array into four logical checkpoints. It demonstrates how to perform arithmetic operations using values stored at specific calculated offsets within the array structure.
- [Task 86 Array Tail Operations V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_86_V0.1) — This project focuses on manipulating elements at the end of a large array using dynamic indexing. It demonstrates how to reference positions relative to the array length ($n-1$, $n-2$, etc.) and perform arithmetic operations between these elements. 
- [Task 85 Array Boundaries & Midpoint V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_85_V0.1) — This project focuses on accessing specific strategic points within an array: the beginning, the end, and the mathematical middle. It demonstrates how to use the array size variable $n$ to calculate indices dynamically, which is essential for algorithms like binary search.
- [Task 84 Array Basics V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_84_V0.1) — This project introduces the fundamental concepts of arrays in Java. It demonstrates how to allocate memory for a fixed-size collection, assign values to specific positions using indices, and retrieve data from the start and end of the array.
- [Task 83 Tournament Scoreboard V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_83_V0.1) — This project simulates a tournament management system where scores are pre-calculated for each round. It focuses on using a `for` loop to automate data entry (sequential numbers 1 through 10) and simultaneous data display, mimicking a real-time scoreboard.
- [Task 82 Weather Station Update Languages List V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_82_V0.1) — This project simulates a weather station data management system. It focuses on the default initialization of floating-point arrays and the precise manipulation of data at a specific index. The task reinforces the concept of zero-based indexing and manual array traversal.
- [Task 81 Fantasy Favorite Languages List V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_81_V0.1) — This project simulates a simple blog entry preparation where a list of favorite programming languages is stored in a fixed-size array. The primary focus is understanding how to retrieve the total capacity of an array using the built-in `length` property.
- [Task 80 Fantasy Inventory System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_80_V0.1) — This project simulates a basic inventory system for a fantasy game. It illustrates the fundamental concepts of array declaration, memory allocation for a specific capacity, and the use of zero-based indexing to store and retrieve data.
---

## Explicit and Implicit Type Casting in Java.
- [Task 79 Academic Performance V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_79_V0.1) — This project focuses on calculating a student's **average score** from mixed numeric sources. It demonstrates how to maintain precision during division by using `double` literals and how to truncate the final result for administrative reporting. 
- [Task 78 Weather Sensor V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_78_V0.1) — This project simulates a data overflow scenario in a legacy weather sensor. It investigates the behavior of **narrowing primitive conversion** when an `int` value exceeds the 8-bit capacity of a `byte`, leading to unexpected results due to bit truncation and the two's complement representation.
- [Task 77 Spy Cryptography V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_77_V0.1) — This project simulates a cryptographic mission where characters are encoded into numbers and decoded back. It demonstrates the internal representation of the **char** data type in Java as a 16-bit Unicode integer and explores both implicit (automatic) and explicit type casting.
- [Task 76 Warehouse Inventory V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_76_V0.1) — This project simulates a warehouse calculation where raw material weight must be converted into a count of finished goods. It highlights the use of **explicit type casting** in Java to perform truncation, effectively discarding fractional data to find the number of whole units available.
---

## Rounding and formatting numbers.
- [Task 75 Global Sales Reporting V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_75_V0.1) — This project simulates the reporting system of a global corporate leader. It focuses on presenting massive financial figures in a human-readable format by utilizing the **DecimalFormat** grouping separator to distinguish thousands and maintain precise decimal alignment. 
- [Task 74 Financial Report V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_74_V0.1) — This project simulates the preparation of a quarterly financial report for investors. It demonstrates how to use the **DecimalFormat** class in Java to maintain a consistent professional appearance by ensuring all monetary values are displayed with exactly two decimal places.
- [Task 73 Magic Shop V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_73_V0.1) — This project simulates a currency formatting system for a magical shop. It highlights a common task in software development: rounding a `double` value to exactly two decimal places for financial displays using the **scaling and rounding** technique.
- [Task 72 Laser Calibration V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_72_V0.1) — This project simulates resource management for space colonization. It focuses on converting high-precision engineering estimates into actionable logistics data by using the **Math.round** method to determine the nearest whole number of materials needed.
---

## Accuracy issues and special values.
- [Task 71 Laser Calibration V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_71_V0.1) — This project simulates the calibration process of a high-precision laser system. It demonstrates a critical engineering practice in software development: using a **tolerance (epsilon)** to compare floating-point values, ensuring that minor numerical fluctuations do not cause logic errors.
- [Task 70 Mystic Numbers V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_70_V0.1) — This project simulates an exploration into undefined mathematical territories. It demonstrates how Java's `double` type handles operations that do not result in a real number, specifically the square root of a negative value, resulting in the **NaN** (Not a Number) constant.
- [Task 69 Cosmic Boundary V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_69_V0.1) — This project simulates an exploration into the limits of numerical calculations. It investigates how Java's `double` type handles division by zero, representing states like **Infinity** that exist beyond standard arithmetic results.
- [Task 68 Chemical Experiment V0.1 V0.2 V0.3](https://github.com/YuriiJavaDev/JavaBasics_Task_68_V0.1) — This project simulates a laboratory experiment in which a scientist mixes two precisely measured components (0.1 and 0.2) to achieve a target concentration of 0.3. It demonstrates the inherent precision issues of the double data type when performing floating-point operations in Java and offers a professional solution, as well as a creative hack for simple calculations.
---

## Introduction to Fractional Numbers and the Double Type.
- [Task 67 Magic Apples V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_67_V0.1) — This project simulates the distribution of magical items where fractional parts are required. It highlights a common pitfall in Java: **integer division**, and demonstrates how to use **type casting** to obtain a precise `double` result from `int` operands.
- [Task 66 Price Formatter V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_66_V0.1) — This project demonstrates the critical difference between **visual formatting** and **mathematical rounding**. It ensures financial integrity by synchronizing the stored variable value with the displayed price, preventing discrepancies between customer receipts and internal accounting records.
- [Task 65 Vending Machine V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_65_V0.1) — This project simulates the payment processing unit of a smart vending machine. It introduces interactive user input using the **Scanner** class, allowing the system to capture real-time payment data in a floating-point format.
- [Task 64 Space Navigation V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_64_V0.1) — This project simulates a navigation calculation for a spacecraft. It demonstrates how to perform division using the **double** data type to ensure high precision in mission-critical calculations.
--- 

## Numbers and Symbols in Java.
- [Task 63 Cyrillic Rune V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_63_V0.1) — This project concludes the series of character studies by exploring a Cyrillic symbol. It demonstrates that Java's **char** type natively supports a wide range of global characters through the Unicode standard.
- [Task 62 Rune Decryptor V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_62_V0.1) — This project simulates the decryption of an ancient rune. It focuses on the relationship between the **char** data type and its underlying **ASCII** numeric representation, demonstrating how Java handles character encoding.
- [Task 61 Dragon Hoard V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_61_V0.1) — This project focuses on handling numeric data that exceeds the 32-bit limit of the standard `int` type. It demonstrates how to correctly declare a 64-bit **long** variable for massive values, such as a dragon's hoard, using underscores for readability and the mandatory suffix.
- [Task 60 Hero Inventory V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_60_V0.1) — This project simulates the creation of a base inventory for an RPG (Role-Playing Game) hero. It demonstrates how to choose and declare appropriate **numeric primitive types** in Java based on the nature and range of the data being stored.
---

## The "do-while" loop: introduction and nuances of work.
- [Task 56 Daily Sales Tracker V1.1](https://github.com/YuriiJavaDev/JavaBasics_Task_56_V1.1) — An enhanced version of the sales tracking utility. This iteration introduces advanced flow control using an infinite loop (`while(true)`), demonstrating how to selectively process data using `continue` to skip insignificant entries (zeros) and `break` to terminate the sequence.
- [Task 56 Daily Sales Tracker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_56_V0.1) — This application simulates a point-of-sale system that records daily transactions. It aggregates multiple sales entries into a single total. The program utilizes a sentinel-controlled loop where a negative value serves as the termination signal for the workday.
- [Task 55 Password Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_55_V0.1) — This project simulates a secure registration form component. It focuses on string validation using a **Do-While Loop**, ensuring that the user provides a password that meets specific security requirements (minimum length of 6 characters).
- [Task 54 Console Menu V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_54_V0.1) — This project implements a basic interactive command-line menu using a **Do-While Loop**. It allows users to perform specific actions (like printing a greeting) repeatedly without restarting the application. The program maintains an active state until the user explicitly chooses to exit. 
- [Task 53 ATM PIN Validator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_53_V0.1) — This project simulates an ATM user interface for PIN-code validation. It utilizes the **Do-While Loop** to repeatedly request input from the user until a valid **four-digit positive integer** (between 1000 and 9999) is provided.
- [Task 52 Game Bootstrapper V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_52_V0.1) — This project demonstrates the unique behavior of the **Do-While Loop** in Java. Unlike a standard `while` loop, the `do-while` structure ensures that the code block is executed **at least once** because the exit condition is checked only after the iteration is complete.
---

## The "for" loop: introduction and nuances of work.
🧩 **Nested for-loops: working with 2D grids.**
- [Task 59 Password Finder V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_59_V0.1) — This project simulates a brute-force search for a "perfect password" consisting of two numbers. It employs **nested for-loops** to iterate through possible combinations and utilizes an early exit strategy once the target condition (sum equals 13) is met.
- [Task 58 Asteroid Field Visualization V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_58_V0.1) — This program simulates a space shuttle's radar view of an asteroid field. It uses **nested for-loops** to generate a precise 5x7 grid of star symbols (⭐). The project demonstrates basic 2-dimensional rendering in a console environment.
- [Task 57 Radar Coordinate System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_57_V0.1) — This project simulates a radar scanning grid by generating a 3x4 coordinate table. It utilizes **nested for-loops** to iterate through rows (i) and columns (j), outputting the precise position of each cell in an `i,j` format.

🧩 **Single-level Iterations: flow control and sequence management.**
- [Task 51 Coordinate Tracker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_51_V0.1) — This project simulates the tracking of two objects moving in opposite directions. It utilizes an advanced **For Loop** structure where two variables are initialized, updated, and evaluated simultaneously within a single loop header.
- [Task 50 Product Cost Calculator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_50_V0.1) — This project implements a calculation engine for a dynamic pricing model. In this scenario, the price of an item is directly proportional to its position in the sequence (e.g., the 1st item costs 1, the 2nd costs 2, etc.). It utilizes a **For Loop** to aggregate the total cost for a set number of products (N).
- [Task 49 Train Seating V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_49_V0.1) — This project simulates the identification of even-numbered seats in a train carriage. It utilizes a **For Loop** to iterate through a range of numbers (0 to 10) and incorporates an **If Statement** with the **Modulo Operator (%)** to filter and display only even values.
- [Task 48 New Year Countdown V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_48_V0.1) — This project simulates a festive New Year's Eve countdown. It utilizes a **For Loop** to iterate backwards from 5 to 1, demonstrating precise control over loop initialization, termination conditions, and decrementing steps.
---

## The "while" loop: introduction and nuances of its operation.
- [Task 47 Coffee Expense Tracker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_47_V0.1) — This project implements a budget-tracking utility specifically for coffee expenses. It utilizes a **While Loop** to continuously collect user input for beverage costs. The sequence is terminated when a negative value is detected, acting as a sentinel signal.
- [Task 46 Cinema Seats V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_46_V0.1) — This project simulates the display of available seating in a cinema row. It utilizes a **While Loop** to iterate through seat numbers starting from 2, incrementing by 2, until reaching the limit of 10.
- [Task 45 Smartphone Unlock V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_45_V0.1) — This project simulates a smartphone security interface. It employs a **While Loop** integrated with the **Scanner class** to continuously prompt the user for a password until the predefined correct value ("java") is entered.
- [Task 44 Spaceship Launch V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_44_V0.1) — This project simulates a spaceship ignition sequence. It utilizes a **While Loop** to perform a controlled reverse countdown from a starting value to one, followed by a launch signal.
---

## Ternary operator in Java: concise conditions and nuances regarding Clean Code.
- [Task 43 Amusement Park Ticketing System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_43_V0.1) — This project implements a multi-tier age categorization logic for an amusement park. It utilizes **Nested Ternary Operators** to evaluate four distinct age groups within a single expression.
- [Task 42 Dynamic Greeting System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_42_V0.1) — This project implements a simple time-aware greeting mechanism. It utilizes the **Ternary Operator** to evaluate the current hour and select between two different greeting strings ("Good morning" or "Good day").
- [Task 41 Online Store Order Parity Checker V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_41_V0.1) — This project simulates a basic order sorting mechanism for an e-commerce platform. It utilizes the **Ternary Operator** to perform a parity check on order numbers, classifying them as either "Even" or "Odd".
- [Task 40 Sports Performance Analysis V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_40_V0.1) — This project simulates a sports timing system. It focuses on the **Ternary Operator**, a concise alternative to the standard `if-else` statement for simple value assignments based on a condition.
---

## Operator precedence and parentheses in conditions.
- [Task 39 Bank Loan Approval Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_39_V0.1) — This project simulates a banking decision system using two distinct sets of evaluation rules. It focuses on **Complex Logical Expressions** and the strategic use of parentheses to enforce specific business requirements using the same applicant data.
- [Task 38 Party Access Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_38_V0.1) — This project explores the **Associativity of Logical Operators**. It tests the admission logic for a private event by evaluating three mandatory conditions using the logical AND (`&&`) operator with different grouping strategies.
- [Task 37 Concert Ticket Purchase Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_37_V0.1) — This project analyzes the impact of **Operator Grouping** on logical expressions. It compares standard Java precedence rules with custom-defined logic using parentheses to determine concert ticket eligibility.
- [Task 36 Vacation Planner Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_36_V0.1) — This project simulates a vacation feasibility check. It focuses on the **Precedence of Logical Operators**, demonstrating how Java evaluates complex boolean expressions containing both `||` (OR) and `&&` (AND) without explicit parentheses.
---

## Boolean logical type and logical operations.
- [Task 35 Smart Thermostat Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_35_V0.1) — This project simulates the core logic of a smart thermostat. It focuses on **Range Validation**, using logical operators to check if a numeric value resides between defined inclusive boundaries (20°C to 25°C).
- [Task 34 Picnic Planner Logic V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_34_V0.1) — This project simulates a decision-making algorithm for weekend planning. It focuses on **Advanced Logical Operators** to evaluate multiple boolean conditions simultaneously.
- [Task 33 Football Match Result Recorder V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_33_V0.1) — This project simulates a basic sports scoring system. It demonstrates how to use **Relational Operators** to compare two numeric values and store the resulting truth value in a `boolean` variable.
- [Task 32 Boolean Fundamentals V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_32_V0.1) — This project introduces the **Boolean Primitive Type** in Java. It demonstrates how to store and display logical truth values, which serve as the foundation for conditional execution and decision-making in programming.
---

## Nested "if", multi-level logic.
- [Task 31 Loyalty Program Discount Calculator V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_31_V0.1) — This project simulates a loyalty program logic. It utilizes **Nested Conditional Logic** to calculate specific discount percentages based on user demographics (age) and membership status (club card).
- [Task 30 Conference Access Management V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_30_V0.1) — This project simulates a conference registration system. It utilizes **Complex Nested Conditionals** to perform high-level visitor filtering based on age and specialized invitation categories (VIP vs. GUEST).
- [Task 29 Exclusive Club Entry System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_29_V0.1) — This project simulates an entry control system for an exclusive club. It utilizes **Nested Conditional Logic** to validate a user's eligibility based on two factors: minimum age and specific residency (Prague).
- [Task 28 Secure Access System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_28_V0.1) — This project simulates a two-factor security gate. It utilizes **Nested Conditional Logic** to perform a hierarchical check of user credentials: age verification followed by a secret code validation.
---

## Conditional operator "if-else".
- [Task 27 Time-based Greeting System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_27_V0.1) — This project simulates an adaptive greeting system. It utilizes **Multi-Branch Conditional Logic** to analyze time-of-day data and return a context-specific greeting.
- [Task 26 Simple Login System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_26_V0.1) — This project simulates a basic security gate. It focuses on the **Single-Branch Conditional** structure (`if` without `else`) and introduces the concept of string value comparison.
- [Task 25 Clothing Advisor V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_25_V0.1) — This project simulates a simple weather assistant. It uses conditional branching to analyze temperature data and provide appropriate clothing recommendations.
- [Task 24 Cinema Access Control V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_24_V0.1) — This project simulates a cinema ticketing system. It introduces the fundamental concept of **Conditional Logic**, where the program executes different blocks of code based on a boolean condition (age verification).
---

## Keyboard input.
- [Task 23 Digital Business Card V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_23_V0.1) — This project simulates a digital business card generator. It focuses on handling mixed data types (String and int) and demonstrates professional string manipulation.
- [Task 22 Cashier System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_22_V0.1) — This project simulates a simple cashier terminal. It focuses on basic arithmetic operations and handling multiple integer inputs sequentially.
- [Task 21 Player Registration System V1.1](https://github.com/YuriiJavaDev/JavaBasics_Task_21_V1.1) — This project is a transitional milestone in Java learning journey. While the base task requires simple console input/output, this implementation elevates the solution into an **enterprise-ready architecture**.
- [Task 21 Player Registration System V0.2](https://github.com/YuriiJavaDev/JavaBasics_Task_21_V0.2) — This project represents the basic foundation of a Player Registration System. Added console queries for user input.
- [Task 21 Player Registration System V0.1](https://github.com/YuriiJavaDev/JavaBasics_Task_21_V0.1) — This project represents the basic foundation of a Player Registration System.
- [Task 20 Login System](https://github.com/YuriiJavaDev/JavaBasics_Task_20) — This project demonstrates how to handle user input in Java using the Scanner class to read and display a password from the keyboard.
---

## Conversion between data types.
- [Task 19 Game Score Calculator](https://github.com/YuriiJavaDev/JavaBasics_Task_19) — This project demonstrates how to parse string-based numeric data (including negative values) into integers and perform arithmetic operations on the resulting data.
- [Task 18 Movie Year Extractor](https://github.com/YuriiJavaDev/JavaBasics_Task_18) — This project demonstrates how to convert numeric data stored as a String into a primitive int type to enable mathematical operations.
- [Task 17 Flight Tracker](https://github.com/YuriiJavaDev/JavaBasics_Task_17) — This project demonstrates string concatenation in Java by combining numeric flight data with destination text to create a complete status message.
- [Task 16 Access Code Formatter](https://github.com/YuriiJavaDev/JavaBasics_Task_16) — This project demonstrates how to convert primitive numeric data types into string representations for data transmission or messaging purposes.
---

## Strings and text: String type, working with strings.
- [Task 15.1 Anagram Encoder V0.1](https://github.com/YuriiJavaDev/AnagramEncoder_V0.1) — An advanced continuation of string manipulation topics. This is project implements a complex algorithm to reverse only letters within words while preserving the exact positions of all non-letter characters. It demonstrates professional-grade coding with JUnit 5 testing, Maven lifecycle management, and efficient use of StringBuilder.
- [Task 15 String data cleaning and manipulation](https://github.com/YuriiJavaDev/JavaBasics_Task_15) — This project focuses on data normalization using the String class. It simulates a real-world scenario where user-provided data (like a city name) contains unnecessary spaces and needs to be formatted.
- [Task 14 Escaping a quote by Yurii Gagarin](https://github.com/YuriiJavaDev/JavaBasics_Task_14) — This project demonstrates the use of escaping characters in Java strings. It shows how to include special characters, such as double quotes, inside a String object literal without breaking the code structure.
- [Task 13 User Profile Creation](https://github.com/YuriiJavaDev/JavaBasics_Task_13) — This project demonstrates string concatenation in Java. It shows how to combine multiple object types (String) into a single output using the + operator.
- [Task 12 Message from the future](https://github.com/YuriiJavaDev/JavaBasics_Task_12) — This project focuses on the String class in Java. It demonstrates how to declare a variable of an object type, initialize it with a string literal containing a message "from the future", and print the stored character sequence to the console.
---

## Integers: int type, operations with int type. Determining the remainder after division "%". Increment and decrement.
- [Task 11 Hero Health Tracking](https://github.com/YuriiJavaDev/JavaBasics_Task_11) — This project simulates tracking a character's health in a game environment. It demonstrates the practical use of unary operators: increment (++) and decrement (--).
- [Task 10 Prize Distribution Logic](https://github.com/YuriiJavaDev/JavaBasics_Task_10) — This project demonstrates the use of integer division and the modulo operator (%) in Java. It simulates a scenario where a set number of prizes must be distributed equally among teams, and the remainder is calculated.
- [Task 09 Single-Line Variable Management](https://github.com/YuriiJavaDev/JavaBasics_Task_9) — This project demonstrates Java's ability to declare and initialize multiple variables of the same type in a single statement. While this approach increases compactness, it is explored here primarily for syntax understanding.
---

## Memory addressing and variables. How to declare a variable and assign a value to it.
- [Task 08 Bank Account Transactions](https://github.com/YuriiJavaDev/JavaBasics_Task_8) — This project simulates basic banking operations using integer variables. It demonstrates how to perform balance transfers between accounts and apply bonuses using fundamental arithmetic operations in Java.
- [Task 07 Memory Allocation & Concatenation](https://github.com/YuriiJavaDev/JavaBasics_Task_7) — This project focuses on understanding the memory footprint of different primitive data types in Java. It demonstrates how to combine descriptive text with actual variable values using string concatenation.
- [Task 06 String Manipulation & Immutability](https://github.com/YuriiJavaDev/JavaBasics_Task_6) — This project demonstrates how Java handles String variables and references. It explores the concept of object assignment and string immutability by creating a copy of a variable and modifying it independently.
- [Task 05 Game Character Profile](https://github.com/YuriiJavaDev/JavaBasics_Task_5) — This project demonstrates the use of various Java primitive and reference data types. The goal was to create a profile for a game character by storing different types of information (level, gold, rating, and name) and displaying them in the console.
---

## How to make comments in code.
- [Task 04 Compilation Error Analysis & Clean Code](https://github.com/YuriiJavaDev/JavaBasics_Task_4) — This project focuses on debugging a non-compilable Java program. The objective was to identify, analyze, and comment out lines that cause compilation errors or violate task constraints, ensuring the program runs without.
- [Task 03 Code Blocking & Shortcuts](https://github.com/YuriiJavaDev/JavaBasics_Task_3) — This project focuses on the use of single-line comments (//) to control code execution. The primary goal was to demonstrate how to block the execution of all commands in a Java program so that it produces no output, as per the task requirements.
---

## Console output
- [Task 02 Phrase Assembly with Console Output](https://github.com/YuriiJavaDev/JavaBasics_Task_2) — This project demonstrates the difference between System.out.print() and System.out.println() methods in Java. The goal is to assemble phrases from individual words by controlling the cursor position on the console, ensuring that words appear on the same line or move to a new one as required.
- [Task 01 Console Output Basics](https://github.com/YuriiJavaDev/JavaBasics_Task_1) — This is a foundational Java project designed to demonstrate basic console output operations. The goal of the task is to correctly use standard output streams to display mixed data types (integers and Unicode characters) on separate lines.
---

# 💾 Databases and Backend (Course 2)
- PostgreSQL integration (in progress).
- ...
- Multithreading and GitLab tasks (Petro).

# 🎨 Credits
- Social preview illustration found via open sources.
