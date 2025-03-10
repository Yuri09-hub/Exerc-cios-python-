# jokenp-
um programa que faz o computador jogar jokenpô
import random

print('Pedra, Papel, Tesoura')
usuario = str(input('Faça a sua escolha: '))

lista = ['Pedra', 'Papel', 'Tesoura']
computador = random.choice(lista)

if computador == usuario:
    print("\033[33m EMPATE  (computador: {}, Usuario: {}  )\033[m ".format(computador,usuario))

elif computador == 'Pedra' and usuario == 'Papel':
    print('\033[32m VOCÊ GANHOU (computador: {}, Usuario: {} ) \033[m  '.format(computador,usuario))


elif computador == 'Papel' and usuario == 'Pedra':
    print('\033[31m VOCÊ PERDEU (computador: {}, Usuario: {} ) \033[m  '.format(computador,usuario))

elif computador == 'Tesoura' and usuario == 'Papel':
    print('\033[31m VOCÊ PERDEU (computador: {}, Usuario: {} ) \033[m  '.format(computador,usuario))

elif computador == 'Papel' and usuario == 'Tesoura':
    print('\033[32m VOCÊ GANHOU (computador: {}, Usuario: {} ) \033[m  '.format(computador, usuario))

elif computador == 'Pedra' and usuario == 'Tesoura':
    print('\033[31m VOCÊ PERDEU (computador: {}, Usuario: {} ) \033[m  '.format(computador, usuario))

elif computador == 'Tesoura' and usuario == 'Pedra':
    print('\033[32m VOCÊ GANHOU (computador: {}, Usuario: {} ) \033[m  '.format(computador,usuario))
