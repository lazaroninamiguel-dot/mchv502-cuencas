# S10.1 · Lluvia ERA5 vs CHIRPS · Subcuenca Sumbay

Resultados del cuaderno [`S10.1_lluvia_ERA5_CHIRPS.ipynb`](../notebook/S10.1_lluvia_ERA5_CHIRPS.ipynb) (punto de referencia: lat −15,8891, lon −70,9896; periodo desde 2015-01-01).

| Archivo | Contenido |
|---|---|
| `lluvia_era5_Subcuenca-Sumbay.csv` | Lluvia diaria ERA5 (Open-Meteo) en el punto de referencia: `fecha`, `lluvia_mm` |
| `lluvia_chirps_Subcuenca-Sumbay.csv` | Lluvia diaria CHIRPS (Google Earth Engine) en el mismo punto: `fecha`, `lluvia_mm` |
| `lluvia_cuenca_era5_Subcuenca-Sumbay.csv` | Lluvia diaria ERA5 promediada sobre los puntos de la malla dentro de la cuenca |
| `puntos_cuenca_Subcuenca-Sumbay.geojson` | Puntos de la malla (0,03°) dentro de la cuenca, usados para el promedio |
| `umbrales_Subcuenca-Sumbay.csv` | Umbrales de lluvia Fuerte (P90), Severa (P95) y Extrema (P99), ERA5 vs CHIRPS (días con lluvia > 2 mm) |
