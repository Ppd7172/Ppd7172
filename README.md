#include <stdio.h>

int main() {
    int num1, num2, temp;

    // Input numbers from the user
    printf("Enter the first number: ");
    scanf("%d", &num1);

    printf("Enter the second number: ");
    scanf("%d", &num2);

    // Print original numbers
    printf("\nBefore swapping: num1 = %d, num2 = %d\n", num1, num2);

    // Swap the numbers
    temp = num1;
    num1 = num2;
    num2 = temp;

    // Print swapped numbers
    printf("After swapping: num1 = %d, num2 = %d\n", num1, num2);

    return 0;
}
