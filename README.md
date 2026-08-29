import math

# Input the coordinates of the two points
x1 = float(input("Enter x1: "))
y1 = float (input("Enter y1: "))
x2 = float (input("Enter x2: "))
y2 = float(input("Enter y2: "))

# Calculate the distance between the two points
distance = math.sqrt(math.pow(x2- x1, 2) + math.pow(y2 -y1, 2))

# Display the result
print("The distance between the two points is: ", round(distance, 2))

