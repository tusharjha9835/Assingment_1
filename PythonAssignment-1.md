## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans_1:- Because it is simple to use and more understandable to humans.

Q2. Why is Python called a dynamically typed language?
Ans_2:- Because in Python we don't have to declare the type of variable it understands it on its own.

Q3. List some pros and cons of Python programming language?
Ans_3:- Pros of Python :- easy to use,simple,objecte-oriented,supports built in libraries.
         Cons of Python :- runtime errors,poor memory efficiency.

Q4. In what all domains can we use Python?
Ans_4:- web dev, game dev, data analytics, data engineering, web scraping.

Q5. What are variable and how can we declare them?
Ans_5:- symbolic name that is a reference or pointer to an object, in python a variable is created the moment you first assign a value to it. 

Q6. How can we take an input from the user in Python?
Ans_6:- we use input() function to take input from the user.

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans_7:- string data type.

Q8. What is type casting?
Ans_8:- Converting one datatype into another is known as type casting or, type-conversion.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans_9:- Yes but we have to use input().split()

Q10. What are keywords?
Ans_10:- keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans_11:- We cannot use a keyword as a variable name, function name or any other identifier. They are used to define the syntax and structure of the Python language. In Python, keywords are case sensitive. There are 33 keywords in Python.

Q12. What is indentation? What's the use of indentaion in Python?
Ans_12:- Indentation refers to the spaces at the beginning of a code line.Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
Ans_13:- By using the print function.

Q14. What are operators in Python?
Ans_14:- Operators are special symbols in Python that carry out arithmetic or logical computation.

Q15. What is difference between / and // operators?
Ans_15:- / used for division.
         // used for Floor division.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans_16:- using print("```
iNeuroniNeuroniNeuroniNeuron
```")

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans_17:- num = int(input("Enter a number: "))
if (num % 2) == 0:
   print("Even")
else:
   print("Odd")

Q18. What are boolean operator?
Ans_18:- The logical operators and, or and not are also referred to as boolean operators. 

Q19. What will the output of the following?
```
1 or 0 = 1

0 and 0 = 0

True and False and True = False

1 or 0 or 0 = 1
```

Q20. What are conditional statements in Python?
Ans_20:- is used to handle conditions in your program.

Q21. What is use of 'if', 'elif' and 'else' keywords?

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans_22:- 
age = int(input("Enter the age: "))
if (age >= 18):
   print("I can vote")
else:
   print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
evensum = 0
length = len(numbers)
for j in range(length):
if (numbers[j]%2) == 0:
even_sum = even_sum + numbers[j]
print("Sum of even no in this list=",even_sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans_24:- 
num1=int(input("Enter First Number"))
num2=int(input("Enter Second Number"))
num3=int(input("Enter Third Number"))
if (num1> num2 and num1> num3):
    print("The Largest number is", num1)
elif (num2 > num1 and num2> num3):
    print ("The Largest number is", num2)
else:
    print ("The Largest number is", num3)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
b=[]
for i in numbers:
    if i > 150:
        if i > 500:
            break
        continue
    if i % 5 == 0:
        b.append(i)
        
print(b)