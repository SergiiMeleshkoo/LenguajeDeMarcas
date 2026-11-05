
# UD21 - Ejercicio 5: Especificidad CSS

## Parte A — Detective de colisiones

### Predicciones antes de abrir el navegador

Antes de comprobar el resultado, estas son mis predicciones:

| Elemento | Color previsto | Motivo |
|---|---|---|
| Hola CSS | Marrón | Selector #titulo tiene más especificidad que h1 y .grande. |
| Texto 1 | Morado | El selector p.aviso combina una etiqueta y una clase, por lo que supera a p y .aviso. |
| Texto 2 | Negro | El selector #importante tiene más especificidad que los selectores de etiqueta y clase. |
| Texto 3 | Naranja | El selector div p es más específico que p, porque selecciona un párrafo dentro de un div. |

Cuanto más específico (más texto, vaya jaja), más importancia y si es de igual especificidad se considera la última.

### Comprobación después de abrir el navegador

Las predicciones han sido correctas!! El navegador muestra los siguientes colores:

| Elemento | Color real | Selector ganador |
|---|---|---|
| Hola CSS | Marrón | #titulo |
| Texto 1 | Morado | p.aviso |
| Texto 2 | Negro | #importante |
| Texto 3 | Naranja | div p |
