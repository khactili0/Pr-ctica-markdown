# Los Cactuar de Final Fantasy

## Un enemigo pequeño con un ataque legendario

Los **Cactuar** son criaturas con forma de cactus que aparecen en muchas entregas de la saga *Final Fantasy*, creada por Square (hoy Square Enix). Son famosos por ser rápidos, difíciles de atrapar y por su ataque `1000 agujas`, que causa siempre el mismo daño fijo sin importar las defensas del rival. Son un ejemplo de cómo un monstruo sencillo puede convertirse en un icono de la cultura de los videojuegos a nivel mundial.

![Cactuar de Final Fantasy (imagen local)](assets/mi-imagen.jpg)

*Figura 1. Imagen de un Cactuar guardada en la carpeta `assets` del repositorio.*

## Simulación de su ataque

Este pequeño programa en Python imita el ataque `1000 agujas`:

```python
import random

def mil_agujas(vida_enemigo):
    dano = 1000
    vida_enemigo -= dano
    return max(vida_enemigo, 0)

vida = random.randint(1000, 9999)
print(f"Vida inicial del enemigo: {vida}")
vida = mil_agujas(vida)
print(f"Vida tras el ataque del Cactuar: {vida}")
```

## Características

Lo que hace especial a un Cactuar (lista desordenada):

- Tiene forma de cactus con brazos y una cara sencilla.
- Se mueve muy rápido y suele huir del combate.
- Su ataque más conocido causa siempre el mismo daño fijo.
- Aparece como enemigo, jefe opcional o mascota según el juego.

Pasos habituales para derrotar a uno en un juego de la saga (lista ordenada):

1. Localizar la zona desértica donde aparece.
2. Atacar antes de que huya del combate.
3. Aprovechar sus puntos débiles con la magia adecuada.
4. Recoger las recompensas, que suelen ser objetos raros.

## Datos básicos

| Aspecto             | Descripción                        | Ejemplo                          |
|---------------------|------------------------------------|----------------------------------|
| Nombre en inglés    | Cactuar                            | Criatura recurrente de la saga   |
| Nombre en japonés   | Sabotender                         | Nombre original en japonés       |
| Ataque característico | 1000 agujas                      | Daño fijo de 1000 puntos         |

## Enlaces

- Más información en la [Wikipedia sobre Final Fantasy](https://es.wikipedia.org/wiki/Final_Fantasy).
- Consulta la [documentación ampliada](docs/detalles.md) de este proyecto.

## Mi instituto

![IES Clara del Rey, Madrid (Wikimedia Commons)](https://upload.wikimedia.org/wikipedia/commons/2/28/I.e.s._clara_del_rey_%28Prosperidad%2C_Madrid%29.jpg)

*Figura 2. Imagen de mi instituto obtenida de Wikimedia Commons.*
