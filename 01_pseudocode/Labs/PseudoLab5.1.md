# Exercise Workbench
* Design a While loop that lets the user enter a number. The number should be multiplied by 10, and the result stored in a variable named product. The loop should iterate as long as product contains a value less than 100.

```
// Variable to hold user number
Declare Integer nums

// Variable to number after multiplication
Declare Integer product

// Constant for Max Number
Constant Integer MAX_NUM = 100

While product < MAX_NUM
   Display "Please enter a number between 1-10"
   input nums
   product += nums * 10
End While 
```

* Design a Do-While loop that asks the user to enter two numbers. The numbers should be added and the sum displayed. The loop should ask the user whether he or she wishes to perform the operation again. If so, the loop should repeat; otherwise it should terminate.
```
// Go again
Declare String doAnother = "Y"

//Declarations
Declare Integer num1
Declare Integer num2

While doAnother == "Y"
   Display "Please enter a number"
   input num1
   Display "Please enter another number"
   input num2
   Display "The total is $", (num1 + num2)
   Display "Would you like to do it again, Press Y for yes, or N for no"
   input doAnother
End while
```

* Design a For loop that displays the following set of numbers:

0, 10, 20, 30, 40, 50, . . . , 1000
```
//Declarations
Declare Integer num = 0

//Main
Main()
   forl=Loop()
return

forLoop()
   for n in range(101)
      Display num
         num += 10
   end for
```

* Design a loop that asks the user to enter a number. The loop should iterate 10 times and keep a running total of the numbers entered.

```
//Declarations
Declare Integer nums =[0,0,0,0,0,0,0,0,0,0]
Declare Integer number
Declare Integer numtotal

//main
for i in len(nums)
   Display "Enter a number"
   input number
   numstotal += number
end for
Display " your total is $", numstotal

```

* Design a For loop that calculates the total of the following series of numbers:
![image](https://user-images.githubusercontent.com/47218880/67423054-31740800-f599-11e9-9565-031c1f729e1c.png)
```
//Declare Integer denominator, numerator
//Declare Real value, total
Set denominator = 30
Set total = 0
For numerator = 1 To 30
  Set value = numerator / denominator
  Set total = total + value
  Set denominator = denominator - 1
End For
Display total
```
* Design a nested loop that displays 10 rows of # characters. There should be 15 # characters in each row.
```
for i in range(10)
   for e in len(15)
      Display "#"
   end for
end for

```

* Convert the While loop in the following code to a Do-While loop:
```
Declare Integer x = 1
While x > 0
   Display "Enter a number."
   Input x
End While
```
* Convert the Do-While loop in the following code to a While loop:
```
Declare String sure
Do
  Display "Are you sure you want to quit?"
  Input sure
While sure != "Y" AND sure != "y"
```
* Convert the following While loop to a For loop:
```
Declare Integer count = 0
While count < 50
   Display "The count is ", count
   Set count = count + 1
End While
```
* Convert the following For loop to a While loop:
```
Declare Integer count
For count = 1 To 50
   Display count
End For
```
