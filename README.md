# Proyecto: Estudio de Serigrafía

## ⚪​ Integrantes del Grupo
* **Amaya, Milton** ([GitHub](https://github.com/miltonamaya864))
* **Baroni, Eneas Pablo** ([GitHub](https://github.com/eneasbaroni))
* **Fava Perez, Maria Pia** ([GitHub](https://github.com/pia-fava))
* **Ortega, Santiago Andrés** ([GitHub](https://github.com/Ortegas87))
* **Rivas, Mariela Yanina** ([GitHub](https://github.com/MarielaRivas))

**Ciclo Lectivo:** 2026 | **Institución:** Instituto Superior Politécnico Córdoba (ISPC)

---

## ⚪​ Descripción del Dataset
El dataset representa la actividad comercial de un **Estudio de Serigrafía** ubicado en **Córdoba, Argentina**. Contiene información integral que vincula a los clientes con sus pedidos (presupuestos), el detalle técnico de los productos solicitados y el resultado económico de dichas operaciones.

Esta herramienta está diseñada para analizar:
* **Comportamientos de compra** de diferentes segmentos (particulares, empresas y revendedores).
* **Eficiencia operativa** mediante el análisis de tiempos de respuesta (latencia).
* **Preferencias técnicas** según el tipo de producto y técnica de estampado.

---

## ⚪​ Diccionario de Variables

| Variable | Descripción | Tipo de Variable |
| :--- | :--- | :--- |
| `id_venta` | Identificador único de la venta realizada. | Cualitativa Nominal |
| `id_presupuesto` | Identificador único de la solicitud de presupuesto. | Cualitativa Nominal |
| `monto_total (ARS)` | Importe final cobrado al cliente. | Cuantitativa Continua |
| `monto_neto (ARS)` | Valor de la venta antes de impuestos. | Cuantitativa Continua |
| `metodo_pago` | Medio por el cual se abonó (efectivo, tarjeta, etc.). | Cualitativa Nominal |
| `fecha_venta` | Marca temporal de la transacción comercial. | Cualitativa (Temporal) |
| `id_cliente` | Identificador único del cliente. | Cualitativa Nominal |
| `fecha_hora_ingreso` | Momento en que el cliente solicitó el presupuesto. | Cualitativa (Temporal) |
| `fecha_hora_rta` | Momento en que el estudio envió la respuesta. | Cualitativa (Temporal) |
| `latencia_min` | Tiempo de respuesta medido en minutos. | Cuantitativa Discreta |
| `estado` | Situación del presupuesto (ej. aprobado). | Cualitativa Nominal |
| `tipo_cliente` | Clasificación (particular, empresa, revendedor). | Cualitativa Nominal |
| `nombre` | Nombre del cliente o contacto. | Cualitativa Nominal |
| `apellido` | Apellido del cliente (si aplica). | Cualitativa Nominal |
| `provincia_o_ciudad` | Ubicación geográfica del pedido. | Cualitativa Nominal |
| `id_producto` | Código interno del producto base solicitado. | Cualitativa Nominal |
| `cantidad_copias` | Volumen de unidades a estampar. | Cuantitativa Discreta |
| `cantidad_colores` | Complejidad del diseño según sus colores. | Cuantitativa Discreta |
| `medida` | Área de impresión (ej. 20x20 cm). | Cualitativa Ordinal |
| `tecnica` | Método aplicado (serigrafía, DTF, etc.). | Cualitativa Nominal |
| `ubicacion` | Lugar de la prenda donde se aplica el diseño. | Cualitativa Nominal |
| `nombre_producto` | Descripción del artículo (remera, buzo, etc.). | Cualitativa Nominal |
| `precio_lista_base (ARS)` | Precio unitario del producto sin personalización. | Cuantitativa Continua |
