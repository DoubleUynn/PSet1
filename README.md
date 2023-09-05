# Problem Set 1
***
## Hello
Shall we have you write your first program?

Edit the hello.c to include the following code from the lecture:

```C
#include <stdio.h>

int main(void)
{
    printf("hello, world\n");
}
```

#### Compiling Programs

Now, before we can execute the hello.c program, recall that we must compile it with a compiler, translating it from source code into machine code (i.e., zeroes and ones). Execute the command below to do just that:
(Note: your working directory must be the hello directory, you can see your working directory with pwd (print working directory) and navigate directories using cd (change directory)

> make hello

And then execute this one:

> ls

(short for list)
This time, you should see not only hello.c but hello listed as well? You’ve now translated the source code in hello.c into machine code in hello.
Now execute the program itself by executing the below.

> ./hello

Hello, world, indeed!

#### Getting User Input
Suffice it to say, no matter how you compile or execute this program, it only ever prints hello, world. Let’s personalize it a bit, just as we did in class.
Modify this program in such a way that it first prompts the user for their name and then prints hello, so-and-so, where so-and-so is their actual name.
As before, be sure to compile your program with:

> make hello

And be sure to execute your program, testing it a few times with different inputs, with:

> ./hello

[Hints](https://cs50.harvard.edu/ap/2024/curriculum/x/psets/1/hello/#hints) available
Adapted from: https://cs50.harvard.edu/ap/2024/curriculum/x/psets/1/hello/
***
## Mario - Less Comfortable


