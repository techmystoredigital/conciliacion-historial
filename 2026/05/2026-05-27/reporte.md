# Reporte de Procesamiento — 2026-05-27

**Fecha y hora (Bogota):** 2026-05-27 10-54-32

**Estado:** ❌ ERROR

**Carpeta historial:** `2026-05-27_10-54-32`

## ⚠️ Errores detectados

- Script 1 (Recargas): re-disparo del mismo dia o cajas ya procesadas. NO se modifico el Yopago. [line 57]
- Script 3 (Conciliacion): No hay archivo paso1_Yopago en OUTPUTS [line 14]

**Estado de los scripts:** Script1=error, Script2=ok, Script3=error

## Resumen

- Outputs copiados al historial: **2**
- Archivos eliminados de input: **7**

## Outputs generados

- `paso2_Banco coop. Credil (1).xlsx`
- `paso2_Bancos Coop. valles de lirio .xlsx`

## Detalle tecnico de Scripts

```json
{
  "script1": {
    "script1_status": "error",
    "script1_paso1_id": null,
    "script1_paso1_name": null,
    "script1_error": "re-disparo del mismo dia o cajas ya procesadas. NO se modifico el Yopago. [line 57]",
    "script1_raw": "{\"error\":\"re-disparo del mismo dia o cajas ya procesadas. NO se modifico el Yopago. [line 57]\"}"
  },
  "script2": {
    "script1_status": "error",
    "script1_paso1_id": null,
    "script1_paso1_name": null,
    "script1_error": "re-disparo del mismo dia o cajas ya procesadas. NO se modifico el Yopago. [line 57]",
    "script1_raw": "{\"error\":\"re-disparo del mismo dia o cajas ya procesadas. NO se modifico el Yopago. [line 57]\"}",
    "script2_status": "ok",
    "script2_paso2_id": "1aHfpM4m5mtmczWZqYVo814LBaGuXUg32",
    "script2_paso2_name": "paso2_Bancos Coop. valles de lirio .xlsx",
    "script2_error": null,
    "script2_raw": "{\"kind\":\"drive#file\",\"id\":\"1aHfpM4m5mtmczWZqYVo814LBaGuXUg32\",\"name\":\"paso2_Bancos Coop. valles de lirio .xlsx\",\"mimeType\":\"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet\",\"starred\":false,\"trashed\":false,\"explicitlyTrashed\":false,\"parents\":[\"1qulBT2VmQn1XL6cK1kednqiTSWzcO0Dq\"],\"spaces\":[\"drive\"],\"version\":\"2\",\"webContentLink\":\"https://drive.google.com/uc?id=1aHfpM4m5mtmczWZqYVo814LBaGuXUg32&export=download\",\"webViewLink\":\"https://docs.google.com/spreadsheets/d/1aHfpM4m5mtmczWZ"
  },
  "script3": {
    "script1_status": "error",
    "script1_paso1_id": null,
    "script1_paso1_name": null,
    "script1_error": "re-disparo del mismo dia o cajas ya procesadas. NO se modifico el Yopago. [line 57]",
    "script1_raw": "{\"error\":\"re-disparo del mismo dia o cajas ya procesadas. NO se modifico el Yopago. [line 57]\"}",
    "script2_status": "ok",
    "script2_paso2_id": "1aHfpM4m5mtmczWZqYVo814LBaGuXUg32",
    "script2_paso2_name": "paso2_Bancos Coop. valles de lirio .xlsx",
    "script2_error": null,
    "script2_raw": "{\"kind\":\"drive#file\",\"id\":\"1aHfpM4m5mtmczWZqYVo814LBaGuXUg32\",\"name\":\"paso2_Bancos Coop. valles de lirio .xlsx\",\"mimeType\":\"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet\",\"starred\":false,\"trashed\":false,\"explicitlyTrashed\":false,\"parents\":[\"1qulBT2VmQn1XL6cK1kednqiTSWzcO0Dq\"],\"spaces\":[\"drive\"],\"version\":\"2\",\"webContentLink\":\"https://drive.google.com/uc?id=1aHfpM4m5mtmczWZqYVo814LBaGuXUg32&export=download\",\"webViewLink\":\"https://docs.google.com/spreadsheets/d/1aHfpM4m5mtmczWZ",
    "script3_status": "error",
    "script3_paso3_id": null,
    "script3_paso3_name": null,
    "script3_error": "No hay archivo paso1_Yopago en OUTPUTS [line 14]",
    "script3_raw": "{\"error\":\"No hay archivo paso1_Yopago en OUTPUTS [line 14]\"}",
    "master_status": "ERROR_EN_ALGUN_SCRIPT",
    "timestamp": "2026-05-27T15:55:48.110Z",
    "resumen": "Falla detectada. script1=error, script2=ok, script3=error"
  }
}
```

---
_Generado por Conciliacion_HISTORIAL_POST_
