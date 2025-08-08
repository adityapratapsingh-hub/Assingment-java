# Assingment-java
#Q1. Create a class StudentInfo with a method displayInfo() that prints your name, age, and grade.

class StudentInfo {
    void displayInfo() {
        System.out.println("Name: Aman Sharma");
        System.out.println("Age: 16");
        System.out.println("Grade: 10th");
    }

    public static void main(String[] args) {
        StudentInfo student = new StudentInfo();
        student.displayInfo();
    }
}
#Q2. Create a class Calculator with a method addNumbers() that adds two numbers and prints the result

import java.util.*;
public class calculator{
    public void add(){
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        int sum = a+b;
        System.out.println("Sum ="+sum);
    }
    public static void main(String args[]){
        calculator su =new calculator();
        su.add();
    }
}

#Q3. Create a class Greeting with a method sayHello() that takes your name as a parameter and prints:
public class greeting {

    public void say(String name) {
        System.out.println("hello, " + name + "! welcome to java programming.");
    }

    public static void main(String[] args) {
        greeting obj = new greeting();
        obj.say("aditya"); 
    }
}

#Q4. Create a class Circle with a method calculateArea() that calculates and prints the area of a circle.

import java.util.*;
public class Circle{
    public void calArea(){
        Scanner sc = new Scanner(System.in);
        int radius=sc.nextInt();
        double area=(3.14f*radius*radius);
        System.out.println("Area of the = "+area);
    }
    public static void main(String args[]){
        Circle a=new Circle();
        a.calArea();
    }
}

Q5. Create a class SimpleInterest with a method calculateInterest() that calculates simple interest.
import java.util.*;
class SimleInterest{
    public void calInterest(){
        Scanner sc = new Scanner(System.in);
        int p =sc.nextInt();
        int r =sc.nextInt();
        int t =sc.nextInt();
        double SI = (p*r*t)/100;
        System.out.println("SimleInterest = "+SI);
    }
    public static void main(String args[]){
        SimleInterest Si = new SimleInterest();
        Si.calInterest();
    }
}
