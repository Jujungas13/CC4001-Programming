# CS4001 Coursework 1 – Gadget Shop (Java)

This repository contains my CS4001 Coursework 1 Java project: a simple **Gadget Shop** application. 
It demonstrates object-oriented programming using **inheritance** and **encapsulation** with three classes: `Gadget`, `Mobile`, and `MP3`. 
A Java Swing GUI (`GadgetShop`) allows the user to add gadgets to an `ArrayList`, display all stored gadgets with index numbers, make calls on Mobile devices (credit decreases by call duration), and download music to MP3 devices (memory decreases by download size). 
The program includes input validation and dialog messages for invalid display numbers and incorrect inputs.

---

## Files Included
- `Gadget.java` – Base class (model, price, weight, size)
- `Mobile.java` – Extends `Gadget` (credit, add credit, make call)
- `MP3.java` – Extends `Gadget` (memory, download music, delete music)
- `GadgetShop.java` – Swing GUI + button handling + main method

---

## How to Compile and Run (Command Prompt)
javac Gadget.java Mobile.java MP3.java GadgetShop.java
java GadgetShop

---
