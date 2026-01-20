# python-project
python project description
def fibonacci(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibonacci(n-1) + fibonacci(n-2)

# Main program
n = int(input("Enter how many Fibonacci numbers to print: "))

for i in range(n):
    print(fibonacci(i))

