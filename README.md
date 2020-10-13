# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
echo "Hello World!";
?>


```
----------------------------------------


</br>

# Question 2

### **Question:**

> ***Write a program to add two numbers.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$num1=1;
$num2=5;
$sum = $num1 + $num2;
echo "Sum of the two numbers is : $sum";
?>



```
----------------------------------------

</br>

# Question 3

### **Question:**

> ***Write a program to subtract two numbers.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$num1=5;
$num2=1;
$sub = $num1 - $num2;
echo "difference of the two numbers is : $sub";
?>




```
----------------------------------------

</br>

# Question 4

### **Question:**

> ***Write a program to divide two numbers.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$num1=6;
$num2=2;
$div = $num1 / $num2;
echo "the division of two numbers is : $div";
?>






```
----------------------------------------


</br>


# Question 5

### **Question:**

> ***Write a program to multiply two numbers.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$num1 = 6;
$num2 = 2;
$mult = $num1 * $num2;
echo "the product of two numbers is : $mult";
?>


```
----------------------------------------


</br>



# Question 6

### **Question:**

> ***Write a program to find the area of a circle.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$radius = 2.0;
$pi = 3.14159;
$area = $pi * $radius * $radius;
echo("<br> radius = $radius centimeter");
echo("<br> area = $area centimeter square");
?>



```
----------------------------------------


</br>

# Question 7

### **Question:**

> ***Write a program to find the square root of a number.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$num1 = 4.0;
$num2 = sqrt($num1);
echo("The square root of a number = $num2");
?>




```
----------------------------------------

</br>

# Question 8

### **Question:**

> ***Write a program to find the cube root of a number.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$num1 = 6.0;
$num2 = pow(($num1), 1/3);
echo("The cube root of a number = $num2");
?>



```
----------------------------------------

</br>

# Question 9

### **Question:**

> ***Write a program to round off a number.***

---------------------------------------

<strong>Solution: </strong>

```php language

<?php
$num1 = 4.5;
$num2 = round ($num1);
echo("The round off of a number = $num2");
?>


```
----------------------------------------

</br>


# Question 10

### **Question:**

> ***Write a program to find the incremented and decremented values of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$num1 =2;
$num2=3;
$num3 = $num1 +1;
$num4 = $num1 - 1;
$num5 = $num2 +1;
$num6 = $num2 - 1;
echo ("The incremented value of  $num1 = $num3 ");
echo ("The decremented value of  $num1 = $num4 ");
echo ("The incremented value of  $num2 = $num5 ");
echo ("The decremented value of  $num2 = $num6 ");
?>


```
----------------------------------------

</br>


# Question 11

### **Question:**

> ***Write a program to find the greatest of two numbers using if – else statement.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$x = 4.5;
$y=5;
if($x>$y){
echo (" x is greater than y");
} else {
echo (" y is greater than x");
}
?>


```
----------------------------------------


</br>

# Question 12

### **Question:**

> ***Write a program to print the first ten natural numbers using for loop statement.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
for ($i=1; $i<=10; $i++)
echo ("$i");
?>



```
----------------------------------------


</br>

# Question 13

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php  
$i = 1;
while($i <= 10) {
echo "$i ";
$i++;
} 
?>




```
----------------------------------------


</br>


# Question 14

### **Question:**

> ***Write a program to print the first nine natural numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php  
$i = 1;
do {
echo "$i ";
$i++;
} while($i <= 9);
?>




```
----------------------------------------


</br>


# Question 15

### **Question:**

> ***Write a program to print the average of the first 10 numbers using for loop statement.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
$i; 
$avg; 
$sum = 0;
for( $i=1; $i<=10; $i++)
$sum = $sum + $i;
$avg = $sum/10;
echo "sum of the first 10 numbers = $sum ";
echo"average of the first 10 numbers = $avg  ";
?>





```
----------------------------------------


</br>


# Question 16

### **Question:**

> ***Write a program to add two numbers using PHP function.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
function addition($a, $b) {
return $a + $b;
}
$sum = addition(4, 3);
echo "the sum of two numbers = $sum ";
?>






```
----------------------------------------

</br>


# Question 17

### **Question:**

> ***Write a program to display the current date and time.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php
    $currentDateTime = date('Y-m-d H:i:s');
    echo $currentDateTime;
?>



```
----------------------------------------


</br>



# Question 18

### **Question:**

> ***Write a program to calculate area of a triangle with base as 20 and height as 25.***

---------------------------------------

<strong>Solution: </strong>

```php language

<?php  
 $base = 10;  
 $height = 15;  
 echo "area  = " . ($base * $height) / 2;  
 ?>  



```
----------------------------------------


</br>


# Question 19

### **Question:**

> ***Write a program to convert temperature from fahrenheit to celsius.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php  
 $far = 89;  
 $cel=($far - 32) * (5/9);
 echo "Temperature in Fahrenheit is : $far". "<br />"; 
 echo "Temperature in Celcius is : $cel" ; 
  ?> 



```
----------------------------------------

</br>

# Question 20

### **Question:**

> ***Write a program to print factorial of a number..***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php  
$num = 5;  
$fact = 1;  
for ($x=$num; $x>=1; $x--)   
{  
  $fact = $fact * $x;  
}  
echo "$fact";  
?> 

```
----------------------------------------

</br>


# Question 21

### **Question:**

> ***Write a program to reverse a given string.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php  
$str = "JavaScript";  
$len = strlen($str);  
for ($i=($len-1) ; $i >= 0 ; $i--)   
{  
  echo $str[$i];  
}  
?>  


```
----------------------------------------

</br>



# Question 22

### **Question:**

> ***Write a program to count the number of vowels in a given string.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php

function vowel_Count($string)
{
    preg_match_all('/[aeiou]/i', $string, $matches);
    return count($matches[0]);
}
print_r(vowel_Count('Python'));


?>



```
----------------------------------------

</br>


# Question 23

### **Question:**

> ***Write a program to find sum of array elements.***

---------------------------------------

<strong>Solution: </strong>

```php language


<?php
$a=array(1,2,3,4);
echo array_sum($a);
?>


```
----------------------------------------

</br>

# Question 24

### **Question:**

> ***Write a program to check whether a number is Even or Odd.***

---------------------------------------

<strong>Solution: </strong>

```php language
<?php  
$num=253;  
if($num%2==0)  
{  
 echo "$num is Even Number";   
}  
else  
{  
 echo "$num is Odd Number";  
}   
?>  

```
----------------------------------------

</br>

# Question 25

### **Question:**

> ***Write a program to list the first 15 prime numbers.***

---------------------------------------

<strong>Solution: </strong>

```php language

<?php  
$count = 0;  
$num = 2;  
while ($count < 15 )  
{  
$div=0;  
for ( $i=1; $i<=$num; $i++)  
{  
if (($num%$i)==0)  
{  
$div++;  
}  
}  
if ($div<3)  
{  
echo $num." </br> ";  
$count=$count+1;  
}  
$num=$num+1;  
}  
?> 


```
----------------------------------------


</br>


# Question 26

### **Question:**

> ***Write a program to reverse a given number.***

---------------------------------------

<strong>Solution: </strong>

```php language

<?php  
$num = 253;  
$rev = 0;  
while ($num > 1)  
{  
$rem = $num % 10;  
$rev = ($rev * 10) + $rem;  
$num = ($num / 10);   
}  
echo "$rev";  
?>  

```
----------------------------------------

</br>

# Question 27

### **Question:**

> ***Write a program to check whether 507 is Armstrong or not.***

---------------------------------------

<strong>Solution: </strong>

```php language

<?php  
$num=507;  
$total=0;  
$x=$num;  
while($x!=0)  
{  
$rem=$x%10;  
$total=$total+$rem*$rem*$rem;  
$x=$x/10;  
}  
if($num==$total)  
{  
echo "Armstrong number";  
}  
else  
{  
echo "No it is not an armstrong number";  
}  
?>  


```
----------------------------------------

</br>

# Question 28

### **Question:**

> ***Write a program to print table of a number.***

---------------------------------------

<strong>Solution: </strong>

```php language

<?php    
define('a', 7);   
for($i=1; $i<=10; $i++)   
{   
  echo "7 * $i = ", $i*a;   
  echo '<br>'; 
}  
?>

```
----------------------------------------

</br>


# Question 29

### **Question:**

> ***Write a program to print the first 12 numbers of a Fibonacci series.***

---------------------------------------

<strong>Solution: </strong>

```php language

<?php  
$num = 0;  
$n1 = 0;  
$n2 = 1;  
echo $n1.' '.$n2.' ';  
while ($num < 10 )  
{  
    $n3 = $n2 + $n1;  
    echo $n3.' ';  
    $n1 = $n2;  
    $n2 = $n3;  
    $num = $num + 1; 
    }
?>  

```
----------------------------------------


</br>


# Question 30

### **Question:**

> ***Write a program to swap two numbers 65 and 98 using a third variable.***

---------------------------------------

<strong>Solution: </strong>

```php language

<?php  
$a = 65;  
$b = 98;   
$c = $a;  
$a = $b;  
$b = $c;  
echo "After swapping:<br><br>";  
echo "a =".$a."  b=".$b;  
?>  
```
----------------------------------------

</br>


<h2>   Papers </h2>

<ul>

 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(1).pdf" style="text-decoration:none;">Use of Design Patterns in
PHP-Based Web Application Frameworks</a></li>


 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(2).pdf" style="text-decoration:none;">A Research Paper OnWebsite Development OptimizationUsing Xampp/PHP </a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(3).pdf" style="text-decoration:none;">Analysis and Practical Application of PHP Frameworks in Development of Web Information Systems</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(4).pdf" style="text-decoration:none;">Application of PHP and MySQL for search and retrieval Web services in Web information systems</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(5).pdf" style="text-decoration:none;">Web application development with Laravel PHP Framework version 4 </a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(6).pdf" style="text-decoration:none;">A Comparison Study of Web Based Application Development Using PHP and ASP.NET</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(7).pdf" style="text-decoration:none;">Application of Web Content Management System (WCMS) For Website Development And Maintenance Tools Using PHP</a></li>

 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(8).pdf" style="text-decoration:none;"> Securing PHP – Approaches to Web Application security</a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(9).pdf" style="text-decoration:none;">Performance Comparison of QEC Network based JAVA Application and Web based PHP Application</a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(10).pdf" style="text-decoration:none;">A new model for the selection of web development frameworks: application to PHP frameworks </a></li>
 
 
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(11).pdf" style="text-decoration:none;">PHP Application Architecture</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(12).pdf" style="text-decoration:none;">Selecting A PHP Framework For A Web Application Project — The Method And Case Study</a></li>

 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(13).pdf" style="text-decoration:none;"> Vulnerability Detection of php applications using Php-Code Analyzer before deploying web application</a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(14).pdf" style="text-decoration:none;">Web Security: Detection of Cross Site Scripting in PHP Web Application using Genetic Algorithm</a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(15).pdf" style="text-decoration:none;">Web Testing Application With PHP Automated Tool </a></li>
 
  <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(16).pdf" style="text-decoration:none;">Client-Side Validation and Verification of PHP Dynamic Websites</a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(17).pdf" style="text-decoration:none;">PHP Framework for Database Management Based on MVC Pattern </a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(18).pdf" style="text-decoration:none;">T100 – A Content Management System for PHP Web Applications Development </a></li>
 
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(19).pdf" style="text-decoration:none;"> Generating a PHP Metamodel using Xtext Framework</a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(20).pdf" style="text-decoration:none;">PHP modernization approach generating KDM models from PHP legacy code</a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(21).pdf" style="text-decoration:none;">Anti-WebShell PHP Backdoor Scanner pada Linux Server</a></li>
 
  <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(22).pdf" style="text-decoration:none;">Deploy PHP on Heroku</a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(23).pdf" style="text-decoration:none;">PHP MySQL to MySQLi migration </a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(24).pdf" style="text-decoration:none;">Simplification of Arithmetic and Variable Script in Hypertext Preprocessor (PHP)</a></li>
  
  <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(25).pdf" style="text-decoration:none;">Firebase And MySQL Performances For Data Exchanging With CSV File In PHP-based Website</a></li>
 
  <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(26).pdf" style="text-decoration:none;">PHP PDO MYSQL</a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(27).pdf" style="text-decoration:none;">Teaching The Basis Of Communication With The Server In PHP </a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(28).pdf" style="text-decoration:none;">Evaluation of PHP Framework Measured Using Object-Oriented Metrics with the Analytic Hierarchy Process</a></li>
    <li><a target="_blank" href="https://github.com/manjunath5496/PHP-Exercises-for-Beginners/blob/master/php(29).pdf" style="text-decoration:none;">Reasoned PHP</a></li>
  
  
   
  
  
  
  
  
</ul>

