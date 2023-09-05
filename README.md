# aprendiendo-react-desaprendiendo-jquery

> [Grabación completada](https://www.webreactiva.com/cursos/masterclass/aprendiendo-react-desaprendiendo-jquery)

## Guión del directo

- Instalación de React con Vite
- Presentación de la solución de Sergi
- Presentación de la solución de José Manuel
- Refactorizaciones de Sergi
- Extras de José Manuel
- Postlive!

## Requisitos de la Calculadora de muñecos cabezones

Para que veáis a lo que se enfrentan los Reactionarios...

Requisito básico
- La calculadora va a tener siempre un precio final en euros con 2 decimales al final de todos los campos

> [Ya la tenemos resuelta en jQuery](https://codepen.io/delineas/pen/eYQXWYR?editors=0010)



> [Solución de Sergi](https://github.com/sergioedo/jquery2react-deck) / [Diapositivas en Reactionarios.dev](https://reactionarios.dev/)
> [Solución de José Manuel](https://github.com/jmgomezdev/desaprendiendo-jquery)

1️⃣ Selector de producto
Elegir entre tres personajes, cada uno tiene un precio
- 13,5€ Jon Snow
- 16,5€ Danerys Targaryen
- 19€ Tyrion Lannister

2️⃣ Cambio según elección
Si eliges el segundo personaje aparece un check para definir si lo quieres con o sin dragon en el hombro: 44,5€ mas con dragón 

3️⃣ Número de muñecos
Input de tipo entero: multiplica el precio final por la cantidad

4️⃣ Aplicación de impuestos
Para no tener que capturar la IP del usuario lo que hacemos es cargar un país de forma aleatoria  desde https://randomuser.me/api/
- Si el país empieza por vocal, aplican 10% de impuestos
- Si empieza por consonante, 20 % (injusticias de Hacienda, ya se sabe)
- Mostramos el % de impuestos justo antes del precio final
