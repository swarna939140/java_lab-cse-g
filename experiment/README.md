# EXPERIMNET-1:
##TITLE: 1a.)display default primitive data types
```
public class DefaultValuesDemo {
    static byte b;
    static short s;
    static int i;
    static long l;
    static float f;
    static double d;
    static char c;
    static boolean bool;

    public static void main(String[] args) {
        System.out.println("byte: " + b);
        System.out.println("short: " + s);
        System.out.println("int: " + i);
        System.out.println("long: " + l);
        System.out.println("float: " + f);
        System.out.println("double: " + d);
        System.out.println("char: [" + c + "]");
        System.out.println("boolean: " + bool);
    }
}
```
## output
![output for display](https://github.com/swarna939140/java_lab-cse-g/blob/0da43b9afde77d20e380b530261b4de1194408ba/Screenshot%20(3).png)
## title: 1b) discriminant
```
import java.util.Scanner;
class QuadraticEquationSolution {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a value of a:");
        double a = sc.nextDouble();
        System.out.println("Enter a value of b:");
        double b = sc.nextDouble();
        System.out.println("Enter a value of c:");
        double c = sc.nextDouble();
        double D = b * b - 4 * a * c;
        if (D > 0) {
            double x1 = (-b + Math.sqrt(D)) / (2 * a);
            double x2 = (-b - Math.sqrt(D)) / (2 * a);
            System.out.println("Roots are real and distinct:");
            System.out.println("x1 = " + x1);
            System.out.println("x2 = " + x2);
        }
        else if (D == 0) {
            double y = -b / (2 * a);
            System.out.println("The roots are real and equal:");
            System.out.println("y = " + y);
        }
        else {
            double real = -b / (2 * a);
            double img = Math.sqrt(-D) / (2 * a);
            System.out.println("Roots are complex:");
            System.out.println("x1 = " + real + " + " + img + "i");
            System.out.println("x2 = " + real + " - " + img + "i");
        }
        sc.close();
    }
}
```
## output:
![output for discriminant](https://github.com/swarna939140/java_lab-cse-g/blob/46202f99a6bc0f6783d5278e12898f758ec63950/1b.png)
## title 2a) reactangle
```
class rectangle{
double length;
double breadth;
double area{
recturn (length *breadth);
}
double perimeter{
return(2*length +b breadth);
}
}

class main{
public static void main (String args[]){
rectangle rect =new  rectangle ();
rect.length=10;
rect.breadth=5;
double area =rect.area();
double perimeter=rect.perimeter();
System.out.println("area of given rectangle:"+area);
System.out.println("perimeter of given rectangle:"+perimeter);
}
}

```
## output :
![output for rectangle](https://github.com/swarna939140/java_lab-cse-g/blob/7b24859261b5c68fc12a7b68584728c319467878/Screenshot%20(1).png)

