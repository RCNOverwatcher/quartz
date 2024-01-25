---
banner: "![[computerscience.jpg]]"
---
# Recursion

> [!Info] Introduction
> Recursion is the term used to describe when a sub-program calls itself! After every call to itself a test is done. This checks to see if the sub-program should call itself again. This continues until the test result is such that the recursion (and therefore the calls to itself) ends. Recursion can require a little thought to fully understand the mechanism! Let's look at some examples. The first example is the classic factorial example using functions.
> 
The 'factorial' of a number is arrived at by multiplying every integer from the number down to 1. So, for example,
**Factorial(6) = 6 x 5 x 4 x 3 x 2 x 1 = 720**  
**Factorial(4) = 4 x 3 x 2 x 1 = 24**
>
We can define a function that will work out the factorial of a number, K.
>
**Function Fact(K)**  
**BEGIN**  
**IF K <=1 then**  
      **Fact := 1**  
**ELSE**  
      **Fact := K x Fact(K-1)**  
**END**

> [!Info] Recursive vs Iterative
> **Comparison of iterative versus recursion**
> **Every time a call is made using recursion, the processor in the computer has to stop what it's doing and save all of the contents of special memory boxes in the CPU called 'registers' before it can do the call. After a call has finished, it then has to go to the place it saved the registers (called the 'stack') and put the values back in.**
> 1. If a recursive routine keeps calling itself, then it has to keep pushing values onto the stack, and ultimately keep taking them off (or 'popping') values off the stack. The problem with this is that the stack is a fixed size, so too many calls and you will quickly fill up the stack and get a 'stack overflow' error. Also, it takes time to push and pop values on and off the stack. As long as there aren't too many recursive calls, then recursion is fast. Too many calls, and relative to iteration, the process becomes slow.
> 2. You can see from the two examples above that there are less instructions using recursion. Less instructions means a smaller program, smaller object code and a program that should in theory run faster.
> 3. Some people find recursion difficult to follow compared to iterative routines. With practice, however, and knowing how to trace a recursive routine, it does become fairly easy.