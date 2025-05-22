# calculator-for-microit
print('enter the two operands with an operator')
val1=float(input())
operator=input()
val2=float(input())
if operator=='+':
  result=val1+val2
  print(result)
elif operator=='-':
  result=val1-val2
  print(result)
elif operator=='*':
  result=val1*val2
  print(result)
elif operator=='/':
  result=val1/val2
  print(result)
else:
   print('enter the valid operator or operands')
   
