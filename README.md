# What is Stack in Data structure?

A Stack is a linear data structure that follows the LIFO (Last-In-First-Out) principle. Stack has one end, whereas the Queue has two ends (front and rear). It contains only one pointer top pointer pointing to the topmost element of the stack. Whenever an element is added in the stack, it is added on the top of the stack, and the element can be deleted only from the stack. In other words, a stack can be defined as a container in which insertion and deletion can be done from the one end known as the top of the stack.

# Functions
push();
pop();
top();
isEmpty();
size();

## Usage

```C++
Stack<int> myStack;
myStack.push(10);
myStack.push(20);
myStack.push(30);
myStack.pop();
std::cout << "Top element: " << myStack.top() << std::endl;

```


## Stack object can be in any data type like int, boolean, String, char, double ..... etc.

Example
```CPP
Stack<int> myStack;
```
```CPP
Stack<string> myStack;
```
```CPP
PStack<double> myStack;
```
```CPP
Stack<char> myStack;
```
