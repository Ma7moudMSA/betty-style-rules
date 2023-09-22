# Betty Style 



![Dynamic Badge](https://img.shields.io/badge/https%3A%2F%2Fgithub.com%2Falx-tools%2FBetty%2Fwiki?)

![my badge/](https://badgen.net/badge/Betty/ALX)

1. **Indentation**: Use the tab key for indentation instead of spaces. Indent every block of code you write, including nested blocks. Here is an example:

```
int main(void)
{
    int i;

    for (i = 0; i < 10; i++)
    {
        printf("Hello, world!\n");
    }

    return (0);
}
```

2. **Breaking long lines and strings**: Break long lines and strings into multiple lines to improve readability. Here is an example:

```
printf("This is a very long string that should be broken up into multiple lines to improve readability. "
       "It can be difficult to read long strings like this when they are all on one line.");
```

3. **Placing Braces**: Place opening braces on the same line as the function or control statement, and closing braces on a new line. Here is an example:

```
if (x > y)
{
    printf("x is greater than y\n");
}
else
{
    printf("y is greater than x\n");
}
```

4. **Placing Spaces**: Avoid using spaces for indentation. Use the tab key instead. Here is an example:

```
int main(void)
{
    int x = 10;
    int y = 20;

    if (x > y)
    {
        printf("x is greater than y\n");
    }
    else
    {
        printf("y is greater than x\n");
    }

    return (0);
}
```

5. **Naming**: Use descriptive names for variables, functions, and other identifiers. Here is an example:

```
int calculate_sum(int num1, int num2)
{
    int sum;

    sum = num1 + num2;

    return (sum);
}
```

6. **Functions**: Functions should be short and focused on a single task. Here is an example:

```
int calculate_sum(int num1, int num2)
{
    return (num1 + num2);
}
```

7. **Commenting**: Include comments to explain the purpose and functionality of your code. Here is an example:

```
/* This program calculates the sum of two numbers */

#include <stdio.h>

int main(void)
{
    int num1;
    int num2;
    int sum;

    /* Prompt user for input */
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);

    /* Calculate sum */
    sum = num1 + num2;

    /* Display result */
    printf("The sum of %d and %d is %d\n", num1, num2, sum);

    return (0);
}
```

8. **Macros and Enums**: Use uppercase letters for macros and enums, and separate words with underscores. Here is an example:

```
enum Color
{
    RED,
    GREEN,
    BLUE
};

#define MAX_VALUE 100
```



(1) Betty Styles For C Programming Explained - Dr. Ehoneah Obed. https://blog.ehoneahobed.com/betty-styles-for-c-programming-explained.
(2) betty style in c - W3schools. https://www.w3schools.blog/betty-style-in-c.
(3) Home · alx-tools/Betty Wiki · GitHub. https://github.com/alx-tools/Betty/wiki.
(4) Betty style usage · alx-tools/Betty Wiki · GitHub. https://github.com/alx-tools/Betty/wiki/Betty-style-usage.
(5) alx-tools/Betty: Holberton-style C code checker written in Perl - GitHub. https://github.com/alx-tools/Betty.