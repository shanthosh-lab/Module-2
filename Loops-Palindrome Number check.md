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
num=int(input())

rev=0

temp=num

while temp>0:

rev=(10*rev)+temp%10

temp//=10

if rev==num:

print("The given number {} is a Palindrome".format(num))

else:

print("The given number {} is not a palindrome".format(num))
## Output

<img width="1247" height="233" alt="488744369-92e202b9-0a0c-4aa1-b66d-356cfdfe412e" src="https://github.com/user-attachments/assets/027f36b1-a847-4063-84a6-42d6666f580b" />

## Result
Thus, To write a Python program that checks whether a given number is a palindrome using loops is verified.
