# AreaCalculatorTriangleCircle
Calculates the area of a Circle or a Triangle using Python 
""" This program computes the area of two shapes, a Circle or Triangle"""

print "Calculator begins now..."

option = raw_input("Enter C for Circle or T for Triangle: ") 

if option == 'C':
  radius = float(raw_input("Enter radius: "))
  area = 3.14159 * radius**2
  print "Area of your Circle: %f " % (area)
elif option == 'T':
  base = float(raw_input("Enter base: "))
  height = float(raw_input("Enter height: "))
  area = 0.5 * base * height
  print "Area of your Triangle: %f " % (area)
else:
    print "Error! Invalid shape, please try again."
    print "Exiting program..."
