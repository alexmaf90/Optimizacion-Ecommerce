# Descripción del Proyecto

Este proyecto consiste en actuar como consultores para un ecommerce del sector cosméticos, con el objetivo de analizar datos transaccionales para identificar acciones de optimización de la tasa de conversión (CRO). Buscamos incrementar visitas, conversiones, ticket medio, y, en última instancia, aumentar la facturación global.

## Objetivos y KPI's

- **Objetivo Principal:** Crear una segmentación RFM y un sistema de recomendación avanzado para impulsar visitas, conversiones, y ticket medio.
- **KPIs Clave:**
  - Visitas
  - Conversión
  - Frecuencia de compra
  - Ticket medio
  - Tasa de abandono de carrito
  - LTV (Lifetime Value)

## Entidades y Datos Analizados

- **Usuarios:** Logados y no logados (cookies temporales). No se conoce el estado de logueo de los usuarios debido a normativas de privacidad.
- **Clientes:** Usuarios con al menos un evento de compra.
- **Sesiones:** Interacciones de los usuarios con el sitio web.
- **Eventos:** Interacciones clave, como mirar producto, añadir al carrito, eliminar del carrito, y compra.
- **Productos:** Información relevante sobre los productos transaccionados.

## Análisis e Insights
 
### Análisis del customer Journey: Situación inicial 

GRAFICO DE FUNNEL 

Conclusiones:

Las tasas de partida son un 60% de carrito sobre visualiazaciones y un 22% de compra sobre carrito

Por tanto existe un 40% de visitas sobre las que hay que trabajar para conseguir más carritos, y un 78% de carritos sobre los que trabajar para conseguir más compras

#### Customer Journey por sesion 

En cada sesión, de media:

- Se ven 2.2 productos
- Se añaden 1.3 productos al carrito
- Se eliminan 0.9 productos del carrito
- Se compran 0.3 productos

#### Análisis de los eventos por horas

GRafico Eventos por horas

**Insight #1**: todas las métricas se maximzan en las franjas entre las 9 y las 13 y entre las 18 y las 20

Esta información es muy relevante por ejemplo de cara a paid ads, tanto de generación de tráfico como de retargeting

Además, parece haber algún subtipo de usuario que compra a la 1 de la mañana, que aunque no sea muy frecuente sí compra mucho

#### Media de facturación mensual 

- La media de facturación mensual es de 124.309,92.

#### Tendencia de los eventos en los últimos meses 

Gráfico tendencia Noviembre y diciembre

El análisis de las tendencias de compra revela varios patrones interesantes:

- **Black Friday**: El mayor pico de ventas coincide con el Black Friday (29 de noviembre), con un aumento significativo unos días antes, el 22 de noviembre, probablemente debido al inicio de la semana de Black Friday.
- **Navidad**: Las ventas durante los días de Navidad presentan una tendencia decreciente, lo que indica que los consumidores anticipan sus compras navideñas.
- **Reyes y San Valentín**: No se observan picos de ventas durante la semana de Reyes ni en los días previos a San Valentín. Sin embargo, hay un notable aumento de ventas el 27 de enero, posiblemente relacionado con un evento local.

**Insight #2**: La mayoría de las compras navideñas se concentran en la semana del Black Friday.

### Análisis de los clientes 

#### Distribucion en cuanto al gasto 

Grafico gasto clientes 

La gran mayoría de los clientes han gastado menos de 50€ en el período.

#### Distribucion en cuanto al número de compras

Grafico 

**INSIGHT #3** La gran mayoría de los clientes sólo hace una compra.

Existe gran recorrido para mejorar este ratio mediante:

email marketing con newletters y ofertas personalizadas

#### Productos por cliente de media en cada compra

**INSIGHT #4** La compra mediana incluye 5 productos.

Pero un 25% de los clientes compran más de 10 productos en la misma compra.

Existe gran recorrido para mejorar este ratio mediante: sistemas de recomendación en el momento de la compra

#### Clientes que generan más ingresos

**INSIGHT #5** Existen clientes con gasto medio decenas de veces superior a la media.

Hay que fidelizar estos clientes mediante programas de fidelización.

### Análisis de supervivencia o de cohortes 

Dado que solo tenemos 5 meses de histórico vamos a crear análisis de cohortes a 3 meses vista, lo cual nos da para hacer 3 cohortes.

Grafico de cohortes 

**INSIGHT #6:** El 90% de que los nuevos clientes no vuelve a comprar en los meses posteriores

### LTV (Life Time Value) de los clientes 

Teniendo en cuenta el 90% de que los nuevos clientes no vuelve a comprar en los meses posteriores podemos calcular el LTV con el histórico que tenemos sin miedo a equivocarnos mucho.

**INSIGHT #7:** El LTV medio es de 42€.

Aplicando nuestro margen sobre esa cifra y el % que queremos dedicar a captación nos sale el importe máximo a invertir en CPA.

Aplicar las acciones de CRO permitirá incrementar el LTV y por tanto también el CPA, siendo una ventaja estratégica muy importante.

### RFM

**REVISAR ESTA SECCION**

### Análisis de los productos 

- Identificación de productos más vendidos. Posiblemente destacando estos productos en la tienda se podrían incrementar las ventas

- **INSIGHT #8**: Casi la mitad de los productos no han tenido ninguna venta en los 5 meses del histórico.

  Se podría realizar un análisis sobre estos productos: ¿No se ven?, ¿Se ven pero no se compran?, ¿Son más baratos en la competencia?

  #### Relación entre el precio y el volumen de ventas

  Grafico correlacion precio-compras

  #### Productos que se eliminan del carrito

  Identificación de los productos que más se eliminan del carrito

  ### Productos más vistos

  GRafgico

  #### Productos vistos pero no comprados

  Grafico

  Hay una oportunidad con estos productos, porque por algún motivo generan el interés de los clientes, pero finalmente no los compran.

  ### Sistemas de recomendación
