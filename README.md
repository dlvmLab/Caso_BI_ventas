# 📊 Dashboard de Ventas — Power BI

Dashboard interactivo en Power BI que analiza el desempeño comercial de una empresa: ventas, costes, beneficio y participación por categoría de producto, división geográfica y vendedor.

<p align="center">
  <img src="assets/dashboard.gif" alt="Vista previa del dashboard" width="850">
</p>

## 🔍 Contenido del dashboard

**KPIs principales (tarjetas):**
- Cantidad vendida
- Ventas
- Coste
- Beneficio
- % Beneficio

**Visualizaciones:**
- 📊 Gráfico de barras: Cantidad por producto
- 📈 Gráfico de columnas: Ventas por vendedor
- 🍩 Gráfico de dona: Ventas por categoría
- 🍩 Gráfico de dona: Ventas por división geográfica

**Filtros (slicers):**
- País
- Ciudad
- Producto
- Compañía
- Puesto

## 🗂️ Modelo de datos

El modelo relacional está compuesto por 5 tablas:

| Tabla | Contenido |
|---|---|
| `Pedidos` | Hechos: cantidad, ventas, coste por pedido |
| `Productos` | Catálogo de productos y categorías |
| `Clientes` | Datos de clientes (país, ciudad, división) |
| `Vendedores` | Datos de vendedores (nombre, puesto) |
| `Medidas` | Medidas DAX calculadas (Ventas, Coste, Beneficio, % Beneficio, Cantidad) |

## 🛠️ Herramientas

- Power BI Desktop
- DAX (medidas calculadas)
- Modelo de datos relacional (esquema estrella)

## 📁 Archivos

- `PowerBI_Caso_01.pbix` — archivo del dashboard (requiere Power BI Desktop para abrir)
- `assets/dashboard.gif` — vista previa animada del dashboard

## 🚀 Cómo usarlo

1. Descarga el archivo `.pbix`
2. Ábrelo con [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (gratis)
3. Explora los filtros y visualizaciones de forma interactiva∫