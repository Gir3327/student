# student


# Cube
l = float(input('Please Enter the Length of any Side of a Cube: '))
 
sa = 6 * (l * l)
Volume = l * l * l
LSA = 4 * (l * l)
 
print("\n Surface Area of Cube = %.2f" %sa)
print(" Volume of cube = %.2f" %Volume)
print(" Lateral Surface Area of Cube = %.2f" %LSA)


# Sphere
PI = 3.14
radius = float(input('Please Enter the Radius of a Sphere: '))
sa =  4 * PI * radius * radius
Volume = (4 / 3) * PI * radius * radius * radius
 
print("\n The Surface area of a Sphere = %.2f" %sa)
print("\n The Volume of a Sphere = %.2f" %Volume)


Pyramid
PI = 3.14
radius = float(input('Please Enter the Radius of a Cylinder: '))
height = float(input('Please Enter the Height of a Cylinder: '))
 
sa = 2 * PI * radius * (radius + height)
Volume = PI * radius * radius * height
L = 2 * PI * radius * height
T = PI * radius * radius
 
print("\n The Surface area of a Cylinder = %.2f" %sa)
print(" The Volume of a Cylinder = %.2f" %Volume)
print(" Lateral Surface Area of a Cylinder = %.2f" %L);
print(" Top OR Bottom Surface Area of a Cylinder = %.2f" %T)
