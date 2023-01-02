```C#
// My solution
string englisVersion = "View English output:";
Console.WriteLine($@"{englisVersion}
    c:\Exercise\ACME\data.txt
");
string russianVersion = "Посмотреть русский вывод:";
Console.WriteLine($@"{russianVersion}
    c:\Exercise\ACME\ru-RU\data.tx
");

```

## Other solution
```C#
string projectName = "ACME";
string englishLocation = $@"c:\Exercise\{projectName}\data.txt";
Console.WriteLine($"View English output:\n\t\t{englishLocation}\n");
            
string russianMessage = "\u041f\u043e\u0441\u043c\u043e\u0442\u0440\u0435\u0442\u044c \u0440\u0443\u0441\u0441\u043a\u0438\u0439 \u0432\u044b\u0432\u043e\u0434";
string russianLocation = $@"c:\Exercise\{projectName}\ru-RU\data.txt";
Console.WriteLine($"{russianMessage}:\n\t\t{russianLocation}\n");
```

This code is merely "one possible solution". You may have some variation in naming variables or in the character escape sequences you used. You may have used Console.Write() instead of Console.WriteLine(). You may have attempted to combine everything together without using several variables.

However, as long as your code follows the instructions from the challenge and produces the desired output, then congratulations! Continue on to the knowledge check in the next unit.
