/question ( add two nuber using input from the user)
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        System.out.println("taking input from the user");
        Scanner s=new Scanner(System.in);
        System.out.println("enter the number 1");
        int a=s.nextInt();
        System.out.println("enter the number 1");
        int b=s.nextInt();
        int sum=a+b;
        System.out.println("adding of two numbers");
        System.out.println(sum);
    }
}

//out put 
java -cp /tmp/MYw6mhD0EH Main
taking input from the userenter the number 1
22
enter the number 1
33
adding of two numbers
55


// student percentage using input from the user



import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        System.out.println("taking input from the user");
        Scanner s=new Scanner(System.in);
        int total=100;
        System.out.println("enter the number marks");
        int a=s.nextInt();
        System.out.println("enter the number marks");
        int b=s.nextInt();
        System.out.println("enter the number marks");
        int c=s.nextInt();
        System.out.println("enter the number marks");
        int d=s.nextInt();
        System.out.println("enter the number marks");
        int e=s.nextInt();
        int sum=a+b+c+d+e;
        System.out.println(sum);
        float percentage=sum*100/500;
        System.out.println("your percentage is =" +percentage);
        }
}

//output

java -cp /tmp/MYw6mhD0EH Main
taking input from the user
enter the number marks
23
enter the number marks
44
enter the number marks
54
enter the number marks
34
enter the number marks
98
253
your percentage is =50.0

// question (what will be the result of the following expression) float a=7/4*9/2


class HelloWorld {
    public static void main(String[] args) {
        float a=7/4*9/2;
        System.out.println(a);
    }
    
    //output
    
    java -cp /tmp/A4X2pour0i HelloWorld
4.0

//(use comparision operator to find out wether a given nuber is greater then the user enterd number or not)

import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
        System.out.println(" enter the number using user input from the user :");
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        System.out.println("the given number is  ");
        System.out.println(a>10);
        
    }
}

//output

java -cp /tmp/A4X2pour0i HelloWorld
enter the number using user input from the user :12
the given number is  
true

//question (write the following expression in a java program)(v^2-u^2/2*a*s)

class HelloWorld {
    public static void main(String[] args) {
    int a=2; 
    int v=3;
    int u=4;
    int s=5;
     System.out.println(v^2-u^2/2*a*s);
    }
}
//output

java -cp /tmp/A4X2pour0i HelloWorld
-9

