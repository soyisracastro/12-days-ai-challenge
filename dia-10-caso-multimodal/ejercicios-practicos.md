# Dia 10: Ejercicios Practicos
## Caso Multimodal

**Tiempo estimado:** 30-45 minutos
**Objetivo:** Practicar el procesamiento de multiples formatos de documentos en un mismo proyecto usando IAs multimodales.

---

## Requisitos Previos

### Antes de empezar:

1. **Herramientas configuradas**
   - Cuenta en Claude (Projects)
   - Cuenta en ChatGPT
   - Opcional: Cuenta en Gemini

2. **Documentos para practicar**
   - Puedes usar documentos reales (anonimizados) o crear ejemplos
   - Mix de formatos: PDFs, imagenes, hojas de calculo
   - Minimo 5-10 documentos para practicar

3. **Consideracion de seguridad**
   - Si usas documentos reales, anonimiza datos sensibles
   - Reemplaza nombres, RFCs, numeros de cuenta
   - O usa documentos de practica/ejemplo

---

## Ejercicio 1: Preparacion de Documentos Multimodales (10 minutos)

### Objetivo
Organizar documentos en diferentes formatos para procesamiento eficiente.

### Paso 1: Reune Documentos de Ejemplo (5 minutos)

Necesitas reunir o crear 8-10 documentos en diferentes formatos:

**Opcion A: Documentos reales anonimizados**
- 2-3 PDFs (contratos, declaraciones, dictamenes)
- 2-3 imagenes (facturas escaneadas, comprobantes)
- 1-2 hojas de calculo (estados financieros, conciliaciones)

**Opcion B: Documentos de practica**
- Descarga ejemplos de facturas del SAT
- Usa plantillas de Excel de estados financieros
- PDFs de contratos ejemplo disponibles online

**Opcion C: Crear simulados**
- Genera PDFs de ejemplo con ChatGPT/Claude
- Crea hojas de calculo basicas
- Usa capturas de pantalla como imagenes

### Paso 2: Organiza y Renombra (3 minutos)

Crea estructura de carpetas:
```
proyecto-multimodal/
├── contratos/
│   ├── contrato-arrendamiento.pdf
│   └── contrato-servicios.pdf
├── facturas/
│   ├── factura-001.jpg
│   ├── factura-002.png
│   └── factura-003.pdf
├── financieros/
│   ├── estado-financiero-2024.xlsx
│   └── conciliacion-bancaria.xlsx
└── declaraciones/
    └── declaracion-anual-2023.pdf
```

**Criterios de nombres:**
- Descriptivos y claros
- Fecha si aplica
- Sin espacios (usa guiones)
- Categoria identificable

### Paso 3: Documenta tu Inventario (2 minutos)

Crea una lista de tus documentos:

| Archivo | Formato | Tipo | Informacion clave |
|---------|---------|------|-------------------|
| contrato-arrendamiento.pdf | PDF | Contrato | Renta mensual, vigencia |
| factura-001.jpg | Imagen | Factura | Monto, RFC, fecha |
| estado-financiero-2024.xlsx | Excel | Financiero | Ingresos, gastos |
| ... | ... | ... | ... |

---

## Ejercicio 2: Analisis Multimodal Basico (15 minutos)

### Objetivo
Procesar multiples formatos simultaneamente en Claude Projects.

### Paso 1: Crear Proyecto en Claude (2 minutos)

1. Ve a claude.ai
2. Crea nuevo proyecto: "Practica Multimodal Dia 10"
3. En instrucciones del proyecto:
   ```
   Eres un asistente de analisis documental para contadores.
   Procesas PDFs, imagenes y hojas de calculo.
   Extraes datos clave y identificas discrepancias.
   Siempre citas la fuente especifica de cada dato.
   ```

### Paso 2: Subir Documentos (3 minutos)

En el proyecto de Claude:
1. Haz clic en "Add content"
2. Sube tus documentos (PDFs, imagenes, Excel)
3. Claude los procesara automaticamente

**Nota:** Claude acepta multiples formatos simultaneamente.

### Paso 3: Analisis Inicial (5 minutos)

Inicia conversacion con:

```
Analiza todos los documentos que te subi y proporciona:

1. Un inventario de los documentos (nombre, tipo, contenido principal)
2. Extrae los datos financieros clave de cada documento
3. Identifica relaciones entre documentos (ej: factura relacionada
   con gasto en estado financiero)
4. Lista cualquier discrepancia o informacion faltante que notes

Cita especificamente de donde sacas cada dato.
```

**Registra los hallazgos:**
```
Inventario de Claude:
[Copia aqui lo que Claude identifico]

Datos clave extraidos:
[Copia la extraccion]

Relaciones identificadas:
[Copia las relaciones]

Discrepancias:
[Copia discrepancias si las hay]
```

### Paso 4: Pregunta Focalizada (5 minutos)

Haz una pregunta especifica sobre los datos:

**Ejemplo 1 - Verificacion de gastos:**
```
Segun el estado financiero, ¿cuanto se declaro en gastos de
arrendamiento? Compara esto con el monto del contrato de
arrendamiento y las facturas relacionadas. ¿Coinciden?
```

**Ejemplo 2 - Analisis de facturas:**
```
De las facturas en imagenes, extrae: RFC emisor, fecha, monto
total, y conceptos. Crea una tabla con estos datos. Luego suma
los montos totales.
```

**Ejemplo 3 - Cruce de informacion:**
```
Segun los estados de cuenta, ¿que pagos se realizaron? Compara
estos pagos con las facturas que tenemos. ¿Hay pagos sin factura
de soporte?
```

**Registra la respuesta:**
```
Mi pregunta:
[...]

Respuesta de Claude:
[Copia la respuesta]

¿La respuesta fue precisa? ¿Cito correctamente?
[Tu evaluacion]
```

---

## Ejercicio 3: Caso Integrado - Revision Fiscal (15 minutos)

### Objetivo
Resolver un caso completo usando workflow multimodal.

### El Caso

> Una persona moral te contrata para revisar su situacion fiscal del ejercicio 2023. Te proporciona:
>
> - Declaracion anual 2023 (PDF)
> - Estado de resultados 2023 (Excel)
> - 15 facturas de gastos principales (mix de PDF e imagenes)
> - Contrato de arrendamiento de oficina (PDF)
> - Estados de cuenta bancarios del año (PDF)
>
> **Objetivo:** Verificar que los gastos deducibles declarados tienen soporte documental adecuado y cumplen requisitos de LISR.

### Paso 1: Planea tu Workflow (3 minutos)

Antes de ejecutar, planea tu estrategia:

| Paso | Accion | Herramienta | Tiempo estimado |
|------|--------|-------------|-----------------|
| 1 | __________ | __________ | __ min |
| 2 | __________ | __________ | __ min |
| 3 | __________ | __________ | __ min |
| 4 | __________ | __________ | __ min |
| 5 | __________ | __________ | __ min |

**Mi herramienta principal para este caso:**
```
[Claude Projects / ChatGPT / Gemini - elige y justifica]

Justificacion:
```

### Paso 2: Ejecuta el Analisis (10 minutos)

**IMPORTANTE:** Como este es un caso de practica, si no tienes todos estos documentos, usa los que tengas disponibles y adapta el ejercicio.

**2.1 Preparacion (2 minutos)**
- Abre tu herramienta elegida
- Sube todos los documentos disponibles
- Da contexto del proyecto

**2.2 Extraccion de datos (3 minutos)**

Prompt sugerido:
```
Necesito analizar la deducibilidad de gastos. Por favor:

1. De la declaracion anual, extrae el monto total de gastos
   deducibles declarados

2. Del estado de resultados en Excel, extrae el detalle de
   gastos por categoria

3. De las facturas (PDFs e imagenes), extrae: RFC emisor,
   fecha, monto, concepto, y verifica que cumplan requisitos
   basicos (RFC, fecha, desglose)

4. Del contrato de arrendamiento, extrae: monto mensual,
   vigencia, RFC arrendador

5. De los estados de cuenta, identifica los pagos de renta
   realizados

Crea una tabla comparativa con esta informacion.
```

**Resultado de extraccion:**
```
[Copia aqui la tabla que genero la IA]
```

**2.3 Analisis de discrepancias (3 minutos)**

Prompt de seguimiento:
```
Ahora compara:

1. ¿El total de gastos declarados coincide con el estado de
   resultados?

2. ¿Las facturas de gastos suman un monto coherente con lo
   declarado?

3. ¿Los pagos de renta en estados de cuenta coinciden con el
   contrato y las facturas?

4. ¿Hay alguna factura que no cumpla requisitos fiscales?

5. Identifica cualquier discrepancia o area de riesgo.

Lista los hallazgos en orden de importancia.
```

**Hallazgos identificados:**
```
[Copia los hallazgos]
```

**2.4 Recomendaciones (2 minutos)**

Prompt final:
```
Basado en tu analisis, proporciona 3 recomendaciones
especificas para este cliente sobre:
- Documentacion faltante
- Riesgos identificados
- Acciones correctivas
```

**Recomendaciones:**
```
[Copia las recomendaciones]
```

### Paso 3: Evalua el Proceso (2 minutos)

Reflexion personal:

**¿Que funciono bien en el proceso multimodal?**
```

```

**¿Que limitaciones encontraste?**
```

```

**¿Cuanto tiempo habria tomado esto manualmente?**
```

```

**¿Cuanto tiempo tomo con IA?**
```

```

---

## Ejercicio 4 (BONUS): Comparacion de Herramientas (15 minutos)

### Objetivo
Comparar capacidades multimodales de diferentes herramientas.

### Instrucciones

**Toma 3-5 de tus documentos y procesalos en DOS herramientas diferentes:**

**Opcion 1: Claude vs ChatGPT**
**Opcion 2: Claude vs Gemini**
**Opcion 3: ChatGPT vs Gemini**

**Usa el mismo prompt en ambas:**
```
Analiza estos documentos y extrae:
1. Datos financieros clave
2. Fechas importantes
3. Montos totales
4. Cualquier discrepancia

Presenta en tabla comparativa.
```

**Comparacion de resultados:**

| Aspecto | Herramienta 1: _____ | Herramienta 2: _____ |
|---------|---------------------|---------------------|
| Precision en extraccion | | |
| Manejo de imagenes | | |
| Procesamiento de Excel | | |
| Contexto (cuantos docs acepto) | | |
| Velocidad | | |
| Facilidad de uso | | |
| Calidad de respuesta | | |

**Mi conclusion:**
```
Para casos multimodales, prefiero __________ porque:

```

---

## Problemas Comunes y Soluciones

### Problema 1: "La IA no lee bien mi imagen escaneada"
**Solucion:**
- Mejora la calidad de la imagen (contraste, resolucion)
- Intenta con otra herramienta (Claude vs ChatGPT)
- Si es critico, usa OCR especializado primero
- Pide a la IA que te diga que puede ver para diagnosticar

### Problema 2: "No extrae correctamente datos de mi Excel"
**Solucion:**
- Exporta el Excel como PDF y sube ambos
- Describe la estructura de tu hoja de calculo
- Especifica en que hoja/celda esta cada dato
- Si es muy complejo, usa Gemini con integracion a Sheets

### Problema 3: "Procesa solo algunos archivos, ignora otros"
**Solucion:**
- Subelos en lotes mas pequeños
- Nombra archivos descriptivamente
- Menciona explicitamente que documentos subiste
- Pregunta "¿Cuantos documentos ves?"

### Problema 4: "Las respuestas tienen errores en numeros"
**Solucion:**
- Siempre verifica numeros criticos manualmente
- Pide que muestre de donde extrajo cada numero
- Procesa documentos financieros de uno en uno para precision
- Usa Code Interpreter de ChatGPT para calculos

---

## Checklist de Finalizacion

- [ ] Organice documentos en diferentes formatos
- [ ] Cree un proyecto multimodal en Claude o ChatGPT
- [ ] Practique extraccion de datos de PDFs, imagenes y Excel
- [ ] Ejecute un caso integrado completo
- [ ] Compare precision entre al menos 2 herramientas
- [ ] Identifique limitaciones del procesamiento multimodal
- [ ] Documente mi workflow preferido para casos multimodales

---

## Reflexion Final

### Antes vs Despues

**Antes de este ejercicio, ¿como procesabas documentos multiples?**
```

```

**¿Que caso de uso multimodal implementaras primero en tu practica?**
```

```

**¿Que precauciones tomaras con datos sensibles?**
```

```

---

## Preparacion para Dia 11

**Dia 11: Diseña tu Sitio Web**

El proximo dia aprenderas a crear tu sitio web profesional con HTML y CSS sin saber programar, usando IA para generar todo el codigo.

**Para prepararte:**
- Piensa que informacion quieres en tu sitio web profesional
- Que servicios ofreces que quieras destacar
- Ten a la mano logos o imagenes que quieras usar
- Define tu propuesta de valor como contador

---

**¿Completaste los ejercicios?** Excelente. Ahora dominas el procesamiento multimodal, una habilidad que muy pocos contadores tienen. Nos vemos en el Dia 11.
