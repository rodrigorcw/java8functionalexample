# 🛍️ Java 8 Functional Product Filter

A simple Java 8 console application that demonstrates **functional programming** concepts like:

- Lambda Expressions
- Streams API
- Functional Interfaces
- Optional

This app loads a list of products, filters them by category and price, and prints the results in a clean and sorted way.

---

## 📦 Features

- Filter products by category and minimum price
- Sort products by price
- Find the first product over a given price using `Optional`
- Fully written using Java 8 functional style

---

## 📁 Project Structure

src/ ├── Product.java └── ProductFilterService.java


---

## ▶️ How to Run

1. **Clone the repository** or copy the files into your IDE.
2. Compile and run `ProductFilterService.java`.

### Example (if using terminal):

```bash
javac Product.java ProductFilterService.java
java ProductFilterService

💡 Sample Output
Filtered Products:
Chair (Furniture) - $150.0
Desk (Furniture) - $300.0

Expensive product found: Laptop (Electronics) - $1200.0

🧠 Concepts Used
List.stream()

filter, map, sorted, collect

Method references (String::toUpperCase, Product::getPrice)

Optional.ifPresent

✅ Requirements
Java 8+

🚀 Future Ideas
Add user input (Scanner)

Load products from a JSON or CSV file

Convert into a Spring Boot REST API


