# Carrito inteligente con tope de presupuesto

Demo conceptual de un módulo para supermercados en línea: el cliente escribe su lista de compras y un monto máximo, y el sistema arma el carrito más conveniente sin pasarse del presupuesto.

**Probar la demo:** https://acivitico.github.io/carrito-inteligente/

## La idea

La misma herramienta puede perseguir objetivos distintos según el momento económico y el modelo de negocio:

- **Ahorro:** rendir cada peso, con el menor precio por kilo o por litro y las marcas propias del supermercado.
- **Equilibrio:** combinar precio y marca.
- **Exploración:** cuando hay margen, marcas líderes y premium.

Si el presupuesto no alcanza, el sistema explica qué quedó afuera y por qué. El comprador siempre puede cambiar cualquier producto por otro.

## Cómo está pensado

La IA entiende, el código calcula y el negocio decide qué optimizar.

- **Interpretar la lista:** en producción lo haría un modelo de lenguaje pequeño. En esta demo se usan reglas simples.
- **Armar el carrito:** un algoritmo de optimización clásico (una variante del problema de la mochila) elige un producto por renglón sin exceder el presupuesto. Se ejecuta en el navegador, en milisegundos.
- **Decidir el objetivo:** es una decisión de negocio, no técnica.

## Aclaraciones

Las marcas son reales, pero los precios, las ofertas y el segmento asignado a cada una son inventados para la demo y no corresponden a ningún comercio. Las marcas propias del supermercado ficticio se llaman Canasta Clara y Primer Precio.

## Autor

Alfredo E. Civitico Biraben, en [LinkedIn](https://www.linkedin.com/in/acivitico/).
