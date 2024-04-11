import math
a=int(input("Введите a:"))
b=int(input("Введите b:"))
if a<b:
    c=a**2
    if c == 100:
        c=c+b
    else:
        c=c+a
else:
    c=math.sqrt(a)-math.sqrt(b)
d=2*c
print(d)
