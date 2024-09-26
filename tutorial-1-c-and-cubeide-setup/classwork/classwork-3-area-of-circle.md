[Back to Main](../README.md)

# Classwork 3: Area of circle

> pi\*z\*z\*a

Construct a function called `circleArea` to calculate the area of a circle using `float`s. Modify the following code:

```c
#include <stdio.h>
#include <stdbool.h>

// your function starts here
#include <math.h>
float circleArea(float radius){
    return radius*radius*M_PI;
}
// your function ends here

int main() {
  printf("%f", circleArea(5.0f));
  return 0;
}
```
