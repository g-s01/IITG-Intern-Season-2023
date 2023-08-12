# Google Hiring Process

<details>
<summary>Pay and Duration</summary>
Pay: 1.14L/month
    
Duration: 8-10 weeks
</details>

## OA

### Questions

<details>
<summary>
Q1
</summary>
<img src = "./Hybrid%20Sequence/Hybrid%20Sequences-1.jpeg"/>
<img src = "./Hybrid%20Sequence/Hybrid%20Sequences-2.jpeg"/>
<img src = "./Hybrid%20Sequence/Hybrid%20Sequences-3.jpeg"/>
<img src = "./Hybrid%20Sequence/Hybrid%20Sequences-4.jpeg"/>
</details>

<details>
<summary>
Q2
</summary>
<img src = "/Median%20Sum/Median%20Sum-1.jpeg"/>
<img src = "/Median%20Sum/Median%20Sum-2.jpeg"/>
<img src = "/Median%20Sum/Median%20Sum-3.jpeg"/>
<img src = "/Median%20Sum/Median%20Sum-4.jpeg"/>
<img src = "/Median%20Sum/Median%20Sum-5.jpeg"/>
</details>

<details>
<summary>
Q3
</summary>
<img src = "/Prime%20Grid/Prime%20Grid-1.jpeg"/>
<img src = "/Prime%20Grid/Prime%20Grid-2.jpeg"/>
<img src = "/Prime%20Grid/Prime%20Grid-3.jpeg"/>
<img src = "/Prime%20Grid/Prime%20Grid-4.jpeg"/>
</details>

<details>
<summary>
Q4
</summary>
<img src = "./Toys/Toys-3.jpeg"/>
<img src = "./Toys/Toys-2.jpeg"/>
<img src = "./Toys/Toys-1.jpeg"/>
<img src = "./Toys/Toys-4.jpeg"/>
</details>

See [this](https://leetcode.com/discuss/interview-question/3760132/Google-SWE-Intern-OA-2023-(India)-Both-Questions) for more questions in this year's Google rounds.

### Solutions

<details>
<summary>
Q1
</summary>
Straight forward 2D-dp.
States: Indexes of the two arrays
</details>

<details>
<summary>
Q2
</summary>
See <a href = "https://leetcode.com/discuss/interview-question/3767717/google-intern-swe-2023-OA"> this </a>
</details>

<details>
<summary>
Q3
</summary>
Straight forward Dijkstra.
Calculate unique prime factors using sieve (upto 1e3 should work, then see primality of the by division by primes lesser than 1e3), then run a loop for making the edges, since p <=7. Then apply dijkstra.
</details>

<details>
<summary>
Q4
</summary>
Maintain a segment tree of the prefix sum, do cost of broken toys = 0 in a query. Find the index whose prefix sum is just than the amt to be paid and subtract the # of broken toys whose index is less than this index to answer the query.
</details>

More discussions and questions:
1. [Google Online Assessment Questions](https://leetcode.com/discuss/interview-question/352460/Google-Online-Assessment-Questions)

2. [Special Subsequence](https://leetcode.com/discuss/interview-question/3771949/Google-intern-OA-Problem-15072023-(Special-Subsequence)-Anyone-Please-help-how-to-solve-it) and [another discussion on the same](https://leetcode.com/discuss/interview-question/3759965/Google-Internship-OA)