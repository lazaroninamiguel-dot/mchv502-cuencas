# mchv502-cuencas

Trabajos del curso **MCHV-502 · Programación y SIG para el análisis de cuencas**, Maestría en Manejo y Gestión de Cuencas Hidrográficas, CATIE.

**Autor:** Miguel Ángel Lázaro Nina (Perú)

## Cuencas de estudio

- **Subcuenca del río Sumbay-Chili** (Imata, Arequipa): 190,3 km², de 4489 a 5036 msnm.
- **Microcuenca Llallahui-Tacune**.

## Estructura del repositorio

```
mchv502-cuencas/
├── datos_base/              Insumos compartidos entre tareas (estaciones del Perú)
├── T03_delimitacion/
│   └── resultados/          Cuencas y redes de drenaje (.geojson)
└── T04_lluvia/
    ├── notebook/            Cuadernos de Colab (.ipynb)
    ├── insumos/             Estaciones con lluvia y ráster CHIRPS recortado
    └── resultados/          Superficies interpoladas, validación cruzada y lluvia media
```

Cada tarea guarda por separado lo que **entra** (insumos) y lo que **sale** (resultados). Los resultados de una tarea pueden ser insumos de la siguiente: la cuenca y la red de la T03 se usan en la T04.

## Tareas

| Tarea | Tema | Contenido |
|---|---|---|
| T03 | Delimitación de cuencas | Límite de la cuenca y red de drenaje de Imata y Llallahui-Tacune |
| T04 | Interpolación de lluvia | Vecino más cercano e IDW, validación cruzada dejando una estación afuera, lluvia media sobre la cuenca |

## Datos

- **Lluvia:** CHIRPS v3, media anual 2015–2025.
- **Estaciones:** red del SENAMHI (Perú).

## Cómo ejecutar

Abra un cuaderno de `T04_lluvia/notebook/` y pulse **Open in Colab**. Los datos se leen directamente desde este repositorio mediante enlaces *raw*, así que no hace falta descargar nada.
