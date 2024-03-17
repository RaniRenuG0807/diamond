# diamond
diamond or rhombus pattern in python. interview question for placement. 

# Diamond
n=int(input("Enter Number "))
for i in range(1,2*n):
    for j in range(1,2*n):
        if (i<=n and (j>=n-i+1 and j<=n+i-1)):
            print("*",end=" ")
        elif (i>n and (j>=i-n+1 and j<=2*n-(i-n+1))):
            print("*",end=" ")
        else:
            print(" ",end=" ")
    print()




