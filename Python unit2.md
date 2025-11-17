# Python-2-experiment-default-arguments-
def operations(a, b):
    add = a + b
    sub = a - b
    mul = a * b
    div = a / b
    quo = a // b
    rem = a % b
return add, sub, mul, div , quo, rem
u, v, w, x, y, z = operations(17, 5)
print("Addition:", u)
print("Addition:", v)
print("Subtraction:", w)
print("Multiplication: ", x)
print("Division: ", y)
print("Remainder: ", z)


#2.2 default arguments of function 
#8. Function using default arguments
def greet(name="Guest"):
print("Hello,", name)
greet("Satya")
greet()


#2.3 Check if substring is present in a string
string = input("Enter the main string: ")
substring = input("Enter the substring: ")
if substring in string:
print("Substring is present.")
else:
print("Substring is not present.")

#9. Function using default arguments
def string_length(s):
count = 0
for _ in s:
count += 1
return count
text = input("Enter a string: ")
print("Length of string:", string_length(text))


#11. List operations: addition, insertion, slicing
lst = [10, 20, 30, 40]
# Addition (append)
lst.append(50)
print("After addition:", lst)
# Insertion
lst.insert(2, 25)
print("After insertion at index 2:", lst)
# Slicing
print("Slicing from index 1 to 4:", lst[1:5])

#12. Perform any 5 built-in functions on a list
lst = [4, 2, 9, 1, 5]
print("Original list:", lst)
print("Length:", len(lst))
print("Maximum:", max(lst))
print("Minimum:", min(lst))
print("Sorted list:", sorted(lst))
print("Sum:", sum(lst))
Original list: [4, 2, 9, 1, 5]
Length: 5
Maximum: 9
Minimum: 1
Sorted list: [1, 2, 4, 5, 9]

















