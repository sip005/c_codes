#include <stdio.h>

int main() {
    // Declare a 2x4x3 array
    int array[2][4][3];

    // Initialize the array elements with user input
    printf("Enter 24 values for the 2x4x3 array:\n");
    for (int i = 0; i < 2; ++i) {
        for (int j = 0; j < 4; ++j) {
            for (int k = 0; k < 3; ++k) {
                scanf("%d", &array[i][j][k]);
            }
        }
    }

    // Print the array
    printf("Generated 2x4x3 Array:\n");
    for (int i = 0; i < 2; ++i) {
        printf("[\n");
        for (int j = 0; j < 4; ++j) {
            printf("  [");
            for (int k = 0; k < 3; ++k) {
                printf("%d", array[i][j][k]);
                if (k < 2) {
                    printf(", ");
                }
            }
            printf("]\n");
        }
        printf("]\n");
    }

    return 0;
}
