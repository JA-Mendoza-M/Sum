# Tutoriales: Usando el Módulo `Sum` en Proyectos Reales

Bienvenido a la sección de tutoriales. Aquí encontrarás proyectos y guías prácticas que te enseñarán a utilizar el módulo `Sum` en diferentes contextos. Cada tutorial está diseñado para que puedas aprender mientras creas algo útil.

## Tutorial 1: Calculadora Básica de Sumas

En este tutorial, crearemos una sencilla calculadora de sumas usando el módulo `Sum`. La calculadora tomará dos números como entrada y devolverá su suma.

### Paso 1: Preparar el Entorno

Primero, asegúrate de tener el módulo `Sum` instalado. Si no lo has hecho ya, sigue los pasos de la [guía de instalación](how-to-guides.md).

### Paso 2: Crear el Script de la Calculadora

1. Abre un editor de texto o IDE y crea un nuevo archivo llamado `calculadora.py`.
2. Importa la función `sum` desde el módulo `Sum`.

    ```python
    from sum import sum
    ```

3. Solicita al usuario que ingrese dos números flotantes:

    ```python
    # Solicitar entrada al usuario
    a = float(input("Ingresa el primer número: "))
    b = float(input("Ingresa el segundo número: "))
    ```

4. Llama a la función `sum` para calcular la suma de los dos números:

    ```python
    resultado = sum(a, b)
    print(f"La suma de {a} y {b} es: {resultado}")
    ```

5. Guarda el archivo y ejecútalo.

### Paso 3: Probar la Calculadora

Ejecuta el script en tu terminal o IDE. Deberías ver una salida como esta:


