#Shandi Young
#11/24/2024
#P2HW1
#Update to travel P1HW2


print('This program calculates and displays travel expenses.')
budget = float(input('Enter Budget:'))
print()
location = (input('Enter your travel destination:'))
gas = float(input('How much do you think you will spend on gas?:'))
hotel = float(input('Approximately, how much will you need for accomodation/hotel:'))
food =float(input('Last, how much do you need for food?:'))
# calc expenses
expenses = gas + hotel + food
#calc balance
remainAmount = budget - expenses
print('\n---------Travel Expenses---------\n')
print(f'Location:           {location}')
print(f'Gas:                ${gas:,.2f}')
print(f'Hotel:              ${hotel:,.2f}')
print(f'Food:               ${food:,.2f}')
print()
print(f'Remaining Balance:  ${remainAmount:,.2f}')
