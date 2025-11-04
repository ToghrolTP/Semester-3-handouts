Arithmetic Operators
Assignment Operators
Comparision operators
Increment/Decrement operators
Logical operators
String Operators
Array Operators
Conditional Operators

```php
define("cars", ["Volvo", "BMW", "Toyota"]);
echo "<h1>" . cars[0] . "</h1>";

// Arithmetic Operators Examples
$x = 10;
$y = 5;

echo "<h2>Arithmetic Operators:</h2>";
echo "<p>Addition: $x + $y = " . ($x + $y) . "</p>";
echo "<p>Subtraction: $x - $y = " . ($x - $y) . "</p>";
echo "<p>Multiplication: $x * $y = " . $x * $y . "</p>";
echo "<p>Division: $x / $y = " . $x / $y . "</p>";
echo "<p>Modulus: $x % $y = " . $x % $y . "</p>";
echo "<p>Exponentiation: $x ** $y = " . $x ** $y . "</p>";

// Comparision
$a = 10;
$b = 5;
$c = "10";

echo "<h2>Comparison Operators:</h2>";
echo "<p>Equal: $a == $c is " . ($a == $c ? "true" : "false") . "</p>";
echo "<p>Identical: $a === $c is " . ($a === $c ? "true" : "false") . "</p>";
echo "<p>Not equal: $a != $b is " . ($a != $b ? "true" : "false") . "</p>";
echo "<p>Not identical: $a !== $c is " .
    ($a !== $c ? "true" : "false") .
    "</p>";
echo "<p>Greater than: $a > $b is " . ($a > $b ? "true" : "false") . "</p>";
echo "<p>Less than: $a < $b is " . ($a < $b ? "true" : "false") . "</p>";
echo "<p>Greater than or equal: $a >= $b is " .
    ($a >= $b ? "true" : "false") .
    "</p>";
echo "<p>Less than or equal: $a <= $b is " .
    ($a <= $b ? "true" : "false") .
    "</p>";

```