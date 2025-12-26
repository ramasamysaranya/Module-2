# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
~~~
import math
n = int(input())
for r in range(n):
    print((n-r-1)*" ",end="")
    for c in range(0,r+1):
        print(f"{math.comb(r,c)}",end=" ")
    print(" ")
~~~

## Sample Output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/f23b99fc-ffb0-43bd-800c-1569b9c6833a" />

## Result
Thus, the program has been executed successfully.
