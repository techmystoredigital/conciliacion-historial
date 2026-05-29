# Reporte de Procesamiento — 2026-05-29

**Fecha y hora (Bogota):** 2026-05-29 16-03-32

**Estado:** ❌ ERROR

**Carpeta historial:** `2026-05-29_16-03-32`

## ⚠️ Errores detectados

- Script 2 (Bancos): [HEADERS_ACUM] Falta columna Valor/Monto en el acumulativo [line 47]
- Script 3 (Conciliacion): No hay archivos paso2_Banco en OUTPUTS [line 15]

**Estado de los scripts:** Script1=ok, Script2=error, Script3=error

## Resumen

- Outputs copiados al historial: **1**
- Archivos eliminados de input: **7**

## Outputs generados

- `paso1_Recargas Concesionario Yopago.xlsx`

## Detalle tecnico de Scripts

```json
{
  "script1": {
    "script1_status": "ok",
    "script1_paso1_id": "1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4",
    "script1_paso1_name": "paso1_Recargas Concesionario Yopago.xlsx",
    "script1_error": null,
    "script1_raw": "{\"kind\":\"drive#file\",\"id\":\"1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4\",\"name\":\"paso1_Recargas Concesionario Yopago.xlsx\",\"mimeType\":\"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet\",\"starred\":false,\"trashed\":false,\"explicitlyTrashed\":false,\"parents\":[\"1qulBT2VmQn1XL6cK1kednqiTSWzcO0Dq\"],\"spaces\":[\"drive\"],\"version\":\"3\",\"webContentLink\":\"https://drive.google.com/uc?id=1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4&export=download\",\"webViewLink\":\"https://docs.google.com/spreadsheets/d/1-0VHRJVFtyODOsM"
  },
  "script2": {
    "script1_status": "ok",
    "script1_paso1_id": "1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4",
    "script1_paso1_name": "paso1_Recargas Concesionario Yopago.xlsx",
    "script1_error": null,
    "script1_raw": "{\"kind\":\"drive#file\",\"id\":\"1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4\",\"name\":\"paso1_Recargas Concesionario Yopago.xlsx\",\"mimeType\":\"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet\",\"starred\":false,\"trashed\":false,\"explicitlyTrashed\":false,\"parents\":[\"1qulBT2VmQn1XL6cK1kednqiTSWzcO0Dq\"],\"spaces\":[\"drive\"],\"version\":\"3\",\"webContentLink\":\"https://drive.google.com/uc?id=1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4&export=download\",\"webViewLink\":\"https://docs.google.com/spreadsheets/d/1-0VHRJVFtyODOsM",
    "script2_status": "error",
    "script2_paso2_id": null,
    "script2_paso2_name": null,
    "script2_error": "[HEADERS_ACUM] Falta columna Valor/Monto en el acumulativo [line 47]",
    "script2_raw": "{\"error\":\"[HEADERS_ACUM] Falta columna Valor/Monto en el acumulativo [line 47]\"}"
  },
  "script3": {
    "script1_status": "ok",
    "script1_paso1_id": "1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4",
    "script1_paso1_name": "paso1_Recargas Concesionario Yopago.xlsx",
    "script1_error": null,
    "script1_raw": "{\"kind\":\"drive#file\",\"id\":\"1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4\",\"name\":\"paso1_Recargas Concesionario Yopago.xlsx\",\"mimeType\":\"application/vnd.openxmlformats-officedocument.spreadsheetml.sheet\",\"starred\":false,\"trashed\":false,\"explicitlyTrashed\":false,\"parents\":[\"1qulBT2VmQn1XL6cK1kednqiTSWzcO0Dq\"],\"spaces\":[\"drive\"],\"version\":\"3\",\"webContentLink\":\"https://drive.google.com/uc?id=1-0VHRJVFtyODOsMI7Arr0dlO0zJfHZa4&export=download\",\"webViewLink\":\"https://docs.google.com/spreadsheets/d/1-0VHRJVFtyODOsM",
    "script2_status": "error",
    "script2_paso2_id": null,
    "script2_paso2_name": null,
    "script2_error": "[HEADERS_ACUM] Falta columna Valor/Monto en el acumulativo [line 47]",
    "script2_raw": "{\"error\":\"[HEADERS_ACUM] Falta columna Valor/Monto en el acumulativo [line 47]\"}",
    "script3_status": "error",
    "script3_paso3_id": null,
    "script3_paso3_name": null,
    "script3_error": "No hay archivos paso2_Banco en OUTPUTS [line 15]",
    "script3_raw": "{\"error\":\"No hay archivos paso2_Banco en OUTPUTS [line 15]\"}",
    "master_status": "ERROR_EN_ALGUN_SCRIPT",
    "timestamp": "2026-05-29T21:04:17.227Z",
    "resumen": "Falla detectada. script1=ok, script2=error, script3=error"
  }
}
```

---
_Generado por Conciliacion_HISTORIAL_POST_
