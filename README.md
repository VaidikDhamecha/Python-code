# Python-code
n=int(input("Enter the No:"))
print("right angle triangle")
for i in range(1,n+1):
    print("*"*i)

print("left angle triangle")

for i in range(1,n+1):
    print(" "*(n-i)+"*"*i)

print("reverse right angle triangle")

for i in range(n,0,-1):
    print("*"*i)

print("reverse left angle triangle")

for i in range(n,0,-1):
    print(" "*(n-i)+"*"*i)
    
print("number triangle")

for i in range(1,n+1):
    for j in range(1,i+1):
        print(j,end=" ")
    print()

print("* pyramid")

for i in range(n):
    for j in range(n-i-1):
        print(" ",end="")
    for j in range(i+1):
        print("*",end=" ")
    print()

