def second_highest(array):
    array.sort()
    maximum = array[len(array) - 1]
    for i in range(len(array)):
        if array[len(array) - 1 - i] < maximum:
            return array[len(array) - 1 - i]


n = int(input())
array = list(map(int, input().split()))
print(second_highest(array))
