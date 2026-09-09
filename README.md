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

#Reflection:
#Using a library is more practical because it saves time and makes calculations easier.
#In this program math.sqrt() and math.pow() were easier to use because they helped me calculate the distance.
#Without math.sqrt() and math.pow() it would take me longer to calculate the distances and makes it difficult for me, also making the code longer.
