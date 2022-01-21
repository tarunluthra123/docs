# Some useful maths formulas

## GCD - Euclid's Algo

```d
gcd(a, b) = gcd(b%a, a) if a > 0
gcd(a, b) = b           if a == 0
```

### Pseudocode - Iterative

```d
function gcd(a, b):
    while a != 0:
        a, b = b%a, b
    return b
```

### Pseudocode - Recursive

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

### Pseudocode

```d
function lcm(a, b):
    return (a * b) / gcd(a, b)
```

## Arithmetic Progression - AP

An arithmetic progression (AP), also called an arithmetic sequence, is a sequence of numbers which differ from each other by a common difference. For example, the sequence 2, 4, 6, 8, ... is an arithmetic sequence with the common difference 2.

Let `d` = common difference \
Let `a` = first term

### Formula for Nth term

![](assets/images/ap_nth.png)

```d
T(n) = a + (n - 1) * d
```

### Sum of AP

![](assets/images/ap_sum.png)

```d
S(n) = (2 * a + (n - 1) * d) * n / 2
```

## Geometric Progression - GP

A geometric progression (GP), also called a geometric sequence, is a sequence of numbers which differ from each other by a common ratio. For example, the sequence 2, 4, 8, 16, ... is a geometric sequence with common ratio 2.

Let `a` = Initial Term \
Let `r` = Common ratio

### Nth term

![](assets/images/gp_nth.png)

```py
T(n) = a * pow(r, n-1)
```

### Sum of GP

![](assets/images/gp_sum.png)

```d
S(n) = a * ((pow(r,n) - 1)/(r - 1))     if r != 1
S(n) = a * n                            if r == 1
```
