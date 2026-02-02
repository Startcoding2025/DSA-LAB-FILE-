# DSA-LAB-FILE-
DSA LAB WORK

// LAB-2

//QN-1 write a program to read n elements into an array and display the elements using a for loop

#include <stdio.h>

int main() {
    // Write C code here
int n , i;
int arr[100];

printf("Enter a number of elements: ");
scanf("%d" , &n);

printf("Enter %d elements:\n" , n);
for(i = 0; i < n; i++) {
    scanf("%d" , &arr[i]);
}

printf("Array elements are:\n");
for(i = 0; i < n ; i++) {
    printf("%d" , arr[i]);
}

    return 0;
}


/*OUTPUT-Enter a number of elements: 5
Enter 5 elements:
1 2 3 4 5
Array elements are:
12345
*/



