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
a=int(input())

o=1

for i in range (1,a+1):

for j in range (1,i+1):

print(o,end=(" "))

o+=1
print()

## Sample Output
<img width="742" height="647" alt="488743977-9dd804ad-163d-4b7a-a8a1-65da3213d8d2" src="https://github.com/user-attachments/assets/c5977768-e330-4551-b666-2997d0e42fb1" />




## Result
Thus, This project demonstrates a simple Python program to generate Floyd’s Triangle, where the number of rows is provided by the user us verified.

