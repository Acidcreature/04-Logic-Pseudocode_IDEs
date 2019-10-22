1. Design an If-Then statement (or a flowchart with a single alternative decision structure) that assigns 20 to the variable y and assigns 40 to the variable z if the variable x is greater than 100.
```
if x > 100 then 
   y = 20 AND z = 40
```
2. Design an If-Then statement (or a flowchart with a single alternative decision structure) that assigns 0 to the variable b and assigns 1 to the variable c if the variable a is less than 10.
```
If a < 10 then
   b = 0 AND c = 1
```
3. Design an If-Then-Else statement (or a flowchart with a dual alternative decision structure) that assigns 0 to the variable b if the variable a is less than 10. Otherwise, it should assign 99 to the variable b.
```
if a < 10 then
   b = 0
else b = 99
```
4. The following pseudocode contains several nested If-Then-Else statements. Unfortunately, it was written without proper alignment and indentation. Rewrite the code and use the proper conventions of alignment and indentation.
```
If score < 60 Then
   Display "Your grade is F."
Else If score < 70 Then
   Display "Your grade is D."
Else If score < 80 Then
   Display "Your grade is C."
Else If score < 90 Then
   Display "Your grade is B."
Else
   Display "Your grade is A."
End If
```
5. Design nested decision structures that perform the following: If amount1 is greater than 10 and amount2 is less than 100, display the greater of amount1 and amount2.
```
If amount1 > 10 AND amount2 < 100 then
   if amount1 > amount2 AND amount1 != amount2
      display amount1
   else
      display amount2
end if
```
6. Rewrite the following If-Then-Else If statement as a Select Case statement.
```
Case based on selection
   Case selection == 1 
      Report "You selected A."
   Case selection == 2 
      Report "You selected 2."
   Case selection == 3
      Report "You selected 3."
   Case selection == 4 
      Report "You selected 4."
   Default
      Report "Not good with numbers, eh?"
End Case

```
7. Design an If-Then-Else statement (or a flowchart with a dual alternative decision structure) that displays “Speed is normal” if the speed variable is within the range of 24 to 56. If speed holds a value outside this range, display “Speed is abnormal.”

```
If speed >= 24 AND <= 56 then
   display "Speed is normal"
else
   display "Speed is abnormal"
end if
```

8. Design an If-Then-Else statement (or a flowchart with a dual alternative decision structure) that determines whether the points variable is outside the range of 9 to 51. If the variable holds a value outside this range it should display “Invalid points.” Otherwise, it should display “Valid points.”
```
if points >= 9 AND <= 51 then
   display "Valid points"
else
   display "Invalid points"
end if
```
9. Design a case structure that tests the month variable and does the following:

* If the month variable is set to 1, it displays “January has 31 days.”

* If the month variable is set to 2, it displays “February has 28 days.”

* If the month variable is set to 3, it displays “March has 31 days.”

* If the month variable is set to anything else, it displays “Invalid selection.”

```
input month
Case based on month
   Case month == 1 
      Report "January has 31 days."
   Case month == 2 
      Report "February has 28 days."
   Case month == 3
      Report "March has 31 days."
   Default
      Report "Invalid selection."
End Case
```

10. Write an If-Then statement that sets the variable hours to 10 when the flag variable minimum is set.
```
if minimum then
   set hours = 10
