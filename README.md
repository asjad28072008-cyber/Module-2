# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
x=16
print(bin(x))
```

## Output

<img width="378" height="121" alt="Screenshot 2025-10-19 211607" src="https://github.com/user-attachments/assets/98aa2b22-ddea-4efc-a04e-0d96668d19fb" />



## Result
Thus,the pythin program has been executed successfully


# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

```
a=int(input ())
b=int(input ())
def result (a,b):
    gh=a%b
    return gh
gh=result (a,b)
print ("modulo is",gh)
```

## Output

<img width="614" height="302" alt="Screenshot 2025-10-19 213033" src="https://github.com/user-attachments/assets/76b7bbfc-cc95-45a8-a49d-299dbbc40f79" />



## Result
Thus ,the python progrsm has been executed successfully




# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
result=lambda a,b :a+b
a=int(input())
b=int(input())
print(result(a,b))
```

## Output

<img width="383" height="217" alt="Screenshot 2025-10-20 104740" src="https://github.com/user-attachments/assets/ae237dc1-c1c9-4b89-ae83-4a427c96e51d" />



## Result
Thus,the python program has been executed successfully





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






## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
rev=0
temp=num
pal=0
while temp>0:
    rem=temp%10
    pal=(pal*10)+rem
    temp//=10
if num!=pal:
    print("The given number",num,"is not a palindrome")
else:
    print("The given number",num,"is a Palindrome")
```
## Output


<img width="1078" height="228" alt="Screenshot 2025-10-20 105623" src="https://github.com/user-attachments/assets/0af99412-9783-4a15-a462-5db4fdd9ce7c" />




## Result
Thus, the Python program that checks whether a given number is a palindrome using loops is created successfully.
