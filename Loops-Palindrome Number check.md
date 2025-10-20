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
