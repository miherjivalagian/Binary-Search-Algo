def binarySearch(arr, x, low, high):
    if high >= low:
        mid = low + (high - low)//2
    if arr[mid] == x:
        return mid
    elif arr[mid] > x:
        return binarySearch(arr, x, low, mid-1)
    else:
        return binarySearch(arr, x, mid+1, high)
    else:
        return -1
    arr = [1,2,3,4,5,6,7,8,9,10]
    x = int(input("Enter a number between 1 and 10: "))
    result = binarySearch(arr, x, 0, len(arr)-1)
    if result != -1:
        print("element is present at position" + str(result))
    else:
        print("Element not found")
    