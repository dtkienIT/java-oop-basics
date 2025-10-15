# Java OOP Practice – Book Management

A simple Java project to practice basic Object-Oriented Programming (OOP) concepts including **class creation**, **encapsulation**, **instances**, and **user input handling**.

---

## 📘 Project Description

This project demonstrates how to:

- Create a Java class with private attributes and public getter/setter methods.
- Use encapsulation to protect class members.
- Create and manage multiple instances of a class.
- Accept user input using the `Scanner` class.
- Display object data in a readable format using the `toString()` method.

---

## 🧩 Classes Overview

### **Book.java**

Defines the `Book` class with attributes:

- `title` – book title
- `author` – book author
- `price` – book price

Includes:

- Setter and getter methods for all attributes
- A custom `toString()` method to format the output

### **BooksMenu.java**

Main class that:

- Uses a menu to allow users to **add** or **view** books
- Stores up to **10 books** in an array
- Reads input from the console

---

## ⚙️ Environment Setup

To run this project, make sure your computer has **Java Development Kit (JDK)** installed.

### **1️⃣ Check if Java is installed**

Open your terminal or command prompt and type:

```bash
java -version
```

If you see output like:

```bash
java version "18.0.2" (or any version number)
```

then Java is already installed.

If not, continue below.

### **2️⃣ Install Java (if not installed)**

🔹 For Windows:

1. Go to the [Oracle Java Downloads webpage](https://www.oracle.com/java/technologies/downloads/?er=221886)

2. Download and install the latest Java SE Development Kit (JDK).

3. During installation, check the option to “Set JAVA_HOME variable”.

4. Restart your terminal.

### **3️⃣ Verify installation**

```bash
javac -version
```

If you see a version number (e.g. javac 18.0.2), your environment is ready.

---

## 💻 How to Run

1. **Clone** the repository:
   ```bash
   git clone https://github.com/dtkienIT/java-oop-basics.git
   ```
2. Compile the Java files

```bash
  javac Book.java BooksMenu.java
```

3.  Run the program

```bash
java BooksMenu
```
## 🧠 Example Output
```bash
Press 1 to view books, 2 to add books, any other key to exit
2
Enter book title
The Great Gatsby
Enter book author
F. Scott Fitzgerald
Enter book price
15.99

Press 1 to view books, 2 to add books, any other key to exit
1
Title - The Great Gatsby
Author - F. Scott Fitzgerald
Price - 15.99

```