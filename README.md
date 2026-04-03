# Towards-Defensive-programming-II
Exception Handling
# Exception Handling is a type of Error handling allowing us to manipulate and correct our code
in this case we will use the try/except block 

while True :
      try :
      x = int(input("please enter a value, try again...))
      break
  except ValueError : 
       print("sorry, that value does not match, try another value")
# should our user enter an incorrect value, our programme will provide a custom type-Error output as a result allowing us to identify the specific type error 

Another Example of Exception handling is Exception itself to create a custom type error for an invalid input 
example :
# opening a file that does not exist 
  file = open("numbers.txt", "r")
  print("file does not exist")

# These techniques allow us to Catch Error, Identify stack trace and provide cutom type_Error an output for an incorrect input in our programme
