# Lectura del número n

**Enunciat:**

llegir un número n, seguit d'una seqüència de n números reals. Si n no és major que 0, el programa acaba:

## Ejercicio Python

```python
#Lo primer que fem es importar de la llibreria Yogi el "Read"
from yogi import read

# Després col·loquem una variable que sigui "N" i posem "read(int)" que el que fa és, preguntar-te un nombre sencer
n = read(int)       

# Aquí fem un bucle que quan "NO" és més gran que 0 el bucle es farà les vegades de la quantitat que has ficat abans a "N"
for _ in range(n):         

#      Aqui llegira un número real, que es podrà escriure la quantitat de vegades que t'ho bucle
    dada = read(float)
