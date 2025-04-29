## Experiment No: 1d – Conditional Statements- Checking  Odd number and it is greater than or equal to 25 or not using nested if..else

## AIM  
To Write a Python program to check whether the given number is Odd number and it is greater than or equal to 25 or not using nested if..else.
## ALGORITHM  

1.Begin the program.

2.Prompt the user to enter an integer value.

3.Read and store the number.

4.Check if the number is odd (i.e., number % 2 != 0).

If true, then:
a. Check if the number is greater than or equal to 25.

If true, print “Odd and greater than or equal to 25.”

Else, print “Odd but less than 25.”

Else, print “The number is even.”

5.Terminate the program.

## PROGRAM

a=int(input())

if a%2!=0 and a>=25:

    print(a,"is an Odd number")
    
    print(f"{a} is greater than or equal to 25")
    
elif a%2!=0 and a<=25:

    print(a,"is an Odd number")
    
    print(f"{a} is lesser than 25")  
    
else:

    print(f"{a} is NOT an Odd number")
    
    
## OUTPUT
![image](https://github.com/user-attachments/assets/c9a51254-baf8-4c3f-aff1-cb9778084bf3)


## RESULT
Thus the Python program to check whether the given number is Odd number and it is greater than or equal to 25 or not using nested if..else was implemented and executed  successfully
