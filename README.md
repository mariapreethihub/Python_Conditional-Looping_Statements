## 1.Conditional Statement in Python

     Conditional statements allow the program to make decisions based on certain conditions.

 **Types of Conditional Statements:**

  **1.if statement** -Executes a block of code if the condition is True.
  
      Example: 
      x=5
      if x>2:
          print("x is greater than 2") # Output:x is greater than 2
         
  **2.if-else statement** -Executes one block of code if the condition is True, otherwise executes another block.
     
      Example:
      x = 5
      if x > 5:
          print("x is greater than 5")
      else:
          print("x is less than or equal to 5")  # Output: x is less than or equal to 5
    
  **3.if-elif-else statement**- Checks for multiple conditions.
  
      Example:
      x = 5
      if x > 10:
          print("x is greater than 10")
      elif x > 5:
          print("x is between 6 and 10")  
      else:
          print("x is less than or equal to 5") # Output: x is less than or equal to 5.
    
  **4.Nested if statement**- An if statement inside another if statement.
  
      x = 10
      if x > 5:
          print("x is greater than 5")
        if x > 10:
            print("x is greater than 10")
        else:
          print("x is between 5 and 10")   # Output: x is greater than 5 x is between 5 and 10

        
## 2. Looping Statements
      
      Looping statements help execute a block of code multiple times.

  **Types of Looping Statements:**
     
  **1. for loop**- The for loop is used to iterate over a sequence (list, tuple, dictionary, set, or string).
  
       Syntax: for element in collection:
                   Block of code

       Example: for i in range(5):  
                   print(i)  
       Output: 0 1 2 3 4

 **2. while loop**- Executes a block of code as long as the condition is True.
 
      Syntax :while Boolean_Expression:
                  Block of code
                  
      Example:
      x = 1
      while x <= 5:
          print(x)
          x += 1
      Output: 1 2 3 4 5
      
**3. Nested Loops**-A loop inside another loop.

     Example: 
       for i in range(3):
           for j in range(2):
               print(f"i={i}, j={j}")
     Output:
     i=0, j=0
     i=0, j=1
     i=1, j=0
     i=1, j=1
     i=2, j=0
     i=2, j=1
     
**4. Loop Control Statements** - Loop Control Statements helps to control the flow of loops.

     1.break – Stops the loop completely.
     
       Example:
       for i in range(5):
           if i == 3:
               break
           print(i)
       Output: 0 1 2
      
     2.continue – Skips the current iteration and moves to the next.
     
       Example:
       for i in range(5):
           if i == 3:
               continue
           print(i)
       Output: 0 1 2 4
