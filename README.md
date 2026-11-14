# 🎲 Juegos de Mesa de Todos los Tiempos

Vitrina virtual de la colección de juegos de mesa de David: ediciones antiguas y modernas, con fotos, editorial o fabricante, año, país, edición, número de jugadores, estado, completitud y tasación en pesos chilenos (CLP). Incluye música de fondo y calculadora para ir sumando piezas.

**Totales:** 0 Fichas · 0 Unidades · $0 (CLP, venta Chile)

## 🛒 Tienda web
**[https://dacam32-del.github.io/vitrina-juegos-de-mesa/](https://dacam32-del.github.io/vitrina-juegos-de-mesa/)**

## Agregar una pieza
1. Fotos en `img/` como `JUE-00N.jpg`, `JUE-00N-2.jpg`, … (copiar tal cual, sin recorte ni compresión).
2. Agregar un objeto al arreglo de `data.json` (pmin/pmax en CLP numéricos para filtros y totales). Ejemplo:

```json
{
  "id": "JUE-001",
  "tipo": "Juego de mesa",
  "titulo": "Nombre del juego",
  "editorial": "Editorial o fabricante",
  "fabricante": "",
  "edicion": "1.ª edición",
  "anio": "1995",
  "epoca": "1980–1999",
  "y": 1995,
  "ep": "1980–1999",
  "pais": "Alemania",
  "jugadores": "2–4",
  "idioma": "Español",
  "genero": "Estrategia",
  "estado": {
    "escala": "Bueno",
    "nota": 7,
    "detalle": "Caja con roce en bordes; componentes completos y en buen estado"
  },
  "completitud": "Completo",
  "rareza": "Común",
  "valor_internacional_usd": "",
  "valor_internacional_clp": "",
  "venta_chile_clp": "$10.000 – $18.000",
  "stock": 1,
  "notas": "",
  "dolar": 992.48,
  "fecha": "2026-11-13",
  "imgs": ["img/JUE-001.jpg", "img/JUE-001-2.jpg"],
  "pmin": 10000,
  "pmax": 18000
}
```

Campos principales: `titulo` (nombre), `editorial` / `fabricante`, `anio`, `pais`, `edicion`, `jugadores`, `estado`, `completitud`, `venta_chile_clp` (precio en CLP) y `imgs` (fotos).
