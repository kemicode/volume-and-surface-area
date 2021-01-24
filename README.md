# volume-and-surface-area
#Name: Oluwakemi LaBadie
#Student ID Number: 00002489343
#Write a program that propmts the user to enter the three dimensions,
#possibly with decimals, of a cardboard shipping box. The program should 
#then print the volume of the box accurate to 2 decimal places and the total
#surface are of the box to 3 decimal places.

#Pseudocode
#start Program
#prompt user for the 3 dimensions of cardboard shipping box.
#assign each side to variables; length, widht, depth
#calculate the volume of the box
#print answer to 2 decimal places
#calculate the total surface area of the box
#print answer to 3 decimal places
#end program


#Start Program

#prompt user for the 3 dimensions of cardboard shipping box.

length = float(input('Enter length'))
Width = float(input('Enter width'))
Depth = float(input('Enter depth'))

#calculate the volume of the box
volume = length * Width * Depth

#format answer to 2 decimal places
print('The volume of the box is:')
print(format(volume, ".2f"))


#calcuate the surface of the box to 3 decimal places
surface_area = Width * length *2 + Width * Depth *2 + length * Depth * 2

#format answer to 3 decimal places
print('The Surface Area of the box is,')
print(format(surface_area, ".3f"))


#End Program    
