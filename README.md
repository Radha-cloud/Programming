# Programming
Programming with C
ARRAYS
#include <stdio.h>

int main() {
    // Different ways to initialise arrays
    // Declare an array to store top 5 scores. --> 980, 903,785, 761,600

    //Method 1: Specifying size and initialising elmts
    long scoresOne[5] = {980, 903, 785, 761, 600};
    printf("%ld\n", scoresOne[4]);

    //Method 2: Just initialising elmts
    long scoresTwo[ ] = {980, 903, 785, 761, 600};
    printf("%ld\n", scoresOne[2]);

    //Method 3: Just declaring size
    long scoresThree[5];
    scoresThree[0] = 980;
    scoresThree[1] = 903;
    scoresThree[2] = 785;
    scoresThree[3] = 761;
    scoresThree[4] = 600;

    printf("%ld\n", scoresOne[2]);

  return 0;
}
