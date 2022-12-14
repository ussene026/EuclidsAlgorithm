# Euclid's Algorithm
Euclid's algorithm is a simple and efficient method of finding the greatest common divisor between two non-zero integers. It is one of the oldest algorithms, known since it appeared in Books VII and X of Euclid's Elements around 300 BC. The algorithm does not require any factoring.

The GCD of two integers is the largest integer that divides both without leaving a remainder. Euclid's algorithm is based on the principle that the GCD does not change if the smaller number is subtracted from the larger one. For example, 21 is the GCD of 252 and 105 (252 = 21 × 12; 105 = 21 × 5); since 252 − 105 = 147, the GCD of 147 and 105 is also 21. As the larger of the two numbers is reduced, repeating this process will successively generate smaller numbers, until they converge to zero.

At this point, the MDC is the other integer, greater than zero. By reversing the steps of Euclid's algorithm, the GCD can be expressed as the sum of the two original numbers, each multiplied by a positive or negative integer, for example: 21 = 5 × 105 + (−2) × 252. This important property is called the Bézout identity.
