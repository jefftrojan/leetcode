## My Beginner-friendly leetcode solutions


<br>
<details>
<summary>running sum of 1d array </summary>

# Intuition
The intuition behind the runningSum method is to calculate the cumulative sum of the elements in a given list. A cumulative sum is a sum of all the elements in a list up to a certain point. For example, if we have a list [1, 2, 3, 4], the cumulative sum of this list would be [1, 3, 6, 10].

The runningSum method uses the accumulate function from the itertools module to generate the cumulative sum of the elements in the input list nums. The accumulate function returns an iterator that yields cumulative sums of the elements in nums. The method then converts the iterator into a list using the list function and returns the result.

The intuition behind this approach is to use a function from the itertools module to efficiently generate the cumulative sum of the elements in nums. By using the accumulate function, the method avoids the need to store intermediate values in a list, which can be memory-intensive for large inputs.

# Approach
Input: The method takes a list of integers nums as input.

Cumulative sum calculation: The method uses the accumulate function from the itertools module to calculate the cumulative sum of the elements in nums. The accumulate function returns an iterator that yields cumulative sums of the elements in nums.

Conversion to a list: The method converts the iterator returned by accumulate into a list using the list function.

Output: The method returns the list as the final result.

This approach is simple, efficient, and memory-efficient, as it avoids the need to store intermediate values in a list and instead generates the cumulative sums one at a time as needed. By using the accumulate function, the method can handle large lists of integers without consuming too much memory.

# Complexity
- Time complexity: O(n)

- Space complexity: O(n)

# Code
```
class Solution:
    def runningSum(self, nums: List[int]) -> List[int]:
        # from python3's itertools, we can use accumulate to return the sums 
        return list(accumulate(nums))
        
```


</details>
<br><hr>

<details>
    <summary> Enter new task solution </summary>


</details>
<br><hr>