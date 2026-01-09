# Virtual Employee Simulator 🧑‍💼💻

An Object-Oriented Programming (OOP) based workforce management and simulation system built using Java.  
This project models real-world employee behavior such as productivity, stress, skills, and energy through a dynamic, real-time simulation.

---

## 📌 Project Overview

The **Virtual Employee Simulator** is a console-based Java application designed as an academic OOP course project.  
It demonstrates how core object-oriented principles can be applied to simulate realistic employee workflows in a corporate environment.

Managers can create employees, perform actions like work, break, training, and rewards, while a background simulation thread dynamically updates employee attributes over time.

---

## ✨ Features

- Unique Employee ID generation
- Employee roles: **Developer, Tester, Designer**
- Dynamic attributes:
  - Productivity
  - Stress
  - Energy
  - Skill level
- Real-time simulation using **multithreading**
- Custom exception handling for invalid actions
- File handling using **serialization** (save & load employees)
- Modular package-based architecture

---

## 🧠 OOP Concepts Used

- **Inheritance** – Role-based employee hierarchy  
- **Polymorphism** – Runtime method overriding (`work()`)
- **Abstract Classes & Interfaces**
- **Custom Exceptions**
  - LowEnergyException
  - HighStressException
  - EmployeeNotFoundException
  - InvalidActionException
- **Multithreading** – Background simulation updates
- **Encapsulation & Modularity**
- **File Handling** – Object serialization

---

## 🏗️ Project Structure
