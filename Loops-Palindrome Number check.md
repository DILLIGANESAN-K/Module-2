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
rev=0
tem=num

while tem>0:
    rev=(10*rev)+tem%10
    tem//=10

if (rev==num):
    print(f"The given number {num} is a Palindrome")
else:
    print(f"The given number {num} is not a palindrome")
```
## Output
![443920855-bf3298f3-60e3-4bb5-9f0c-8525a72514fa](https://github.com/user-attachments/assets/fa845684-b10a-4f04-b34a-5cfa767acbd5)

## Result
Thus the program that checks whether a given number is a palindrome using loops is executed successfully.
