[README_LinkedLists.md](https://github.com/user-attachments/files/29223219/README_LinkedLists.md)
# Linked-Lists
Java sorted linked list with ordered insert, delete, and display. Includes OddGame, an interactive mode where divisibility rules trigger different list operations until the n# Linked Lists

**Course:** IB Computer Science SL
**Year:** Junior Year, Semester 1

## Description

A Java implementation of a sorted singly linked list with a menu-driven interface. Supports ordered insertion, deletion by value, list display, and a length counter. Also includes `OddGame`, an interactive mode where user inputs trigger different list operations based on divisibility rules, ending when the running total reaches 100.

## Files

| File | Purpose |
|---|---|
| `Node.java` | Node class storing integer data and a next pointer |
| `LinkedList.java` | Core list class: insert, delete, show, calcTotal, oddGame |
| `MyProgram.java` | Menu-driven driver for insert, delete, display, and length |
| `OddMenu.java` | Driver that launches the OddGame mode |

## How to Run

```bash
javac *.java
java MyProgram       # interactive menu
java OddMenu         # launches OddGame
```

## Key Concepts

- Singly linked list traversal and pointer manipulation
- Sorted insertion maintaining ascending order
- Edge case handling for head and tail deletion
- Iterative total calculation across all nodes

## OddGame Rules

| Condition | Action |
|---|---|
| Odd, not divisible by 5 | Append to end |
| Odd and divisible by 5 | Prepend double the value |
| Even, not divisible by 5 | Remove last node |
| Even and divisible by 5 | Remove head node |

Game ends when the sum of all node values reaches or exceeds 100.
