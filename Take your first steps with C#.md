# Strings

## String interpolation
```C#
// String interpolation to combine
string firstName = "Bob";
string message = $"Hello {firstName}!";
Console.WriteLine(message);
```
## Use string interpolation whit multiple variables

```C#
string firstName = "Bob";
string greeting = "Hello";
string message = $"{greeting} {firstName}!";
Console.WriteLine(message);
```

```C#
string firstName = "Luis Jacobo";
string greeting = "Hello, I'm";
string message = $"{greeting} {firstName}!";
Console.WriteLine(message);
```

## Avoid intermediate variables
```C#
string firstName = "Luis Jacobo";
string greeting = "Hello, I'm";
Console.WriteLine($"{greeting} {firstName}!");
```

## Cobine verbatim literals and string interpolation
Suppose you need to use a verbatim literal in your template. You can use both the verbatim literal prefix symbol @ and the string interpolation $ symbol together

```C#
string projectName = "First-Project";
Console.WriteLine($@"C:\Output\{projectName}\Data");
```

### Output
C:\Output\First-Project\Data

## Recap
* String interpolation provides an improvement over string concatenation by reducing the number of characters required in some situations.
* You can combine string interpolation and verbatim literals by combining the symbols for each and using that as a prefix for the string template.

