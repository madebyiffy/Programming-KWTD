
# Starting To Write Your Program

## IDEs

An IDE (Integrated Development Environment) is a program that you use to write code, I don't care which IDE you are using, its all personal preference. There's virtually no difference your IDE makes to the code you write so pick whichever you find _aesthetic_ and set it up accordingly.

#

Often times you can just start typing (like in python), but some languages may require you to write a specific setup before you can program

In C++, every program begins like this:

```cpp
  #include <iostream> //This is your space for headers
  using namespace std; //This is to declare namespaces


  //Below is the main function, where your program lives
  int main {
                  //You write your program here
  }
```

Thats a lot to take in at once, so lets understand slowly - 

Headers are like libraries of functions that you can use, without the right header your program won't understand what `print` means!

Namespaces are optional but make writing code cleaner, the namespace is kinda like the name of the book where our function is written in our Library (Header).

## Why int main{}

Every function in C++ requires an exit value, the main function is specially reserved for writing our programs in and its exit value is of the integer type, Essentially, If your code works you will get a 0 and if theres any issues you will get any other number
    



