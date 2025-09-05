# 🌐 Project Presentation: **Nano Framework**

## 📖 What is Nano Framework?
**Nano Framework** is an educational and practical project designed to help students understand how modern Java frameworks (like Spring) work internally by building one from scratch.  

The course is aimed at developers with Java basics who want to dive deeper into concepts such as **Inversion of Control (IoC)**, **Dependency Injection (DI)**, **Aspect-Oriented Programming (AOP)**, **Web request handling**, and **Object-Relational Mapping (ORM)**.  

Nano Framework is not intended to replace existing frameworks but to **expose the principles behind them**, guiding the student step by step in building a fully functional mini-framework.

---

## 🎯 Project Goal
- **Understand how Java frameworks work from the inside.**  
- **Learn advanced concepts** like Reflection, Class Loaders, Dynamic Proxies, Custom Annotations, and Dynamic SQL Query Generation.  
- **Build a real, modular, and extensible framework.**  
- **Apply what is learned in a parallel project (demo-app)** that uses the framework, validating each functionality in a real scenario.  

By the end, the student will have built a complete framework with support for:
1. **IoC and DI** (dependency management).
2. **Web request handling** with a Dispatcher Servlet.
3. **AOP** for cross-cutting concerns like logging and security.
4. **Basic ORM** for database persistence.
5. **Final application** integrating all modules in a real system.

---

## 🧩 Project Structure

The learning is organized into **two parallel projects**:

1. **nano-framework**  
   - Contains the framework source code.  
   - Expanded with each chapter: Reflection → IoC → Dispatcher Servlet → AOP → ORM.  
   - Packaged as a `.jar` at the end.

2. **nano-demo-app**  
   - An application that uses **nano-framework** as a dependency.  
   - Validates each framework module in real scenarios.  
   - Example: if a `JsonParser` is implemented in the framework, the demo-app uses it to serialize `User` objects.

---

## 📚 Chapter Breakdown

1. **Chapter 1: Introduction to Reflection**  
   - Reflection utilities.  
   - Custom annotations.  
   - Final exercise: a **JSON Parser** from scratch.

2. **Chapter 2: Building a Basic IoC Container**  
   - Class scanning with **Class Loaders**.  
   - Component registration.  
   - Dependency injection with `@Inject`.  
   - Final exercise: a functional **IoC container**.

3. **Chapter 3: Web Request Handling**  
   - Servlets and controllers.  
   - Converters, filters, validators.  
   - Final exercise: a **Dispatcher Servlet** like Spring MVC.

4. **Chapter 4: Aspect-Oriented Programming (AOP)**  
   - Dynamic proxies in Java.  
   - Interceptors and aspects (`@LogExecutionTime`, `@Secure`).  
   - Final exercise: a full **AOP system** integrated with IoC.

5. **Chapter 5: Basic ORM**  
   - Entity annotations (`@Entity`, `@Id`, `@Column`).  
   - Class-to-table mapping.  
   - Dynamic SQL generation (insert, select, delete).  
   - Final exercise: a working **mini-ORM**.

6. **Chapter 6: Final Application**  
   - A complete app integrating all modules.  
   - User and role management.  
   - Deployment on an embedded server.  
   - Final exercise: package the framework and run the demo-app.

---

## ⚙️ General Workflow

1. **Step-by-step build:**  
   Each chapter expands framework capabilities with new modules.

2. **Immediate testing:**  
   Each module is validated in real scenarios via the demo-app.

3. **Active learning:**  
   Students implement from scratch functionalities usually hidden inside frameworks like Spring.

4. **Final outcome:**  
   - A **custom framework**: `nano-framework` packaged as `.jar`.  
   - A **real application**: `nano-demo-app` using the framework.

---

## 🚀 Project Benefits
- Encourages **deep understanding** of advanced Java concepts.  
- Reinforces **SOLID** principles and modular design.  
- Explains how modern frameworks work **under the hood**.  
- Provides experience in **library creation** and **application development**.  

---

📁 **Documentation location:**  
Each chapter has its own `README-0X.md` in the repo root, detailing exercises, objectives, theory, and references.

---

👉 In summary: **Nano Framework is a hands-on journey to understand and build your own mini-Spring from scratch, validating each step with a real app.**
