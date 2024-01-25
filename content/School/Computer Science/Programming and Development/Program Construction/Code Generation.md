---
banner: "![[computerscience.jpg]]"
---
# Code Generation 

**Code generation** follows the stages of lexical analysis, syntax analysis, and semantic analysis. A separate program is created that is distinct from the original source code. The code that is generated is a binary representation of the source code, this is known as **object code**. This is the executable version of the code, before linked libraries are included.

Here is a 'Hello World' program in C#:

```csharp
using System;

namespace code_sample
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
```

When this code is built, an executable file is generated. (If you are using C# and want to look for yourself, you can find the .exe file in the folder `/bin/debug`.) The executable file is a binary file that is intended to be read by the computer. If you attempt to look at it in a text editor, it doesn't make any sense. The text editor has translated the binary into the equivalent Unicode characters because it has assumed that the file contains text (but it does not).