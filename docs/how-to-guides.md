# Guía de Uso: Cómo Usar el Módulo `Sum`

Esta guía te llevará a través de los pasos necesarios para usar el módulo `Sum` en tu proyecto. El objetivo principal de este módulo es sumar dos números flotantes.

## Requisitos Previos

- Tener Python instalado en tu máquina (recomendamos la versión 3.x).
- Conocer la sintaxis básica de Python.

## Instalación

Este módulo se puede instalar directamente desde un repositorio de GitHub. Para instalarlo, sigue estos pasos:

1. Clona el repositorio de GitHub:

    ```bash
    git clone git@github.com:JA-Mendoza-M/Sum.git
    ```

2. Navega al directorio del repositorio clonado:

    ```bash
    cd Sum
    ```

3. Si es necesario, puedes instalar las dependencias (aunque este módulo es simple y no debería tener dependencias adicionales):

    ```bash
    pip install -r requirements.txt
    ```

## Cómo Usar el Módulo `sum`

El módulo `sum` proporciona una función sencilla para sumar dos números flotantes. A continuación, se muestra cómo usarla:

1. **Importar la función:**

    Para utilizar la función `sum`, primero debes importarla en tu script Python:

    ```python
    from sum import sum
    ```

2. **Llamar a la función `sum`:**

    La función toma dos argumentos de tipo `float` y devuelve su suma. Aquí hay un ejemplo:

    ```python
    resultado = sum(3.0, 4.0)
    print(f'El resultado de la suma es: {resultado}')
    ```

    **Salida esperada:**
    ```
    El resultado de la suma es: 7.0
    ```

## Casos de Uso Comunes

### Ejemplo 1: Sumar dos números enteros

Aunque el módulo está diseñado para trabajar con flotantes, también puedes usarlo con enteros, ya que Python los convierte automáticamente a flotantes si es necesario.

```python
# Ejemplo con enteros
resultado = sum(10, 5)
print(f'La suma es: {resultado}')

