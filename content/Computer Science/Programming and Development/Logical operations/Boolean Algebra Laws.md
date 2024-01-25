---
banner: "![[computerscience.jpg]]"
---

# Summary of all Boolean algebra laws and identities
### The 12 basic identities
A AND 0 ≡ A Ʌ 0 ≡ A.0 ≡ 0
A AND 1 ≡ A Ʌ 1 ≡ A.1 ≡ A
A AND A ≡ A Ʌ A ≡ A.A ≡ A
A AND (NOT A) ≡ A Ʌ ¬A ≡ A.¬A ≡ 0

A OR 0 ≡ A V 0 ≡ A + 0 ≡ A  
A OR 1 ≡ A V 1 ≡ A + 1 ≡ 1
A OR A ≡ A V A ≡ A + A ≡ A
A OR (NOT A) ≡ A V ¬A ≡ A + A ≡ 1

NOT NOT A ≡ ¬¬ A ≡ A ≡ A
A OR (A AND B) ≡ A V (A Ʌ B) ≡ A + A.B ≡ A
A OR ((NOT A) AND B) ≡ A V (¬A Ʌ B) ≡ A + $\overline{A}$.B ≡ A + B
(A OR B) AND (A OR C) ≡ (A V B) Ʌ (A V C) ≡ (A + B)(A + C) ≡ A + B.C


### Commutative law
A.B ≡ B.A
A + B ≡ B + A

### Associative law
(A.B).C ≡ A.(B.C)
(A + B) + C ≡ A + (B + C)

### Distributive law
A.(B + C) ≡ (A.B) + (A.C)
A + (B.C) ≡ (A + B).(A + C)

### De Morgan's laws
NOT(A.B) ≡ NOT(A + B)
NOT(A + B) ≡ NOT(A.B)

### NOTES
1) The easiest form to use when doing Boolean algebra is to use a dot for AND, a plus symbol for OR and a bar for NOT. We recommend using this format when doing Boolean algebra, even if it means converting a question first.
2) The dot may or may not be omitted when used for AND. Sometimes you will see e.g. A.B and sometimes AB and they are used interchangeably.
3) The order of precedence for Boolean algebra is: Brackets first, then NOT, then AND and finally OR. If you are in any doubt about the order that operators should be done in, always use brackets to make the expression clear.