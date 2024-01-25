---
banner: "![[furthermaths.jpg]]"
---
# Quick Sort

>[!Info] Method
>1. Choose the item at the median of the list to be the first pivot. (if no exact median, choose value to the right)
>2. Write down all the items that are less than the pivot, keepiung their order, in a sub list.
>3. Write down the pivot of the sub-list.
>4. Write down the remaining items (items greater than the pivot) in a sub list.
>5. Apply steps 1-4 to each sub list.
>6. When all items have been chosen as pivots, stop.

>[!Example]
>18, 7, 14, 11, 9, <u>12</u>, 21, 3, 10, 17                                            | **12 chosen as pivot**
>7, 11, <u>9</u>, 3, 10, [12] 18, 14, <u>21</u>, 17                           | **9 and 21 chosen as pivot**
>7, <u>3</u>, [9], 11, <u>10</u>, [12], 18, <u>14</u>, 17, [21]      | **3, 10 and 14 chosen as pivot**
>[3], <u>7</u> [9], [10], <u>11</u>, [12], [14], 18 <u>17</u>, [21] | **7, 11, 17 chosen as pivot**
>[3], [7], [9], [10], [11], [12], [14], [17], <u>18</u>, [21]                        | **18 as pivot**
