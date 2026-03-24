Skip to content
Vinothkumar-honesty
19AI307_JAVA
Repository navigation
Code
Pull requests
Actions
Projects
Security
Insights
19AI307_JAVA/Module-03
/DAY-5(B)/
Go to file
t
Vinothkumar-honesty
Vinothkumar-honesty
Update developer name and registration number
156e7e6
 · 
1 hour ago
This branch is 18 commits ahead of and 22 commits behind Priyasenthil17/19AI307_JAVA:main.
19AI307_JAVA/Module-03
/DAY-5(B)/
Name	Last commit message	Last commit date
..
README.md
Update developer name and registration number
1 hour ago
README.md
Ex.No:3(F) WRAPPER CLASS
QUESTION:
Find the largest digit in a number using wrapper class methods.

AIM:
To write a Java program to find the largest digit in a given number using Wrapper Class methods.

ALGORITHM :
Start the program.
Import the necessary package 'java.util'
Read the number from the user.
Convert the number to a string using wrapper class Integer.toString().
Traverse each character, convert it back to an integer using Character.getNumericValue().
Compare digits and store the largest digit.
Display the largest digit.
Stop the program.
PROGRAM:

SOURCE CODE:
import java.util.Scanner;

public class LargestDigit {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String input = sc.nextLine(); 

        int largest = 0;

        for (int i = 0; i < input.length(); i++) 
        {
            int digit = Character.getNumericValue(input.charAt(i));
            if (digit > largest) {
                largest = digit;
            }
        }

        System.out.println("The largest digit is: " + largest);
        sc.close();
    }
}
OUTPUT:
java36

RESULT:
Thus, the program to find the largest digit in a number using Wrapper Class methods was successfully executed.

 
