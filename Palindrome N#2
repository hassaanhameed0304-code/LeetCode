#include <stdbool.h>
#include <stdio.h>
#include <string.h>

bool isPalindrome(int x) {
    char original[12]; 
    sprintf(original, "%d", x);
    int n = strlen(original);
    for(int i = 0; i < n / 2; i++) {
        if(original[i] != original[n - 1 - i]) {
            return false;
        }
    }
    return true;
}
