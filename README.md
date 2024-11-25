# Shandi Youmg
# Nov 23, 2024
# P2LAB2
# Dictionary cars

# MPGs of vehicles.


#create a dictionary of vehicles

dict_mpg = {"Camaro":18.21,
       "Prius":52.36,
       "Model S":110,
       "Silverado":26}
# input vehicle of choice
vehicle = input('Enter a vehicle to see its mpg:')
#add input and directory to statement to import 
print(f'The {vehicle} gets {dict_mpg[vehicle]} mpg')
#input miles to be driven
miles = float(input(f'How many miles will you drive the {vehicle}? '))
# calculate gallons needed for the drive. 
gallons_needed = miles / dict_mpg[vehicle]
# display resutls of calculations. 
print(f'You will need {gallons_needed:.2} gallons of gas to drive {miles} miles.')
