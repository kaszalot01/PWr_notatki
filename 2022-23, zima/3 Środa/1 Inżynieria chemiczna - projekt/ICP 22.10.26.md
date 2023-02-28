Zwrócić uwagę na zad 2 z listy 3 - może być na kolokwium

Zad 1
```python
import numpy as np  
D=50*10**-3  
m=2.16  
ro=1000  
a=30/360*2*np.pi  
d=30*10**-3  
p1=245000  
g=10  
L=8  
  
S1=(D**2)*np.pi/4  
u1=m/(ro*S1)  
  
S2=(d**2)*np.pi/4  
u2=m/(ro*S2)  
  
print(p1+u1**2*ro/2-u2**2*ro/2-ro*g*np.sin(a)*L)
```

Zad 3

```python
import numpy as np  
  
D1=75*10**-3  
d0=30*10**-3  
mi=0.732  
dp=9632  
ro1=1.2  
ro2=1000  
mi=0.732  
  
S0=((d0**2)*np.pi)/4  
S1=((D1**2)*np.pi)/4  
S2=S0*mi  
  
# alpha, mdot ,u  
m=S0/S1  
print(m)  
alpha=mi/((1-m**2*mi**2)**0.5)  
  
u01=alpha*(2*dp/ro1)**0.5  
u11=u01*m  
mdot11=u11*ro1*S1  
print(alpha, u11, mdot11)
```