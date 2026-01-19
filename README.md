# Welcome (feel free to visit our repositry)!
<h2>
This will be only a TEST so please be patient and if you needed anything feel free to visit our repository, and open a branch if you face any problem.
</h2>
<h3>
  we'll start with linux basics then we will treat the OS of the major (OS) out there, then we will continue with the programming languages that you will need through this course like (python, Golang, C++, Java, mysql , Ruby and finally Docker) through this course. 
</h3>
<h4>
  and then we'll finish with the packet-tracer, burpsuit, wireshark,msfconsole, beef, aircrakcer-ng (for wifi attacks like devil twin) for the aircracker-ng you'll need a wifi adapter that support the debian sys.
</h4>
<h5>
#Multiplication/Exponent Table App

print("Welcome in this multiplication/Exponent Table App")
name = input("Please enter your name: ").title().strip()
message = name + ", Math is cool!"
num = float(input("Please enter your number: "))
print("\nMultiplication Table For: " + str(num))
print("\n\t 1.0 * " + str(num) + " = " + str(round(1*num, 4)))
print("\n\t 2.0 * " + str(num) + " = " + str(round(2*num, 4)))
print("\n\t 3.0 * " + str(num) + " = " + str(round(3*num, 4)))
print("\n\t 4.0 * " + str(num) + " = " + str(round(4*num, 4)))
print("\n\t 5.0 * " + str(num) + " = " + str(round(5*num, 4)))
print("\n\t 6.0 * " + str(num) + " = " + str(round(6*num, 4)))
print("\n\t 7.0 * " + str(num) + " = " + str(round(7*num, 4)))
print("\n\t 8.0 * " + str(num) + " = " + str(round(8*num, 4)))
print("\n\t 9.0 * " + str(num) + " = " + str(round(9*num, 4)))
print("\nExponenation Table For: " + str(num))
print("\n\t 1.0 ** " + str(num) + " = " + str(round(1**num, 4)))
print("\n\t 2.0 ** " + str(num) + " = " + str(round(2**num, 4)))
print("\n\t 3.0 ** " + str(num) + " = " + str(round(3**num, 4)))
print("\n\t 4.0 ** " + str(num) + " = " + str(round(4**num, 4)))
print("\n\t 5.0 ** " + str(num) + " = " + str(round(5**num, 4)))
print("\n\t 6.0 ** " + str(num) + " = " + str(round(6**num, 4)))
print("\n\t 7.0 ** " + str(num) + " = " + str(round(7**num, 4)))
print("\n\t 8.0 ** " + str(num) + " = " + str(round(8**num, 4)))
print("\n\t 9.0 ** " + str(num) + " = " + str(round(9**num, 4)))

print(message)
print("\t" + message.lower())
print("\t\t" + message.title())
print("\t\t\t" + message.upper())

#Instructor code

#Basic Data Types Challenge 5: Multiplication/Exponent Table Program

print("Welcome to the Multiplication/Exponent Table Program")
#Gather user input
name = input("\nHello, what is your name: ").title().strip()
num = float(input("What number would you like to work with: "))
message = name + ", Math is cool!"
#Multiplication table
print("\nMultiplication Table For " + str(num))
print("\n\t 1.0 * " + str(num) + " = " + str(round(1*num, 4)))
print("\t 2.0 * " + str(num) + " = " + str(round(2*num, 4)))
print("\t 3.0 * " + str(num) + " = " + str(round(3*num, 4)))
print("\t 4.0 * " + str(num) + " = " + str(round(4*num, 4)))
print("\t 5.0 * " + str(num) + " = " + str(round(5*num, 4)))
print("\t 6.0 * " + str(num) + " = " + str(round(6*num, 4)))
print("\t 7.0 * " + str(num) + " = " + str(round(7*num, 4)))
print("\t 8.0 * " + str(num) + " = " + str(round(8*num, 4)))
print("\t 9.0 * " + str(num) + " = " + str(round(9*num, 4)))
#Exponent table
print("\nExponent Table For " + str(num))
print("\n\t" + str(num) + " ** 1 = " + str(round(num**1, 4)))
print("\t" + str(num) + " ** 2 = " + str(round(num**2, 4)))
print("\t" + str(num) + " ** 3 = " + str(round(num**3, 4)))
print("\t" + str(num) + " ** 4 = " + str(round(num**4, 4)))
print("\t" + str(num) + " ** 5 = " + str(round(num**5, 4)))
print("\t" + str(num) + " ** 6 = " + str(round(num**6, 4)))
print("\t" + str(num) + " ** 7 = " + str(round(num**7, 4)))
print("\t" + str(num) + " ** 8 = " + str(round(num**8, 4)))
print("\t" + str(num) + " ** 9 = " + str(round(num**9, 4)))
#Math is cool!
print("\n" + message)
print("\t" + message.lower())
print("\t\t" + message.title())
print("\t\t\t" + message.upper())
  
</h5>

<h6>

  #Quadratic Equation Solver App

import cmath

print("Welcome to thi Quadratic Equation Solver App")

print("\nA quadratic equation is of the form ax^2 + bx + c = 0 ")
print("Your solutions can be real or complex numbers. ")
print("A complex number has two parts: a + bj")
print("Where a is the real portion and bj is the imaginary portion.")


eq_number = int(input("\nHow many equation you want to solve today: "))

for i in range(eq_number):
    print("Solving equation number : " + str(i+1))
    a = float(input("Please enter your value of a: "))
    b = float(input("Please enter your value of b: "))
    c = float(input("Please enter your value of c: "))
    so hey please be patient as we work through this course so we'll be there working on them at least the next 3 months. so be patient and if you have any question please dont hesitate to ask. and please fell free to open a branch and idicate your the problem you faced.
    x1 = (-b + cmath.sqrt(b**2 - 4*a*c))/(2*a)
    x2 = (-b - cmath.sqrt(b**2 - 4*a*c))/(2*a)

    in this segment we will work on the OS SYS a lot so please don't hisitate on asking question or you can open a branch on the segment you did't understand.
    print("\nThe solutions to " + str(a) + " x^2 + " + str(b) + "x + " + str(c) + " = 0 are: ")
    print("\n\tx1 = " + str(x1))
    print("\tx2 = " + str(x2))
    print("\nThank you for using the Quadratic Equation Solver App.   Goodbye.")              
so please it's not your first reply at all or even be nice to them so we can help you with that at the first place and pleas ebe patient about it or even open a branch if you didn't talk about it in the first plase
</h6>

<h7>
and the next thing about this is all about to be or not to be so please if you had any problem about it just reach us or leave a comment what did hurt you at the first place and we will reach to talk with you.





  
</h7>

