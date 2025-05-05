# csci411-week-5-solved
**TO GET THIS SOLUTION VISIT:** [CSCI411 Week 5 Solved](https://www.ankitcodinghub.com/product/csci411-week-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98715&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI411 Week 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Written Problems

1. Consider the following refined notion of bitonicity. Call a sequence S = [s1, s2, . . . , sn] an initially increasing bitonic sequence if there is an index 1 ≤ i ≤ n such that s1 &lt; s2 &lt; ··· &lt; si and si &gt; si+1 &gt; ··· &gt; sn. On the other hand, call S an initially decreasing bitonic sequence if there is an index 1 ≤ j ≤ n such that s1 &gt; s2 &gt; ··· &gt; sj and sj &lt; sj+1 &lt; ··· &lt; sn. S is bitonic if it is either initially increasing or initially decreasing and bitonic.

Given a sequence A, we would like to determine its longest bitonic subsequence.

<ol>
<li>(a) &nbsp;(5 pts) Find a longest bitonic subsequence of the sequence A = [5, 8, 8, 3, 4, 1, 7, −3, 2, 9, 12].Show your work.</li>
<li>(b) &nbsp;(15 pts) Describe the optimal substructure of this problem. In particular, define the longest bitonic subsequence of A in terms of the solution for shorter sequences. You may assume that we have a solution for the longest increasing subsequence problem. Justify your answer.</li>
<li>(c) &nbsp;(10 pts) Write pseudocode for a function LBS(A) which returns the length of a longest bitonic subsequence of A. You are given a function LIS(A) that returns a list L that is the same length as A such that L[i] is the length of the longest increasing subsequence of A ending at index i.</li>
<li>(d) &nbsp;(5 pts) Analyze the asymptotic run time of your algorithm.1</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2. Given two strings A and B, we can transform A to B using insertions, deletions, and substitutions. Each of these operations comes with a prespecified cost. Our goal is to determine the minimum cost of changing A to B. We call this cost the edit distance from A to B.

For example, suppose A = “ataccg” and B = “aacgca” and insertions, deletions, and substitutions all have cost 1. Then we can transform A to B by (1) deleting the t, (2) inserting a g between the two c’s, and (3) substituting the last g for an a. This process has total cost 3 and the edit distance from A to B is 3.

We can represent this transformation with the following alignment: Aatac cg

Ba acgca

Here, insertions are represented by an underscore (“ ”) in A, deletions are represented by an

underscore in B, and substitutions are represented by mismatched characters.

<ol>
<li>(a) &nbsp;(5 pts) Determine the edit distance and an optimal alignment between the strings “exponen-tial” and “polynomial”. Show your work (draw the resulting alignment).</li>
<li>(b) &nbsp;(15 pts) Describe the optimal substructure of this problem. In particular, define the editdistance between A and B in terms of the solution for shorter strings. Justify your answer.</li>
<li>(c) &nbsp;(10 pts) Write pseudocode for a function editDistance(A, B, ins, del, sub) which re- turns the edit distance between A and B given costs for insertions, deletions, and substitu- tions. Assume that matches have a cost of 0. This function does not need to generate an alignment.</li>
<li>(d) &nbsp;(5 pts) Analyze the asymptotic run time of your algorithm.</li>
</ol>
Coding Problem

(30 pts) Write a C++ implementation of the pseudocode you developed for problem (2c) modified to return an alignment and submit to Blackboard and to turnin as assignment 4.cpp. You may find the skeleton code in assignment 4 skeleton.cpp on Blackboard helpful.

<ul>
<li>Input will come from cin
<ul>
<li>– &nbsp;The first line contains a single integer n indicating the number of examples. n+1 lines follow.</li>
<li>– &nbsp;The second line contains three space separated integers. These represent the cost of an insertion, a deletion, and a substitution respectively and may be positive, negative, or zero. The cost of a match is assumed to be 0.</li>
<li>– &nbsp;The next n lines each contain two space separated strings, A and B.</li>
</ul>
</li>
<li>Print output to cout– Your output should consist of three lines per example.

– The first line is the alignment of string A.

– The second line is the alignment of string B.

– The third line is the cost or score associated with the alignment.</li>
<li>If there is ever a choice between multiple actions which would result in different optimal align- ments, prefer substitutions to deletions and deletions to insertions (first try substitution, then try deletion, and finally try insertion).2</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Examples

Example 1:

Input:

4

111

expon poly snowy sunny coarse course ataccg aacgca

Expected output: expo n

poly 4

snowy sunny 3 coarse course 1

atac cg a acgca 3

Example 2:

Input:

2

332

ataagcc gtacc aagtaac gcccgtaa

Expected output: ataagcc

gt a cc

8

aagtaac gcccgtaa 13

Example 3:

Input:

2

135

coarse course break brake

Expected output:

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
co arse cou rse 4 break br ake 4

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
