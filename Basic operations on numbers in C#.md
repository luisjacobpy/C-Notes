# Simple Addition and Implicit Data Conversion
## Step 1: Add two numeric values
```C#
// addition
int firstNumber = 12;
int secondNumber = 7;
Console.WriteLine(firstNumber + secondNumber);
```
## Step 2: Mix data types to force implicit type conversions

```C#
// Mix Data
string firstName = "Bob";
int widgetsSold = 7;
Console.WriteLine(firstName + " sold " + widgetsSold + " widgets.");
```
Output
```BASH
Bob sold 7 widgets.
```

## Add parentheses

```C#
string firstName = "Bob";
int widgetsSold = 7;
Console.WriteLine(firstName + " sold " + (widgetsSold + 7) + " widgets.");
```  

Output
```BASH
Bob sold 14 widgets.
```

# Basic Math Operations
```C#
int sum = 7 + 5;
int difference = 7 - 5;
int product = 7 * 5;
int quotient = 7 / 5;

Console.WriteLine("Sum: " + sum);
Console.WriteLine("Difference: " + difference);
Console.WriteLine("Product: " + product);
Console.WriteLine("Quotient: " + quotient);
```
Output
```BASH
Sum: 12
Difference: 2
Product: 35
Quotient: 1
```

+ is the addition operator
- is the subtraction operator
* is the multiplication operator
/ is the division operator

## Division using literal decimal data

```C#
decimal decimalQuotient = 7.0m / 5;
Console.WriteLine("Decimal quotient: " + decimalQuotient);
```
Output
```BASH
Decimal quotient: 1.4
```

## Add code perform division using literal decimal data
```C#
int first = 7;
int second = 5;
decimal quotient = (decimal)first / (decimal)second;
Console.WriteLine(quotient);

```
Output
```BASH
1.4
```

