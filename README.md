# Mini-porjeto
Multa por kilometro - multa acima de 80 km
import random

for i in range(1):
    x=random.choice([70,71,72,73,74,75,76,77,78,79,80,81,82,83,84,85,86,87,88,89,90])
    print(x)

    if x > 80:
        nU=-(80-x)
        multa = nU*7.00
        print('Você passou {}km/h do limite da velocidade'.format(nU))
        print('Sua multa é de {}'.format(multa))
    else:
        nU = x
        print('Você esta indo a {}km/h  continue assim'.format(nU))
        
