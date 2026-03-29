# 📊 Sales & Customer Analytics Platform

Proyecto de análisis de datos end-to-end utilizando Microsoft Azure y Power BI, enfocado en el análisis de ventas, clientes y rentabilidad.

---

## 🚀 Tecnologías utilizadas

* Microsoft Azure

  * Azure Blob Storage
  * Azure Data Factory
* Power BI
* DAX
* CSV

---

## 🏗️ Arquitectura del proyecto

```
Raw Data (CSV)
   ↓
Azure Blob Storage (raw-data)
   ↓
Azure Data Factory Pipeline
   ↓
Azure Blob Storage (processed-data)
   ↓
Power BI Dashboard
```

---

## ⚙️ Descripción del proyecto

Se desarrolló un flujo completo de datos en la nube, donde:

* Se almacenaron datos en Azure Blob Storage
* Se implementó un pipeline en Azure Data Factory para mover y organizar la información
* Se utilizó Power BI para crear un dashboard interactivo

Este proyecto simula una arquitectura real de análisis de datos utilizada en empresas.

---

## 📊 Análisis realizado

El dashboard incluye:

* Ventas totales
* Ganancia total
* Número de pedidos
* Margen (%)
* Ventas por categoría
* Ventas por región
* Top productos
* Top clientes

---

## 📈 KPIs (medidas en DAX)

```DAX
Ventas Totales = SUM('sales_data_processed'[Sales])

Ganancia Total = SUM('sales_data_processed'[Profit])

Total Pedidos = COUNT('sales_data_processed'[Order ID])

Margen = DIVIDE(SUM('sales_data_processed'[Profit]), SUM('sales_data_processed'[Sales]))
```

---

## 💡 Insights

* La categoría Technology lidera las ventas
* Existe concentración de ingresos en clientes principales
* Hay diferencias de rendimiento entre regiones
* El margen permite analizar la rentabilidad real

---

## 🧠 Habilidades demostradas

* Análisis de datos
* Power BI
* Azure Data Factory
* Azure Blob Storage
* Visualización de datos
* ETL básico

---



![dashboard-sales-customer](https://github.com/user-attachments/assets/cce577bf-84cf-4ad2-bbc9-d4fb74c361c9)
![dashboard-sales-customer](https://github.com/user-attachments/assets/e61d81b4-dabf-4b67-a370-7316f9d8b40a)
![azure-data-factory](https://github.com/user-attachments/assets/6ee4d65d-5fe0-445f-a103-2ccd41e96828)


## 👨‍💻 Autor

Javier Castro
