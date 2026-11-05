# Ejercicio 4
## Parte A - selector id y error
El error que me salió fue el siguiente:
```
Error: Duplicate ID corp.

From line 14, column 5; to line 14, column 18

/h1>↩↩    <h2 id="corp">Secció
```
Además de un aviso de donde estuvo el primer id:
```
Warning: The first occurrence of ID corp was here.

From line 12, column 5; to line 12, column 18

 -->↩↩    <h1 id="corp">Mi pág
 ```
ID se usa para identificar a un único elemento. Para repetir el mismo identificador en varios elementos hay que usar "class". Por eso mismo se desaconseja usar id ya que no es reutilizable.