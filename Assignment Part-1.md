#Assignment Part-1

Q1 Why do we call Python as a general purpose and high-level programming language?
  ->  Python is computer programming language often used to build website and software, automate tasks and conduct analysis.Python is general-purpose language, meaning          it can used to create a variety of different programs and isn't specialized for any specific problems.

Q2 What is python called a dynamically typed language?
->   Python is a dynamically typed language.This Means that the Python interpreter does type checking only as code runs, and the type of varibale is allowed to change        over its lifttime 
Q3. List some pros and cons of Python programming language?
->  Pros:
    Easy to use
    Easy to integrate
    Multi-paradigm approach
    High library support
  Cons:
    Slow speed of execution compared to C,C++
    Absence from mobile computing and browsers
    
Q4 In what all domains can we use Python?
->  * Data Science
    * Machine Learning
    * Deep Learning 
    * Artificial Intelligence
    * Computer Scripting 

Q5. What are variable and how can we declare them?
-> A variable declation always contains two components: type of the varibale and its name 
 
Q6. How can we take an input from the user in Python?
->  By using input() functions

Q7. What is the default datatype of the value that has been taken as an input using input() function
-> String 
Q8. What is type casting?
->  Type Casting is the method to convert the variable data type into certain data type in order to the operation required to be performed by users
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why
->  Yes 
    x,y,z = input("enter number").split()

Q10. What are keywords?
->   Special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes 

Q11. Can we use keywords as a variable? Support your answer with reason.
->   Yes we can but we shoudn't it will override the properties of the keyword

Q12. What is indentation? What's the use of indentaion in Python?
->   Indentation is the whitespace used in python. Indentation is used to create block of statement

Q13. How can we throw some output in Python?
->   print()

Q14. What are operators in Python?
->   * Arithmetic operators 
     * Comparison Operators 
     * Logical Operators 
     * Bitwise Operators 
     * Assigment Operators 
 
 Q15. What is difference between / and // operators?
 ->   / is used for float division and // is used of floor(interger) division
 
Q16. Write a code that gives following as an output.
->   "iNeuron"*3

Q17. Write a code to take a number as an input from the user and check if the number is odd or even
->   num = float(input("Enter number: "))
     if num%2 == 0:
        print("even")
     else:
        print("odd")
        
Q18. What are boolean operator?
->   not,and ,or,True,False

Q19. What will the output of the following?
->   1,0,False,1

Q20. What are conditional statements in Python?
->   A condition statement as the name suggests itself, is used to handle conditions in your program> Thease statements guid the program while making decisions based on the condition encoutered by the program 

Q21. What is use of 'if', 'elif' and 'else' keywords?
->   if is the first condition check for the condition.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
->    
      age = int(input('Enter the age'))
      
      if age >= 18:
        print('I can vote')
      else:
        print('I can't vote')
 
Q23. Write a code that displays the sum of all the even numbers from the given list.
-> Ans .
        numbers = [12, 75, 150, 180, 145, 525, 50]
        add = 0
        for i in numbers:
            if i %2 == 0:
                 add += i
            else:
                continue
        print(add)
        
        
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
-> 
ans
x, y, z = input("Enter 3 numbers seprated by comma: ")
if int(x) > int(y) and int(x) > int(z):
  print(x,'is greatest')
elif int(y) > int(z):
  print(y,"is greatest")
else:
  print(z,"is greatest")
  
 Q25. Write a program to display only those numbers from a list that satisfy the following conditions
->
ANS
numbers = [12, 75, 150, 180, 145, 525, 50]
lst = []

for i in numbers:
    if i > 150:
        if i >500:
            break
    elif i % 5 == 0:
        lst.append(i)
        
print(lst)


Q26. What is a string? How can we declare string in Python?
-> Ans
    python are arrays of btyes represeting unicode characters
    
   
 Q27. How can we access the string using its index?
-> Ans . Sqaure brackets can used to access the elements of the string.

 
      



  
