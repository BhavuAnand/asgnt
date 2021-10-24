############### Input a filename and print the extension of that ###################

filename = input("Input the Filename: ")
f_extns = filename.split(".")
print ("The extension of the file is : " + repr(f_extns[-1]))



############## area of circle ###################

r=float(input("Enter the Radius of circle: "))
area = 3.14*r*r
print("Area of Circle: ",area)
