# Java OOP Practice – Book Management

A simple Java project to practice basic Object-Oriented Programming (OOP) concepts including **class creation**, **encapsulation**, **instances**, and **user input handling**.

---

## 📘 Project Description

This project demonstrates how to:

- Create a Java class with constructor, private attributes and public getter/setter methods.
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
- Two constructors:
  - A **default constructor** that initializes `title` and `author` to `null`
  - An **overloaded constructor** that sets all attributes (`title`, `author`, `price`)
- Setter and getter methods for all attributes  
- A custom `toString()` method to display book details in a formatted way  

---

### **BooksMenu.java**

Main class that provides an interactive console menu to:

- **View all books** currently stored  
- **Add new books**, with an option to choose between the **default** or **overloaded** constructor  
- **Compare the prices** of two books and display the more expensive one  
- Store up to **10 books** in an array  
- Handle all user input via the `Scanner` class  


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
Press 1 to view books, 2 to add books, 3 to compare prices of books, any other key to exit
2
Which constructor do you want to use? Press 1 for default,any other key for overloaded constructor
1
Enter book title
Gone with the wind
Enter book author
Margaret Mitchell
Enter book price
45
Press 1 to view books, 2 to add books, 3 to compare prices of books, any other key to exit
2
Which constructor do you want to use? Press 1 for default,any other key for overloaded constructor
2
Enter book title
Inner Excellence
Enter book author
Kim Murphy
Enter book price
12
Press 1 to view books, 2 to add books, 3 to compare prices of books, any other key to exit
1
Title - Gone with the wind
Author - Margaret Mitchell
Price - 45.00
Title - Inner Excellence
Author - Kim Murphy
Price - 12.00
Press 1 to view books, 2 to add books, 3 to compare prices of books, any other key to exit

```