# Código ejecutado en Linux Mint
El siguiente script fue utilizado en un trabajo práctico de la materia Matemática para convertir números del 0 al 15 a su representación binaria. Incluye una pausa de un segundo entre cada número para visualizar el proceso paso a paso.

## Python en Linux Mint
- Se ejecutó `python3 --version` para verificar que Python está instalado por defecto.
- Se creó un archivo llamado `ayso.py` desde la terminal con el editor `nano`.

### Capturas de pantalla

## Script ejecutado
```python
import time # Importamos la biblioteca time para agregar la funcion time.sleep().

for numero in range(0, 16):
    time.sleep(1)
    binario = ""
    n = numero
    if numero == 0:
        print("0 en binario es 0")
    else:
        while n > 0:
            residuo = n % 2
            binario = str(residuo) + binario
            n = n // 2
        print(f"{numero} en binario es {binario}")
```

### Capturas de la ejecución del script
