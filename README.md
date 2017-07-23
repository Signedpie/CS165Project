# CS165Project
Projectile motion and file storage 

For anyone else who stumbles upon this project: this is a 2nd semester c++ project where we set out to apply constant a
accleration equations to a program. It's a little dissapointing how little physics actually went into this project.

ok. here is the jist of what have so far....

classes:
  Projectile---- holds initail inputs of funcition
                 has member functions to get and vet input, calculate output, and format output with correct digits
  StackChar----- used in sigfig function in main. purpose is to turn input into a stack for calculating sig figs.
  FileStorage--- creates repository for data recorded with each run of the main program

input: accepts user input as a c-string
   void input---- condenses function calls to input value into the code
   void getValue- asks for input and catches all invalid inputs thrown by Projectile::inputVet

output:void output currently just applies significant figures and couts in scientific notation
           ----- could make it not use sceintific notation but then applying sifFigs is more complicated/ harder to show




consepts hit:
  chapter 9: pointers -> taken care of in StackChar/ we could pass an object by pointer
  chapter 10: c-strings manipulation
  chapter 11: structures -> in StackChar / linked list
  chapter 12: FileStorage/ advanced file manipulation
  chapter 13: classes -> we've got 3 classes
  chapter 16: exceptions -> through out input and inputVet function/ memberfunctions
  chapter 17: Linked lists-> in the dynamic stack from StackChar
  chapter 18: StackChar -> use of a dynamic stack
  
  
other consepts to hit/ ways to hit them:
  chapter 19: recursion -> no fucking idea
  chapter 8: searching and sorting -> in the file sotrage aspect of the code we should have a file retriaval wich will need
                                      a search aspect to it. 
  
summary: We've hit pretty much every topic we needed to, or at least brushed them all.
