1.1) 15 people, call out for dog playdate. O(1)

1.2) 15 people, ask sequentially for dog playdate. O(n)

2) even or odd input. O(1), it's a simple arithmetic operation

3) are you here? O(n^2) for the nested for loops

4) doubler. O(n), for having to look at each element and perform an O(1) operation.

5) naive search. O(n), for having to look at each element

6) create pairs. O(n^2) for nested loops

7) compute the sequence. This generates the fibonacci sequence, and is probably O(2^n) for the recursive nature of the process

8) efficient search. Looks like some kind of binary tree, continuously splitting to search. probably O(log n)

9) random element. O(1), just picking a single random element from the input

10) what am i? for all elements from 2 until n, this function performs n mod i. If n is divisible by i, it returns false. O(n) for the single loop-though the elements