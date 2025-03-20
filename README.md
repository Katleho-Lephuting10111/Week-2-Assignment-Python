# Week-2-Assignment-Python

#Create an empty list
my_list = []

#Append elements to my_list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

#Insert 15 at second position
my_list.insert(1, 15)

#Extend my_list with another list
my_list.extend([50, 60, 70])

#Remove last element from my_list
del my_list[7]

#Sort my_list in ascending order
my_list.sort()

#Find and print index of 30
index_30 = my_list.index(30)
print("Index of 30:", index_30)

print("Final my_list:", my_list)
