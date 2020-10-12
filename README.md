# py101Assignment1
python code
# python program to find the largest number in a list
list = []
num = int(input("Enter number of elements in list: "))
for i in range(1, num + 1):
    ele = int(input("Enter elements: "))
    list.append(ele) 
list.sort()
print("first largest element is:", list[-1])

#Output

Enter number of elements in list: 3
Enter elements: 5
Enter elements: 8
Enter elements: 7
first largest element is: 8

# Python Program to Find the Second Largest Number in a List

list = []
num = int(input("Enter number of elements in list: "))
for i in range(1, num + 1):
    ele = int(input("Enter elements: "))
    list.append(ele) 
list.sort()
print("Second largest element is:", list[-2])

#Output
Enter number of elements in list: 4
Enter elements: 54
Enter elements: 65
Enter elements: 43
Enter elements: 546
Second largest element is: 65

#Python Program to Merge Two Lists and Sort it

def Merge(list1, list2): 
    final_list = list1 + list2 
    final_list.sort() 
    return(final_list) 

list1 = [254, 148, 91, 41, 226, 341] 
list2 = [24, 45, 38, 352, 125, 260] 
print(Merge(list1, list2)) 

#output

[24, 38, 41, 45, 91, 125, 148, 226, 254, 260, 341, 352]

#Python Program to Swap the First and Last Value of a List

def swapList(newList): 
    size = len(newList) 
    temp = newList[0] 
    newList[0] = newList[size - 1] 
    newList[size - 1] = temp   
    return newList

newList = [12, 35, 9, 56, 24] 
print(swapList(newList))

#output

[24, 35, 9, 56, 12]
