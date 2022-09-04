# Vowel_Consonant
#include<stdio.h>
void CheckVowelOrConsonant(char ch);

void main() {
  char ch;
  printf("Enter a Character:");
  scanf("%c/n",ch);

  if((ch >='a' && ch <= 'z')||(ch >= 'A' && ch <= 'Z'))
  CheckVowelOrConsonant(ch);
  else
  printf("%c",ch,"is not an alphabet");
  return;
}

void CheckVowelOrConsonant(char ch) {
  if(ch=='a' || ch=='e'||ch=='i' || ch=='o'||ch=='u' || ch=='A'||ch=='E' || ch=='I'||ch=='O' || ch=='U')
   printf("Character %c",ch,"is a Vowel");
  else
   printf("Character %c",ch,"is NOT a Vowel");
   return;
}
