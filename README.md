# 35.-Search-Insert-Position

```python
low = 0
high = len(nums)-1
while low<=high :
    mid = (low + high) // 2
    if target == nums[mid] :
        return mid
    elif target > nums[mid]:
        low = mid + 1
    elif target < nums[mid]:
        high = mid - 1
else :      
    return low
```

