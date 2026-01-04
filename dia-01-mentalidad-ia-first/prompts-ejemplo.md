# Prompts de Ejemplo para Contadores
## Día 1: Mentalidad IA-First

Estos prompts están listos para copiar, pegar y adaptar a tus necesidades específicas.

---

## La Fórmula Universal

```
ROL + CONTEXTO + TAREA + FORMATO
```

Todos los prompts siguientes usan esta estructura para obtener mejores resultados.

---

## Categoría 1: Consultas Fiscales

### Prompt 1.1: Análisis de Deducibilidad
**Herramienta recomendada:** Claude (análisis) o Gemini (si necesitas info actualizada)

```
Actúa como un contador fiscal especialista en México.

CONTEXTO:
Mi cliente es [TIPO DE CONTRIBUYENTE: persona física con actividad empresarial /
persona moral / RESICO] del sector [GIRO DEL NEGOCIO].

CONSULTA:
Quiere saber si puede deducir [DESCRIPCIÓN DEL GASTO].

NECESITO QUE ME INDIQUES:
1. Si es deducible o no, y bajo qué condiciones
2. El porcentaje o límite de deducción aplicable
3. Los requisitos documentales (CFDI, contratos, etc.)
4. El fundamento legal (artículos de LISR, CFF)
5. Recomendaciones prácticas para el cliente

Responde de forma estructurada y práctica.
```

### Prompt 1.2: Comparativo de Regímenes
**Herramienta recomendada:** ChatGPT

```
Actúa como asesor fiscal en México.

Mi cliente es [DESCRIPCIÓN: médico, abogado, comerciante, etc.] con ingresos
anuales aproximados de $[MONTO].

Prepara una comparación entre RESICO y Régimen de Actividades Empresariales
y Profesionales que incluya:

1. Requisitos para tributar en cada uno
2. Tasa de ISR aplicable
3. Obligaciones fiscales (declaraciones, contabilidad)
4. Deducciones permitidas
5. Ventajas y desventajas de cada uno
6. Mi recomendación basada en su perfil

Presenta la información en una tabla comparativa seguida de tu recomendación.
```

### Prompt 1.3: Tratamiento de Ingresos
**Herramienta recomendada:** Claude

```
Soy contador público en México. Necesito analizar el tratamiento fiscal de
los siguientes ingresos:

SITUACIÓN:
[Describe la situación específica del cliente y los tipos de ingresos]

ANALIZA:
1. Clasificación de cada ingreso (gravado, exento, no objeto)
2. Momento de acumulación
3. Retenciones aplicables
4. Fundamento legal
5. Obligaciones formales derivadas

Estructura tu respuesta por tipo de ingreso.
```

---

## Categoría 2: Redacción de Documentos

### Prompt 2.1: Correo a Cliente (Explicación de Impuestos)
**Herramienta recomendada:** ChatGPT

```
Actúa como contador público. Redacta un correo profesional pero accesible
para mi cliente.

SITUACIÓN:
[Describe qué necesitas explicar al cliente]

EL CORREO DEBE:
- Ser claro y evitar tecnicismos innecesarios
- Explicar el "por qué" de manera simple
- Incluir los próximos pasos si los hay
- Tener un tono profesional pero cercano
- Ser breve (máximo 3-4 párrafos)

Incluye línea de asunto sugerida.
```

### Prompt 2.2: Oficio de Respuesta al SAT
**Herramienta recomendada:** Claude

```
Actúa como contador público especialista en procedimientos fiscales en México.

CONTEXTO:
Recibí un requerimiento del SAT con folio [NÚMERO] de fecha [FECHA].
El SAT solicita: [DESCRIPCIÓN DE LO SOLICITADO]

SITUACIÓN DEL CLIENTE:
[Explica los antecedentes relevantes]

REDACTA:
Un oficio de respuesta formal que incluya:
1. Datos de identificación (dejar espacios para completar)
2. Referencia al requerimiento
3. Respuesta punto por punto a lo solicitado
4. Lista de documentos que se anexan
5. Cierre formal

El tono debe ser respetuoso, formal y técnicamente preciso.
```

### Prompt 2.3: Propuesta de Servicios Contables
**Herramienta recomendada:** ChatGPT

```
Actúa como contador público que busca nuevos clientes.

PERFIL DEL PROSPECTO:
- Tipo de negocio: [GIRO]
- Tamaño aproximado: [PEQUEÑO/MEDIANO]
- Régimen fiscal: [SI LO CONOCES]
- Necesidades detectadas: [LISTA]

REDACTA:
Una propuesta de servicios que incluya:
1. Introducción breve y profesional
2. Servicios que ofrezco (alineados a sus necesidades)
3. Beneficios de trabajar conmigo
4. Esquema de honorarios sugerido (dejar espacio para montos)
5. Siguiente paso / llamado a la acción

El tono debe ser profesional, confiable y orientado a generar confianza.
Máximo 1 página.
```

---

## Categoría 3: Análisis de Documentos

### Prompt 3.1: Revisión de Contrato
**Herramienta recomendada:** Claude (subir el documento)

```
Actúa como contador fiscal especialista en contratos en México.

Analiza el contrato adjunto y proporciona:

1. RESUMEN EJECUTIVO (1 párrafo)
   - Tipo de contrato y partes involucradas
   - Objeto principal

2. IMPLICACIONES FISCALES
   - Retenciones de ISR/IVA aplicables
   - Obligaciones de facturación
   - Momentos de causación de impuestos

3. CLÁUSULAS DE RIESGO
   - Identifica cláusulas que puedan generar contingencias fiscales
   - Señala ambigüedades o términos problemáticos

4. RECOMENDACIONES
   - Modificaciones sugeridas
   - Puntos a negociar
   - Documentación adicional necesaria

[SUBIR CONTRATO PDF]
```

### Prompt 3.2: Análisis de Estados Financieros
**Herramienta recomendada:** ChatGPT o Claude

```
Actúa como analista financiero con experiencia en México.

Te proporciono los siguientes estados financieros:
[PEGAR DATOS O DESCRIBIR CIFRAS PRINCIPALES]

REALIZA:
1. Análisis de razones financieras principales
   - Liquidez
   - Apalancamiento
   - Rentabilidad
   - Eficiencia

2. Identificación de banderas rojas o áreas de preocupación

3. Comparación con promedios del sector [SI APLICA]

4. Recomendaciones concretas

Presenta los resultados en formato ejecutivo para presentar a dirección.
```

---

## Categoría 4: Cálculos Explicados

### Prompt 4.1: Cálculo de ISR
**Herramienta recomendada:** ChatGPT

```
Actúa como contador fiscal en México.

DATOS:
- Tipo de contribuyente: [PERSONA FÍSICA/MORAL]
- Período: [MES/AÑO]
- Ingresos del período: $[MONTO]
- Deducciones autorizadas: $[MONTO]
- [OTROS DATOS RELEVANTES]

CALCULA:
El ISR a pagar mostrando:
1. Procedimiento paso a paso
2. Aplicación de la tarifa correspondiente
3. Fundamento legal de cada paso
4. Resultado final
5. Verificación del cálculo

Presenta el procedimiento de forma que pueda explicarlo a mi cliente.
```

### Prompt 4.2: Cálculo de Nómina
**Herramienta recomendada:** ChatGPT

```
Actúa como especialista en nóminas en México.

DATOS DEL TRABAJADOR:
- Salario mensual: $[MONTO]
- Período de pago: [SEMANAL/QUINCENAL/MENSUAL]
- Prestaciones adicionales: [LISTA]
- Antigüedad: [AÑOS]

CALCULA:
1. Salario diario integrado (SDI)
2. Cuotas IMSS (patronales y del trabajador)
3. ISR a retener
4. Percepciones totales
5. Deducciones totales
6. Neto a pagar

Muestra el procedimiento completo y las bases legales.
```

---

## Categoría 5: Investigación

### Prompt 5.1: Búsqueda de Fundamento Legal
**Herramienta recomendada:** Gemini (para info actualizada) + Claude (para análisis)

```
Necesito encontrar el fundamento legal para la siguiente situación fiscal
en México:

SITUACIÓN:
[Describe el caso específico]

BUSCO:
1. Artículos de ley aplicables (LISR, LIVA, CFF, etc.)
2. Reglas de la Resolución Miscelánea Fiscal relacionadas
3. Criterios del SAT relevantes
4. Jurisprudencia o tesis si existe

Proporciona las referencias específicas con sus extractos relevantes.
```

### Prompt 5.2: Resumen de Cambios Fiscales
**Herramienta recomendada:** Gemini

```
Dame un resumen de los principales cambios fiscales en México para [AÑO]
que afecten a [TIPO DE CONTRIBUYENTE].

INCLUYE:
1. Cambios en tasas o límites
2. Nuevas obligaciones
3. Obligaciones eliminadas o simplificadas
4. Fechas importantes
5. Impacto práctico para mis clientes

Cita las fuentes oficiales (DOF, SAT) cuando sea posible.
```

---

## Categoría 6: Automatización y Plantillas

### Prompt 6.1: Crear Plantilla de Documento
**Herramienta recomendada:** ChatGPT

```
Crea una plantilla profesional para [TIPO DE DOCUMENTO: opinión, carta,
informe, etc.] que pueda reutilizar con diferentes clientes.

CARACTERÍSTICAS:
- Uso: [DESCRIBIR SITUACIÓN TÍPICA]
- Tono: [FORMAL/SEMI-FORMAL/TÉCNICO]
- Extensión aproximada: [CORTO/MEDIO/LARGO]

LA PLANTILLA DEBE INCLUIR:
1. Estructura clara con secciones definidas
2. Marcadores [ENTRE CORCHETES] donde debo insertar datos específicos
3. Texto base que pueda mantener sin cambios
4. Opciones de párrafos alternativos cuando aplique
5. Notas de uso para mí (qué información necesito tener)
```

### Prompt 6.2: Crear Checklist
**Herramienta recomendada:** ChatGPT

```
Crea un checklist completo para [PROCESO: declaración anual, alta de cliente,
cierre mensual, etc.].

EL CHECKLIST DEBE INCLUIR:
1. Pasos en orden cronológico
2. Documentos necesarios en cada paso
3. Responsable sugerido (contador, cliente, auxiliar)
4. Fechas límite típicas (si aplica)
5. Verificaciones de calidad
6. Errores comunes a evitar

Formatea como lista con casillas de verificación.
```

---

## Tips para Mejores Resultados

### Sé Específico
```
❌ "Ayúdame con impuestos"
✅ "Calcula el ISR de una persona física RESICO con ingresos de $50,000 en enero 2025"
```

### Da Contexto
```
❌ "¿Esto es deducible?"
✅ "Mi cliente es persona moral del sector comercio. ¿Puede deducir gastos de comidas con clientes por $15,000 mensuales?"
```

### Especifica el Formato
```
❌ "Explícame las retenciones"
✅ "Explícame las retenciones de ISR en arrendamiento. Presenta la información en una tabla con: concepto, tasa, fundamento, y ejemplo numérico"
```

### Pide Verificación
```
"Después de tu respuesta, verifica si hay algún punto que pudiera variar dependiendo de interpretaciones o cambios recientes en la ley."
```

---

## Prompt Maestro (Copia y Adapta)

```
Actúa como [ROL: contador fiscal especialista en México / asesor financiero /
especialista en nóminas].

CONTEXTO:
[Describe la situación, tipo de cliente, antecedentes relevantes]

TAREA:
[Describe específicamente qué necesitas: analizar, calcular, redactar,
explicar, comparar, etc.]

NECESITO QUE INCLUYAS:
1. [Elemento específico 1]
2. [Elemento específico 2]
3. [Elemento específico 3]
4. Fundamento legal cuando aplique

FORMATO DE RESPUESTA:
[Describe cómo quieres la respuesta: tabla, lista, párrafos, paso a paso,
resumen ejecutivo, etc.]

CONSIDERACIONES ADICIONALES:
[Cualquier restricción, preferencia o contexto adicional]
```

---

*Prompts de Ejemplo v1.0 - Reto 12 Días de IA para Contadores*
*TodoConta.com*
