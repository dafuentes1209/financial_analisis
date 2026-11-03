# Análisis de series de tiempo financieras: oro vs. petróleo

Análisis exploratorio en Python de los precios del oro (GC=F) y del petróleo WTI (CL=F) desde 2020, con datos descargados de Yahoo Finance mediante yfinance.

## Contenido
- `analisis_activos.ipynb`: descarga de datos, gráfica de precios y comparación de ambos activos normalizados en base 100.
- `oro_data.csv` y `petroleo_data.csv`: copia de los datos diarios (2020-01-02 a 2024-12-31).

## Observaciones
- Con base 100, el oro se triplica entre 2020 y comienzos de 2026.
- El petróleo registra el precio negativo del WTI en abril de 2020, un pico en 2022 y termina cerca de su nivel inicial.

## Cómo ejecutarlo
```bash
pip install yfinance pandas matplotlib jupyter
jupyter notebook analisis_activos.ipynb
```
El notebook descarga los datos en vivo, así que los resultados pueden cambiar con el tiempo.
