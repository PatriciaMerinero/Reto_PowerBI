<img width="961" height="701" alt="image" src="https://github.com/user-attachments/assets/38f6b747-750b-472a-bf59-b3c306e61e7a" />




# Reto Power BI – Tablas Ventas, Productos, Vendedores y Objetivos

Este proyecto forma parte del reto de Power BI en el que se solicita:

- Conectarse al conjunto de datos proporcionado.
- Limpiar y transformar los datos en Power Query.
- Crear las tablas: **Ventas**, **Vendedores**, **Productos** y **Objetivos**.
- Aplicar transformaciones específicas (Antigüedad en Vendedores, campo Fecha en Objetivos).
- Cargar el modelo en Power BI y exportarlo.

## 📁 Estructura de archivos

El proyecto está organizado de la siguiente manera:

<img width="206" height="193" alt="image" src="https://github.com/user-attachments/assets/e56e6c91-c742-44d1-b6ca-e25f87ab3c7c" />




## 🧩 Transformaciones realizadas

- **Ventas**: Se eliminaron columnas innecesarias, se ajustaron tipos y se identificó como tabla de hechos.  
- **Vendedores**:  
  - Creación de columna personalizada `Antigüedad`  
    - ≤ 2019 → “Vendedor Antiguo”  
    - ≥ 2020 → “Nueva Incorporación”  
  - Renombrada columna “Gerencia Comercial” a “Región”.  
- **Productos**: Asignación de tipos y limpieza de nombres.  
- **Objetivos**: Creación de campo `Fecha` combinando `Mes Nombre` y `Año`.

## 💾 Archivo de Power BI

El archivo principal del modelo se encuentra en:  
**`Reto_PowerBI.pbix`**

## 📤 Entrega

Repositorio preparado para su revisión y entrega en GitHub.
