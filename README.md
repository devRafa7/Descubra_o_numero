# Descubra o número
import random

aleatorio = random.randint(0, 7)

chute = int(input('Chute um número de 0 a 7, vamos ver se você é bom com chutes hahaha: '))

if chute > aleatorio:
  print(f'Quase cara! O número sorteado foi um pouquinho menor do que o seu chute... O número sorteado foi {aleatorio}.')
  
if chute < aleatorio:
  print(f'Parece que você chutou baixo hein meu camarada haha, tente novamente. O número sorteado foi {aleatorio}')
  
if chute == aleatorio:
  print(f'Na mosca cara!!! O número sorteado realmente foi {aleatorio}.')
