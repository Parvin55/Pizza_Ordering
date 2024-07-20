# Pizza_Ordering


print("PIZZA ORDERING PROGRAM.............")
size=input("Enter the size for pizza(S/M/L): ")
p=0
if(size=="S" or size=="s"):
    p=100
    print(f"Price is {p}")
    pp=input("Wan't pepporoni(Y/N): ")
    if(pp=="Y" or pp=="y"):
        p+=20

elif(size=="M" or size=="m"):
    p = 200
    print(f"Price is {p}")
    pp = input("Wan't pepporoni(Y/N): ")
    if (pp == "Y" or pp == "y"):
        p += 50

elif(size=="L" or size=="l"):
    p = 300
    print(f"Price is {p}")
    pp = input("Wan't pepporoni(Y/N): ")
    if (pp == "Y" or pp == "y"):
        p += 50

else:
    print("Enter correct size!!")


if(size=="S" or size=="s" or size=="M" or size=="m" or size=="L" or size=="l"):
    c=input("Extra cheese(Y/N)?: ")
    if(c=="Y" or c=="y"):
        p+=20
    print("**************************")
    print("TOTAL BILL: ", p)


![Screenshot (125)](https://github.com/user-attachments/assets/c0470455-81f5-4c0e-b14d-7ef4dd2e0fa0)
