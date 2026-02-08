TASK-1A:

import java.util.Scanner;
class EvenOddCount {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
int even = 0, odd = 0;
System.out.println("Enter 5 numbers:");
for(int i=0; i<5; i++){
int num = sc.nextInt();
if(num % 2 == 0)
even++;
else
odd++;
}
System.out.println("Even numbers = " + even);
System.out.println("Odd numbers = " + odd);
}
}


TASK_1B:

import java.util.Scanner;
class LastDigitSum {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
System.out.print("Enter first number: ");
int a = sc.nextInt();
System.out.print("Enter second number: ");
int b = sc.nextInt();
int sum = (a % 10) + (b % 10);
System.out.println("Sum of last digits = " + sum);
}
}


TASK-1C:

import java.util.Scanner;
class PrimeCheck {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
System.out.print("Enter a number: ");
int n = sc.nextInt();
boolean isPrime = true;
if(n <= 1){
isPrime = false;
} else {
for(int i = 2; i <= Math.sqrt(n); i++){
if(n % i == 0){
isPrime = false;
break;
}
}
}
if(isPrime)
System.out.println("Prime Number");
else
System.out.println("Not a Prime Number");
}
}


TASK-1D:

import java.util.Scanner;
class Factorial {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
System.out.print("Enter a number: ");
int n = sc.nextInt();
long fact = 1;
for(int i=1; i<=n; i++){
fact *= i;
}
System.out.println("Factorial = " + fact);
}
}


TASK-1E:

import java.util.Scanner;
class Fibonacci {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
System.out.print("Enter N: ");
int n = sc.nextInt();
int a = 0, b = 1, c = 0;
if(n == 0)
System.out.println("Fibonacci = 0");
else if(n == 1)
System.out.println("Fibonacci = 1");
else {
for(int i = 2; i <= n; i++){
c = a + b;
a = b;
b = c;
}
System.out.println("Fibonacci = " + c);
}
}
}
