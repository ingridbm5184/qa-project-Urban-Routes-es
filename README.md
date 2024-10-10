
# Proyecto Urban Routes

# Proyecto de Pruebas Automatizadas de Urban Routes

Este proyecto utiliza Pytest y Selenium para automatizar las pruebas de extremo a extremo de la aplicación Urban Routes.

## Descripción

El objetivo de este proyecto es crear un conjunto de pruebas automatizadas para validar el correcto funcionamiento de la aplicación Urban Routes. Éstas pruebas cubren los principales flujos de la aplicación, como configurar la ruta, seleccionar la tarifa Comfort, rellenar el número de teléfono, agregar una tarjeta de crédito, escribir un mensaje para el conductor, solicitar una manta y pañuelos, pedir helados, y verificar la aparición de los modales correspondientes.

## Tecnologías y Técnicas Utilizadas

- Python
- Pytest
- Selenium
- Page Object Model

## Estructura del Proyecto

El proyecto cuenta con los siguientes archivos:

- `main.py`: Contiene la implementación de las pruebas automatizadas.
- `data.py`: Almacena los datos de prueba utilizados en las pruebas.

## Lista de Comprobación

| Casos de prueba                                                     | Estado |
|---------------------------------------------------------------------| --- |
| 1. Configurar la dirección                                          | ✓ |
| 2. Seleccionar la tarifa Comfort                                    | ✓ |
| 3. Rellenar el número de teléfono                                   | ✓ |
| 4. Agregar una tarjeta de crédito                                   | ✓ |
| 5. Escribir un mensaje para el conductor                            | ✓ |
| 6. Pedir una manta y pañuelos                                       | ✓ |
| 7. Pedir 2 helados                                                  | ✓ |
| 8. Aparece el modal para buscar un taxi                             | ✓ |
| 9. Esperar a que  aparezca la información del conductor en el modal | ✓ |

## Instrucciones de Ejecución

1. Asegúrate de tener Python 3 y pip instalados en tu sistema.
2. Crea un entorno virtual y actívalo.
3. Instala Pytest con su comando en la terminal: ` pip install pytest `
4. Instala Selenium con su comando en la terminal: ` pip install selenium `
5. Ejecuta las pruebas en la terminal el comando: ` pytest `

Ingrid Bernal Mechea - Cohorte 13 QA