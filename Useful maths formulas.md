# Some useful maths formulas

## GCD - Euclid's Algo

```d
gcd(a, b) = gcd(b%a, a) if a > 0
gcd(a, b) = b           if a == 0
```

#### Pseudocode - Iterative

```d
function gcd(a, b):
    while a != 0:
        a, b = b%a, b
    return b
```

#### Pseudocode - Recursive

```d
function gcd(a, b):
    if a == 0:
        return b
    return gcd(b%a, b)
```

## LCM

Compute using the formula

```d
gcd(a, b) * lcm(a, b) = a * b
```

Compute GCD using Euclid's algo and find LCM with the above formula.

#### Pseudocode

```d
function lcm(a, b):
    return (a * b) / gcd(a, b)
```

## Arithmetic Progression - AP

An arithmetic progression (AP), also called an arithmetic sequence, is a sequence of numbers which differ from each other by a common difference. For example, the sequence 2, 4, 6, 8, ... is an arithmetic sequence with the common difference 2.

Let `d` = common difference \
Let `a` = first term

#### Formula for Nth term

![](assets/images/ap_nth.png)

```d
T(n) = a + (n - 1) * d
```

#### Sum of AP

![](assets/images/ap_sum.png)

```d
S(n) = (2 * a + (n - 1) * d) * n / 2
```

## Geometric Progression - GP

A geometric progression (GP), also called a geometric sequence, is a sequence of numbers which differ from each other by a common ratio. For example, the sequence 2, 4, 8, 16, ... is a geometric sequence with common ratio 2.

Let `a` = Initial Term \
Let `r` = Common ratio

#### Nth term

![](assets/images/gp_nth.png)

```py
T(n) = a * pow(r, n-1)
```

#### Sum of GP

![](assets/images/gp_sum.png)

```d
S(n) = a * ((pow(r,n) - 1)/(r - 1))     if r != 1
S(n) = a * n                            if r == 1
```

## Combinations

The combination is a way of selecting items from a collection, such that the order of selection does not matter.

#### Formula:

<img src="./assets/images/combination_formula.png" width="300">
```d
C(N, R) = N! / ((N-R)! * R!)
```

#### Pseudocode

```d
function combination(n, r):
    numerator = factorial(n)
    denominator = factorial(n-r) * factorial(r)
    return numerator / denominator
```

#### Recursive Formula:

```d
C(n, r) = 1                         ,if r = 0 or if r = n
C(n, r) = C(n-1, r-1) + C(n-1, r)   ,all other cases
```

#### Pseudocode - Recursive

```d
function combination(n, r):
    if r == 0 or r == n:
        return 1
    return combination(n-1, r-1) + combination(n-1, r)
```

#### Important Property

![](assets/images/combination_property.png)

```d
C(n, r) = C(n, n - r)
```

## Permutations

A permutation is a mathematical technique that determines the number of possible arrangements in a set when the order of the arrangements matters.

#### Formula

<img src="./assets/images/permutation_formula.png" width="300">
```d
P(n, r) = n! / (n-r)!
```

#### Pseudocde

```d
function permutation(n, r):
    numerator = factorial(n)
    denominator = factorial(n-r)
    return numerator / denominator
```
