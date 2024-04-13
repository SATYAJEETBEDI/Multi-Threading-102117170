# Multi-Threading-102117170

The "Matrix Multiplication Performance Benchmark" project evaluates the impact of multi-threading on matrix multiplication tasks. Using Python libraries like NumPy, threading, and Pandas, the project generates random matrices and measures the execution time of matrix multiplication with varying numbers of threads (1 to 8). The results are analyzed and visualized to understand how concurrency affects performance. This project offers insights into optimizing computational tasks involving matrix operations.

Function explanation:
1. **generate_random_matrices(n, size)**:
   - Generates `n` random matrices of size `size x size`.

2. **multiply_matrices(matrices)**:
   - Multiplies a list of matrices together, starting with a constant matrix.

3. **perform_multiplication_with_threads(num_threads)**:
   - Performs matrix multiplication using multiple threads, dividing the task among them for parallel computation.

The table corresponding to the time taken with respect to number of threads is as follows:
![image](https://github.com/SATYAJEETBEDI/Multi-Threading-102117170/assets/99906282/4c2825f3-56ed-432f-9c28-03f5cf3d358d)

Graph:
![image](https://github.com/SATYAJEETBEDI/Multi-Threading-102117170/assets/99906282/9e1d0987-160b-4404-b8da-1e11bc2fa755)
