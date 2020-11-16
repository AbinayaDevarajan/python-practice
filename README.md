# python-practice


## Counters:

```
For counting the elements in a list 

https://docs.python.org/2/library/collections.html


def singleNumber(self, nums: List[int]) -> int:
        counter = Counter(nums)
        for k, v in counter.items():
            if v ==1:
                return k 
```
