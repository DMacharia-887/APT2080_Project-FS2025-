# APT2080_Project-FS2025-

This is Group's 4 Github Repo for the APT2080 FS2025 Class. <br>
Members:
1. Dennis Macharia 663843
2. Chris Ngure 669798
3. Abdiweli osman 668106
4. Mercy Musila 673821
5. Abdi Dakane 673007
6. Abdulhalim Mohamed Abeid 673465
7. Tamia Wambugu 674367

# 🧑‍💻 SOFTWARE ENGINEERING REPORT / PRESENTATION NOTES

## Project: Rock–Paper–Scissors Game in Python

---

## 1️⃣ SOFTWARE CONCEPT AND OVERVIEW

**What is the Project?**

The Rock–Paper–Scissors program is a small Python-based interactive game that allows a user to play against the computer.  
It was developed by applying the **Software Engineering Process**, following the main **Software Development Life Cycle (SDLC)** stages:

- Requirement Analysis
- System Design
- Coding and Implementation
- Testing
- Maintenance and Evolution

This project demonstrates how engineering principles can be applied even to a simple software system — ensuring the final product is functional, reliable, maintainable, and user-friendly.

---

## 2️⃣ REQUIREMENT ENGINEERING PROCESS

(From *Software Development Activities.pdf*)

### 2.1 Feasibility Study

| Type                  | Description                                                              |
|-----------------------|--------------------------------------------------------------------------|
| Technical Feasibility | Python supports all required operations (`random`, `time`, input/output) |
| Operational Feasibility | The game runs interactively on any console, no installation required    |
| Economic Feasibility  | No cost involved — open-source tools used                                |

✅ **Result:** The project was fully feasible.

---

### 2.2 Requirements Elicitation and Analysis

**Functional Requirements:**
- Accept user input (rock, paper, or scissors)
- Randomly generate computer choice
- Determine the winner based on choices
- Display the result
- Keep a running scoreboard (Wins, Losses, Ties)
- Allow user to quit or enable “predictor/cheat” mode

**Non-Functional Requirements:**
- User-friendly text interface
- Reliable and quick response
- Portable and easy to run
- Maintainable code with clear structure

---

### 2.3 Software Requirement Specification (SRS)

**Inputs:**
- User choice (string input)
- Optional command (“quit” or “predictor”)

**Processing:**
- Compare user and computer choices
- Apply game logic
- Update scoreboard

**Outputs:**
- Result of round (Win/Lose/Tie)
- Current scoreboard
- System message or fun fact

---

### 2.4 Software Requirement Validation
Requirements were validated through:
- Walkthroughs
- Prototyping
- Test-case generation

---

## 3️⃣ SOFTWARE DESIGN STAGE

(From *Software Design.pdf*)

### 3.1 Problem Partitioning and Modularity
Modules:
- `get_computer_choice()`
- `determine_winner()`
- **Main Game Loop**

**Benefits:**
- Easier testing
- Simplified maintenance
- Functional independence

---

### 3.2 Abstraction and Information Hiding
- Each function hides internal details
- Follows abstraction principles
- Low coupling

---

### 3.3 Functional Independence
- `get_computer_choice()` → randomization logic
- `determine_winner()` → comparison logic
- Main loop → display & user interaction

✅ **High cohesion** and **low coupling** achieved.

---

### 3.4 System Design Structure (Simplified DFD)



