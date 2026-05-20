# Historial — Conciliación bancaria Mine Store Digital

Registro automático del procesamiento diario de conciliación bancaria.
Cada commit corresponde a una ejecución del workflow "Procesar Día" en N8N.

## Estructura

```
YYYY/MM/DD/
├── reporte.md   ← resumen humano-legible del día
├── master.json  ← log estructurado del workflow master
├── script1.json ← log del Script 1 (Recargas)
├── script2.json ← log del Script 2 (Bancos)
└── script3.json ← log del Script 3 (Conciliación)
```

Los archivos pesados (.xlsx) NO se versionan acá. Quedan en Google Drive
en la carpeta `HISTORIAL/YYYY-MM-DD/` (links dentro de cada `reporte.md`).

## Cómo funciona

1. La encargada dispara "Procesar Día" desde el HTML o Claude
2. Los Scripts 1+2+3 procesan los archivos del día
3. El workflow "Historial Diario" automáticamente:
   - Hace snapshot de inputs y outputs en Drive
   - Genera reporte.md + logs JSON
   - Hace commit + push a este repo

## Notificaciones

Activar "Watch" en este repo → llegan emails automáticos por cada push.

## Acceso

Por ahora público para facilitar testing.
Se hará privado cuando el sistema pase a producción definitiva.
