## **Hello World (Plain Java + Maven) – Theoretical Explanation**

### **1. Purpose**
A *Hello World* program using **Plain Java with Maven** demonstrates how:
- A basic Java application is structured
- Maven manages the **project lifecycle**
- Java code is **compiled, packaged, and executed**

This setup is commonly used for **real-world Java projects**.

---

### **2. What Is Plain Java?**
- Plain Java refers to a **basic Java application** without frameworks like Spring.
- It contains:
    - A **class**
    - A **main() method**
- Execution starts from the `main()` method.

---

### **3. What Is Maven?**
**Maven** is a **build and dependency management tool** used in Java projects.

It helps in:
- Project structure standardization
- Dependency management
- Compilation
- Packaging
- Running tests

Maven uses a configuration file called **`pom.xml`**  
(POM = **Project Object Model**).

---

### **4. Standard Maven Project Structure**
Maven enforces a **standard directory layout**, which improves maintainability.

- `src/main/java` → Application source code
- `src/test/java` → Unit test code
- `pom.xml` → Maven configuration

This structure allows tools and IDEs to understand the project automatically.

---

### **5. Role of `pom.xml`**
The **`pom.xml`** file defines:
- Project coordinates (**groupId, artifactId, version**)
- Packaging type (JAR/WAR)
- Java version for compilation
- Plugins and dependencies (if required)

Maven reads this file to decide **how to build the project**.

---

### **6. Java Compilation Process with Maven**
1. Developer writes Java source code (`.java`)
2. Maven invokes the **Java Compiler (javac)**
3. Source code is converted into **Bytecode (`.class`)**
4. Bytecode is packaged into a **JAR file**

This process ensures **consistent builds across environments**.

---

### **7. Execution Flow**
- The **JVM** loads the compiled classes from the JAR
- The **main() method** is called
- The program executes line by line
- Output is printed to the console using `System.out.println()`

---

### **8. Why Use Maven for Hello World?**
Using Maven even for a simple program helps you:
- Learn **enterprise-grade project setup**
- Follow **industry standards**
- Scale easily to larger applications
- Manage dependencies with minimal effort

---

### **9. Output**
When executed successfully, the program prints:



---

### **10. Key Takeaway**
- **Plain Java** → Core programming logic
- **Maven** → Build lifecycle & dependency management
- **Hello World** → Foundation for larger Java applications

This approach is widely used in **enterprise and production environments**.
