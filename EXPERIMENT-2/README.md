# Experiment-2
## 2a) Title: Create a class methods and invoke them inside main method
## Source Code
``` java
class Rectangle{
double length;
double breadth;
double area(){
return breadth*length;
}
double perimeter(){
return 2*(length+breadth);
}
public static void main(String[] args){
Rectangle rect = new Rectangle();
rect.length = 10;
rect.breadth = 5;
double area = rect.area();
double perimeter = rect.perimeter();
System.out.println("area of the given rectangle:" +area);
System.out.println("perimeter of the given rectangle:" +perimeter);
}
}
```
## Output:
![Experiment-2a Output](2a.png)

## 2b)Title:Write a java program implement method overloading
## Source code
``` java
class Sum{
int sum(int a,int b){
return a+b;
}
int sum(int a,int b,int c){
return a+b+c;
}
double sum(double a,double b){
return a+b;
}
public static void main(String args[]){
Sum s= new Sum();
System.out.println("sum of 2 integer:" +s.sum(36,46));
System.out.println("sum of 3 integer:" +s.sum(20,36,46));
System.out.println("sum of two real numbers:" +s.sum(30.465,15.675));
}
}
```
## output:
![experiment-2b output](2b.pgn)




