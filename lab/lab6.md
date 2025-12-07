public static int sanjiao(int n){
return n*(n+1)/2;

}

public static void main(String[] args) {
for(int i=1;i<=20;i++){
System.out.println(sanjiao(i));

}


}





   public static void multiPrint(int n, char c){
  for(int i=0;i<=n;i++){
System.out.print(c);
}
System.out.println(" ");
}

public static void main(String[] args) {
for(int i=0;i<=5;i++){
multiPrint(i,'c');
}
System.out.println(" ");
multiPrint(5,'c');
multiPrint(5,'c');
multiPrint(5,'c');
multiPrint(5,'c');
multiPrint(5,'c');



public static int[] reverseEach(int[] arr) {
int[] result = new int[arr.length];

for (int i = 0; i < arr.length; i++) {
int n = arr[i];
int rev = 0;
while (n != 0) {
rev = rev * 10 + (n % 10);
n /= 10;
}
result[i] = rev; }
    return result; }
public static void main(String[] args) {
int[] numbers = {1234, 56, 789, 900, 10, 444, 305, 81, 9, 1000};
int[] reversed = reverseEach(numbers);
for (int r : reversed) {
System.out.println(r);
  }
}
















    public static int ojld(int a,int b){
        int g=1;
    for(int i=1;i<a&&i<b;i++){
    if(a%i==0&&b%i==0){
         g =i;}
    }
    return g;
    }
        
    public static void main(String[] args) {
        int x=200;
        int y=625;
    System.out.print(ojld(x,y));






public static void dui(int a,int b,int c){
int n=0;
if(a*b==c){
n++;  }
System.out.print(n);
}
public static void main(String[] args) {   
Random rand=new Random();
int x=rand.nextInt(13);
int y=rand.nextInt(13);
Scanner input= new Scanner(System.in);
int u=input.nextInt();
dui(x,y,u);





