# Lab 1

## Q1: 
> Write a Java program with a method named 'totalSum' that takes in an argument of two integers and return its sum. Call this method from main( ) and print the results.


	public class totalSum {
	public static int totalSum(int number1, int number2) {
		return number1 + number2;
	}

	public static void main(String[] args) {
		System.out.println(totalSum(10,20));
		
        
	}
	}



## Q2:
> Write a Java program with a method named 'getGrades' that will display grades according to the marks entered into the method call as below:
```
Marks        Grade
91-100         A+
81-90          A-
71-80          B+
61-70          B-
51-60          C+
41-50          D-
<=40          Fail
```


		
	public class getGrades {
	public static String getGrades(int number) {
		if (number >= 91 && number <=100) {
			return "A+";
		}else if(number >=81 && number <=90){
			return "A-";
		}else if(number >=71 && number <=80) {
			return "B+";
		}else if(number >=61 && number <=70) {
			return "B-";
		}else if(number >=51 && number <=60) {
			return "C+";
		}else if(number >=41 && number <=50) {
			return "D-";
		}else if(number >0 && number <=40) {
			return "Fail";
		}else {
			return "Enter correct number";
		}	
	}
	
	public static void main(String[] args) {
		System.out.println("Your grade is "+ getGrades(90));
		
        
	}
	}



## Q3:
> Write a program to print the factorial of a number by defining a method named 'factorial'. Factorial of any number n is represented by n! and is equal to 1*2*3*....
``` 
4! = 1*2*3*4 = 24
3! = 3*2*1 = 6
2! = 2*1 = 2
Also,
1! = 1
0! = 0
```


	public class factorial {
	public static int factorial(int n) {
		if(n==0) {
			return 0;
		}else{	
		int total = 1;
		for( int i=n; i>1; i--) {
			total *=i;
		}
		return total;
		}
	}
	
	public static void main(String[] args) {
		System.out.println(factorial(0));
		
        
	}
	}



## Q4
> Write a Java method to create the area of a pentagon.



	
	public class areaOfPentagon {
	public static  double areaOfPentagon(double base, double height) {
		return base * height /2;
	}
	
	public static void main(String[] args) {
		System.out.println(AreaOfPentagon(3,2));
		
        
	}
	}


