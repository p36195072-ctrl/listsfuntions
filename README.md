# listsfuntions
Python List Functions

A beginner-friendly Python project that demonstrates different list functions and operations in Python.

📌 Description

This project shows how to:

Copy a list
Remove items from a list
Extend one list using another list
Print updated lists

It is useful for beginners learning Python list methods.

 Concepts Used:
Python Lists
copy()
remove()
extend()
List Printing
💻 Code
lucky_people = [9,45,5,6,24,53,24,64,63]

friends = ["jon","jon","jim","kevin","sev"]

friends2 = friends.copy()

friends2.remove("jim")

friends.extend(lucky_people)

friends2 = friends.copy()

print(friends2)
▶️ Output
['jon', 'jon', 'jim', 'kevin', 'sev', 9, 45, 5, 6, 24, 53, 24, 64, 63]
