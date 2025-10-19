## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a *palindrome* using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable num.
2. Assign the value of num to a temporary variable temp.
3. Initialize a variable rev to 0 (used to store the reversed number).
4. Use a while loop to reverse the digits:
   - While temp > 0:
     - rev = (10 * rev) + temp % 10
     - temp = temp // 10
5. After the loop, compare rev with num:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
Add code Here
```
n=int(input())
rev=0
org=n
while n>0:
    rem=n%10
    rev=rev*10+rem
    n//=10
if(rev==org):
  print("The given number",org,"is a Palindrome")
else:
    print("The given number",org,"is not a palindrome")
```

## Output
![WhatsApp Image 2025-10-19 at 19 34 44_b76ebad9](https://github.com/user-attachments/assets/23e3c9b8-173c-496c-9c74-84e422cdfa33)



## Result
The program successfully takes a number as input from the user, reverses it using a while loop, and compares it with the original number.
If both are equal, it confirms that the number is a palindrome; otherwise, it displays that it is not a palindrome.
\
