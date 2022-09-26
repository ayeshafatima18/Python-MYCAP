# Python-MYCAP
# 1) write a Python program which accepts the radius of a circle from the user and computes area.
r = float(input ("Input the radius of the circle : "))
area= (3.14*(r**2))
print ("The area of the circle with radius " + r+"is"+area)

#input : Input the radius of the circle: 1.1
#output : THe area of the circle with radius 1.1 is 3.801

# 2) write a Python program to accept a filename from the user and print the extension of that
filename = input("Input the Filename: ")
f_extns = filename.split(".")
print ("The extension of the file is : " + repr(f_extns[-1]))

#Input:Input the Filename: abc.py
#output: The extension of the file is : 'python'


