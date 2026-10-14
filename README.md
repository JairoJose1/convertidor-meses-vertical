# Convertidor de meses a tabla vertical

Herramienta web (HTML + JS puro, sin build) para **verticalizar** tablas horizontales exportadas de la plataforma.

## Qué hace

- Detecta columnas de meses (Ene Cantidad, Ene Precio, Ene Importe, etc.).
- Conserva todas las columnas descriptivas a la izquierda.
- Descarta columnas de Total y Diferencia.
- Genera una fila por cada mes con: `N° mes`, `Mes`, `Cantidad`, `Precio unitario`, `Importe`.
- Consolida varios archivos en una sola tabla (columna `Archivo`).
- Omite meses sin movimiento (opcional).
- Búsqueda inteligente en lenguaje libre, filtros tipo Excel, edición inline, export a Excel/CSV o copiar a portapapeles.

## Uso

1. Abre `index.html` en el navegador (o clónalo y ábrelo localmente).
2. Arrastra uno o varios `.xlsx` / `.csv`.
3. Filtra, edita si es necesario y descarga la base vertical.

## Tecnología

- SheetJS (xlsx) vía CDN para leer/escribir Excel.
- Sin frameworks. Todo en un solo archivo.

## Licencia

MIT
