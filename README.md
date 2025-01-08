# Off-by-One Error in Assembly Leading to Overflow
This repository demonstrates a common off-by-one error in assembly language. The `bug.asm` file contains the erroneous code, while `bugSolution.asm` provides a corrected version.

**The Bug:**
The code attempts to increment a value stored on the stack. However, it doesn't account for potential integer overflow. If the value reaches its maximum limit, adding 1 will lead to an incorrect result or a program crash.

**The Solution:**
The solution involves checking for potential overflow before the increment operation.  This ensures the code handles all possible scenarios gracefully.