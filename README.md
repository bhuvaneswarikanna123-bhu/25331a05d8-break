# 25331a05d8-break
#include <stdio.h>

int main() {
    int i;

    // Demonstrating break
    printf("Using break statement:\n");
    for(i = 1; i <= 10; i++) {
        if(i == 6) {
            break;  
        }
        printf("%d ", i);
    }

    printf("\n\n");

    // Demonstrating continue
    printf("Using continue statement:\n");
    for(i = 1; i <= 10; i++) {
        if(i == 6) {
            continue; 
        }
        printf("%d ", i);
    }

    return 0;
}
