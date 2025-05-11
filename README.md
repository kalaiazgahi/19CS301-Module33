# 19CS301-Module33
Exp.No:3(a)	STRING- FIND AND REPLACE
### AIM
To write a Python function that accepts a string and prints the first three and last three characters of the string.

### ALGORITHM

Step 1: Begin the program.

Step 2: Define a function slice() that takes a string as input.

Step 3: Use string slicing to get the first three characters (string[:3]).

Step 4: Use string slicing to get the last three characters (string[-3:]).

Step 5: Display the first and last three characters.

Step 6: Terminate the program.

### PROGRAM
```def replacestr(str1,replace_str):
   def slice(a):
    b=str(a)[0:3]
    c=str(a)[-3:]
    print("The first 3 characters are '"+b+"'")
    print("The last 3 characters are '"+c+"'")
a=input()    
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/f5e9f3fe-b5f1-435f-b9fb-572fe4ae2ab3)


### RESULT
Thus, the Python function that accepts a string and prints the first three and last three characters has been implemented and executed successfully.




Exp.No:3(b)	REGEX-PATTERN MATCHING USING REGEX

### AIM
To write a Python program that matches a string that has an a followed by two to three 'b'.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept a string str1 from the user.

Step 3:	 Define a regular expression pattern as r"[a]+b{2,3}".

Step 4:	 Use the re.match() function to check if the string str1 matches the given pattern. If the string str1 matches the pattern, proceed to step 5. Else If the string str1 does not 
          match the pattern, proceed to step 6.

Step 5:	 Print "Found a match!" if the string matches the pattern.

Step 6:	 Print "Not matched!" if the string does not match the pattern.

Step 7:	 Terminate the program.

### PROGRAM
```import re
str1=input()
pattern=r"[a]+b{2,3}"
if re.match(pattern,str1):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/b473b268-4127-4409-9985-e43d47b02847)

### RESULT
Thus the python program for pattern matching using regular expression was  implemented and executed successfully.

Exp.No:3(c)	LIST- EVEN NUMBERS LIST

### AIM
To write a python function that accepts N and to create a list with even numbers up to N.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer a.

Step 3:	 Create an empty list l.

Step 4:	In For Loop, Iterate through the numbers from 1 to a-1.For each number i, check if i is even: If i % 2 == 0, append i to the list l.

Step 5:	 Print the list l which contains all even numbers from 1 to a-1.

Step 6:	 Terminate the program.
### PROGRAM
```def createlist(a):
    l=[]
    for i in range(1,a):
        if (i%2==0):
            l.append(i)
    print(l)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/a21369b0-1967-4362-b91f-84bb82becbcd)

### RESULT
Thus the python program for printing a list with even numbers up to n, was implemented and executed successfully.

Exp.No:3(d)	TUPLES- A TUPLE WITH MULTIPLES OF 5
### AIM
To write a Python program to create a tuple with multiples of 3 up to N (excluding N), and print the sum of the elements in the tuple. The value of N is to be entered by the user.


### ALGORITHM

Step 1: Begin the program.

Step 2: Accept an integer N from the user.

Step 3: Initialize an empty list multiples_of_3_list.

Step 4: Use a for loop to iterate from 3 to N (exclusive), with a step of 3.

 
Step 5: Convert the list to a tuple named multiples_of_3_tuple.

Step 6: Calculate the sum of the tuple using sum() function.

Step 7: Print the tuple and the sum.

Step 8: Terminate the program.


### PROGRAM
```
a=int(input())
b=[]
sum=0
for i in range(3,a,3):
    sum+=i
    b.append(i)
print(tuple(b))
print("Sum is",sum)
    
```
### OUTPUT
![image](https://github.com/user-attachments/assets/65fa6bfc-46e8-45c2-b2ad-e5fe4f573728)



 
### RESULT
Thus the python program for printing a tuple with numbers that are multiples of 5 up to n, was implemented and executed successfully.

Exp.No:3(e)	SEB- STRING SLICING
### AIM
To write a python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Take a slice of input_string starting from index 2 up to index 10.

Step 3:	 Reverse the substring.

Step 4:	 slice the reversed string, extracting every second character, starting from the first.

Step 5:	 Print the sliced string in the above step.

Step 6:	 Terminate the program.
### PROGRAM
```
def slice(input_string):
    substring = input_string[2:10:]
    reversed_substring = substring[::-1]
    print(f"The reversed string is '{reversed_substring[::2]}'")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/1c3e5d33-4525-44e9-93c4-3431af135a04)

### RESULT
Thus the python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string was implemented and executed successfully.









