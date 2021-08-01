
#Armstrong Number in Python

n = int(input("Enter the number: "))
print()

#store the initial value of n in temp
temp = n
sum = 0

while (n>0):
    sum = sum +(n%10)*(n%10)*(n%10)
    n = n//10
    
if temp == sum:
    print("I am Armstrong Number")
else:
    print("I'm not Armstrong number")
    
    
# Input = 153
# Output = I am Armstrong Number
