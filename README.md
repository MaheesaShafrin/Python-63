# Python-63
Python program to find the geometric mean of n numbers
c = 0
p = 1.0

count = int(input("Enter the number of values: "))

while c < count:
    x = float(input("Enter a real number: "))
    p = p * x
    c = c + 1

gm = pow(p, 1.0 / count)
print("The geometric mean is:", gm)

Output:
Enter the number of values: 3
Enter a real number: 2
Enter a real number: 8
Enter a real number: 4
The geometric mean is: 3.9999999999999996
