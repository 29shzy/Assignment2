2)
#include <stdio.h>

int main() {
    int N;

    // Taking input from the user
    printf("Enter the number of rows: ");
    scanf("%d", &N);

    // Printing the right-angled triangle
    for (int i = 1; i <= N; i++) {
        for (int j = 1; j <= i; j++) {
            printf("* ");
        }
        printf("\n");
    }

    return 0;
}
