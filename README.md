info.h - This will mean that what ever is put in the header file cannot be changed.

#define CLASS "EM108"
#define Pass 40

#include <stdio.h>
#include <stdlib.h>
#include "Info.h"


int main()
{
   int goodGrade = (Pass * 2);
   printf("%s considers %d a suitable grade for 1.1", CLASS, goodGrade); / ALL CAPS MEANS ITS DEFINED DOESNT CHANGE /

   return 0;
}


Input with Scanf - Tutorial 11

#include <stdio.h>
#include <stdlib.h>


int main()
{
  char favclass[20];
  char favouritelecturer[20];
  int classnumber 
  
  pintf("What class do you most enjoy? /n");
  scanf("%s" , favclass);
  
  pintf("Who d you believe to be the best lecturer? /n");
  scanf("%s" , favlecturer);
  
  pintf("How many class do you have? /n");
  scanf("%d" , &favclass); / remember need this sign /
  
  printf("You best class wil be %s were %s will lecturer you and in the end of year exams you will pass %d classes" , favclass, favlecturer, classnumber);

   return 0;
}
