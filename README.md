# Challenge-Alura-Store
# 🛍️ Análisis de Ventas para Alura Store - Challenge Data Science

Este proyecto forma parte del reto **"Practicando Python para Data Science: Challenge Alura Store"**, en el cual se analizan los datos de ventas de cuatro tiendas ficticias para determinar cuál tiene mejor desempeño y cuál debería considerar cerrar o fusionar.

## 📁 Dataset

Se trabajó con datos públicos proporcionados por Alura Latam:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Los datos incluyen:
- Categoría de producto
- Cantidad vendida
- Precio
- Calificación del cliente
- Costo de envío

---

## 📊 Análisis Realizado

Se evaluaron las tiendas según los siguientes criterios:

| Criterio                    | Tienda 1        | Tienda 2        | Tienda 3        | Tienda 4        |
|----------------------------|-----------------|-----------------|-----------------|-----------------|
| Ingresos Totales           | 🟢 **1,150M**    | 1,116M          | 1,098M          | 🔴 **1,038M**    |
| Porcentaje del total       | 26%             | 25%             | 25%             | 24%             |
| Calificación promedio      | 🔴 3.98          | 4.04            | 🟢 **4.05**      | 4.00            |
| Productos vendidos         | 2359            | 2359            | 2359            | 2358            |
| Costo de envío promedio    | 🔴 26,018        | 25,216          | 24,805          | 🟢 **23,459**    |

---

## ✅ Conclusiones

### Tiendas recomendadas para mantener:
- **Tienda 1**: Genera más ingresos.
- **Tienda 2**: Buen desempeño general.
- **Tienda 3**: Mejor calificada por clientes.

### Tienda que se recomienda cerrar o fusionar:
- **Tienda 4**:
  - Menores ingresos totales.
  - Calificación ligeramente inferior.
  - Prácticamente igual volumen de ventas.
  - Solo se destaca por tener el menor costo de envío.

Aunque la tienda 4 es más eficiente en logística, su rendimiento general no compensa. Se sugiere considerar **cerrarla** o **fusionar operaciones logísticas** con otras tiendas.

---

## 📌 Herramientas utilizadas

- Python
- Pandas
- Numpy


