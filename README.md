# list_task

list1=[56,87,96,45,89]
print(max(list1))

list1.sort()
print("maximum element in a list is: ",list1[-1])
print("second maximum element in a list is: ",list1[-2])

list2=[23,43,53,12,87]
list=list1+list2
list.sort()
print("the sorted list is: ",list)

temp=list[0]
list[0]=list[-1]
list[-1]=temp
print("list after swapping first and last elemnt is: ",list)
