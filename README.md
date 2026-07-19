# Caso-estudio-Sistema-facturacion-v2
# Sistema de Facturación con Vectores

## Descripción

Este proyecto consiste en el desarrollo de un sistema de facturación web realizado como parte de la asignatura **Técnica de Programación** de la Universidad Estatal de Milagro (UNEMI).

El objetivo principal fue implementar la lógica de un sistema de facturación utilizando **JavaScript puro** y **vectores (arreglos)** para almacenar la información de los productos, sin emplear objetos, JSON o librerías externas.

El sistema permite agregar productos, calcular automáticamente los valores de la factura y actualizar la información en tiempo real.

## Objetivos

- Aplicar el uso de vectores para almacenar información.
- Implementar programación modular mediante funciones.
- Manipular dinámicamente el DOM con JavaScript.
- Validar la entrada de datos del usuario.
- Calcular automáticamente los valores de la factura.


## Funcionalidades

- Agregar productos al detalle de la factura.
- Actualizar automáticamente el precio unitario al seleccionar un producto.
- Registrar la cantidad de productos.
- Mostrar el detalle en una tabla.
- Calcular automáticamente:
  - Subtotal
  - IVA (15%)
  - Descuento fijo
  - Total a pagar
- Eliminar productos de la factura.
- Actualizar los totales en tiempo real.


## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (ES6)



## Lógica implementada

El sistema utiliza **vectores separados** para almacenar la información de los productos registrados.

```javascript
descripciones[]
cantidades[]
precios[]
totales[]
```

Cada posición de los vectores corresponde al mismo producto, permitiendo agregar, eliminar y actualizar la información de forma sincronizada.


## Funcionamiento

1. Seleccionar un producto.
2. Ingresar la cantidad.
3. Presionar el botón **Agregar**.
4. El producto se registra en la tabla.
5. El sistema calcula automáticamente:
   - Subtotal
   - IVA
   - Descuento
   - Total
6. Si se elimina un producto, los valores se recalculan automáticamente.


## Validaciones implementadas

- No permite agregar un producto sin seleccionarlo.
- No permite ingresar cantidades menores a 1.
- Actualiza automáticamente el precio del producto seleccionado.
- Recalcula los totales después de cada operación.


## Resultados obtenidos

Durante las pruebas realizadas se comprobó que:

- Los productos se agregan correctamente.
- La información se muestra correctamente en la tabla.
- Los cálculos del subtotal, IVA, descuento y total son correctos.
- La eliminación de productos actualiza automáticamente la factura.
- El sistema cumple con los requerimientos establecidos en la guía práctica.



## Aprendizajes obtenidos

Con este proyecto se fortalecieron conocimientos sobre:

- Programación modular.
- Manejo de arreglos (vectores).
- Manipulación del DOM.
- Validación de datos.
- Desarrollo de aplicaciones web con JavaScript.

## Información adicional

Universidad Estatal de Milagro (UNEMI)

Carrera: Ingeniería en Software

Asignatura: Técnica de Programación
