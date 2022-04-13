# tabela-de-descontos
Primeiro codigo de python que eu faço para usar no dia-a-dia, para facilitar fazer os cálculos das porcentagens de desconto dos livros  que eu anuncio no mercado livre. 

while True:
  n=float(input('preço: R$'))
  if n<=100:
    print('Tabela')
  elif n<=200:
    print(f'Classico: {n*0.95:.2f}')
    print(f'Premium: {n}')
  elif n<=300:
    print(f'Classico: {n*0.85:.2f}')
    print(f'Premium: {n*0.9:.2f}')
  elif n<=500:
    print(f'Classico: {n*0.8:.2f}')
    print(f'Premium: {n*0.85:.2f}')
  elif n>=501:
    print(f'Classico: {n*0.75:.2f}')
    print(f'Classico: {n*0.8:.2f}')
  if n<0:
    break
print('ENCERRADO')
