#include <stdio.h>
int main() {
    int sw;
   printf("Enter switch (1 = ON, 0 = OFF): ");
    scanf("%d", &sw);
    if (sw == 1)
        printf("Blood Pressure Monitor is ON\n");
    else if (sw == 0)
        printf("Blood Pressure Monitor is OFF\n");
    else
        printf("Invalid input\n");
 return 0;
}

