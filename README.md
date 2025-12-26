# two-sum
def twosum(nums,target):
    n=len(nums)
    for i in range(n):
        sum=nums[i]
        for j in range (i+1 ,n):
            if sum+nums[j]==target:
                return[i,j]
nums=[2,7,11,5]
target=9
print(twosum(nums,target))
