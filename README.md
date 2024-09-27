# codsoft-task-2
calculator

print("1-Addition")
print("2-subtraction")
print("3-multiplication")
print("4-division")
choice=int(input("choose an operation:"))

if(choice in [1,2,3,4]):
    num1=int(input("enter first number:"))
    num2=int(input("enter second number:"))

    if(choice==1):
        result=num1+num2
    elif(choice==2):
        result=num1-num2
    elif(choice==3):
        result=num1*num2
    elif(choice==4):
        result=num1/num2

else:
    print("Invalid operator")
print("The Result of the operation is {}".format(result))            
    
