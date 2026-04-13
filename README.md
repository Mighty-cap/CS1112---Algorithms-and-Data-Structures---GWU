# CSCI 1112 — Data Structures & Algorithms

George Washington University · Java · Freshman year

Java implementations of core data structures and algorithms, written for CSCI 1112 at GWU. Each assignment folder has the source files and the original spec.

## Assignments

| # | Topic | What's in it |
|---|-------|--------------|
| 01 | Linked lists | `LinkedList` with `CatalogItem` and `Song` nodes — `add`, `remove`, `get`, `contains`, `clear`, `isEmpty` |
| 02 | Sorting & searching | Selection, bubble, and insertion sort + binary search, applied to a `ClassSchedule` structure |

## Concepts covered

Singly linked lists, node-based structures, ArrayList vs. LinkedList tradeoffs, O(n²) sorting (selection, bubble, insertion), binary search O(log n), Big O analysis and time complexity comparisons.

## Repo structure

    assignments/
      assignment-01-linkedlist/
        src/          <- .java source files
        spec.pdf
      assignment-02-sorting/
        src/
        spec.pdf
    lecture-notes/    <- course PDFs

## Running the code

Each assignment compiles independently. From inside a `src/` folder:

    javac *.java
    java Main

*More assignments added as the course progresses.*
