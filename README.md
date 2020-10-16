[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3412356&assignment_repo_type=AssignmentRepo)
# Lab4RandomNumbersAndUserInput

## Introduction
In this lab you will apply methods from the Math class to generate random numbers within a specified range.  
You will also apply methods from the Scanner class to create a Mad Libs game. 

## Code Challenge 1

- [ ] Your task is to create a random number generator.  Your simulator will prompt the user for two numbers.  The first number should be negative.  The second number should be greater than the absolute value of the first number.  The numbers will represent the range.  Once the input is received your program should generate two random numbers (int type) within the range specified, where the lowest number is inclusive but the highest number is not.  Consider the example below, 

```
Type a negative number: -5

Type a postive number that is greater than 5: 50

You got a -4 and a 36

```
public class random {
class GenerateRandomid main( String args[] ) {
      int min = -50;
      int max = 50;
      System.out.print {
    public static voln("Random value in double from "+min+" to "+max+ ":");
      double random_double = Math.random() * (max - min + 1) + min; 
      System.out.println(random_double);
        
      System.out.println("Random value in int from "+min+" to "+max+ ":");
      int random_int = (int)(Math.random() * (max - min + 1) + min);
      System.out.println(random_int);
    }
  }  
}

## Code Challenge 2

- [ ] Implement the Mad Libs game you started in the group portion of this lab.  

- [ ] Your program must prompt the user for at least 5 things and should include the following data types: int, String, double

- [ ] **After** you have collected all the information, your program must incorporate the user's input into a story.  One of the fields in the story should also include the result of a calculation.  

- [ ] The story should be printed to the console using 1 print statement


public class madLib;{
public static void main(String[] args) {
System.out.print("Enter place: ");
String place = keyboardInput.nextLine();

System.out.print("Enter noun: ");
String noun = keyboardInput.nextLine();

System.out.print("Enter family member: ");
String familyMember = keyboardInput.nextLine();

System.out.println("I like to go to " + place);
System.out.println(" When I go I bring my" + noun);
System.out.println(familyMember +"loves to go with me");
}
}



