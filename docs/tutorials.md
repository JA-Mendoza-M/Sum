# Tutoriales: Usando el Módulo `Sum` 

## Calculadora básica de sumas

La calculadora tomará dos números como entrada y devolverá su suma.

### Paso 1: Preparar el Entorno

Instalar sum siguiendo los pasos de la [guía de instalación](how-to-guides.md).

### Paso 2: Crear el Script de la Calculadora

- Abre un editor de texto y crea un nuevo archivo llamado `calculadora.py`.
- Importar la función `sum` desde el módulo `Sum`.

   `from sum import sum`


- Solicitar al usuario que ingrese dos números:

   `a = float(input("Ingresa el primer número: "))`

   `b = float(input("Ingresa el segundo número: "))`


- Llamar la función `sum`:

   `resultado = sum(a, b)`

   `print(f"La suma de {a} y {b} es: {resultado}")`
