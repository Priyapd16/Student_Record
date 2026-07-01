# Student Record Management System
### Language: C | OS: Linux | Compiler: Terminal

A multi-file console application to manage student 
records using a Singly Linked List with persistent 
storage via File I/O.

---

## Features
- Auto roll number generation
- Add / Delete / Modify / Display records
- Delete by roll number or name
- Sort by name (A→Z) or percentage (High→Low)
- Data persistence using student.txt
- Clean menu-driven interface

## Build & Run
$ make
$ ./exe
## Project Structure
├── student.h → Struct & declarations
├── main.c → Menu loop
├── stud_add.c → Add record
├── stud_del.c → Delete record
├── stud_show.c → Display records
├── stud_mod.c → Modify record
├── stud_save.c → File save & load
├── stud_sort.c → Sort records
└── Makefile → Build automation
## Concepts Used
- Singly Linked List
- Dynamic Memory Allocation (malloc/free)
- File I/O (fprintf/fscanf)
- Multi-file C programming
- Makefile build system
