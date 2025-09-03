#include <stdio.h>

int main() {
    int a, b, c, max;

    // Input 3 numbers
    printf("Enter three numbers: ");
    scanf("%d %d %d", &a, &b, &c);

    // Compare using if-else
    if (a >= b && a >= c)
        max = a;
    else if (b >= a && b >= c)
        max = b;
    else
        max = c;

    // Output the result
    printf("The maximum number is: %d\n", max);

    return 0;
}