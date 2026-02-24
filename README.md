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
**How to Use the GUI#**

Enter gadget details (model, price, weight, size).
Add a Mobile using the Mobile credit field, or add an MP3 using the memory field.
Click Display All to view gadgets and their index numbers.
Use Display Number (Index) to select a gadget:
Make A Call works only with a Mobile index.
Download Music works only with an MP3 index.

---
**Testing Evidence (Screenshots)**

Screenshots for required tests are stored in the screenshots/ folder:
Add a Mobile
Add an MP3
Display all gadgets
Make a call
Download music
Compile + run in Command Prompt
Invalid display number dialog boxes (non-integer and out of range)
Use Clear to reset all fields.

---
