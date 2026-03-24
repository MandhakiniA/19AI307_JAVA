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
You’re making changes in a project you don’t have write access to. Submitting a change will write it to a new branch in your fork MandhakiniA/19AI307_JAVA, so you can send a pull request.
19AI307_JAVA/Module-02/DAY-4
/
README.md
in
main

Edit

Preview
Indent mode

Spaces
Indent size

2
Line wrap mode

Soft wrap
Editing README.md file contents
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
# Ex.No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:
Write a class that uses a constructor to initialize variables and overrides toString() method.

## AIM:
To write a Java program that initializes object variables using a constructor and overrides the toString() method to display object details in a readable format.

## ALGORITHM :

1. Define a class Student with two instance variables:

     String name

     int age

2. Create a parameterized constructor to initialize these variables.

3. Override the toString() method to return the student details in a formatted string.

4. In the main() method:

    - Read the name and age from the user.

    - Create a Student object using the constructor.

5. Print the object, which automatically calls the overridden toString() method.

6. End the program.



## PROGRAM:


## SOURCE CODE:

```
import java.util.Scanner;

class Student {
    String name;
    int age;

    public Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    @Override
    public String toString() {
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
