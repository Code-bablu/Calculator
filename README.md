# Calculator
#Use only addition substraction multiplication and division in this program. Everytime you have to run the code for any kind of execution ...I didn't use loops in this program 


def addition(x,y):
    print(x+y)

    
print("1 is for addition ")
prindef multiply(x,y):
    print(x*y)
def substraction(x,y):
    print(x-y)
def division(x,y):
    print(x/y)
t("2 is for multiply ")
print("3 is for substraction")
print("4 is for division ")

get_input=int(input("="))
match get_input:
    case 1:
       a=int(input("a="))
       b=int(input("b="))
       addition(a,b)
       
    case 2:
       a=int(input("a="))
       b=int(input("b="))
       multiply(a,b)
    
    case 3:
       a=int(input("a="))
       b=int(input("b="))
       substraction(a,b)
    case 4:
       a=int(input("a="))
       b=int(input("b="))
       division(a,b)
    case 5:
        print("have a great day ! ")
       
        
