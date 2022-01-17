---
layout: post
title: Practical Nightingale Week
subtitle: Consistency is the key
# cover-img: /assets/img/path.jpg
# thumbnail-img: /assets/img/thumb.png
# share-img: /assets/img/path.jpg
tags: [algorithms, leetcode, learning]
---

[**Florence Nightingale**](https://en.wikipedia.org/wiki/Florence_Nightingale#Statistics_and_sanitary_reform), more prominently known as a nurse, was also the first female member of the Royal Statistical Society and a pioneer in statistical graphics.

About the title of this post, I got it from docker name-generator.

Review something I've learned last week, starting from Leetcode problems I solved.

### Daily problems

#### [849. Maximize Distance to Closest Person](https://leetcode.com/problems/maximize-distance-to-closest-person/)

_Sunday 16 Jan_

It's an easy problem but I can't write the best code. All thing need to do is find the maximum distance between 1's elements in an input array. But the bound case is the exception. 

I need an additional code for the bound case. 

The solution from discussion is clean, clear. This is the type of solution I want to create.


#### [1345. Jump Game IV](https://leetcode.com/problems/jump-game-iv/)

_Saturday 15 Jan_

This is a hard problem but if you can clarify the requirement, it's not hard. I couldn't do it and I remember I was in lazy mode on this day. Just copy the solution to complete the daily challenge and gain Leetcode coins. 

How to exceed yourself?

I'm noted about this problem and will solve **_all Jump Game problems in Leetcode_** next week.


#### [8. String to Integer (atoi)](https://leetcode.com/problems/string-to-integer-atoi/)

_Friday 14 Jan_

One of the most disliked problems in Leetcode, I think. I can use the built-in function for this problem and just return something like return int(str). This is a way I did before. 

Honestly, I was 1 year ago just needed a solution, I wanted to be better in problem-solving skills but with the shortest path and don't wanna take so much time for this. Maybe I'm now also like this but have a little different. :D

If you implement **atoi function** by yourself, this question becomes interesting.

We need to take a look at some cases like: "+323 aaa", "-323", "32-ab" and the difficult part is overflow from the input (in this question, the result must be in the range of 32-bit integer). I'll do it again.
.
.
.
I took more than 20 minutes to solve this problem again. Sad story ~.~. Failed with the empty testcase. 

**Always read carefully the question constraints.**


#### [452. Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)

_Thursday 13 Jan_

It's an easy question for me. But writing clear, clean code is not easy, so the medium level is right :v. 

Sorting with start time or end time is ok, but will have a different comparison to get the correct answer.

If you have two interval [s1, e1], and [s2, e2] => two intervals have an intersection if **(e1 >= s2 and e2 >= s1)**

I'll do it again.
.
.
.
Less than 10 minutes to solve this problem again. First, I sorted the input with start time and don't have a clean, clear code. But, I do it with this try.


#### [701. Insert into a Binary Search Tree](https://leetcode.com/problems/insert-into-a-binary-search-tree/)

_Wednesday 12 Jan_

It's easy problem. I solved it with iteration for the first time and recursion for the second time. 


#### [1022. Sum of Root To Leaf Binary Numbers](https://leetcode.com/problems/sum-of-root-to-leaf-binary-numbers/)

_Tuesday 11 Jan_

Another tree problem. For the first time, I need a string path to track value from root to left and use the built-in function int(str, base) to get the answer. But it will be easier if use bit manipulation. `_cur_val = cur_val << 1 | node.val_`


#### [67. Add Binary](https://leetcode.com/problems/add-binary/)

_Monday 10 Jan_

The idea for this problem is straightforward but writing a clean, clear solution is not easy. 
Let do it again.
. 
.
.
Done, after maybe less than 10 minutes. 


### Weekly Contest

I solved 3 problems in [**this weekly contest**](https://leetcode.com/contest/weekly-contest-276).

I'm too lazy now, maybe I'll add my comment next week. 

Too much for the first time.