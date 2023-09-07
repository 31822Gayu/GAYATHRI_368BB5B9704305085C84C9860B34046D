# GAYATHRI_368BB5B9704305085C84C9860B34046Ddef factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
num = 5
result = factorial(num)
print(f"The factorial of {num} is {result}")
