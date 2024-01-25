---
banner: "![[computerscience.jpg]]"
---
# Lexical Analysis 

> [!Info] Lexical Analysis Steps 
> 1.  The source code is looked at. Any unnecessary parts of it are removed. This would include comments and spaces. Keywords and symbols are then replaced with ‘tokens’. A token is a generic description of the type of symbol. For example, if you had a constant called 'months_in_year', this would be replaced by the token CONSTANT. If you had variables called 'speed' and 'distance' then these would be replaced with the token VARIABLE. If you had a keyword 'IF', this would get replaced with the selection token for 'IF'. If you had a maths operator such as ‘>’, this would get replaced with the token OPERATOR. By replacing symbols, variables, keywords and so on with generic tokens, you can turn a program into a set of 'patterns' of instructions. It is then a relatively easy job for the compiler in the syntax stage to check each pattern against the allowable ones. Tokens replace:
> 2. 
> -  A keyword like IF, FOR, PRINT, THEN and so on.
> - A symbol that has got a fixed meaning, such as +, *.
> - Numeric constants.
> - User-defined variable names.

> [!Example] Example 
> - For example, if you had the following line in a program: **IF x > 10 THEN** this might be changed into this pattern of tokens:
> - **SELECTION/IF-VARIABLE-OPERATOR-CONSTANT-SELECTION/THEN**
> - Notice that the spaces have been removed and generic descriptions (tokens) have replaced keywords, variables, symbols and numeric constants.
> - A look-up table is created. This stores the values of all constants used along with their data type.
> - Variable names are also entered into the look-up table.
> - Once you have lexically analysed your program, you end up with a string of tokens. This is passed to the syntax analysis stage.

