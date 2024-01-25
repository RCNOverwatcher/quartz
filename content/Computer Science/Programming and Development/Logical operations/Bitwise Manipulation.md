---
banner: "![[computerscience.jpg]]"
---

# Bitwise Manipulation

> [!Info] The operators
> You can manipulate the bits in binary with certain bitwise operations.
> These are:
> - & (AND)
> - | (OR)
> - ^ (XOR)
> - ~ (Complement)
> - \>\> (Binary shift right)
> - << (Binary shift left)

> [!Info] Masks
> > *"A mask is a bit pattern that has been defined by a programmer, which allows specific bits in a piece of data to be tested or altered."*
> 
> Masks can be used to reset certain bits to 0. To reset all bits to 0 apart from the first 3, you would set the mask to 11111000 and use the bitwise AND operator.

> [!Info] Using XOR to encode data
> Because XOR returns 1 if only one of the bits are toggled and 0 of both bits are the same, you can use a mask as a encryption/decryption key to encrypt data.
> E.G. [XOR Encypt/Decrypt](https://md5decrypt.net/en/Xor/)


