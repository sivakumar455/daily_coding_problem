## [<<](../28) Problem 29 [>>](../30)

Run-length encoding is a fast and simple method of encoding strings. The basic idea is to represent repeated
successive characters as a single count and character. Implement run-length encoding and decoding. You can assume
the string to be encoded have no digits and consists solely of alphabetic characters. You can assume the string to
be decoded is valid.

Examples:

    >>> coding_problem_29('AAAABBBCCDAA')
    '4A3B2C1D2A'
    
    >>> coding_problem_29('4A3B2C1D2A')
    'AAAABBBCCDAA'
