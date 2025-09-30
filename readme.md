C is a `general purpose`, `procedural` programming language developed in the early
1970s by Dennies Ritchie at `Bell Labs`.

**Why C is important?**
1. Foundation of modern language (i.e, python, C++, java)
2. Used in `system programming`, operating system (Unix/Linux), compilers and embedded system.
3. Know for speed, portability and low-level memory accesss.

**Key Features**:
1. Compiled not interpreted.
2. Work close with Hardware (Pointers, memory management)
3. Provides structural programming (functions, control Structures)
4. Small standard library but most powerfull.

**Getting started with Hello World**:

The only way to learn programming is to write the program. And the first program
for all programming languages is `Hello World.`

**hello.c**
```c
#include <stdio.h>

main(){
printf("Hello World");
}
```

If you are using unix based OS (Linux), then to run above program.
1. Compile it (`gcc hello.c`)
2. This will create a executable file (`a.out`) with some warning (ignore as of now)
3. Now run the executable file (`./a.out`)

<img width="699" height="189" alt="image" src="https://github.com/user-attachments/assets/14ea2358-f641-4be7-aa97-bf3e72820065" />

Now let's understand the program:
1. Our example have function main()
2. Normally you have liberty to choose function name but main is special function
3. You program start executing from `main`, This means every program must have a main somewhere.
4. Main usually calls other functions to help perform its job.
5. First line of program `#include <stdio.h>` tells compiler to include information about standard
input/output library.

<img width="692" height="274" alt="image" src="https://github.com/user-attachments/assets/0c6086d9-86b6-4c47-9c0a-d85d2e8821e7" />

