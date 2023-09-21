input_str = input("Enter a list of numbers separated by spaces: ")
list1 = [int(x) for x in input_str.split()]
positive_numbers = []
for num in list1:
    if num > 0:
        positive_numbers.append(num)
if positive_numbers:
    print(", ".join(map(str, positive_numbers)))
else:
    print("No positive numbers found in the list.")
