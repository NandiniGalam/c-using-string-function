# c-using-string-function
#include <stdio.h>
#include <string.h>
#define MAX_SIZE 100 
int main()
{
  char text1[MAX_SIZE], text2[MAX_SIZE];
  printf("ENTER ANY STRING:");
  scanf("%s",text1);
  strcpy(text2, text1);
  printf("first string = %s\n",text1);
  printf("second string = %s\n",text2);
  return 0;
}
