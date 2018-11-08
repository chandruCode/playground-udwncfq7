#include <stdio.h>
//problem: display all odd numbers from 1 to 20
//Loop category: counter control
//Loop type: for loop

void main () {

int counter; //delare control variable

printf (" all odd numbers from 1 to 20: \n");
for (counter=1;counter<=20;counter++){
if(counter %2!=0)
printf ("%2d",counter);
}//end of loop

}//end of program
