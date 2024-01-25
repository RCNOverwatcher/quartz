---
banner: "![[computerscience.jpg]]"
---
<div class="title">​</div>
<div class="title">​</div>

# Hash Tables

Hash tables are a type of data structure that applies a mathematical formula to a piece of data to generate a memory location to output the data to.

E.G. A=1, B=2 C=3, etc
JACOB would be 10+1+3+15+2=31

If clashes exist then a solution is to go where the data should be, and then if it doesn’t exist, travel along consecutive memory locations until the data is found. The other solution is to set up an overflow area where data that cannot be stored will go. This area can then be searched in the event of a clash.

A good hashing algorithm will:

-   Minimise clashes.
    
-   Ensure that the hash codes of data aren't spread too far apart, wasting memory.
    
-   Be quick to calculate.

