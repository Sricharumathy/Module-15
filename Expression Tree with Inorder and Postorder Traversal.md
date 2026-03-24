# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```
#Reg No 212222060279
#Name Thiyaga Sri Charumathy


from binarytree import build,Node
x=['/','*','+','+',4,'-',2,3,1,None,None,9,5,None,None]
t=build(x)
print(t.inorder)
print(t.postorder)
```

## OUTPUT
<img width="971" height="81" alt="image" src="https://github.com/user-attachments/assets/124c497a-ae35-4e24-97f8-54d06a60fa4e" />


## RESULT
Thus the Python program to build the given expression tree and print the inorder and postorder traversals was created and executed successfully.
