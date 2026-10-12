# Distance-Calculatorr
Added distance calculator with comments and README
import math
 
# Ask the user for the coordinates
x1 = float(input("Enter Point 1A: "))
y1 = float(input("Enter Point 2A: "))
x2 = float(input("Enter Point 1B: "))
y2 = float(input("Enter Point 2B: "))

# Compute the distance using sqrt() and pow()
distance = math.sqrt(math.pow(x2 - x1, 2) + math.pow(y2 - y1, 2))

# Display the result
print(f"The distance between the two points is: {distance:.2f}")
