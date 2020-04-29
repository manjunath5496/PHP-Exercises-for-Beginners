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
$num1 =1;
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
$num1 =5;
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
$num1 =6;
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
echo("\n radius = $radius centimeter");
echo("\n area = $area centimeter square");
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
echo("\n the cube root of a number = $num2");
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
echo("\n the round off of a number = $num2");
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
echo ("\n The incremented value of  $num1 = $num3 ");
echo ("\n The decremented value of  $num1 = $num4 ");
echo ("\n The incremented value of  $num2 = $num5 ");
echo ("\n The decremented value of  $num2 = $num6 ");
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
echo (" \n $i");
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
echo "\n  $i ";
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
echo "\n $i ";
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
echo "\n sum of the first 10 numbers = $sum ";
echo"\n average of the first 10 numbers = $avg  ";
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

> ***Write a program to sort an array of all prime numbers between 1 and a given integer.***

---------------------------------------

<strong>Solution: </strong>

```JS language

<!DOCTYPE html>
<html>
<body>
<script>
function sort_prime(num) {

  var prime_num1 = [],
      prime_num2 = [];
  for (var i = 0; i <= num; i++) {
    prime_num2.push(true);
  }
  for (var i = 2; i <= num; i++) {
    if (prime_num2[i]) {
      prime_num1.push(i);
      for (var j = 1; i * j <= num; j++) {
        prime_num2[i * j] = false;
      }
    }
  }

  return prime_num1;
}
document.write(sort_prime(11));
</script>
</body>
</html>



```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/28.html" target="_blank">
Try it Yourself &raquo; </a></div>
</br>


# Question 29

### **Question:**

> ***Write a program to check whether there is at least one element which occurs in two given sorted arrays of integers.***

---------------------------------------

<strong>Solution: </strong>

```JS language

<!DOCTYPE html>
<html>
<body>
<script>
function check_common_element(arra1, arra2) {
  for (var i = 0; i < arra1.length; i++)
  {
    if (arra2.indexOf(arra1[i]) != -1) 
      return true;
  }
  return false;
}
document.write(check_common_element([1,2,3], [3,4,5]));
</script>
</body>
</html>




```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/29.html" target="_blank">
Try it Yourself &raquo; </a></div>
</br>


# Question 30

### **Question:**

> ***Write a program to find the maximum difference between any two adjacent elements of a given array of integers.***

---------------------------------------

<strong>Solution: </strong>

```JS language

<!DOCTYPE html>
<html>
<body>
<script>
function max_difference(arr) {
	var max = -1;
    var temp;
	for (var i = 0; i < arr.length - 1; i++)
      {
		temp = Math.abs(arr[i] - arr[i + 1]);
		max = Math.max(max, temp);
	  }
	return max;
}

document.write(max_difference([1, 2, 3, 8, 9]));
</script>
</body>
</html>



```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/30.html" target="_blank">
Try it Yourself &raquo; </a></div>
</br>




