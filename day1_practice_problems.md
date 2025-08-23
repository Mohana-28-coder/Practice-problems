********************DAY-1 PRACTICE PROBLEM**************************

1.Problem Statement:
Print the following output : Let's learn 'JAVA' together with Selvi
Input Format:
NA
Output Format:
Let's learn 'JAVA' together with Selvi

public class Main{
public static void main(String[] args) 
{
 System.out.println("Let's learn 'JAVA' together with Priya");
}
}


2.Problem Statement:
Print the following output : If you want to shine like a "Sun",first burn like a "Sun".
Input Format:
NA
Output Format:
If you want to shine like a "Sun",first burn like a "Sun".

public class Main{
public static void main(String[] args) 
{
 System.out.println("If you want to shine like a \"Sun\",first burn like a \"Sun\".");
}
}




3.Problem Statement:
Print the following output : \n ,%%, \
Input Format:
NA
Output Format:
\n

public class Main{
public static void main(String[] args) 
{
 System.out.println("\\n");
}
}

4.Problem Statement:
Declare 2 integer variables and initialize their values as 20 and 10
Input Format:
NA
Output Format:
Print the stored the values as space separated.


public class Main{
public static void main(String[] args) {
    int a=20;
    int b=30;
    System.out.println(a+" "+b);
}
}




5.Problem Statement:
Accept a character and print the character
Input Format:
Accept  a character as a input.
Output Format:
Print the Character

import java.util.*;
public class Main{
public static void main(String[] args) {
    Scanner sc= new Scanner(System.in);
    char character= sc.next().charAt(0);
    System.out.println(character);
}
}

6.Problem Statement:
Given 2 numbers, print the first number as a 5-digit number and print the second number in the next line with 5 width space
Explanation: If numbers are 25 and 98,print the first number as 00025 and second number as 3 space and 98(   98).
Input Format:
Accept the two integer as a input
Output Format:
5 digit number format followed by number with 5 width space in new line.

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int num1 = scanner.nextInt();
        int num2 = scanner.nextInt();
        System.out.printf("%05d \n %5d", num1, num2);
    }
}


7.Problem Statement:
Accept a character and print its corresponding ASCII value.
Input Format:
Accept a character as input.
Output Format:
Input character:ASCII value

import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        char letter= sc.next().charAt(0);
        int Asciivalue= letter;
        System.out.println(letter+":"+Asciivalue);
}
}

8.Accept an integer value and print the corresponding character associated with the integer value.

import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        int Asciivalue= sc.nextInt();
           char character= (char)Ascii; 
           System.out.println(Asciivalue+":"+character);
}
}

9.Accept a floating point value and print it with 20 width space and round off to 4 decimal places.
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        float num = scanner.nextFloat();
        System.out.printf("%20.4f\n", num);
    }
}


10.Accept a floating point  value and precision value and print the floating point  value according to the precision given.

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        float floatValue = scanner.nextFloat();
        int precision = scanner.nextInt();
                 System.out.printf("%." + precision + "f", floatValue);
    }
}

11.Display the given floating point value to its nearest integer value

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        float a = scanner.nextFloat();
                System.out.println(Math.round(a));
    }
}


12.Accept a number that starts with 0x it indicates that the number is a hexadecimal value. Print the corresponding decimal value.
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
         String input = scanner.next();


                System.out.println(Integer.decode(input));
    }
}
13.Get a value and print its corresponding hexadecimal number
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int input = scanner.nextInt();

        System.out.println(Integer.toHexString(input));
    }
}
14.Get a floating point value and print the floating point value without any trailing zeros.
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String input = sc.next();
        System.out.println(input.replaceAll("0*$", "").replaceAll("\\.$", ""));
    }
}


15.Print the statement using concatenation
public class hello{
    public static void main(String[] args) {
        String sent1 = "Welcome to ";
        String sent2= "my Java World!!..";
        String result = sent1 + "" + sent2; // Concatenation
        System.out.println(result); // Output: Welcome to my Java World
    }
}
