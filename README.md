# python-task1
# python program to compute area of a circle
from math import pi
rad=float(input ("Input the radius of the circle: "))
print("The area of the circle with radius "+str(rad)+" is:"+str(pi * rad**2))


# pyhton program to display the extension of a given filename
f=input("Input Filename:")
fext=f.split(".")
print ("The extension of the file is:"+fext[-1])
