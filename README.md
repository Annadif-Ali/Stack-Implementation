# Stack-Implementation

Stack Implementations
1. Stack Implementation Using Array
Description:

In this implementation, a stack is manually managed using an array. We use a pointer called top to keep track of the index of the last element inserted into the stack. The stack supports the following operations:

Push: Adds an element to the top of the stack.
Pop: Removes the top element from the stack.
Peek: Returns the top element without removing it.
isFull and isEmpty: Checks if the stack is full or empty.
Algorithm:

Push Operation:

Check if the stack is full by checking if top == size - 1.
If not full, increment top and insert the new element at arr[top].
Pop Operation:

Check if the stack is empty by checking if top == -1.
If not empty, remove the element at arr[top] and decrement top.
Peek Operation:

Check if the stack is empty.
If not empty, return the element at arr[top].
isFull/isEmpty Operation:

isFull: Returns true if top == size - 1.
isEmpty: Returns true if top == -1.
Time Complexity:

Push: O(1)
Pop: O(1)
Peek: O(1)
2. Stack Implementation Using C++ STL
Description:

The C++ Standard Template Library (STL) provides a built-in stack class, which makes implementing a stack much simpler and safer. This implementation handles all memory management internally, offering easy-to-use functions to manipulate the stack. The stack class supports the following operations:

push: Adds an element to the top of the stack.
pop: Removes the top element.
top: Returns the top element.
empty: Checks if the stack is empty.
Algorithm:

Push Operation (push):

Use st.push(value) to insert an element at the top of the stack.
Pop Operation (pop):

Use st.pop() to remove the top element from the stack.
Access Top Element (top):

Use st.top() to retrieve the element at the top of the stack without removing it.
Check If Stack is Empty:

Use st.empty() to check if the stack has no elements.
Time Complexity:

Push: O(1)
Pop: O(1)
Top: O(1) OUTPUT: Top element of the stack: 10 */
