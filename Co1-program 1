import java.util.Scanner;
class product
{
String pname,pcode;
double price;
void get()
{
Scanner input=new Scanner(System.in);
System.out.println("Enter the name of product:");
pname=input.nextLine();
System.out.println("Enter the code of product:");
pcode=input.nextLine();
System.out.println("Enter the price of product:");
price=input.nextDouble();
}
void display()
{
System.out.println("The Lowest product details:");
System.out.println("pname="+pname);
System.out.println("pcode="+pcode);
System.out.println("price="+price);
}
}
class Main
{
public static void main(String args[])
{
product p1=new product();
product p2=new product();
product p3=new product();
p1.get();
p2.get();
p3.get();
if(p1.price<p2.price && p1.price<p3.price)
{
p1.display();
}
else if(p2.price<p3.price)
{
p2.display();
}
else
{
p3.display();
}
}
}
