# STUDENT_RECORD_MANAGEMENT_SYSTEM
# Student Record Management System in C

## 1. Project Description

This is a **Student Record Management System** developed using the C programming language.

The project uses a **Singly Linked List (SLL)** to store student records dynamically.

Each student record contains:

- Roll number
- Student name
- Percentage
- Address of the next student node

The program provides a menu-driven interface through which the user can perform different operations on student records.

---

# 2. Objectives

The main objectives of this project are:

- To understand structures in C
- To understand self-referential structures
- To implement a singly linked list
- To understand pointers and double pointers
- To perform insertion and deletion in a linked list
- To search for a particular record
- To modify student information
- To sort records
- To reverse a linked list
- To use dynamic memory allocation
- To save records into a file

---

# 3. Technologies Used

- C Programming Language
- Structures
- Pointers
- Singly Linked List
- Dynamic Memory Allocation
- File Handling
- String Handling

---

# 4. Student Structure

The main structure used in this project is:

```c
typedef struct student
{
    int rollno;
    char name[20];
    float percentage;
    struct student *next;
} SLL;
