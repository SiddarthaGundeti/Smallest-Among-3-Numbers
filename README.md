# Smallest-Among-3-Numbers

Input: 6 5 4

Output: 4
Question Explanation:

The program is designed to find the smallest value among three given integers A, B, and C.

Logical Approach:

Read Input:
Read three integers A, B, and C, each from a separate line.

Initialize Smallest Value:
Initially, assume the smallest value is A. Store this value in a variable named smallest_value.

Compare with B:
Check if B is less than smallest_value. If it is, update smallest_value to B.

Compare with C:
Check if C is less than smallest_value. If it is, update smallest_value to C.

Output:
Print the value of smallest_value, which now contains the smallest of the three numbers.

Example for Clarity:

If the input values for A, B, and C are 6, 5, and 4 respectively:
Initially, smallest_value is 6 (value of A).
B (5) is less than smallest_value (6), so now smallest_value becomes 5.
C (4) is less than smallest_value (5), so finally smallest_value becomes 4.

The output will be: 4
