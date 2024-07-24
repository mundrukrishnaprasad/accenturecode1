PYTHON CODE
n=10 
k=5
userinp=int(input("enter the candies u want :"))
if userinp>0 and k<=userinp:
 userinp=n-userinp
else:
    print("invalid input")
print(userinp)
