# java-program
sum of digits

class sum
{ public static void main()
{ Scanner sc= new Scanner(System.in);
System.out.println(" enter a number");
int a=sc.nextInt();
int sum=0;
for( int i=0;i>0;i=i/10)
{ int t= i%10;
sum=sum+t; }
System.out.println("sum of the digits of the number="+ sum);
}
}
