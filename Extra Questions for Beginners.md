# Extra Practice Problems for Beginner Batch

## Topic - Loops

#### Easy

1. **Fibonacci Pattern**<br>
   Take N (number of rows), print the following pattern (for N = 4)
   <pre>
    0
    1 1
    2 3 5
    8 13 21 34
    </pre>

   **Constraints**:<br>
   0 < N < 100<br>

   **Explanation**:<br>For given input n, You need to print n(n+1)/2 fibonacci numbers. Kth row contains , next k fibonacci numbers.

   <br>
   <br>

2. **Series Printing**<br>
   Take the following as input.

   A number (N1)
   A number (N2)
   Write a function which prints first N1 terms of the series 3n + 2 which are not multiples of N2.

   **Sample Input**:<br>
   10
   4<br>
   **Sample Output**:<br>
   5
   11
   14
   17
   23
   26
   29
   35
   38
   41<br>
   **Explanation**:<br>
   The output will've N1 terms which are not divisible by N2.

   <br>
   <br>

#### Medium

1. **Reverse Sum**<br>
   Given an integer, find the sum of the number and its reverse.<br>
   **Example Input**:<br>
   `N = 536`<br>
   **Example Output**:<br>
   `1171`<br>
   **Explanation**:<br>
   `536 + 635 = 1171`
   <br>
   <br>
2. **Armstrong Numbers**<br>
   Given an integer, check whether it is an Armstrong Number.
   Armstrong number is a number that is equal to the sum of cubes of its digits. For example 0, 1, 153, 370, 371 and 407 are the Armstrong numbers.

<pre>
    Sample Input:
    153
    Sample Output:
    Yes
    Explanation:
    153 is an Armstrong Number because
    153 = 1<sup>3</sup> + 5<sup>3</sup> + 3<sup>3</sup>
</pre>
   <br>
   <br>
   
3. **Perfect Numbers**<br>
   <p>You are given an integer <strong>A</strong>.</p><p></p><p></p><p></p><p></p><p></p>
    <p>You have to print all the <strong>perfect numbers</strong> which lie in the range <strong>[1, A]</strong> in ascending
    order.</p>
    <p><strong>Perfect number</strong> is a positive integer which is equal to the sum of its proper positive divisors.</p>
    <p>A <strong>proper divisor</strong> of a natural number is the divisor that is strictly less than the number. </p>

**Example Input**:

   <p>Input 1:</p><p></p><p></p><p></p><p></p><p></p>
    <pre> 8 </pre>
    <p>Input 2:</p>
    <pre> 35 </pre>

**Example Output**:

   <p>Output 1:</p><p></p><p></p><p></p><p></p><p></p>
    <pre> 6 </pre>
    <p>Output 2:</p>
    <pre> 
    6 
    28 
    </pre>

#### Hard

1. **Ganesha Pattern**<br>
   Take as input N, an odd number (>=5) . Print the following pattern as given below for N = 7.
   <pre>
   *  ****
   *  *
   *  *
   *******
      *  *
      *  *
   ****  *
   </pre>

   Input Format:
   Enter value of N ( >=5 )

   Constraints:
   N >= 5
   Sample Input:
   7
   Sample Output:
   <pre>
   *  ****
   *  *
   *  *
   *******
      *  *
      *  *
   ****  *
   </pre>

   Explanation:
   Catch the pattern for the corresponding input and print it accordingly.

2. **Different Pattern**<br>
   <p>Given an integer <strong>N</strong>, print the corresponding <strong>Full Numeric Pyramid</strong> pattern for <strong>N</strong>.</p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p>
   <p>For example if <strong>N = 5</strong> then pattern will be like:</p>
   <pre>
   0 0 0 0 5 0 0 0 0 
   0 0 0 4 8 12 0 0 0 
   0 0 3 6 9 12 15 0 0
   0 2 4 6 8 10 12 14 0
   1 2 3 4 5 6 7 8 9 
   </pre>
   <p>If the row are considered as <strong>i</strong>, the value of i for the top-most row will be <strong>N and then N-1, N-2, ...., 1 subsequently for remaining rows</strong>. <br>
   The values of pyramid are decided as <strong>i * (number of non-zero values printed before + 1)</strong>.</p>
   <p><strong>NOTE:</strong> There should be exactly one extra space after each <code> number </code> for each row.</p>
   <p></p>

   <br/>

   **Example Input**:<br>
   3<br>
   **Example Output**:<br>
   <pre>
   0 0 3 0 0
   0 2 4 6 0
   1 2 3 4 5
   </pre>

3. **Hourglass Pattern**<br>
   Take N as input:
   For N = 5, we wish to print the following pattern
   <pre>
                          5 4 3 2 1 0 1 2 3 4 5
                            4 3 2 1 0 1 2 3 4 
                              3 2 1 0 1 2 3 
                                2 1 0 1 2 
                                  1 0 1 
                                    0 
                                  1 0 1 
                                2 1 0 1 2 
                              3 2 1 0 1 2 3 
                            4 3 2 1 0 1 2 3 4 
                          5 4 3 2 1 0 1 2 3 4 5
                          </pre>

## Topic - Arrays

#### Easy

1. **Check if sorted**<br>
   Given an array, check if it sorted

   **Sample Input**:
   <pre>
   5
   1 4 7 9 10
   </pre>

   **Sample Output**:<br>
   Yes

   **Explanation**:<br>
   The given array is sorted

   <br>
   <br>
   <br>
   <br>

2. **Linear Search 2** <br>
   Given an array containing duplicate numbers and a target value, find the index of 2nd occurence of the target value<br>
   **Sample Input**:
   <pre>
   6
   9 2 8 2 4 2
   2
   </pre>

   **Sample Output**:<br>
   3
   <br>
   **Explanation**<br>
   Here target=2
   There are 3 occurences of 2 in the given array.
   The 2nd occurence is found at index=3.

   <br>
   <br>
   <br>
   <br>

#### Medium

1. **Super Maxima**
   <p></p><p></p>
    <p>Write a program to input N numbers from user and print the count of all the super maximas among them. </p>
    <p><strong>NOTE: </strong> An element is super maxima if there exist atleast one element before it 
    and atleast one element after it and following conditions are satisfied:
    </p><ul><li>
    <strong>A[i-1] &lt; A[i] &gt; A[i+1]</strong></li>
    <li>
    <strong>A[i-1] + A[i+1] < A[i]</strong>
    </li>
    </ul>

   **Sample Input**:
    <pre>
    5
    2 3 1 4 2
    </pre>

   **Sample Output**:
    <pre>
    1
    </pre>

   **Explanation**:
    <pre>
    Only 4 satisfies all the conditions, i.e. 4&gt;1, 4>2 and 4>1+2.
    </pre>

   <br>
   <br>
   <br>
   <br>

## Topic - Strings

#### Medium

1. **String Addition**<br>
   Jack is awesome. His friends call him little Einstein. To test him, his friends gave him a string.
   They told him to add the string with its reverse string and follow these rules:

   Every ith character of string will be added to every ith character of reverse string.
   <br>
    <p>
    Both string will contain only lower case alphabets(a-z).
    Eg:- a+a=b,a+c=d,z+a=a (Refer to sample test cases for more details)
    </p>

   **Input**:

   First line contains a value N denoting number of test cases. Next N lines contains string str.

   **Output**:

   For every string str output the string that Jack's friends wants from him.

   **Constraints**

   1 <= N <= 10

   1 <= str <= 10^5

   **SAMPLE INPUT**<br>
   <pre>4
   hello
   codeapocalypse
   programming
   world
   </pre>

   **SAMPLE OUTPUT**
   <pre>wqxqw
   hhtdmqrrqmdthh
   wfxtebetxfw
   aajaa
   </pre>

## Topic - 2D Arrays

#### Medium

1. **Transpose Sum**<br>
   Given a square matrix of size N, find its transpose and compute their sum.

   **Sample Input**:
   <pre>
   2
   1 9
   2 6
   </pre>

   **Sample Output**:
   <pre>
   2 11
   11 12
   </pre>

   **Explanation**:<br>
   Transpose of the given matrix is
   <pre>
   1 2
   9 6
   </pre>

   Sum of original matrix and transpose matrix would be:
   <pre>
   2 11
   11 12
   </pre>

   <br><br><br>

#### Hard

1. **Determinant**<br>
   Given a N\*N matrix, find its determinant.
   Input contains N, size of the matrix in the first line. Next N lines contain each row of the matrix.<br>
   Sample Input:<br>
   <pre>
   3
   4 1 9
   2 0 2
   -1 8 -3
   </pre>

   Sample Output:
   <pre>
    84
   </pre>

   <br>
   <br>
   <br>
   <br>

2. **Wave Print Column Wise**<br>
   Take as input a two-d array. Wave print it column-wise.
   <br>

   **Input Format**:<br>
   Two integers M(row) and N(colomn) and further M \* N integers(2-d array numbers).

   **Constraints**:<br>
   Both M and N are between 1 to 10.

   **Output Format**:<br>
   All M \* N integers seperated by commas with 'END' written in the end(as shown in example).

   Sample Input:
   <pre>
   4 4
   11 12 13 14
   21 22 23 24
   31 32 33 34
   41 42 43 44
   </pre>

   Sample Output:
   <pre>11, 21, 31, 41, 42, 32, 22, 12, 13, 23, 33, 43, 44, 34, 24, 14, END</pre>

## Topic - Maths

#### Easy

1. **Factorial of GCD**<br>
   Given two numbers, find their GCD and prints its factorial.<br>
   **Sample Input**<br>
   12 20<br>
   **Sample Output**<br>
   24

   **Explanation**<br>
   GCD(12,20) = 4
   4! = 24

#### Medium

1. **GCD of N Numbers**<br>
   Given N numbers, find and print their GCD.<br>
   **Sample Input**:
   <pre>
   5
   20 40 100 55 35
   </pre>
   **Sample Output**:<br>
   5
