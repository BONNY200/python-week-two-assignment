﻿# python-week-two-assignment
# this is the empty list
my_list = []

# this is where to append elements to my_list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

#  this is where to insert 15 at the second position (index 1)
my_list.insert(1, 15)

#  this is where to extend my_list with another list
my_list.extend([50, 60, 70])

#  this is where to remove the last element
my_list.pop()

#  here is to Sort the list in ascending order
my_list.sort()

#  here is to find and print the index of 30
index_30 = my_list.index(30)
print("Index of 30:", index_30)
