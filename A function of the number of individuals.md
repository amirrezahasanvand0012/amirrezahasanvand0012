def count_odd_numbers(num1, num2, num3):
    odd_count = 0  # We store the number of odd numbers

    if num1 % 2 == 1:
        odd_count += 1
    if num2 % 2 == 1:
        odd_count += 1
    if num3 % 2 == 1:
        odd_count += 1

    return odd_count

# We receive inputs from the user
num1 = int(input("Prime number: "))
num2 = int(input("The second number: "))
num3 = int(input("The third number: "))

# We call the function and get the number of odd numbers
result = count_odd_numbers(num1, num2, num3)

# We print the result
print(f"Number of odd numbers: {result}")
