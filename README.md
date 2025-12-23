# codesinc
# Printing numbers in c using recursion 
#include <stdio.h>
void Num(int n) {
    if (n>=1) {
        Num(n - 1);
        printf("%d ", n);
    }
}
int main() {
    int n;
    printf("Enter a number: ");
    scanf("%d", &n);
    printf("Numbers from 1 to %d: ", n);
    Num(n);
    return 0;
}
