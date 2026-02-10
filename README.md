# Program-to-Find-the-Average-of-Given-Numbers
count = int(input("Enter the count of numbers: "))

total = 0

for i in range(count):
    x = int(input("Enter an integer: "))
    total = total + x

avg = total / count

print("The average is:", avg)
output
Enter the count of numbers: 3
Enter an integer: 10
Enter an integer: 20
Enter an integer: 30
The average is: 20.0
