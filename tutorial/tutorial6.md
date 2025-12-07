# Tutorial 6 Methods
-----

1. Write statements for each of the following:  
	a. Define a static method that returns the maximum number from 3 integer parameters.  
public static int max(int a,int b,int c){
    int max =a ;
2. if(b>a) max = b;
3. if(c>b) max = c;
4. return max;}

	b. Define a static method that that determine whether the given integer is a square number.  
public static booean square(int b){
   for(int i = 1;i<=n;i++){
   if(i*i=b)
   return false;}}
	c. Define a static method that use to compute combination function `C(n,k)`.  `C(n,k)` gives the number of different k-element subsets that can be found in a given set of n elements. `C(n,k) = n! / (k! (n-k)!`  
5. 
	d. Define a static method that used to determine whether the parameter is a pentagonal number. A pentagonal number is a figurate number that extends the concept of triangular and square numbers to the pentagon. `Pn = ½ n(3n -1)`
    public static boolean five(int t){
    for(int i =1;i>0;i++){
    int a =i*(3*i-1)/2;
    if(a==t){
    return false;}
    if(a>t){
    return true;
	e. Define a static method that displays the number of letters and the number of digits of a String parameter. 
6. public static void number(String a){
   int x=0;
   int y=0;
   for(int i = 0;i<=a.length();i++){
   char v=a.charAt(i);
   if(Character.isLetter(v)){
   x++;}
   else if(Character.isDigit(v)){
   y++;}
   }
   System.out.println("Letters: " + x);
   System.out.println("Digits: " + y);
   }
	f. Define a static void method that generates 10 random numbers within 0 to 100 to the method’s parameter. The random numbers can be accessed by the main method.  
7. public static int[] number(){
   Random rand = new Random();
   int a=rand.nextInt(100);
   int b=rand.nextInt(100);
   int c=rand.nextInt(100);
   int d=rand.nextInt(100);
   int e=rand.nextInt(100);
   int f=rand.nextInt(100);
   int g=rand.nextInt(100);
   int h=rand.nextInt(100);
   int i=rand.nextInt(100);
   int j=rand.nextInt(100);
   return new int[]{a,b,c,d,e,f,g,h,i,j};

}
	g. Define a static void method that returns the area and the circumference of a circle given the argument is radius. `Area = πr2` and `Circumference = 2 πr`.  
public static void roud(int r){
double Area=Math.PI*r*r;
double Circumference=Math.PI*2*r;
System.out.println(Area);
System.out.println(Circumference);
}
	h. Define a static method that generate random number within 0 – 10. The method will return the first random number that generate twice.  
public static int rand(){
Random rand = new Random();
for(int i=0;i>0;i++){
int i =rand.nextInt(10)

}
if(i=i){ 
I++;

}
return n}


2. Write a program that consists of a method that can display three numbers in decreasing order.

public static void three(int a, int b, int c) {
int temp;
if (a < b) { temp = a; a = b; b = temp; }
if (a < c) { temp = a; a = c; c = temp; }
if (b < c) { temp = b; b = c; c = temp; }
System.out.println(a + " " + b + " " + c);
}