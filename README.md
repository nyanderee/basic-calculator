# basic-calculator

def add(x,y):
  return x + y

def subtract(x,y):
  return x - y

def mutiply(x,y):
  return x* y
  
def divide(x,y):
  return x / y
  
def power(x,y):
  return x ** y
  
def modulo(x,y):
  return x % y
  
digit = int(input("Type a number to select operation: "))
print ("1. Add")
print ("2. Subtract")
print ("3. Multiply")
print ("4. Divide")
print ("5. Power")
print ("6. Modulo")

num1 = int(input("Type your first number.")
num2 = int(input("Type your second number.")

if digit == '1':
  print(num1, "+", num2, "=", add(num1, num2))
  
elif choice == '2':
   print(num1,"-",num2,"=", subtract(num1,num2))

elif choice == '3':
   print(num1,"*",num2,"=", multiply(num1,num2))

elif choice == '4':
   print(num1,"/",num2,"=", divide(num1,num2))

elif choice == '5':
   print(num1, '**', num2, '=', power(num1, num2))

elif choice == '6':
   print(num1, '%', num2, '=', modulo(num1,num2))

else:
   print("Invalid input")
