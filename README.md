
# Drink, Speak or Play!
Un _drinking game_ amigable para relaciones.

## ¿Como agregar tarjetas?
1. Crea el fork
2. Crea una nueva rama llamada: nueva carta

**Editando archivo**  
Agrega la entrada directamente en el archivo `db.json` siguiendo esta estructura:

```json
	"category": 0,
	"people": 1,
	"outloud" : true,
	"body" : "Toma un trago!",
	"shots" : 1
```

Para _category_, las categorias son Drink, Speak y Play, representados por los numeros del 0 al 2.

Para _people_, puedes utilizar "?" si es para todos los jugadores.

Para _shots_, puedes utilizar "?" si aplica.

Para _outloud_, puedes utilizar false si la carta no se debe leer en voz alta.

3. Crea el pull request
4. Listo!
