# Off-by-one error in array iteration in Java
This example demonstrates a common off-by-one error in Java when iterating through an array.  The loop condition `i <= arr.length` causes an `ArrayIndexOutOfBoundsException` because array indices are zero-based. The last valid index is `arr.length - 1`.

The solution corrects the loop condition to `i < arr.length` to prevent this error.