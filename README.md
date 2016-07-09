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
