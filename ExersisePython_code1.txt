 #Faulty calculator _condition(45*3=555,56+9=77,56/6=4)
print("Which operator you can use : \n Addition(+), Substraction(-), Multipication(*), Dived(/)")
u = input()
print("Enter your first number")
a = int(input())
print("Enter your second number")
b = int(input())
if a==56 and b==9 and u=="+":
    print("77")
elif a==45 and b==3 and u=="*":
    print("555")
elif a==56 and b==6 and u=="/":
    print("4")
elif u=="+":
    num1=a+b
    print(num1)
elif u=="*":
    num2=a*b
    print(num2)
elif u=="/":
    num3=a/b
    print(num3)
elif u=="-":
    num4=a-b
    print(num4)
else:
    print("Error! please check your operator")
