# Fibonacci-Sequence
 'Fibonacci Sequence' is a project study schedule where the program calculation shows how many terms you want from a Fibonacci sequence

print(23*'=')
print('Fibonacci Sequence')
print(23*'=')

term = int(input('How many terms do you want to show? '))
cont = 0

nA = 1
nB = 0

while cont != term:
    if cont == 0:
        print(nA, end=(''))
        num = nA + nB
        nB = nA
        nA = num
        cont += 1
    else:
        print(' ->', nA, end=(''))

        num = nA + nB
        nB = nA
        nA = num
        cont += 1
print('\nEnd')
