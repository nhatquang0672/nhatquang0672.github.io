---
layout: post
title: Brave Goldstine Week
subtitle: Consistency is the key
# cover-img: /assets/img/path.jpg
# thumbnail-img: /assets/img/thumb.png
# share-img: /assets/img/path.jpg
tags: [algorithms, leetcode, learning]
---

[**Adele Goldstine**](https://en.wikipedia.org/wiki/Adele_Goldstine), born Adele Katz, wrote the complete technical description for the first electronic digital computer, ENIAC.

Today is Valentine Day. I don't need to talk to much about this :v. Because Tet Holiday, I was too lazy and didn't review the problems I solved. Honestly, I try to complete the daily challenge more than get deeply understand the problem. It's stupid. I need a super power from my mind to break all the dumbest thing inside it. I made so many grammar mistakes when writing this paragraph. Hope I can use English smoothly oneday.

Review something I've learned last week.

### Daily problems

#### [78. Subsets](https://leetcode.com/problems/subsets/)

_Sunday 13 Feb_

I remembered that I had the technical intervew when trying get the job after graduation and I got this problem. When I was in university, I saw this problem, I wrote the code to solve it but I didn't understood it. So when I got this problem in the interview, I couldn't handle it. 

When I fail something, maybe can't answer the easy question in the interview, or do a stupid action..., I usually jump into the overthinking status to try to firgure out about the problem. How I can't do stupid work like this ... but I just visit the facial, not deeply into it so the problems occurs again. When I write this sentence, I try my best to describe my mind howerver I'm failed. 

I can solve this problem by several ways, but I'll post the newest way I found after copying from other problems. This is really nice solution but I just do it in Python. Maybe I'll try another language when I face this problem again.

```
    def subsets(self, nums: List[int]) -> List[List[int]]:
        s = {()}
        for v in nums:
            s |= {d+(v,) for d in s}
        return s
```



#### [127. Word Ladder](https://leetcode.com/problems/word-ladder/)

_Sat 12 Feb_

This is a hard problem and I can't solve it, but the solution is really easy. I think I got this problem but when I see it in daily problems, I still can't solve it. Because it wasn't my solution so I forgot about it. 

We can use DFS to deal with this stuff. Try to get the next word from begin word by replacing characters in word with 'abcdefghijklmnopqrstuvwxyz'. I belive in myself :v that I can beat you if I meet you in the future. (`.`)


#### [567. Permutation in String](https://leetcode.com/problems/permutation-in-string/)

_Friday 11 Feb_

This is really nice problem using sliding window. I've read a post from Leetcode about the method to deal with this type problem. By my self, I don't know how to solve it. Maybe I need take more time to do the problems related to sliding window...

I'm stop at here. To be continued :V 


<!-- #### [452. Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)

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

Too much for the first time. -->