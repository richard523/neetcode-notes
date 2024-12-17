# [[defaultdict()]]

We need default dict to set



# [[hashmap]]

### Optimized Solution
```Optimized Solution:
class Solution:
def containsDuplicate(self, nums: List[int]) -> bool:
	hashset = set()

	for n in nums:
		if n in hashset:
			return True
		hashset.add(n)
	return False


```

### My attempt. 15 mins
```My Attempt
class Solution:
    def containsDuplicate(self, nums: List[int]) -> bool:
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
        return False
```

#### ONE LINER:
class Solution:

``` 
 class Solution:

    def containsDuplicate(self, nums: List[int]) -> bool:

        return len(nums) != len(set(nums))
```