You are given a string of length n and a dictionary containing k words. In how many ways can you create the string using the words?

Input

The first input line has a string containing n characters between a–z.

The second line has an integer k: the number of words in the dictionary.

Finally there are k lines describing the words. Each word is unique and consists of characters a–z.

Output

Print the number of ways modulo 109+7.

Constraints
1≤n≤5000
1≤k≤105
the total length of the words is at most 106
Example

Input:
ababc
4
ab
abab
c
cb

Output:
2

Explanation: The possible ways are ab+ab+c and abab+c.
