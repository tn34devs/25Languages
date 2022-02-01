
# 25 Languages - Basic Program

|TN34DeVs | January 30, 2022 |
|-------------------------|--|

If you find this useful, Subscribe to Our Channel [TN34DeVs](https://www.youtube.com/channel/UCnWgev1Pr7mneQWYBJK21mA)
  

**Output for all of the programs are same as below:**

 - > Welcome to TN34DeVs
  - > Number 1: 13 Number 2: 31
 -  > Total of Numbers 1 and 2 = 44
 -  > The Boolean Value: true

   

**1.C - 1972**

	
	#include<stdio.h>  
	#include<stdbool.h>  
	int main()  
	{  
	    int number1 = 13;
	    int number2 = 31;
	    char string1[] = "Welcome to TN34DeVs";
	    bool isAvailable = true;

	    printf("\n%s",string1);
	    printf("\nNumber 1: %d,Number 2: %d",number1,number2);
	    printf("\nTotal of Numbers 1 and 2 = %d",number1+number2);
	    printf("\nThe Boolean Value: %d",isAvailable);
	    
	    return 0;  
	}  

[IDE Link](http://tpcg.io/KZXZOD)

  

----------

**2.C++ - 1985**

	#include <iostream>

	using namespace std;

	int main()
	{
	    int number1 = 13;
	    int number2 = 31;
	    char string1[] = "Welcome to TN34DeVs";
	    bool isAvailable = true;
	    cout<<string1<<endl;
	    cout<<"Number 1: "<<number1<<",Number 2: "<<number2<<endl;
	    cout<<"Total of Numbers 1 and 2 = "<<number1+number2<<endl;
	    cout<<"The Boolean Value: "<<isAvailable;
	    return 0;
	}

[IDE Link](http://tpcg.io/91CU20)

  

**[3.JAVA](http://3.java/) - 1995**

### Java 1.8

	public class HelloWorld{

	    public static void main(String []args){
	       
	    int number1 = 13;
	    int number2 = 31;
	    String string1 = "Welcome to TN34DeVs";
	    Boolean isAvailable = true;

	    System.out.println(string1);
	    System.out.println("Number 1: "+number1+"Number 2: "+number2);
	    System.out.println("Total of Numbers 1 and 2 = "+(number1+number2));
	    System.out.println("The Boolean Value: "+isAvailable);
	    }
	}

[IDE Link](http://tpcg.io/FTEC4R)

  

### Java 10+

	class HelloWorld{

	    public static void main(String []args){
	       
	    var number1 = 13;
	    var number2 = 31;
	    var string1 = "Welcome to TN34DeVs";
	    var isAvailable = true;

	    System.out.println(string1);
	    System.out.println("Number 1: "+number1+"Number 2: "+number2);
	    System.out.println("Total of Numbers 1 and 2 = "+(number1+number2));
	    System.out.println("The Boolean Value: "+isAvailable);
	    }
	}

[IDE Link](https://ideone.com/Ck5SYD)

  

**4.Python3 - 1991**

### Approach 1
	
	number1 = 13
	number2 = 31
	string1 = "Welcome to TN34DeVs"
	isAvailable = True

	print(string1)
	print("Number 1: ",number1,"Number 2: ",number2)
	print("Total of Numbers 1 and 2 = ",(number1+number2))
	print("The Boolean Value: ",isAvailable)

[IDE Link](https://ideone.com/g2PoD1)

  

### Approach 2
	
	number1 = 13
	number2 = 31
	string1 = "Welcome to TN34DeVs"
	isAvailable = True

	print(string1)
	print("Number 1: {0}, Number 2: {1}".format(number1,number2))
	print(f"Total of Numbers 1 and 2 = {(number1+number2)}")
	print(f"The Boolean Value: {isAvailable}")

[IDE Link](https://ideone.com/Er4lAs)

  

  

**5.JavaScript / Node.js - 1995/2009**

### Approach 1

	number1 = 13
	number2 = 31
	string1 = "Welcome to TN34DeVs"
	isAvailable = true

	console.log(string1);
	console.log("Number 1: "+number1+"Number 2: "+number2);
	console.log("Total of Numbers 1 and 2 = "+(number1+number2));
	console.log("The Boolean Value: "+isAvailable);

[IDE Link](http://tpcg.io/YCMW9L)

  

### Approach 2

	number1 = 13
	number2 = 31
	string1 = "Welcome to TN34DeVs"
	isAvailable = true

	console.log(string1);
	console.log(`Number 1: ${number1} Number 2: ${number2}`);
	console.log(`Total of Numbers 1 and 2 = ${(number1+number2)}`);
	console.log(`The Boolean Value: ${isAvailable}`);

[IDE Link](http://tpcg.io/USRWI0)

  

**6.Go - 2009**

### Approach 1

	package main
	import "fmt"

	func main() {
	    var number1 int = 13
	    var number2 int = 31
	    var string1 string = "Welcome to TN34DeVs"
	    var isAvailable bool = true

	    fmt.Printf("\n%s",string1)
	    fmt.Printf("\nNumber 1: %d,Number 2: %d",number1,number2)
	    fmt.Printf("\nTotal of Numbers 1 and 2 = %d",number1+number2)
	    fmt.Printf("\nThe Boolean Value: %v",isAvailable)
	}

[IDE Link](http://tpcg.io/QK2GSW)

  

### Approach 2

	package main
	import "fmt"

	func main() {
	    number1 := 13
	    number2 := 31
	    string1 := "Welcome to TN34DeVs"
	    isAvailable := true

	    fmt.Println(string1)
	    fmt.Println("Number 1:",number1,"Number 2:",number2)
	    fmt.Println("Total of Numbers 1 and 2 =",number1+number2)
	    fmt.Println("The Boolean Value:",isAvailable)
	}

[IDE Link](http://tpcg.io/8RV1PI)

  

**7.TypeScript - 2012**

### Approach 1

	var number1 = 13
	var number2 = 31
	var string1 = "Welcome to TN34DeVs"
	var isAvailable = true

	console.log(string1);
	console.log(`Number 1: ${number1} Number 2: ${number2}`);
	console.log(`Total of Numbers 1 and 2 = ${(number1+number2)}`);
	console.log(`The Boolean Value: ${isAvailable}`);

[IDE Link](https://www.typescriptlang.org/play?ssl=9&ssc=50&pln=1&pc=1&q=100#code/G4QwTgBAdgrgtgIwKZgIwQLwVQZgLABQoksiKATJhDqocRAM4AuYAllAObpYBEA6kgA2AYwD2cJBCaiIAFQByOACwARJADUGPOuAisGAQVCtBIBIMlYWMJIUJioDURYB0g0RwAUzNp1QBKAG57UUdnJDcPTwADeXhkSFQALggAEgBvUgTUAF8IOLJIchSMrIoc6KCQsNd3L2jZUSYQQQhRADN8+JQGbAgQKAATCEosDM8ytABqSfJ-CqqCBydaqIaAC0kAIVFwgYh1FpsS9P0jEBMzCwXAoA)

  

### Approach 2

	var number1: number = 13
	var number2: number = 31
	var string1: String = "Welcome to TN34DeVs"
	var isAvailable: boolean = true

	console.log(string1);
	console.log(`Number 1: ${number1} Number 2: ${number2}`);
	console.log(`Total of Numbers 1 and 2 = ${(number1+number2)}`);
	console.log(`The Boolean Value: ${isAvailable}`);

[IDE Link](https://www.typescriptlang.org/play?&q=100#code/G4QwTgBAdgrgtgIwKZgIwC5r2ZAvBVAZgFgAoUSWRFAJkypwn0NTIogGcAXMASygDmGCAGUe-AUwgAiAOpIANgGMA9nCQQuKiABUAcoQAsAESQA1DtLbgIvDgEFQvBSAQKkmBCpXuQUKTwwSGRkqlAcPkgAdAoqAgAU3HyCqACUANyhKuGRMXHxAAZ62CgEmAAkAN4MKKgAvhDF1JB0EFU1YDR1BRlZOe55CQU6KlwgChAqAGaNJWAcBBB+ACYQNFJV8R2oANQdNKndvaRhEQOxQzoAFhoAQt6+-mbjQRWVdo4gzq7uR+lAA)

  

**8.Rust - 2010**

	fn main() {
	    let number1 = 13;
	    let number2:i32 = 31;
	    let string1:&str = "Welcome to TN34DeVs";
	    let is_available:bool = true;
	    println!("{}",string1);
	    println!("Number 1: {} Number 2: {}",number1,number2);
	    println!("Total of Numbers 1 and 2 = {}",(number1+number2));
	    println!("The Boolean Value: {}",is_available);
	}

[IDE Link](http://tpcg.io/4IDG7G)

  

**9.Ruby - 1995**

	number1 = 13
	number2 = 31
	string1 = "Welcome to TN34DeVs"
	isAvailable = true

	print(string1)
	print("\nNumber 1: ",number1,"Number 2: ",number2)
	print("\nTotal of Numbers 1 and 2 = ",(number1+number2))
	print("\nThe Boolean Value: ",isAvailable)

[IDE Link](http://tpcg.io/V3VT6C)

  

**10.Perl - 1988**

	$number1 = 13;
	$number2 = 31;
	$string1 = "Welcome to TN34DeVs";
	$isAvailable = 1;

	print $string1;
	print("\nNumber 1: ",$number1," Number 2: $number2");
	print("\nTotal of Numbers 1 and 2 = ",($number1+$number2));
	print("\nThe Boolean Value: ",($isAvailable)?true:false);

[IDE Link](http://tpcg.io/S4MFIM)

  

**11.PHP - 1995**

	<?php
	$number1 = 13;
	$number2 = 31;
	$string1 = "Welcome to TN34DeVs";
	$isAvailable = 1;

	echo $string1;
	echo "\nNumber 1: ",$number1," Number 2: $number2";
	echo "\nTotal of Numbers 1 and 2 = ",($number1+$number2);
	echo "\nThe Boolean Value: ",($isAvailable)?true:false;
	?>

[IDE Link](https://onecompiler.com/php/3xh55nqyv)

  

**12.Kotlin - 2011**

	fun main(args: Array<String>) {
	    var number1 = 13;
	    var number2 = 31;
	    var string1 = "Welcome to TN34DeVs";
	    var isAvailable = true;

	    println(string1);
	    println("Number 1: "+number1+"Number 2: "+number2);
	    println("Total of Numbers 1 and 2 = "+(number1+number2));
	    println("The Boolean Value: "+isAvailable);
	}

[IDE Link](https://onecompiler.com/kotlin/3xh55ypvy)

  

**13.C# - 2000**

	using System;
	using System.Collections.Generic;
	using System.Linq;
	using System.Text.RegularExpressions;

	namespace HelloWorld
	{
	public class Program
	{
	    public static void Main(string[] args)
	    {
	        int number1 = 13;
	        int number2 = 31;
	        string string1 = "Welcome to TN34DeVs";
	        bool isAvailable = true;
	    
	        Console.WriteLine(string1);
	        Console.WriteLine("Number 1: "+number1+" Number 2: "+number2);
	        Console.WriteLine("Total of Numbers 1 and 2 = "+(number1+number2));
	        Console.WriteLine("The Boolean Value: "+isAvailable);
	    }
	  }
	}

[IDE Link](http://tpcg.io/NPMS19) [IDE Link2](https://onecompiler.com/csharp/3xh56d6jz)

  

**14.Swift - 2014**

	var number1 = 13
	var number2:Int = 31
	var string1 = "Welcome to TN34DeVs"
	var isAvailable:Bool = true

	print(string1)
	print("Number 1: \(number1) Number 2: \(number2)")
	print("Total of Numbers 1 and 2 = ",(number1+number2))
	print("The Boolean Value: ",isAvailable)

[IDE Link](https://onecompiler.com/swift/3xjgevfvt)

  

**15.Dart - 2011**

	void main() {
	  num number1 = 13;
	  num number2 = 31;
	  String string1 = "Welcome to TN34DeVs";
	  bool isAvailable = true;

	  print(string1);
	  print("Number 1: "+number1.toString()+"Number 2: "+number2.toString());
	  print("Total of Numbers 1 and 2 = "+(number1+number2).toString());
	  print("The Boolean Value: "+isAvailable.toString());
	}

[IDE Link](http://tpcg.io/WK8X59)

  

**16.R - 1993**

	number1 = 13
	number2 = 31
	string1 = "Welcome to TN34DeVs"
	isAvailable = TRUE

	print(string1)
	print(paste("Number 1: ",number1,"Number 2: ",number2))
	print(paste("Total of Numbers 1 and 2 = ",(number1+number2)))
	print(paste("The Boolean Value: ",isAvailable))

[IDE Link](http://tpcg.io/ZBE5PU)

  

**17.Scala - 2004**

	object HelloWorld {
	   def main(args: Array[String]) {
	    var number1 = 13;
	    var number2 = 31;
	    var string1 = "Welcome to TN34DeVs";
	    var isAvailable = true;

	    println(string1);
	    println("Number 1: "+number1+"Number 2: "+number2);
	    println("Total of Numbers 1 and 2 = "+(number1+number2));
	    println("The Boolean Value: "+isAvailable);
	   }
	}

[IDE Link](http://tpcg.io/2JSGXO)

  

**18.Haskell - 1990**

	main = do 
	   let number1 = 13
	   let number2 = 31
	   let string1 = "Welcome to TN34DeVs"
	   let isAvailable = True;
	   
	   print(string1)
	   putStrLn ("Number 1: "++show number1++"Number 2: "++show number2)
	   putStrLn ("Total of Numbers 1 and 2 = "++show (number1+number2))
	   putStrLn ("The Boolean Value: "++show isAvailable)

[IDE Link](https://onecompiler.com/haskell/3xjgnyfs9)

  

**19.Julia - 2012**

	number1 = 13
	number2 = 31
	string1 = "Welcome to TN34DeVs"
	isAvailable = true

	println(string1)
	println("Number 1: ",number1,"Number 2: ",number2)
	println("Total of Numbers 1 and 2 = ",(number1+number2))
	println("The Boolean Value: ",isAvailable)

[IDE Link](http://tpcg.io/HWY1HB)

  

**20.Lisp - 1958**
	
	(setq number1 13)
	(setq number2 31)
	(setq string1 "Welcome to TN34DeVs")
	(setq isAvailable T)

	(write-line string1)
	(format t "Number 1 = ~2d Number 2 = ~2d ~%" number1 number2)
	(format t "Total of Numbers 1 and 2 = ~2d ~%" (+ number1 number2))
	(princ "The Boolean Value: " ) 
	(princ isAvailable)

[IDE Link](http://tpcg.io/ASF5CC)

  

**21.Lua - 1993**

	number1 = 13
	number2 = 31
	string1 = "Welcome to TN34DeVs"
	isAvailable = true

	print(string1)
	print("Number 1: ",number1,"Number 2: ",number2)
	print("Total of Numbers 1 and 2 = ",(number1+number2))
	print("The Boolean Value: ",isAvailable)

[IDE Link](https://onecompiler.com/lua/3xjp486ju)

  

**22.Fortran - 1957**

	program hello
	  integer:: number1 = 13
	  integer:: number2 = 31
	  character(len=19):: string1 = "Welcome to TN34DeVs"
	  logical :: isAvailable =.TRUE. 
	  
	print *, string1
	print *, "Number 1: ", number1, "Number 2: ", number2
	print *, "Total of Numbers 1 and 2 = ",(number1+number2)
	print *, "The Boolean Value: ",isAvailable
	end program hello

[IDE Link](https://onecompiler.com/fortran/3xjp4fhsu)

  

**23.Pascal - 1970**

	program Hello;
	var
	  number1: integer = 13;
	  number2: integer = 31;
	  string1: string = 'Welcome to TN34DeVs';
	  isAvailable: boolean = true;
	begin
	  writeln (string1);
	  writeln ('Number 1: ',number1,' Number 2: ',number2);
	  writeln ('Total of Numbers 1 and 2 = ',(number1+number2));
	  writeln ('The Boolean Value: ',isAvailable);
	end.

[IDE Link](https://onecompiler.com/pascal/3xjp66yd9)

  

**24.ADA - 1980**

	with Ada.Text_IO; use Ada.Text_IO;
	procedure Hello is
	    number1 : Integer := 13;
	    number2 : Integer := 31;
	    string1 : String := "Welcome to TN34DeVs";
	    isAvailable : Boolean := true;
	    total : Integer;
	begin
	    Put_Line(string1);
	    total := number1+number2;
	    Put_Line("Number 1:"& number1'Image &" Number 2:"& number2'Image);
	    Put_Line("Total of Numbers 1 and 2 = " &total'Image);
	    Put("The Boolean Value: "&isAvailable'Image);
	end Hello;

[IDE Link](https://onecompiler.com/ada/3xjp72zn3)

  

**25.NIM - 2008**

	import strformat

	var number1 = 13
	let number2 = 31
	let string1 = "Welcome to TN34DeVs"
	let isAvailable = true

	echo(string1)
	echo(fmt"Number 1: {number1} Number 2: {number2}")
	echo("Total of Numbers 1 and 2 = ",(number1+number2))
	echo("The Boolean Value: ",isAvailable)

[IDE Link](https://play.nim-lang.org/#ix=3Gh8) [IDE Link2](https://ideone.com/vslyAC)


**Keep Visiting for more interesting Codeeeeeeeeeeeee..... ;-) **
