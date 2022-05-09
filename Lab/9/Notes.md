-> The STOS instruction copies the data item from AL (for bytes - STOSB), AX (for words - STOSW) or EAX (for doublewords - STOSD) to the destination string, pointed to by ES:DI in memory.

-> The CMPS instruction compares two strings. This instruction compares two data items of one byte, word or doubleword, pointed to by the DS:SI and ES:DI registers and sets the flags accordingly.

-> The SCAS instruction is used for searching a particular character or set of characters in a string.

->  rep (repeat while equal)
-> repnz (repeat while nonzero) 
-> repz (repeat while zero)
