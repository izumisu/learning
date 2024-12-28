# Problem 1.1

(a) curly braces define a block in C, braces { and } visually group the declarations and statements into a block(for example function). And function, which literaly is a union of statments(or code), so it makes sense to use braces after function.

(b) 7: number, "7": string, '7':character(char)

(c) rewrite: double ans = 10.0 + 2.0 / (3.0 - 2.0) * 2.0;

# Problem 1.2

1. 3.0
2. 3.0
3. 3.0
4. 3.0

# Problem 1.3

code
```
#include<stdio.h>

void main() {

    printf("Hello, 6.087 students");
}
```

#
compile
```
gcc hello.c
```

execute
```
gdb a.out
(gdb) r
```

output
```
Hello, 6.087 students
```

# Problem 1.4

code
```
#include<stdio.h>
#define MSG1 "All your base are belong to us!"

int main(void) {

    const char msg[] = MSG1;
    puts(msg);
    return 0;
}
```

# Problem 1.5

(without explain)

(a) #include<stdio.h>

(b)
int function(int arg1)
{
    return arg1 - 1;
}

(c)
#define MESSAGE "Happy new year!"
puts(MESSAGE);
