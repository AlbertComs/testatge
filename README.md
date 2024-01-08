# Lectura del número n

**Enunciat:**

llegir un número n, seguit d'una seqüència de n números reals. Si n no és major que 0, el programa acaba:

## Ejercicio Python

```python
#Primer importar llibreria
from yogi import read

# llegir un número enter --> n 
n = read(int)       

# si n és mes gran que 0 fer n vegades:
for _ in range(n):         

#      llegir un número real --> dada
    dada = read(float)
