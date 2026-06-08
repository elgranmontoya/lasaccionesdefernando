# Cuadro de mando v3

## Ficheros CSV

### operaciones.csv
Columnas: `date,symbol,type,qty,price,fees,dividend,tax`

- `date`: fecha ISO `YYYY-MM-DD`.
- `symbol`: ticker.
- `type`: `buy`, `sell` o `dividend`.
- `qty`: cantidad de títulos.
- `price`: precio unitario.
- `fees`: comisiones.
- `dividend`: importe del dividendo bruto o neto según tu criterio, pero usa siempre el mismo.
- `tax`: retención fiscal si quieres registrarla.

### cartera.csv
Columnas: `symbol,qty,buy,price,div,com,opened`

- `symbol`: ticker.
- `qty`: cantidad agregada.
- `buy`: precio medio de compra.
- `price`: precio actual o último precio conocido.
- `div`: dividendos acumulados.
- `com`: comisiones acumuladas.
- `opened`: `yes` o `no`.

### seguimiento.csv
Columnas: `symbol,target,price,status`

- `symbol`: ticker vigilado.
- `target`: precio objetivo.
- `price`: precio actual de referencia.
- `status`: estado libre.

### historico.csv
Columnas: `date,symbol,close`

- `date`: fecha ISO.
- `symbol`: ticker.
- `close`: cierre diario.
