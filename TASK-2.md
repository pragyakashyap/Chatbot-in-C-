#                             ****TASK-2

## 2-A

**<u>Solution to the Question 1</u>**

**DIFFERENCE BETWEEN C AND C++ **

| ****C                                                        | ****  C++                                                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| When compared to c++,c is a subset of c++.                   | c++ is a superset of c. c++ can run most of c code while c cannot run c++ code. |
| C supports procedural programming paradigm for code development. | C++ supports both procedural and object oriented programming paradigms. |
| C does not support object oriented programming,therefore it has no support for polymorphism,encapsulation and inheritance. | Being an object oriented programming language C++ supports polymorphism,encapsulation and inheritance. |

**<u>Solution to the Question 2</u>**

The operator (::) is called scope resolution operator in C++. It is used for the following purposes ----

| > -1...To access a global variable when there is a local variable with same name. |
| ------------------------------------------------------------ |
| > - 2...To define a function outside the class.              |
| > - 3...To access a class's static variables.                |
| > - 4...It is used in case of multiple inheritance : if some variable name exist in two ancestors classes, we can use scope resolution operator to distinguish. |

**<u>Solution to the Question 3</u>**

The C++ language has its own string classes and in general it is *mutable*.

**<u>Solution to the Question 4</u>**

Namespace is a feature added in C++. A namespace is a declarative region that provides a scope to the identifiers inside it. we can use namespace in creating two variables or member function having the same name.

**<u>Solution to the Question 5</u>**

``#include <iostream>
//Program is written by PRAGYA KASHYAP

using namespace std;

int main()
{
    int rows, i , j , space;
    cout << "Enter number of rows!" << endl;
    cin >> rows;

```c++
for (i = 1 ; i <= rows ; i++)
{
    for(space = i; space < rows; space++)
    {
        cout << " ";
    }
    for(j=1; j <= (2*i-1); j++)
    {
        cout << "*";
    }

    cout << "\n";
}
return 0;
```
}

> Output 
>
> !(https://imgur.com/a/8BCX9Ef)

**<u>Solution to the Question 6</u>**

Many people say that **C++** is not the right choice to begin for programming because it appears to be tough than other programming languages like **Python** . Suppose you are doing programming first time and it is totally unknown for you that's why it will be hard for the person to learn the hard memory based concept of **C++**.

That is the reason many people prefer **Java** and **Python**. But it is believed that **C++** is the right choice to begin programming. **C++** is too hard in such a way because it requires too much memory. **C++** also has an impact on other programming languages like C# and Java. That means if the person starts with **C++** , he will get a bit concept of other programming language also. 

