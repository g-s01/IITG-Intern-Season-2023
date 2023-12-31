# Salesforce Hiring Process
<details>
<summary>Pay and Duration</summary>
Pay: 1.5L/month
    
Duration: 8 weeks
</details>

## OA - Women in Tech

### Questions

<details>
<summary>
Q1
</summary>
<img src = "./assets/WiT/Salesforce%20Q1-1.jpeg"/>
<img src = "../assets/WiT/Salesforce%20Q1-2.jpeg"/>
</details>

<details>
<summary>
Q2
</summary>
<img src = "./assets/WiT/Salesforce%20Q2-1.jpeg"/>
<img src = "./assets/WiT/Salesforce%20Q2-2.jpeg"/>
</details>

<details>
<summary>
Q3
</summary>
<img src = "./assets/WiT/Salesforce%20Q3-1.jpeg"/>
<img src = "./assets/WiT/Salesforce%20Q3-2.jpeg"/>
</details>

### Solutions

<details>
<summary>
Q1
</summary>
One can do a binary search on answer for finding the required time.
</details>

<details>
<summary>
Q2
</summary>
It is a straight-forward implementation question.
</details>

<details>
<summary>
Q3
</summary>
It is more of a constructive question, wherein to get the answer, first remove all the number which aren't coprime to 
<code>n</code>, then check the product of remaining numbers modulo <code>n</code>, if the product is 1, output the leftover-array or else remove <code>n-1</code> and return the leftover-array.
</details>

## Interview

### DSA

1. There is a `vector` of strings given where each string is of length `2`. Find the length of the longest palindrome possible.

<details>
<summary>Solution</summary>
Store the frequency of each string in a <code>map</code>, then look for the reverse of the string if that string of length <code>2</code> is not a palindrome. Add <code>4*min(freq(string), freq(reverse_string))</code> to the answer. For strings of length <code>2</code> which are palindrome add their total length as it is to the answer.
This approach works as any palindrome can be inserted inside another palindrome without disturbing the palindromicity.
</details>


2. Given an array, find the length of the shortest subarray that shares the degree of that array. Degree of an array is defined as: maximum number of times an element is being repeated.

<details>
<summary>Solution</summary>
Calculate the frequency of each element in the array, then find the mode of the array, then find the index of first and last occurence of this element in the array, the subarray marked by index of first and last occurence of this element would be the shortest subarray which has the same degree as the parent array.
</details>

3. [Longest substring without repeating characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/) 

4. [Sort List](https://leetcode.com/problems/sort-list/)

5. [Valid Anagrams](https://leetcode.com/problems/valid-anagram/)

### OOPS

1. What's the difference between global and static variables?

2. What are 4 pillars of OOPS

3. Runtime Polymorphism

4. Difference between function overriding and function overloading

5. vtable

6. [Diamond Problem](https://www.geeksforgeeks.org/multiple-inheritance-in-c/)

7. Difference between pass by reference and pass by argument

### Tech Stacks

1. Difference between MySQL and MongoDB?

2. What's the advantage of React.js over CSS?

3. Questions related to dev projects

## OA - On campus hiring

### Questions

<details>
<summary>
Q1
</summary>
<img src = "./assets/On-campus%20hiring/Salesforce%20Q1-1.png"/>
<img src = "./assets/On-campus%20hiring/Salesforce%20Q1-2.png"/>
<img src = "./assets/On-campus%20hiring/Salesforce%20Q1-3.png"/>
</details>

<details>
<summary>
Q2
</summary>
<img src = "./assets/On-campus%20hiring/Salesforce%20Q2.png"/>
</details>

<details>
<summary>
Q3
</summary>
<img src = "./assets/On-campus%20hiring/Salesforce%20Q3.png"/>
</details>

### Solutions

<details>
<summary>
Q1
</summary>
One can maintain a map of double, char -> int to store the potential number N and the associated operation. Maintain the map's frequency only for those elements which are of the form sequence.size() - m*k where m is a natural number.
</details>

<details>
<summary>
Q2
</summary>
It is a straight-forward implementation question using substr and map.
</details>
<details>
<summary>
Q3
</summary>
<img src = "./assets/On-campus%20hiring/Salesforce%20Q3%20solution.jpeg">
</details>

## Interview
\<Insert CSEA link>