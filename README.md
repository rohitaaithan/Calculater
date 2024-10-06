# Calculater
import java.util.*;
public class Calc{
public static void main(String args[]){
Scanner sc = new Scanner(System.in);
while(true){
System.out.println("Enter the Value of A");
double a = sc.nextDouble();
System.out.println("Press 1 for +");
System.out.println("Press 2 for -");
System.out.println("Press 3 for *");
System.out.println("Press 4 for /");
System.out.println("Press 5 for %");
System.out.println("Press 6 for Exit");
int operation = sc.nextInt();
System.out.println("Enter the Value of B");
double b = sc.nextDouble();
double res;
switch(operation){
case 1:
res = a+b;
System.out.println("Result is "+ res);
break;
case 2:
res = a-b;
System.out.println("Result is "+ res);
case 3:
res = a*b;
System.out.println("Result is "+ res);
break;
case 4:
res = a/b;
System.out.println("Result is "+ res);
break;
case 5:
res = a%b;
System.out.println("Result is "+ res);
break;
case 6:
System.out.println("Thank You");
sc.close();
default:
System.out.println("Invalid choice");
}
}
}
}

