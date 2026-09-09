import math
# Input the coordinates of the two points
x_cooridnate1 = float(input("Enter x_coordinate1: "))
y_coordinate1 = float (input("Enter y_coordinate1: "))
x_coordinate2 = float (input("Enter x_coordinate2: "))
y_coordinate2 = float(input("Enter y_coordinate2: "))
# Calculate the distance between the two points
distance = math.sqrt(math.pow(x_coordinate2- x_cooridnate1, 2) + math.pow(y_coordinate2 -y_coordinate1, 2))
# Display the result
print("The distance between the two points is: ", round(distance, 2))
