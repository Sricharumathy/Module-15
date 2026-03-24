# Ex. No: 15A - Build a Binary Tree with Float Values

## AIM:
To write a Python program to build a binary tree with a root, left, and right node using floating-point values.

---

## ALGORITHM:

1. **Start the program.**
2. **Import** the `Node` class from the `binarytree` module.
3. **Create a root node** using the `Node` class and assign a floating-point value.
4. **Create left and right child nodes** for the root with float values.
5. **Convert the tree** to a list and print the list of nodes.
6. **End the program.**

---

## PYTHON PROGRAM

```
#Reg No 212222060279
#Name Thiyaga Sri Charumathy



from binarytree import build
l=[]
size=int(input())
for i in range(0, size):
    l.append(input())
root=build(l)
print("Binary Tree : ")
for i in root.values:
    print(i, '-->', end="")
```

## OUTPUT
<img width="707" height="377" alt="image" src="https://github.com/user-attachments/assets/6161026f-32c7-41a9-a2d3-e3b23630e5c1" />


## RESULT
Thus the python program to build a binary tree with a root, left, and right node using floating-point values was successfully executed.
