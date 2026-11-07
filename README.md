# Cotizador Yura Snacks

Herramienta web sencilla para calcular al instante el total de un pedido de Yura Snacks (barras energéticas con quinua y kiwicha) mientras se conversa con el cliente por WhatsApp.

## Qué hace

- Elige el producto, la cantidad y el canal de entrega (recojo o delivery en Lima).
- Calcula el total y muestra el resumen del pedido.
- Copia el resumen con un botón, listo para pegar en WhatsApp.

## Cómo usarla

Abre la página desde el celular, completa los tres campos, toca "Calcular" y luego "Copiar resumen".

## Cómo cambiar precios

Todos los precios y costos de entrega están en un solo lugar, al inicio del bloque de script de `index.html`, en las listas `PRODUCTOS` y `CANALES`. Cambia ahí los valores y se actualiza la lista desplegable y el cálculo.

## Tecnología

Una sola página HTML con CSS y JavaScript incluidos. No usa servidor, base de datos ni librerías externas.

## Limitaciones actuales

- Cotiza un solo producto por pedido.
- Los precios se editan directamente en el código.
