# Puntos multiples corango 1 n -> n+1 easy mode
Como usar: importar libreria easymultpoints.lib
Usar la funcion dk de esta manera:
```
dk(poly 1, poly 2, poly con variable principal, ideal con variables sustituyentes)
```
Te devuelve una lista con todas las ecuaciones de puntos multiples agrupadas en ideales (f1, f2, puntos dobles, puntos triples...) tantos DK como variables le pases en variables sustituyentes.
Ver ejemplo.exe, se puede ejecutar poniendo en la consola:
```
Singular ejemplo.exe
```
Nota: si en algun momento los puntos multiples son suaves, la entrada de la lista se convierte en 1.