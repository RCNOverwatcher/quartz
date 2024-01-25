---
banner: "![[computerscience.jpg]]"
---
# Semantic Analysis 

So far in the stages of compilation, **lexical analysis** has been used to determine whether the tokens within the program are valid, then **syntax analysis** has been used to find out whether the tokens have been used to meet the rules of the language. There is another stage called **semantic analysis** which determines whether what has been written actually has a meaning within the language.

Let's say you are defining rules for constructing grammatically correct sentences in English. One rule for a possible valid sentence construct is:

```
<pronoun> <verb> <plural noun>
```

This means that "I eat crackers" and "They play video games" are valid sentences in English. However, if you are a computer and only use syntax analysis to check validity, "You swim cats" and "We bite movies" are also valid, even though within the English language these sentences make no sense.

### Semantic errors

Semantic analysis can be used to determine whether the code is valid within a given context.

Here is an example in C# where two variables have been declared:

```csharp
int first_number = 8;
int second_number = "6";
```

All tokens are valid within the language, and the assignment statement is formatted correctly. However, line 2 would result in a semantic error when the program is compiled. This is because declaring a string value for an identifier that has been declared to be an integer is not valid.

A semantic error in C#

Let's look at another example, this time in Python:

```python
fruit = ["apple", "peach", "pear"]
print(fruit[4])
```

This code would not produce an error at the lexical analysis stage because all tokens are valid within the language. It would not produce an error at the syntax analysis stage because the list declaration and print statements are correctly formed according to the rules of the language. However, it would produce a semantic error because within the context of the `fruit` list that has been defined, index 4 is out of bounds.
