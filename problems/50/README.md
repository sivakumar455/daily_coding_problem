##Problem 50

Suppose an arithmetic expression is given as a binary tree. Each leaf is an integer and each internal node
is one of '+', '-', '*' or '/'. Given the root to such a tree, write a function to evaluate it.
For example, given the following tree:

*
/   \
+     +
/ \   / \
3   2 4   5

you should return 45, as it is (3 + 2) * (4 + 5).
Examples:

    >>> coding_problem_50(('*', ('+', 3, 2), ('+', 4, 5)))  # (3 + 2) * (4 + 5) == 45
    45
    >>> coding_problem_50(('/', ('+', ('+', 1, 2), 3), 12))  # (1 + 2 + 3) / 12 == 0.5
    0.5

Note: problem 49 was the last one I received; this comes from github.com/r1cc4rdo/daily_coding_problem/pull/7,
a pull request from RMPR (https://github.com/RMPR). Thanks!