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
```
n= int(input())
for i in range(0,n):
    val=1
    for s in range(0,(n-i)-1):
        print(" ",end="")
    for j in range(0,i+1):
        print(val,end=" ")
        val=val*(i-j)//(j+1)
    print()

```

## Sample Output

<img width="645" height="588" alt="Screenshot 2025-10-20 105211" src="https://github.com/user-attachments/assets/24051194-795c-41fe-8bf6-88c2fa457878" />


## Result
Thus,the pyton program has been executed successfully
