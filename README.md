#swapping the numbers by using temporary variable
a=int(input("enter the number"))
b=int(input("enter the number"))
temp=a
a=b
b=temp
print("after swapping the numbers:",a,b)

#swapping the numbers by using temporary variable
a=int(input("enter the number"))
b=int(input("enter the number"))
print("before swapping the numbers:",a,b)
temp=a
a=b
b=temp
print("after swapping the numbers:",a,b)

#swapping of two numbers by using arithmetic operations
a=int(input("enter the number:"))
b=int(input("enter the number:"))
print("before swapping the numbers:",a,b)
a=a+b
b=a-b
a=a-b
print("after swapping the numbers:",a,b)

#swapping of two numbers by using arithmetic operators(*,/)
a=int(input("enter the number:"))
b=int(input("enter the number:"))
print("before swapping the numbers:",a,b)
a=a*b
b=a/b
a=a/b
print("after swapping the numbers:",a,b)
