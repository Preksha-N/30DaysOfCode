/**************************************************
Problem statement
Example 
 
a=3
b=7
Return 10
Return .
Function Description
Complete the solveMeFirst function in the editor below.
solveMeFirst has the following parameters:
int a: the first value
int b: the second value
Returns 
- int: the sum of  and 
   **************************************************/
 import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {


    static int solveMeFirst(int a, int b) {
      	return a+b;

   }

 public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int a;
        a = in.nextInt();
        int b;
        b = in.nextInt();
        int sum;
        sum = solveMeFirst(a, b);
        System.out.println(sum);
   }
}
