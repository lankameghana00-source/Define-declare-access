#include <stdio.h>
struct Student {
 int rno;
 char name[20];
 float marks;
 };
 int main() 
{
 struct Student s;
 printf("Enter Roll Number: ");
 scanf("%d", &s.rno);
 printf("Enter Name: ");
 scanf("%s", s.name);
 printf("Enter Marks: ");
 scanf("%f", &s.marks);
 printf("\nStudent Details:\n");
 printf("Roll Number: %d\n", s.rno);
 printf("Name: %s\n", s.name);
 printf("Marks: %.2f\n", s.marks);
 return 0;
}
