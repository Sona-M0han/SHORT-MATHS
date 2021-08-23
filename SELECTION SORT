######    SELECTION SORT ###########
###  Finding the smallest element and placing at the right position #####
###  Time Complexity = O(n ^2 )
###  both best case and Worst case time complexity is O (n ^2)

arr =  [ 3, 7, 4, 1, 9, 3, 0 ]
print ("Given Array: ", arr)
n = len ( arr )          # size of array

for i in range (n) :
    minindex = i         
    for j in range ( i+1, n ):
        if arr[j] < arr[minindex] : 
            minindex = j   # minindex = index of the smallest element
    arr[i], arr[minindex] = arr[minindex], arr[i]  # placing the smallest element at the right position

print ("Sorted Array:", arr)
