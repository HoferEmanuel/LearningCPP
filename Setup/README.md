# LearningCPP

# Pre-Processor-Statement:
<hr/>
Every code beginning with an `#` is called a processor-statement
A Pre-Processor-Statement gets processed before actual compilation.


### Include a library into the current script:
> It takes all content form the library and pastes it into the script which includes the lib before compilation.
```
#include <iostream>
```

# Main-Funciton:
> The main-function inside a .cpp is also called Entrypoint.

> The main-function does not need to return an value if there is no return-statement the function assumes `0` as its value

# functions

## std::cout << "Hello World" << std::endl
> cout - Console out
Print Hello World inside the console `std::endl` for end-line. 

## std::cin.get()
> cin - Console in
Waits for the user to press "ENTER".

# `<<` Operator
> Think about `<<` as a function because operators are just funcitons.

> `std::cout << "Hello World" << std::endl` 

>  to `std::cout.print("Hello Wolrd").print(std::endl);`