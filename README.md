while True:
    print('Who are you?')
    name = raw_input()
    if name != 'R2D2':
        continue
    print('Hello, Sr. What is the password? (It is a food.)')
    password = raw_input()
    if password == 'Hamburguer':
        break
print('ACCES GRANTED.')


name = ''
while not name:
    print('Enter your name:')
    name = raw_input()
print('How many guests will you have?')
numOfGuests = int(raw_input())
if numOfGuests:
    print('Be sure to have enough room for all your guests.')
print('Done')




