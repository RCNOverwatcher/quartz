---
banner: "![[computerscience.jpg]]"
---
# Syntax Analysis

Syntax analysis is the compilation stage that immediately follows lexical analysis. Once tokens have been assigned to the code elements, the compiler checks that the tokens are in the correct order and that they follow the rules of the programming language being used.

### Rules of language

In Python, the command `print(user_name)` is syntactically correct because it follows the rules for a print statement:

1. Print in lower case
2. Immediately followed by a left-hand bracket
3. Followed by an identifier
4. Closed by a right-hand bracket

This is no different from natural languages like English. For example, the sentence “he Moved wearily” fails on three syntax points:

1. Start with a capital letter
2. Followed by lower case letters
3. End with a full stop

The syntax rules for programming languages are limited, but must be followed.

Syntax rules differ between languages:

- `if a > b:` is syntactically correct in Python
- `if a > b` is not syntactically correct in Python — the rule for using a colon is broken
- `if (a == b)` is syntactically correct in Java
- `if (a = b)` is not syntactically correct in Java — a single equals sign is not a conditional operator