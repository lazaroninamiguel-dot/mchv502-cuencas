# T05 · Escorrentía SCS-CN · microcuenca de cabecera del río Sumbay (Imata)

Resultados del cuaderno `T05_Lazaro_Miguel.ipynb` (semana 8). Malla de 30 m, EPSG:32719, 190.4 km².

| Archivo | Contenido | Uso en el proyecto final |
|---|---|---|
| `S08_cn_actual_imata.tif` | Número de curva por celda (CN medio 87.5; GCN250: 87.9) | M3: escorrentía de cualquier lluvia |
| `S08_escorrentia_actual_imata.tif` | Escorrentía del evento de 24.8 mm, en mm | Mapa de dónde se genera la escorrentía |
| `S08_escorrentia_extra_imata.tif` | Escorrentía extra del escenario (pastizal con pendiente > 8° pasa a suelo desnudo) | Discusión sobre la cobertura |
| `S08_tabla_cn.csv` | Tabla cobertura × grupo de suelo → CN (decisiones declaradas) | Reproducibilidad |
| `S08_curva_lluvia_escorrentia.csv` | Escorrentía media de la cuenca para lluvias de 0 a 150 mm | M3: pasar la lluvia diaria a escorrentía sin recalcular mapas |
| `S08_sensibilidad.csv` | Escorrentía con 25, 50 y 93,6 mm, suelo normal y húmedo | Rango de incertidumbre |
| `S08_comparacion_escenarios.csv` | Cobertura actual frente al escenario | Discusión |
| `S08_resumen_imata.csv` | Valores clave del cuaderno | Tablas del informe |

**Decisiones:** evento de diseño 24.8 mm (media de los máximos diarios anuales CHIRPS 2015–2025, sin el día atípico del 05-05-2018);
Ia = 0,2·S; grupo de suelo HYSOGs250m (sin dato → C, grupo dominante); bofedal y nieve CN 98, agua CN 100.
**Límite:** SCS-CN calcula escorrentía de evento; no representa el flujo base del estiaje.
