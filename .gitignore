#include <stdio.h>

int main() {
    float a, b;
    char op;

    printf("Enter first number: ");
    scanf("%f", &a);

    printf("Enter operator (+, -, *, /): ");
    scanf(" %c", &op);

    printf("Enter second number: ");
    scanf("%f", &b);

    switch(op) {
        case '+':
            printf("Result: %.2f\n", a + b);
            break;

        case '-':
            printf("Result: %.2f\n", a - b);
            break;

        case '*':
            printf("Result: %.2f\n", a * b);
            break;

        case '/':
            if(b == 0)
                printf("Error: Division by zero is not allowed!\n");
            else
                printf("Result: %.2f\n", a / b);
            break;

        default:
            printf("Invalid operator!\n");
    }

    return 0;
}
