# WebDevNotes
## Basics of PHP
### Basic Syntax
Display a text
```php
<?php 
echo "Message To Display";
?>
```
Nested php inside html
```html
<!DOCTYPE html>
<head></head>
<body>
  <h1><?php echo "Message To Display"?></h1>
</body>
```
Comments in php
- One line comment
```php
<?php //This is a comment
      #This is another comment
?>
```
- Multi-line comment
```php
<?php /*This is
      A multi-line
      comment!/*
?>
```
- Comment a part of a line
```php
<?php $a=10+/*20+*/+30;
     //a is evaluated to 40
?>
```
Php is case insensitive for keywords so echo and ECHO are the same.
However, it is case sensitive for variables' names
### Declaring variables
Declaring a variable always begun with a $ folllowed by the variable's name. 
A variable's name can start with a letter or an underscore.
```php
<?php
$var1=10;
$_var2=5;
$result=$var1+$_var2
echo $result;
?>
```
Concatenate two strings 
```php
<?php
$var1="Hello";
$_var2='World!';
echo $var1." ".$_var2; //Will display Hello World!
?>
```
Differrence between single quotes and doubles quotes
```php
<?php
$var1=7;
echo "Php version $var1"; //Will display Php version 7
echo 'Php version $var1'; //Will display Php $var1
?>
```
