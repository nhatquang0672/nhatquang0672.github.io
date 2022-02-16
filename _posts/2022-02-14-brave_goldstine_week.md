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

Now, let continue after pending 48h.

I try to find the post I learned a lot about applying sliding window to string problems but I can't. I'll update this if I can get it later.


#### [560. Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)

_Thursday 10 Feb_

It's not hard problem. Although I submitted some wrong answer but it don't change my mind :v. Let do it again and hope I can solve it in the first time :v .

I try to do another approach but I was failed. Hmmmm...


#### [532. K-diff Pairs in an Array](https://leetcode.com/problems/k-diff-pairs-in-an-array/)

_Wednesday 09 Feb_

THe same with the problem "Subarray Sum Equals K". I solve both of them by using map/dictionary.


#### [258. Add Digits](hhttps://leetcode.com/problems/add-digits/)

_Tuesday 08 Feb_

Although Leetcode think that this problem is easy, but with my view, it's not easy. Can you solve it with O(1) runtime?

I don't realize that the result related to original number mod 9.

#### [389. Find the Difference](https://leetcode.com/problems/find-the-difference/)

_Monday 07 Feb_

I don't have anything to talk about this problem. I solve it with map/dict and after reading the discussion, we handle it with XOR operation.

### Weekly Contest

I just solve first problems in [**this weekly contest**](https://leetcode.com/contest/weekly-contest-280). It's really bad. 

The third problem is easy but because I stuck with the second problem so I don't have enough time to solve it.

Honestly, the second problem is not hard, I immediately got the right idea but don't pass the all testcase because I was missed some case?. Hmmm, it's bad, it's more bad, it's more more bad bad :v