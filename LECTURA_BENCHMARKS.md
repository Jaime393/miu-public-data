# Lectura de benchmarks — Jaime393/miu-public-data

`benchmarks/df/README.md` (393 bytes, 1 línea) dice, íntegro:

> Crear benchmark D_f por tipo de objeto (serie temporal, puntos 2D, contornos, perfiles): dataset con DOI/URL, hash, estimador apropiado, escalas, detrend, intervalo de confianza, nulo/permutación y criterios pass/fail predefinidos. Recalcular primero CO2, FIRMS, HMP2, Allen Coral Atlas y WoSIS con datos reales. No tabular valores heterogéneos como directamente comparables ni calcular K_i.

La especificación del benchmark, como está escrita:

- Por tipo de objeto: serie temporal, puntos 2D, contornos, perfiles.
- Cada dataset con: DOI/URL, hash, estimador apropiado, escalas, detrend, intervalo de confianza, nulo/permutación y criterios pass/fail predefinidos.

Los 5 conjuntos nombrados para recalcular primero, como están escritos:

1. CO2
2. FIRMS
3. HMP2
4. Allen Coral Atlas
5. WoSIS

Ninguno de los 5 conjuntos está en el repo, y no hay benchmark, datos ni script. Verificado por los listados de raíz, `benchmarks/` y `schemas/`.

Fuente: `~/workspace/mineria/miu-public-data/MINERIA.md`, Parte 1, §1.4.
