# Platzom

Platzom es un idioma inventado para el curso de fundamentos e javascript de platzi el mejor lugar de educacion online.

## Descripcion del idioma

- Si la palabra original es un palíndromo,
ninguna regla anterior cuenta y se devuelve
la misma palabra intercalando mayúsculas y minúsculas.

- Si la palabra termina en "ar", se le quitan esos dos caracteres.

- Si la palabra inicia con Z, se le añade "pe" al final.

- Si la palabra traducida tiene 10 o más letras,
se debe partir a la mitad y unir con un guión del medio

## Instalacion

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Creditos

-[Alan Munoz] (https://www.github.com/alammm)

## Licencia

[MIT] (https://opensource.org/licenses/MIT)

