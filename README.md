# Off-by-One Error in Vector Iteration

This example demonstrates a common off-by-one error in C++ when iterating over a `std::vector`. The loop condition `i <= vec.size()` is incorrect, leading to an out-of-bounds access at the end of the vector.  This can cause unexpected behavior, crashes, or undefined results.

The solution shows the corrected loop condition `i < vec.size()` ensuring the loop iterates through all elements without exceeding the bounds of the vector.