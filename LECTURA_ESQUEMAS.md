# Lectura de esquemas — Jaime393/miu-public-data

`schemas/DATASET_SCHEMA_RECONCILIATION.md` (451 bytes, 1 línea) dice, íntegro:

> Completar `schemas/DATASET_SCHEMA_RECONCILIATION.md` comparando directamente el esquema de 2 campos de `alma_dataset_v1.jsonl` con README/config/muestras reales de `mii-datasert-train` de 6 campos. Definir versión, migración, validadores, compatibilidad hacia atrás, procedencia por registro y política de citas. Auditar las citas 2025-2026 y marcar como no verificadas las que no tengan DOI/URL resoluble. Añadir script de conversión y pruebas.

La comparación que pide el archivo, como está escrita:

| Lado | Archivo | Campos |
|---|---|---:|
| 1 | `alma_dataset_v1.jsonl` | 2 |
| 2 | `mii-datasert-train` | 6 |

Ni `alma_dataset_v1.jsonl` ni `mii-datasert-train` están en el repo. Verificado por los listados de raíz, `benchmarks/` y `schemas/`.

La cadena `mii-datasert` aparece escrita así en `schemas/DATASET_SCHEMA_RECONCILIATION.md` y en el mensaje del commit `3b6a0bf`.

Fuente: `~/workspace/mineria/miu-public-data/MINERIA.md`, Parte 1, §1.4.
