# Swift Collections & Control Flow Practical Exercises

This repository contains solutions for practical exercises focused on core Swift programming concepts, including ordered and unordered collections, key-value mappings, conditional statements, ranges, loops, and data aggregation.

## 📌 Topics Covered

* **Arrays**: Index-based collections, array operations (`append`, `insert`, `remove`), properties (`count`, `isEmpty`, `first`, `last`), and common methods (`max`, `min`, `reduce`, `sorted`).

* **Sets**: Unordered unique collections and fundamental set algebra (`union`, `intersection`, `subtracting`, `symmetricDifference`).

* **Dictionaries**: Key-value pairs, optional lookups, nil-coalescing (`??`), and optional binding (`if let`).

* **Control Flow**: Decision-making via `if / else if / else` and matching patterns with `switch` statements and ranges (`...`, `..<`).

* **Loops**: Iterating using `for-in`, `enumerated()`, `while`, and `repeat-while`, along with loop control keywords (`break`, `continue`).

## 🚀 Activities Included

### Exercise 01 – Arrays (Module Management)

* Store a collection of study modules.

* Manipulate array entries and inspect first, last, and total counts.

* Search for a specific module ID (`SE4041`) using `.contains()`.

### Exercise 02 – Sets (Student Enrollment)

* Maintain unique student lists for `mobileDevelopmentStudents` and `gameTechnologyStudents`.

* Perform set operations to analyze overlap, combined participation, and exclusive enrollment.

### Exercise 03 – Dictionaries (Phone Book)

* Map contact names to phone numbers.

* Add, update, and safely retrieve contact details using Swift's optional binding (`if let`).

### Exercise 04 – Conditional Logic (Attendance Monitoring)

* Evaluate attendance percentages to classify performance (`Excellent`, `Good`, `Acceptable`, or `Low`).

### Exercise 05 – Switch & Ranges (Temperature Classification)

* Categorize numerical temperatures into states (`Freezing`, `Cold`, `Moderate`, `Warm`, `Hot`) using closed and half-open ranges inside `switch` blocks.

### Exercise 06 – Loops & Control Flow (Mark Processing)

* Iterate through numerical marks while filtering invalid entries (`continue`) and terminating execution upon encountering specific conditions (`break`).

## 📊 Comprehensive Final Task: Student Grade System

The practical culminates in an integrated grade evaluation program that connects all concepts:

1. **Dictionary Iteration**: Traverses student mark mappings (`Name -> Mark`).

2. **Grade Mapping**: Translates raw numerical marks into letter grades (`A`, `B+`, `B`, `C`, `F`, etc.) using switch ranges.

3. **Data Filtering**: Collects passing students into a dynamic array.

4. **Unique Metrics**: Tracks distinct letter grades issued using a `Set`.

5. **Class Statistics**:

   * Calculates the average mark.

   * Extracts highest and lowest scores using `.max()` and `.min()`.

## 🛠️ How to Run

1. Clone or download this repository.

2. Open any `.swift` file in **Xcode** or **VS Code** with Swift extensions installed.

3. Alternatively, run the scripts directly from your terminal:

```
swift Exercise01.swift
https://swiftfiddle.com/swhimstb6ncs3nis5j3aa3q4dm

https://swiftfiddle.com/g6clju37xrdmjmh3hs47ntj3ce

https://swiftfiddle.com/dfow3ktao5dutc375bvufkqoua
https://swiftfiddle.com/lut6zyymhbdvllorxge2yg775m
```