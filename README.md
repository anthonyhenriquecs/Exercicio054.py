# Exercicio054.py

from datetime import date
atual = date.today().year
p = 0
pn = 0
for c in range(0,7):
    nasc = int(input('Digite o ano em que nasceu:'))
    idade = atual - nasc
    if idade >= 18:
        p += 1
    else:
        pn += 1


print('Pessoas maiores de idade:',p)
print('pessoas menores de idade:',pn)
