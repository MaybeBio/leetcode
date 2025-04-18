1，本质双指针：

class Solution(object):
    def twoSum(self, nums, target):
        """
        :type nums: List[int]
        :type target: int
        :rtype: List[int]
        """
        for i in range(len(nums)):
            for j in range(i+1,len(nums)):
                if nums[i]+nums[j] == target:
                    return [i,j]
                else:
                    continue 

![image](https://github.com/user-attachments/assets/2684ca23-7c51-4d77-910f-305db3b29ce7)



        
