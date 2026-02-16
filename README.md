# sum-of-given-numbers.py

numbers = []
num = int(input('How many numbers: '))
for n in range(num):
    x = int(input('Enter number '))
    numbers.append(x)
print("Sum of numbers in the given list is :", sum(numbers))


output:
How many numbers: 3
Enter number 56
Enter number 45
Enter number 76
Sum of numbers in the given list is : 177


