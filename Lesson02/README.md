# Lesson02: Memory Tables & More -- [Video Link](https://youtu.be/RbmrQcbo92w)

If you haven't done so already:
* Sign up for the [Slack Community](https://forms.gle/Jx3TBiqDFkqB4CEj6)
* Do assignments 0 and 1!


Your assignment this week is to do the following.
* Create memory tables for both of your past assignments from Lesson01. Do this first!
* For the following code samples. 
  1. Create a memory table on paper.
  2. Describe what the program is doing in english.
  3. Write down what you think the program will output.
  2. Run the code to check your memory tables & output, but only do this **AFTER** you've finished 1-3.
```cpp
#include <iostream>

int main() {
  int first = 100;
  int second = 2450;
  float third = 100.0;
  std::cout << "First number is: " << first << std::endl;
  std::cout << "Second number is: " << second << std::endl;
  std::cout << "Third number is: " << third << std::endl;

  first = first + second * 2;
  second = second + 50;
  third = third / second;
  std::cout << "First number is: " << first << std::endl;
  std::cout << "Second number is: " << second << std::endl;
  std::cout << "Third number is: " << third << std::endl;
  
  first = second / first;
  third = first / third;
  std::cout << "First number is: " << first << std::endl;
  std::cout << "Second number is: " << second << std::endl;
  std::cout << "Third number is: " << third << std::endl;
}
```

```cpp
#include <iostream>

int main() {
  std::cout << "Enter a number: ";
  int first = 100;
  
  std::cin >> first;
  int second = 2450;
  float third = 100.0;
  std::cout << "First number is: " << first << std::endl;
  std::cout << "Second number is: " << second << std::endl;
  std::cout << "Third number is: " << third << std::endl;

  first = first + second * 2;
  second = second + 50;
  third = third / second;
  std::cout << "First number is: " << first << std::endl;
  std::cout << "Second number is: " << second << std::endl;
  std::cout << "Third number is: " << third << std::endl;
  
  first = second / first;
  third = first / third;
  std::cout << "First number is: " << first << std::endl;
  std::cout << "Second number is: " << second << std::endl;
  std::cout << "Third number is: " << third << std::endl;
}
```
  * Create a new Repl where you request 2 numbers from the user, and then display their sum.
  * As always share your output with others in the community and provide feedback on their assignments as well. Part of every exercise is to start exposing yourself to the way other's think and approach code.

### Final note
We intentionally try and make sure every assignemnt pushes your boundaries. 
Not everything you need in order to do the assignment was given to you in the videos. 
The goal is to help build your muscle of asking The Right Question. Sometimes you may feel stuck, 
and its important to remember that's completely normal.

First write on paper on what you are trying to get the code to do. 
Then go ahead and ask the question in the Slack Channel for this assignment. Be sure to link your Repl in the question and include a description of
* What line you think is causing the problem (if you don't know for sure, try and have a guess regardless)
* What you **want** your code to do
* What your code is **doing**
