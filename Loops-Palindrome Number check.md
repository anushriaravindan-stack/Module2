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
a=int(input())
num=0
temp=a
while temp!=0:
    s=temp%10
    num=(num*10)+s
    temp=temp//10
if(num==a):
    print("The given number",a,"is a Palindrome")
else:
    print("The given number",a,"is not a palindrome")
```
## Output

<img width="975" height="192" alt="image" src="https://github.com/user-attachments/assets/8ed2157a-333b-404d-a19f-e0fa02de5370" />

## Result

Thus, the Python program to check whether a given number is a palindrome using loops was executed successfully.
