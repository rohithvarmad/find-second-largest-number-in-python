# find-second-largest-number-in-python
lst = []
n = int(input("Enter number of elements : "))
for i in range(0, n):
    ele = int(input())
    lst.append(ele)
    lst.sort()
print("the second higest is", lst[-2])
