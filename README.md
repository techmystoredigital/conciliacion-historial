# Historial de Conciliacion Bancaria — My Store Digital

Bitacora diaria del sistema automatico de conciliacion bancaria.
Cada dia el sistema procesa cajas Virtualsoft, bancos (Valles + Credil) y resumenes,
generando archivos paso1/paso2/paso3. Despues, este repo recibe un commit con el
**reporte.md** y **log.json** del dia.

## Estructura

```
YYYY/
  MM/
    YYYY-MM-DD/
      reporte.md   ← qué pasó hoy (humano-legible)
      log.json     ← stats + errores estructurados
```

## Que NO esta aca

- ❌ Archivos xlsx pesados (esos viven en Drive)
- ❌ Codigo de los scripts (vive en N8N)

Los xlsx se mueven a la carpeta `Historial/` del Drive con la fecha-hora del procesamiento.

## Cuando hay errores

Si el reporte de un dia dice `Estado: ERROR`, ahi vas a encontrar:
- Que paso (mensaje exacto del error)
- En que parte del flujo fallo
- Que hizo la encargada despues (si arreglo manualmente)

Esto te da contexto para reparar el bug o documentar el procedimiento.

## Operacion

- **Disparador:** N8N de la encargada (workflow `Master_Procesar_Dia`)
- **Push automatico:** workflow `Historial` (al final del procesamiento)
- **Notificacion:** GitHub Watch envia email cuando hay commit nuevo

---
Setup: 2026-05-22
