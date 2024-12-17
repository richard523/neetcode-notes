---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Excalidraw Data
## Text Elements
# U If value appears at least twice re ^lnh9abm8

[1, 2, 2, 4]   ---> return true
[1,2,3,4] ------> return false

[1]  --> return fals
[] ---> return false
 ^7rtsrUQZ

[1,1,1,1,2] ---> return true ^bXGy22Lr

# M kind of looks like two sum where we have to store in hash
 if exists in hash, return a value ^YGBCNho1

# P
[1,2,2,4]
{1:1, 2: 2, 4:1}

for i, e in enumerate(hashmap.values()):
    if e > 1:
        return true

if len(nums) < 1:
    return false
else:
    return true

return false


 ^DPZHuDrA

Optimized Solution:
class Solution:
    def containsDuplicate(self, nums: List[int]) -> bool:
        hashset = set()

        for n in nums:
            if n in hashset:
                return True
            hashset.add(n)
        return False

 ^yp70Ebag

My attempt:
# 
        # [1,2,2,4]
        # {1:1, 2: 2, 4:1}
        hashmap = defaultdict(int)

        for i, e in enumerate(nums):
            hashmap[e] += 1
            print(hashmap[e])
        for i, e in enumerate(hashmap.values()):
            if e > 1:
                return True

        if len(nums) < 1:
            return False
        

        return False ^9y46pmtc

hashset = set() ^RrqHtmRn

%%
## Drawing
```compressed-json
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
```
%%