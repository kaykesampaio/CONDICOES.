# Condições
n1 = float(input('Digite a primeira nota: ')) n2 = float(input('Digite a segunda nota: ')) n3 = float(input('Digite a terçeira nota: '))

m = (n1 + n2 + n3)/3

print('A sua média foi {:.1f}'.format(m))

if m >=6.0: print('Sua média foi boa! PARABÉNS!') else: print('Sua média foi ruim! ESTUDE MAIS!')

# Condição simplificada

n1 = float(input('Digite sua primeira nota: ')) n2 = float(input('Digite sua segunda nota: ')) n3 = float(input('Digite sua terçeira nota: '))

m = (n1 + n2 + n3)/3

print('sua média foi {}'.format(m)) print('!PARABÉNS!' if m >=6 else '!ESTUDE MAIS!')
