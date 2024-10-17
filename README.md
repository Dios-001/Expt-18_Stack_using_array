# EXP 18 - Stack Implementation using Array

# Algorithms

## Stack Using STL

### Algorithm

1. **Start.**  
2. **Initialize an Empty Stack:**  
   - Create an empty stack of integers `st`.  
3. **Push Elements onto the Stack:**  
   - Push the value `30` onto the stack.  
   - Push the value `20` onto the stack.  
   - Push the value `10` onto the stack.  
4. **Print the Top Element of the Stack:**  
   - Output the top element of the stack, which is `10`.  
5. **End.**

---

## Stack in Array

### Algorithm

1. **Start.**  
2. **Define the Stack Class:**  
   - Declare attributes:  
     - `capacity` (int)  
     - `top` (int)  
     - `arr` (dynamic array)  
3. **Initialize the Stack:**  
   - Set the stack with the given `capacity` and initialize `top` to `-1` (indicating an empty stack).  
4. **Define Methods:**
   - **push():**  
     - Add an element to the stack if it's not full.  
     - If the stack is full, output "Stack Overflow".  
   - **pop():**  
     - Remove the top element if the stack is not empty.  
     - If the stack is empty, output "Stack Underflow".  
   - **peek():**  
     - Return the top element of the stack.  
     - If the stack is empty, return `-1`.  
5. **In the Main Function:**  
   - Create a stack `st` with a capacity of `5`.  
   - Push the elements `23`, `24`, and `25` onto the stack.  
   - Print the top element using `peek()` (Output: `25`).  
   - Remove the top element using `pop()`.  
   - Print the new top element (Output: `24`).  
6. **End.**


This project demonstrates the implementation of a **stack data structure** using arrays. A stack is a **linear data structure** that follows the **Last In First Out (LIFO)** principle, meaning the last element added is the first to be removed.

## Features

- **Push Operation**: Adds an element to the stack.
- **Pop Operation**: Removes the top element from the stack.
- **Peek Operation**: Retrieves the top element without removing it.
- **Overflow & Underflow Handling**: Handles cases when the stack is full or empty.

## Code Overview

This project includes:

- **C++ code using STL (`stack`)** for stack operations.
- Demonstrates basic stack functionalities like pushing, popping, and peeking elements.

### Sample Code

```cpp
#include <iostream>
#include <stack>
using namespace std;

int main() {
    stack<int> st;
    st.push(30);
    st.push(20);
    st.push(10);

    // Print the top element of the stack
    cout << "Top element of the stack: " << st.top() << endl;

    return 0;
}
```
