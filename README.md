# Library-Management-System
A console-based Library Management System in C++ designed to manage books, members, and borrowing records seamlessly using Object-Oriented Programming (OOP) principles.

## 🚀 Features

* **Inventory Management:** Effortlessly add and track books with unique IDs, titles, and authors.
* **Member Registry:** Maintain a clean directory of members with automated borrowing record assignments.
* **Transaction Engine:** Seamlessly issue and return books while keeping real-time tracking of book availability and user balances.
* **Smart Search Indexing:** Run partial-match, case-insensitive lookups by either book **Title** or **Author** (e.g., searching "row" matches "J.K. Rowling").
* **Formatted Grid View:** View full catalogs laid out in clean, aligned, professional plain-text terminal tables.


## 🛠️ Technical Highlights

* **Object-Oriented Programming (OOP):** Modeled with clean data separation across isolated, domain-specific `Book` and `Member` classes.
* **Dynamic Record Linking:** Rather than managing messy nested objects, member cards track borrowed materials dynamically via custom vectors containing mapped `BookIDs`.
* **Case-Insensitive String Processing:** Implements algorithmic string conversions via `std::transform` to maximize user search flexibility.
