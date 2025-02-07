# Off-by-One Error in Java
This repository demonstrates a common but easily missed error in Java: the off-by-one error in array iteration.
The `bug.java` file contains code that attempts to populate an array, but due to an incorrect loop condition, it tries to access an index beyond the array's bounds, resulting in an `ArrayIndexOutOfBoundsException`.
The `bugSolution.java` file provides the corrected code with the explanation of the fix.
This example highlights the importance of careful attention to loop boundaries when working with arrays in Java.