**Segmentation**\
-> process of logically dividing the main memory of a computer into different segments\
-> enhances the speed of execution of computer system

BIU has 4 16-bit special purpose registers\
-> Code Segment : addressing memory location in code segment of memory\
-> Data Segment : points to the data segment of the moemory where the data is stored\
-> Extra Segment : refers to segment in memory which is another data segment in memory\
-> Stack Segment : addresses stack segment of memory\

Types of Segmentation:
-> Overlapped
-> Non-overlapped

Rules of Segmentation:
-> starting-address must be divisible by 16
-> size of segment = {16 bytes-64 kB}

code segment -> instruction pointer -> address of next instruction
data segment -> bx,di,si -> address of data
stack segment -> sp,bp -> address in the stack
extra segment -> bx,di,si -> address of destination data

Advantages of Segmentation:
-> powerful memory management mechanism
-> data or stack related operations can be performed in different segments
-> allows easy sharing of data
