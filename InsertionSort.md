#Insertion Sort

[22,27,16,2,18,6]
1. Write the insertion steps of provided array above

[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

2. Write the Big-O notation
o(n^2)

3. Time Complexity
        Average Case: O(n^2)
        Best Case O(n) #array is already sorted
        Worst Case O(n^2)

4. After the array is sorted which case will sorting 18 show?
        Average case

Write the first 4 sorting steps of [7,3,5,8,2,9,4,15,6]

for the sake of it I'll write until the amount of times the array has been modified equals to 4

[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6] #It will still check
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6] #It will still check
[2,3,4,5,7,8,9,15,6]
