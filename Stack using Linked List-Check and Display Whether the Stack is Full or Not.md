# # 📚 Stack using Linked List: Check and Display Whether the Stack is Full or Not

This Python program demonstrates how to check if a stack (using `LifoQueue` from the `queue` module) is full or not. It uses the `full()` method to determine the stack's status and then displays the appropriate message.

## 🎯 Aim

To write a Python program that:
- Creates a stack with a fixed size.
- Adds elements to the stack.
- Checks if the stack is full.
- Displays a message indicating whether the stack is full or not.

## 🧠 Algorithm

1. **Import the LifoQueue class**:
   - Import `LifoQueue` from the `queue` module to create the stack.

2. **Create a Stack**:
   - Instantiate a `LifoQueue` with a maximum size (e.g., 4).

3. **Add Elements to the Stack**:
   - Add elements (e.g., 'a', 'b', and 'c') to the stack using the `put()` method.

4. **Check if the Stack is Full**:
   - Use the `full()` method of `LifoQueue` to check if the stack has reached its maximum capacity.

5. **Display the Status**:
   - Print "Stack is full" if the stack is full.
   - Otherwise, print "Stack is not full".

## 📝 Program
```
from queue import LifoQueue

stack = LifoQueue(maxsize=4)

stack.put('a')
stack.put('b')
stack.put('c')
if stack.full():
    print("Stack is full")
else:
    print("Stack is not full")
```

## Sample Input & Output
<img width="499" height="126" alt="Screenshot 2026-03-28 103922" src="https://github.com/user-attachments/assets/33c8b663-b907-43db-a339-2bf92e9ed7d9" />

## Result
Thus, the python program to check and display whether the stack is full or not using linked list has been executed successfully.
