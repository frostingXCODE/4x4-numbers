# 4x4-numbers
//The code itself:
#include <iostream>
using namespace std;

/*
1  2  3
1  2  3
1  2  3
*/


// Let's make the numbers as a 4x4 square stacked 
//Example above ^^^

int h = 13;
 int main(){
     for (int i = 1; i <= 4; i++) {
         for (int j = 1; j < 4; j++) {
             printf(" %d", i * j);
         }
         printf("\n");
     }
}
