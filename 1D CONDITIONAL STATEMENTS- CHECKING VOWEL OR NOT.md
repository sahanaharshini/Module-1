## Experiment No: 1d – Conditional Statements- Checking Vowel or not

## AIM  
To Write a Python program to check whether the given character is a vowel or not using if..else statement
## ALGORITHM  
1. Begin the program.  
2. Take a character input from the user
3. Convert the character to lowercase
4. Check if the lowercase character is one of the vowels: 'a', 'e', 'i', 'o', 'u'
5. If it is a vowel, display "The given character is a vowel"
6. Otherwise, display "The given character is NOT a vowel"
4. Terminate the program.

## PROGRAM
```python
# Reg.No-212223060236
# Name- Sahana Hrahini K
# Write your code here

char = input("Enter a character: ")
char_lower = char.lower()

if char_lower in ['a', 'e', 'i', 'o', 'u']:
    print("The given character is a vowel")
else:
    print("The given character is NOT a vowel")
```

## OUTPUT
<img width="948" height="177" alt="Screenshot 2025-09-24 084421" src="https://github.com/user-attachments/assets/60218dc5-cac5-40e1-a1ef-86492724dbc7" />

## RESULT
The program was successfully executed. It correctly identified whether the given character was a vowel or not.
