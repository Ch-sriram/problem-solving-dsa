# Solving problems, one step at a time

I've created this repository for my own reference and practice purposes. If you come across this repository, feel free to explore, scrutinize and comment on my solutions, or just help yourself pondering about my code.

I like a lot of languages (I'm language agnostic), but I prefer to write code in C++ & rarely in Java & Python.

***NOTE: The code is in the form of GitHub Gists and therefore there is no code inside the repo.***

## Resources

- **General Resources**
  - [MAXimal :: algo](http://e-maxx.ru/algo/)
  - [Vivekanand Khyade's YouTube Channel](https://www.youtube.com/channel/UCx-kFfzekMbhODaBss-ZnsA)
  - [Tushar Roy's YouTube Channel](https://www.youtube.com/user/tusharroy2525)
  - [Amazing Blog Resource on Codeforces](http://codeforces.com/blog/entry/13529)
  - [Explanations of Interview Questions on iDeserve](https://www.ideserve.co.in/)

- **Mathematics**
  - [Finding Trailing Zeros in Factorial of a Number](https://www.purplemath.com/modules/factzero.htm)
  - [Euclidean Algorithm to find GCD](https://www.youtube.com/watch?v=p5gn2hj51hs)
  - [Extended Euclid's Algorithm to find Inverse Modulo](https://www.youtube.com/watch?v=hB34-GSDT3k)
  - [List of Prime Numbers up to 1,000,000,000,000](http://compoasso.free.fr/primelistweb/page/prime/liste_online_en.php)

## Table of Contents

- **Bit Manipulation**
  1. Given an integer N, find 2<sup>N</sup>: [Solution](https://gist.github.com/Ch-sriram/2812981bba250d52e75d34d4db50e294)
  2. Given X<sup>th</sup> & Y<sup>th</sup> bit positions, WAF to create a number where X<sup>th</sup> & Y<sup>th</sup> bit are set: [Solution](https://gist.github.com/Ch-sriram/9171a1a9dad728d37eb95f3f185dfa4f)
  3. Given an integer N & a bit position - i, WAF to check whether the i<sup>th</sup> bit is set in N or not: [Solution](https://gist.github.com/Ch-sriram/fef3d0a6274d20f6705495b7cf5b22e4)
  4. Given an integer - N, count the number of set bits in N: [Solution-1](https://gist.github.com/Ch-sriram/212f8185414fcb71278c6028128fcb2a) & [Solution-2](https://gist.github.com/Ch-sriram/68f0b06e41a6843fd1f6e81b1f4b1804)
  5. Given an integer N, check if it is a power of 2: [Solution](https://gist.github.com/Ch-sriram/62c046a0affda6907f0a06c8856ec74d)
  6. Given an integer N, find its binary representation: [Solution](https://gist.github.com/Ch-sriram/930cd33f5ab4b6e83bbdb17a0a546ca0)
  7. Given two integers A & B, find the number of bits that need to be flipped in B to convert it to A: [Solution](https://gist.github.com/Ch-sriram/2ec6bd3a3b9df442ce53ae260304f73e)
  8. Given an unsigned 32-bit integer N, reverse the bits in the binary representation of the integer, and print the new integer formed: [Solution](https://gist.github.com/Ch-sriram/4f8b4e1517d37fb71d26d71ece1b190a)
  9. Given an integer N, swap the adjacent bits in the binary representation of the integer, and print the new number formed after swapping: [Solution](https://gist.github.com/Ch-sriram/db50671bc159a3724d8b8318a58ab226)
  10. Given integers A & N, compute A<sup>N</sup>: [Naive Solution: O(N)](https://gist.github.com/Ch-sriram/5359bea35cce5a2d1265547a59ccb81c) & [Optimal Solution (fast-exponentiation): O(log N)](https://gist.github.com/Ch-sriram/0678934cc6bd8747f95d5e32ba50b4cf)
  11. Given an array of unique integer elements, print all the subsets of the given array in lexicographical order \[O(2<sup>N</sup>)\] :[Solution](https://gist.github.com/Ch-sriram/133e55e269420125a5d2c99aee089143)


- **Math**
  1. Given an integer N, find the number of trailing zeroes in N! \["N factorial"\]: [Solution](https://gist.github.com/Ch-sriram/398355f7ab6ee6ef52c49cab554365ef)
  2. Given two integers A and B, find their GCD & LCM: [Solution](https://gist.github.com/Ch-sriram/5456cca57a36d43a9d7eecc9c87844d6) 
  3. Given an array of size N, it contains all the numbers from 1 to N+1 inclusive, except one number. You have to find the missing number: [Solution](https://gist.github.com/Ch-sriram/ef37fc6877a6042f5c099edd27af5df2)
  4. Count Primes in Range \[O(N) for sieve of Eratosthenes + O(N) for prefix sum + O(Q * 1) for finding count of primes in given range for each query\] \[Total Time Complexity = O(2N + Q)\]: [Solution in C++](https://gist.github.com/Ch-sriram/0e68dd6941c2496b9aff3e466b88f54c) & [Solution in Java](https://gist.github.com/Ch-sriram/eb998b64e420b1c3e89bbf3af574cd38)
  5. Prime Generator (SPOJ) \[O(R * X), where R = Max Range of 10^5 & X = sqrt(N)\]: [Solution in C++](https://gist.github.com/Ch-sriram/59f96b46335d5041fe4cb413d6906227)

- **Recursion**
  1. Sum of N natural numbers: [Solution](https://gist.github.com/Ch-sriram/ead1c0b832960905fba68998a3449563)
  2. Given an integer N, return the N<sup>th</sup> integer in the Fibonacci Sequence: [Naive Solution O(2<sup>N</sup>)](https://gist.github.com/Ch-sriram/f62ed21b92f3d8cc49f3adbe27847b03)
  3. Given N, return N! ["N factorial"]: [Solution](https://gist.github.com/Ch-sriram/38107caae8ddecc6e29559cfc122a0eb)
  4. Towers of Hanoi/Brahma/Lucas: [Solution](https://gist.github.com/Ch-sriram/5eec7685b6b7112c982338979a936e2b)
  5. Given N pairs of parentheses, write a function to generate all combinations of well-formed valid parentheses: [Solution](https://gist.github.com/Ch-sriram/eba27b5b123faf2537efd36a3ef6688e)

- **Sorting**
  1. Bubble Sort Recursive Algorithm O(N<sup>2</sup>): [Solution](https://gist.github.com/Ch-sriram/be2581094c275d8191f89d565939ad9f)
  2. Insertion Sort Recursive Algorithm O(N<sup>2</sup>): [Solution](https://gist.github.com/Ch-sriram/41ab62e990bb7d5b7990f1734e9d741f)
  3. Selection Sort Recursive Algorithm O(N<sup>2</sup>): [Solution](https://gist.github.com/Ch-sriram/c2ccd12e714379c17b27c360baaeab67)
  4. Find the two repeating elements in a given array: [Solution](https://gist.github.com/Ch-sriram/f4116e9b4aac7a861be8aa4b85302fc0)
  5. Migratory Birds using Counting Sort \[O(N)\]: [Solution](https://gist.github.com/Ch-sriram/0352873393a6ac69f7df077679b2bfb3)
  6. Sum of Pairs: Given an array of integers and a number K, check if there exist a pair of indices i,j s.t. a[i] + a[j] = K and i!=j: [Solution](https://gist.github.com/Ch-sriram/d562c162c1365e253e2612e6281d1f7f)
  7. Largest Concatenated Number: [Solution](https://gist.github.com/Ch-sriram/a05ab29757205a509f22a1f28c030d75)
  8. Power Game: [Solution](https://gist.github.com/Ch-sriram/737842682fe15f91a3eb8a607e9d5f39)
  9. Sort the Half Sorted: [Solution](https://gist.github.com/Ch-sriram/ec720070417f82ce70875e23eaf36d54)
  10. Merge Sort Implementation O(N * log(N)): [Solution](https://gist.github.com/Ch-sriram/7696f1e4140ba4936cbf42cac2b286dd)
  11. Inversion Count of an Array O(N * log(N)): [Solution](https://gist.github.com/Ch-sriram/9a66f3ca68ad5ad1ccb8da2e6cfd9174)
  12. Sort an array of 0s, 1s and 2s \[Used Count Sort\]: [Solution](https://gist.github.com/Ch-sriram/cb1e7aad2a50e46744498153e3f5281d)
  13. Sort element of an element by frequency (a.k.a Frequency Sort): [Solution](https://gist.github.com/Ch-sriram/836d9a0519c5be44e3f20b9cefba084a)

- **Hashing**
  1. Two Sum \[Leetcode\]: [Solution](https://gist.github.com/Ch-sriram/ce2e2a2812084b86f4c611df741bd740)
  2. Count distinct pairs with difference k, where (A[i]-A[j] = k) and (i != j): [Solution](https://gist.github.com/Ch-sriram/444657575747b39e983afea7f541d45d)
  3. Triplet Sum in Array: [Accepted Solution &mdash; Time: O(N<sup>2</sup>) & Space: O(N)](https://gist.github.com/Ch-sriram/2f9a44494821da9536b3011865555e91) & [Unaccepted Solution &mdash; Time: O(2N + N<sup>2</sup>) & Space: O(N)](https://gist.github.com/Ch-sriram/6e79f659fb6c3cded04048796b05dee3)

- **Searching**
  1. Searching for a number in a list - Linear Search \[O(N)\]: [Solution](https://gist.github.com/Ch-sriram/696ccba97e4b4759924001ee6f52032c)
  2. Searching an element in a sorted array - Recursive Binary Search [O(N + log(N))]: [Solution](https://gist.github.com/Ch-sriram/3421b62411f95755276565c010a7f713)
  3. Cube root of a number using recursive binary search \[O(log(N))\]: [Solution for smaller range](https://gist.github.com/Ch-sriram/8edf469e233997a34826db9ac77f40ee) & [Solution for larger range: -10<sup>18</sup> to 10<sup>18</sup>](https://gist.github.com/Ch-sriram/5030489c47dfd83570639fa0b26ff599)
  4. Find floor of given X in a sorted array of size N [Binary Search - O(log(N))]: [Solution in C++](https://gist.github.com/Ch-sriram/cbf75b22db2892a7a8c0e56c5c53c2c8) & [Solution in Python](https://gist.github.com/Ch-sriram/ca82b16ea940ee5ab0365466a29c2f78)
  5. Find the element that appears once in sorted array [Binary Search - O(log(N))]: [Solution](https://gist.github.com/Ch-sriram/886559adf7493ecd872f69642b3ac2c4)
  6. Number of occurrences - given an array and x, find the frequency of x: [Solution in C++](https://gist.github.com/Ch-sriram/23e2701be67eb8c23759b41a1284595d) & [Solution in Python](https://gist.github.com/Ch-sriram/fcef15346076c77db874e0dba7b3d487)
  7. Painters Partition Problem (aka *Allotting Books to Students* Problem) \[Binary Search - O(N*log(Sum(A[0:N-1])))\]: [Solution in C++](https://gist.github.com/Ch-sriram/163cf6a98d07a5ea077cafe9bb12e6e5) & [Solution in Java](https://gist.github.com/Ch-sriram/3e49d229ada23d924163d16d3e3c8953)
  8. Aggressive Cows (SPOJ Problem) [Binary Search - O(2 * (N * log(N)))]: [Solution in Java](https://gist.github.com/Ch-sriram/f10e3db33cc553328f82ce1f896b0e50)

- **Heaps**
  1. Save Konoha (CodeChef: SAVKONO) \[O(N * log(N))\] \[Uses Max Heap\]: [Solution in C++](https://gist.github.com/Ch-sriram/ec5a41b051354ce7e17a8807f85a8a4d)

- **Trees**
  1. Height of a Binary Search Tree [TC: O(N) where 'N' is the number of nodes]: [Solution in C++](https://gist.github.com/Ch-sriram/1f328b53a823c537367f3220514eacf8)
  2. Depth of each node in the Binary Search Tree [TC: O(N) where 'N' is number of nodes in BST]: [Solution in C++](https://gist.github.com/Ch-sriram/1f1487f89777a2e4ce6f65d124c14b37)
  3. Level Order Traversal of BST (or Binary Tree) [TC: O(N) where 'N' is number of nodes && SC: O(N) where 'N' is auxiliary queue size]: [Solution in C++](https://gist.github.com/Ch-sriram/84125d9da959c0b9b503d06fb1323b95)
  4. Zia-Zag Level Order Traversal of BST/Binary Tree [TC: O(N)]: [Solution in C++](https://gist.github.com/Ch-sriram/5bf53ee6d476317f86c42e88bf0c1c4d) & [Solution in Python](https://gist.github.com/Ch-sriram/d5fe21eaf4c1be936bda115f8832f20f)