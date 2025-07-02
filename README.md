# PRODIHY_SD_04 - Sudoku Solver (Task-04)

## 💡 Description

This project is a Java-based program that solves standard 9x9 Sudoku puzzles using a backtracking algorithm. It was developed as part of Task-04 under the internship/project guidelines by Prodigy Infotech.

## 🧩 Task Objective

Create a program that solves Sudoku puzzles automatically. The program takes an unsolved Sudoku puzzle as input and fills in the missing numbers using a backtracking approach to find the correct solution.

## 🛠 Features

- Accepts a 9x9 Sudoku grid with zeros as placeholders for missing numbers.
- Solves the puzzle using backtracking algorithm.
- Validates the placement of numbers according to Sudoku rules.
- Displays the solved grid.

## 📌 How It Works

The program scans the Sudoku board for empty cells. For each empty cell, it tries placing numbers from 1 to 9. If the number is valid (according to Sudoku rules), it proceeds to the next cell. If a dead end is reached, it backtracks and tries a different number.

## 🧪 Sample Input

```java
int[][] board = {
    {5, 3, 0, 0, 7, 0, 0, 0, 0},
    {6, 0, 0, 1, 9, 5, 0, 0, 0},
    {0, 9, 8, 0, 0, 0, 0, 6, 0},
    {8, 0, 0, 0, 6, 0, 0, 0, 3},
    {4, 0, 0, 8, 0, 3, 0, 0, 1},
    {7, 0, 0, 0, 2, 0, 0, 0, 6},
    {0, 6, 0, 0, 0, 0, 2, 8, 0},
    {0, 0, 0, 4, 1, 9, 0, 0, 5},
    {0, 0, 0, 0, 8, 0, 0, 7, 9}
};
