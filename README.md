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

> ***Write a program to find the area of a triangle where lengths of the three of its sides are 5, 6, 7.***

---------------------------------------

<strong>Solution: </strong>

```JS language
<!DOCTYPE html>
<html>
<body>
<script>
var side1 = 5; 
var side2 = 6; 
var side3 = 7; 
var s = (side1 + side2 + side3)/2;
var area =  Math.sqrt(s*((s-side1)*(s-side2)*(s-side3)));
document.write(area);
</script>
</body>
</html>



```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/18.html" target="_blank">
Try it Yourself &raquo; </a></div>
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

> ***Write a program to get the website URL (loading page).***

---------------------------------------

<strong>Solution: </strong>

```JS language
<!DOCTYPE html>
<html>
<body>
<script>
alert(document.URL);
</script>
</body>
</html>

```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/20.html" target="_blank">
Try it Yourself &raquo; </a></div>
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

```JS language
<!DOCTYPE html>
<html>
<body>
<script>
function vowel_Count(str)
{ 

  return str.replace(/[^aeiou]/g, "").length; 
}
document.write(vowel_Count("Python")); 
</script>
</body>
</html>



```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/22.html" target="_blank">
Try it Yourself &raquo; </a></div>
</br>


# Question 23

### **Question:**

> ***Write a program to find sum of array elements.***

---------------------------------------

<strong>Solution: </strong>

```JS language

<!DOCTYPE html>
<html>
<body>
<script>
var num = [1,2,3,4]
var sum = 0;
for(var i = 0; i < num.length; i++){
  sum += num[i]
}
document.write(sum);
</script>
</body>
</html>

```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/23.html" target="_blank">
Try it Yourself &raquo; </a></div>
</br>

# Question 24

### **Question:**

> ***Write a program to create the dot products of two given 3D vectors.***

---------------------------------------

<strong>Solution: </strong>

```JS language

<!DOCTYPE html>
<html>
<body>
<script>
function dot_product(vector1, vector2) {
  var result = 0;
  for (var i = 0; i < 3; i++) {
    result += vector1[i] * vector2[i];
  }
  return result;
}
document.write(dot_product([1,2,3], [1,2,3]))
</script>
</body>
</html>


```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/24.html" target="_blank">
Try it Yourself &raquo; </a></div>
</br>

# Question 25

### **Question:**

> ***Write a program to find the number of even digits in a given integer.***

---------------------------------------

<strong>Solution: </strong>

```JS language

<!DOCTYPE html>
<html>
<body>
<script>
function even_digits(num) {
  var ctr = 0;
  while (num) {
    ctr += num % 2 === 0;
    num = Math.floor(num / 10);
  }
  return ctr;
}
document.write(even_digits(124));
</script>
</body>
</html>


```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/25.html" target="_blank">
Try it Yourself &raquo; </a></div>
</br>


# Question 26

### **Question:**

> ***Write a program to change the capitalization of all letters in a given string.***

---------------------------------------

<strong>Solution: </strong>

```JS language

<!DOCTYPE html>
<html>
<body>
<script>
function change_case(txt) {
    var str1 = "";
    for (var i = 0; i < txt.length; i++) {
        if (/[A-Z]/.test(txt[i])) str1 += txt[i].toLowerCase();
        else str1 += txt[i].toUpperCase();
    }
    return str1;
}
document.write(change_case("germany"));
</script>
</body>
</html>


```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/26.html" target="_blank">
Try it Yourself &raquo; </a></div>
</br>

# Question 27

### **Question:**

> ***Write a program to remove all characters from a given string that appear more than once.***

---------------------------------------

<strong>Solution: </strong>

```JS language

<!DOCTYPE html>
<html>
<body>
<script>
function remove_duplicate_cchars(str) {
  var arr_char = str.split("");
  var result_arr = [];

  for (var i = 0; i < arr_char.length; i++) {
    if (str.indexOf(arr_char[i]) === str.lastIndexOf(arr_char[i]))
      result_arr.push(arr_char[i]);
    }

  return result_arr.join("");
}
document.write(remove_duplicate_cchars("abcdabc"));
</script>
</body>
</html>




```
----------------------------------------

<a class="w3-btn w3-margin-bottom" href="https://manjunath5496.github.io/JavaScript/27.html" target="_blank">
Try it Yourself &raquo; </a></div>
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




