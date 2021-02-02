# tema-pentru-acasa
ecuatia de gradul 2
#Elaborat de Fuior Alexandr
import math
a = float(input('introduceti a:'))
b = float(input('introduceti b:'))
c = float(input('introduceti c:'))
delta = b ** 2 - 4 * a * c
print(delta)
if delta < 0:
    print('ecuatia nu are solutii reale')
elif delta == 0:
    x = -b / 2 * a
else:
    x1 = (-b - math.sqrt(delta)) / (2 * a)
    x2 = (-b + math.sqrt(delta)) / (2 * a)
    print(x1)
    print(x2)
