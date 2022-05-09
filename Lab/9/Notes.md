-> The STOS instruction copies the data item from AL (for bytes - STOSB), AX (for words - STOSW) or EAX (for doublewords - STOSD) to the destination string, pointed to by ES:DI in memory.

-> The CMPS instruction compares two strings. This instruction compares two data items of one byte, word or doubleword, pointed to by the DS:SI and ES:DI registers and sets the flags accordingly.

-> The SCAS instruction is used for searching a particular character or set of characters in a string.

->  rep (repeat while equal)
-> repnz (repeat while nonzero) 
-> repz (repeat while zero)
causes the associated string instruction to repeat until the count register (CX) or the zero flag (ZF) matches a tested condition.

-> The register SI and DI are called index registers. These registers are usually used to process arrays or strings. SI is called source index and DI is destination index.

-> SI is always pointed to the source array and DI is always pointed to the destination. This is usually used to move a block of data, such as records (or structures) and arrays. These register is commonly coupled with DS and ES.

