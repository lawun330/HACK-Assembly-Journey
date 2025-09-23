# HACK Assembly Learning

This repository contains educational examples of **HACK assembly language** implementations, demonstrating fundamental programming constructs and algorithms translated from high-level pseudocode.

## 🎯 About HACK Assembly

HACK is a simplified assembly language designed for educational purposes, particularly in computer science courses like **Nand2Tetris**. It provides a clean, minimal instruction set that helps students understand low-level programming concepts.

## 📁 Repository Contents
### 🔄 **Control Flow Examples**
- **`for_loop.asm`** - Demonstrates for loop implementation
  ```pseudocode
  j = 5
  for(i = 1; i < 5; i++) {
    j--
  }
  ```

- **`if_then_else.asm`** - Shows conditional branching
  ```pseudocode
  i = 4
  if (i < 5) then
    j = 3
  else
    j = 2
  ```

- **`while_loop.asm`** - Implements while loop with nested conditions
  ```pseudocode
  i = 0
  j = 0
  while(i == 0) {
    j++
    if j == 5 then
      i = j
  }
  ```

### 📊 **Data Structure Examples**
- **`array_traversal.asm`** - Array manipulation and traversal
  ```pseudocode
  A[0] = 5, A[1] = 4, A[2] = 3, A[3] = 2, A[4] = 1, A[5] = 0
  for (i = 0; i <= 5; i++) {
    if A[i] == 0 then
      A[i] = 5;
  }
  ```

### 🧮 **Algorithm Examples**
- **`bubble_sort_algorithm.asm`** - Complete bubble sort implementation
  ```pseudocode
  // Bubble Sort Algorithm
  A[0] = 5, A[1] = 4, A[2] = 3, A[3] = 2, A[4] = 1, A[5] = 0
  flag = 1;    // set flag to true to begin first pass
  while (flag == 1) {
    flag = false;        // set flag to false awaiting a possible swap
    for (j = 0; j < 6; j++) {
      if (A[j] > A[j+1]) {    // test for ascending sort
        temp = A[j];          // swap elements
        A[j] = A[j+1];
        A[j+1] = temp;
        flag = 1;            // shows a swap occurred 
      }
    }
  }
  ```

## 🚀 Getting Started

### Prerequisites
- [Software package](https://drive.google.com/file/d/1xZzcMIUETv3u3sdpM_oTJSTetpVee3KZ/view) provided by the [Nand to Tetris](https://www.nand2tetris.org/) platform

### Setup Instructions
1. Download the **HACK Assembler** along with other useful tools (compiler, emulator, simulator) from the [software package](https://drive.google.com/file/d/1xZzcMIUETv3u3sdpM_oTJSTetpVee3KZ/view).
2. Extract the ZIP file.
3. Refer to the [manual](https://drive.google.com/file/d/1IkIR8Pwq3PY49QgXpUJOkUUVht-TKIET/view) for detailed usage instructions.
4. Compile and run `.asm` files using the `nan2tetris/tools/Assembler.bat`.

## 📚 Learning Objectives
- **Control Flow**: Understanding loops, conditionals, and branching
- **Memory Management**: Working with variables and arrays
- **Algorithm Implementation**: Translating algorithms to assembly language
- **Low-Level Programming**: Understanding computer architecture concepts

## 📄 License

This project is part of coursework and is intended for educational purposes.
