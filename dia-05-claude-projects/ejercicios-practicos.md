# Día 5: Ejercicios Prácticos
## Claude Projects

**Tiempo estimado:** 30-45 minutos
**Objetivo:** Crear tu primer Claude Project y aprender a analizar documentos extensos de forma efectiva.

---

## Requisitos Previos

### Antes de empezar:

1. **Claude Pro activo**
   - Necesitas una suscripción a Claude Pro (20 USD/mes)
   - Verifica en https://claude.ai/settings
   - Si no tienes Pro, puedes hacer el ejercicio teórico y activarlo después

2. **Documento largo preparado**
   - Necesitas un documento de 50+ páginas para analizar
   - Opciones:
     - Contrato largo (arrendamiento, servicios, franquicia)
     - Dictamen fiscal
     - Ley completa (LISR, CFF, LIVA)
     - Estados financieros auditados con notas
   - **Formato:** PDF (preferible) o DOCX

3. **Conocimiento del Día 4**
   - Repasa la estructura de instrucciones del Día 4 (Custom GPTs)
   - Las Custom Instructions de Projects usan la misma lógica

---

## Ejercicio 1: Crear tu Primer Claude Project (25 minutos)

### Objetivo
Crear un Claude Project funcional para analizar un contrato o documento largo.

### Paso 1: Preparar el Documento (3 minutos)

**Selecciona uno de estos casos:**

**Opción A: Contrato de Arrendamiento**
- Si tienes un contrato de arrendamiento de 50+ páginas, úsalo (anonimizado)
- Si no, descarga un modelo de contrato largo de internet

**Opción B: Ley del ISR**
- Descarga la LISR completa del sitio de Diputados
- Es perfecta para práctica porque es larga (200+ páginas)

**Opción C: Dictamen Fiscal**
- Si tienes acceso a un dictamen fiscal (anonimizado)
- Excelente para práctica de análisis

**Nota sobre confidencialidad:**
- Si usas documentos de clientes, anonimiza datos sensibles
- Recuerda que los docs se suben a servidores de Anthropic
- Para este ejercicio, usa documentos públicos o anonimizados

### Paso 2: Acceder a Claude Projects (2 minutos)

1. Ve a https://claude.ai
2. Inicia sesión con tu cuenta Pro
3. En el menú lateral izquierdo, busca "Projects"
4. Haz clic en "Create Project" (o "New Project")

### Paso 3: Configurar el Project (5 minutos)

**Nombre del Project:**

Si elegiste Opción A (Contrato):
```
Análisis Contrato Arrendamiento - Ejercicio Día 5
```

Si elegiste Opción B (LISR):
```
Biblioteca LISR - Consulta Rápida
```

Si elegiste Opción C (Dictamen):
```
Revisión Dictamen Fiscal - Ejercicio Día 5
```

**Custom Instructions:**

Para **Opción A - Contrato de Arrendamiento:**
```
CONTEXTO:
Este proyecto contiene un contrato de arrendamiento para análisis
desde perspectiva fiscal y legal básica.

ROL:
Actúa como asesor fiscal y legal especializado en contratos de
arrendamiento en México. Tu análisis debe enfocarse en:
- Obligaciones fiscales de las partes
- Cláusulas con implicaciones fiscales
- Riesgos potenciales
- Cumplimiento de normativa aplicable

DOCUMENTOS INCLUIDOS:
1. Contrato de arrendamiento completo

AL RESPONDER SIEMPRE:
1. Cita el número de cláusula y página específica
2. Identifica qué parte (arrendador/arrendatario) se ve afectada
3. Menciona el fundamento legal cuando aplique (LISR, LIVA, CFF)
4. Señala riesgos y su nivel (bajo/medio/alto)
5. Usa lenguaje claro pero preciso

FORMATO DE RESPUESTA:
- Respuesta directa a la pregunta
- Cláusula(s) relevante(s) con número de página
- Análisis de implicación fiscal
- Riesgos identificados (si aplica)
- Recomendación o consideración adicional
```

Para **Opción B - Ley del ISR:**
```
CONTEXTO:
Este proyecto contiene la Ley del Impuesto Sobre la Renta (LISR)
completa como biblioteca de consulta rápida para contadores.

ROL:
Actúa como asesor fiscal experto en LISR. Ayudas a contadores a
encontrar, entender y aplicar correctamente los artículos de la ley.

DOCUMENTOS INCLUIDOS:
1. Ley del ISR vigente

AL RESPONDER SIEMPRE:
1. Cita el artículo específico completo
2. Explica en lenguaje claro sin perder precisión técnica
3. Incluye ejemplos numéricos cuando sea relevante
4. Menciona artículos relacionados si existen
5. Advierte sobre excepciones o casos especiales

FORMATO DE RESPUESTA:
- Artículo citado textualmente (si es corto) o resumido (si es largo)
- Explicación en lenguaje claro
- Ejemplo práctico si aplica
- Artículos relacionados
- Consideraciones especiales
```

Para **Opción C - Dictamen Fiscal:**
```
CONTEXTO:
Este proyecto contiene un dictamen fiscal para revisión y análisis
de calidad, consistencia y cumplimiento normativo.

ROL:
Actúa como revisor senior de dictámenes fiscales. Tu trabajo es
identificar áreas de oportunidad, inconsistencias y riesgos.

DOCUMENTOS INCLUIDOS:
1. Dictamen fiscal completo con anexos

AL RESPONDER SIEMPRE:
1. Cita la sección específica y número de página
2. Identifica si es un hallazgo crítico, importante o menor
3. Señala el impacto potencial
4. Sugiere qué revisar o corregir
5. Referencia normativa aplicable (NIF, LISR, CFF)

FORMATO DE RESPUESTA:
- Identificación del hallazgo
- Ubicación específica en el documento
- Nivel de importancia (crítico/importante/menor)
- Impacto potencial
- Recomendación de acción
```

### Paso 4: Subir el Documento (3 minutos)

1. En la sección "Project knowledge", haz clic en "Add content"
2. Selecciona "Upload files"
3. Elige tu documento
4. Espera a que se procese (puede tomar 30-60 segundos para docs largos)
5. Verifica que aparezca en la lista de documentos del proyecto

**Indicador de éxito:** Verás el documento listado con su nombre y tamaño

### Paso 5: Crear Primera Conversación (2 minutos)

1. Haz clic en "New chat" dentro del proyecto
2. La conversación automáticamente tiene acceso a:
   - Las Custom Instructions que configuraste
   - El documento que subiste

**Importante:** Todas las conversaciones futuras en este proyecto tendrán el mismo acceso

### Paso 6: Primera Pregunta - Resumen General (5 minutos)

Empieza siempre con una pregunta amplia para obtener un mapa del documento:

**Para Contrato:**
```
Proporciona un resumen estructurado de este contrato que incluya:
1. Tipo de contrato y partes involucradas
2. Objeto del contrato
3. Obligaciones fiscales principales de cada parte
4. Cláusulas que requieren atención especial desde perspectiva fiscal
5. Riesgos potenciales identificados

Incluye números de página para cada punto.
```

**Para LISR:**
```
Proporciona un mapa de la estructura de esta ley:
1. Títulos y sus temas principales
2. Capítulos más relevantes para personas morales
3. Capítulos más relevantes para personas físicas
4. Artículos clave que todo contador debe conocer
5. Secciones sobre regímenes especiales

Incluye números de artículo.
```

**Para Dictamen:**
```
Proporciona un resumen ejecutivo del dictamen que incluya:
1. Tipo de entidad y ejercicio dictaminado
2. Principales cifras financieras y fiscales
3. Áreas de mayor complejidad
4. Salvedades u observaciones (si las hay)
5. Puntos que requieren revisión detallada

Incluye referencias de sección y página.
```

**Evaluación:**
- [ ] Claude leyó y procesó el documento completo
- [ ] El resumen es coherente con el contenido
- [ ] Incluyó números de página o artículo
- [ ] Identificó puntos clave relevantes

### Paso 7: Preguntas Específicas (5 minutos)

Ahora haz 3 preguntas específicas según tu documento:

**Para Contrato - Preguntas sugeridas:**

Pregunta 1:
```
¿Qué obligaciones de retención de impuestos se mencionan en el contrato?
Cita la cláusula específica y explica qué impuesto y a qué tasa.
```

Pregunta 2:
```
Identifica todas las cláusulas que mencionan pagos, contraprestaciones
o cantidades. Lista cada una con su número y monto si aplica.
```

Pregunta 3:
```
¿Hay alguna cláusula que pueda generar riesgo fiscal para el arrendatario?
Evalúa el nivel de riesgo y explica por qué.
```

**Para LISR - Preguntas sugeridas:**

Pregunta 1:
```
¿Qué dice el artículo 28 sobre deducciones no autorizadas?
Lista las fracciones más relevantes para empresas de servicios.
```

Pregunta 2:
```
Busca todos los artículos que mencionen "partes relacionadas".
Lista cada artículo con un resumen de una línea.
```

Pregunta 3:
```
Compara el tratamiento de deducciones entre el Título II (personas morales)
y el Título IV (personas físicas con actividad empresarial). ¿Cuáles son
las diferencias principales?
```

**Para Dictamen - Preguntas sugeridas:**

Pregunta 1:
```
¿Hay alguna inconsistencia entre las cifras presentadas en diferentes
secciones del dictamen? Revisa especialmente conciliación contable-fiscal.
```

Pregunta 2:
```
¿El dictamen menciona o analiza operaciones con partes relacionadas?
¿Qué dice al respecto?
```

Pregunta 3:
```
Identifica los 5 conceptos de mayor impacto en la determinación del ISR.
Lista con cifras y breve explicación.
```

**Evaluación por pregunta:**
- [ ] Claude citó la ubicación específica (página/cláusula/artículo)
- [ ] La respuesta fue precisa y fundamentada
- [ ] Identificó información que sería difícil encontrar manualmente
- [ ] El tono y formato siguieron las Custom Instructions

---

## Ejercicio 2: Los 5 Tipos de Preguntas (10 minutos)

### Objetivo
Practicar los cinco tipos de preguntas efectivas en Claude Projects.

### Instrucciones

Usando el mismo proyecto del Ejercicio 1, haz una pregunta de cada tipo:

**Tipo 1: Búsqueda Específica**
```
[Ajusta según tu documento]
Ejemplo para contrato: "¿Qué dice exactamente la cláusula 15?"
Ejemplo para LISR: "Transcribe el artículo 27 fracción V"
Ejemplo para dictamen: "¿Cuál es el saldo de clientes reportado?"
```

**Tipo 2: Análisis Comparativo**
```
[Si tienes múltiples documentos o secciones]
Ejemplo para contrato: "Compara las obligaciones del arrendador vs arrendatario"
Ejemplo para LISR: "Compara el Título II artículo 25 con el Título IV artículo 103"
Ejemplo para dictamen: "Compara el ISR causado vs ISR pagado en el ejercicio"
```

**Tipo 3: Identificación de Patrones**
```
[Busca patrones o problemas]
Ejemplo para contrato: "¿Hay cláusulas contradictorias en el contrato?"
Ejemplo para LISR: "¿Qué artículos se refieren a deducciones de inversiones?"
Ejemplo para dictamen: "¿Hay tendencias preocupantes en los últimos 3 ejercicios?"
```

**Tipo 4: Extracción Estructurada**
```
[Pide una lista o tabla]
Ejemplo para contrato: "Lista todas las fechas importantes mencionadas en formato tabla"
Ejemplo para LISR: "Lista todos los porcentajes de retención mencionados en el Título V"
Ejemplo para dictamen: "Crea una tabla con todos los impuestos: causado, pagado, saldo"
```

**Tipo 5: Síntesis**
```
[Pide resumen o conclusión]
Ejemplo para contrato: "Resume en 3 bullets los riesgos fiscales TOP del contrato"
Ejemplo para LISR: "Resume las obligaciones fiscales de una PM del Título II"
Ejemplo para dictamen: "Resume la salud fiscal de la entidad en un párrafo"
```

### Evaluación

| Tipo de Pregunta | Funcionó Bien | Qué Mejorarías |
|-----------------|---------------|----------------|
| Búsqueda Específica | [ ] | |
| Análisis Comparativo | [ ] | |
| Identificación de Patrones | [ ] | |
| Extracción Estructurada | [ ] | |
| Síntesis | [ ] | |

---

## Ejercicio 3: Comparación de Tiempo (5 minutos)

### Objetivo
Cuantificar el ahorro de tiempo usando Claude Projects.

### Instrucciones

**Paso 1: Elige una tarea de búsqueda**

Ejemplo:
- "Encuentra todas las cláusulas que mencionen 'impuestos' en el contrato"
- "Lista todos los artículos de la LISR que hablan de arrendamiento"
- "Identifica todas las partidas fiscales no deducibles en el dictamen"

**Paso 2: Mide el tiempo manualmente**

1. Abre el documento en PDF
2. Inicia un cronómetro
3. Busca la información manualmente (usa Ctrl+F si quieres)
4. Detén el cronómetro cuando tengas la lista completa
5. Anota el tiempo: _______ minutos

**Paso 3: Mide el tiempo con Claude**

1. Inicia un cronómetro
2. Haz la misma pregunta a Claude en tu proyecto
3. Detén el cronómetro cuando Claude termine de responder
4. Anota el tiempo: _______ minutos

**Paso 4: Calcula el ahorro**

```
Tiempo manual: _______ minutos
Tiempo con Claude: _______ minutos
Ahorro: _______ minutos
Porcentaje de reducción: _______%
```

### Reflexión

- ¿El ahorro de tiempo fue significativo?
- ¿Claude encontró algo que tú no viste en búsqueda manual?
- ¿En qué tipo de documentos tiene más impacto este ahorro?

---

## Ejercicio 4 (BONUS): Crear Biblioteca Legal Personal (15 minutos)

### Objetivo
Crear tu propia biblioteca legal en Claude para consulta diaria.

### Instrucciones

**Paso 1: Crear el Project**

- **Nombre:** Mi Biblioteca Fiscal México 2024
- **Custom Instructions:**

```
CONTEXTO:
Esta es mi biblioteca legal personal con las leyes fiscales que
consulto más frecuentemente en mi práctica profesional.

ROL:
Actúa como mi asesor fiscal personal. Conozco los temas, solo
necesito recordar artículos específicos, encontrar fundamento
legal o aclarar interpretaciones.

DOCUMENTOS INCLUIDOS:
[Lista los que subas, por ejemplo:]
1. Ley del Impuesto Sobre la Renta (LISR)
2. Código Fiscal de la Federación (CFF)
3. Ley del IVA (LIVA)
4. Reglamento de la LISR (RLISR)

AL RESPONDER:
1. Cita el artículo completo si es corto (<200 palabras)
2. Resume si es muy largo pero mantén precisión
3. Usa lenguaje directo, no necesitas explicarme desde cero
4. Menciona artículos relacionados si son relevantes
5. Advierte si hay actualizaciones recientes (si las sabes)

FORMATO DE RESPUESTA:
- Artículo citado
- Interpretación práctica
- Artículos relacionados (si aplica)
- Consideraciones especiales
```

**Paso 2: Descargar las leyes**

Descarga los PDFs oficiales de:
1. **LISR:** http://www.diputados.gob.mx/LeyesBiblio/pdf/LISR.pdf
2. **CFF:** http://www.diputados.gob.mx/LeyesBiblio/pdf/8_090121.pdf
3. **LIVA:** http://www.diputados.gob.mx/LeyesBiblio/pdf/77.pdf

**Paso 3: Subir los documentos**

1. Sube las 3 leyes al proyecto
2. Puede tomar 1-2 minutos procesar todo
3. Verifica que las 3 aparezcan en "Project knowledge"

**Paso 4: Prueba tu biblioteca**

Haz 5 preguntas que normalmente tendrías que buscar manualmente:

```
1. ¿Qué dice el artículo 28 LISR sobre deducciones no autorizadas?

2. ¿Cuál es la tasa de retención para honorarios según LISR?

3. ¿Qué requisitos de deducción establece el artículo 27 LISR?

4. ¿Cuál es el plazo para aclaración de discrepancias en CFF?

5. ¿Qué actividades están exentas de IVA según la LIVA?
```

**Paso 5: Guarda el proyecto**

Este proyecto ahora es tu biblioteca permanente. Cada vez que necesites consultar legislación fiscal, abre este proyecto y pregunta.

---

## Problemas Comunes y Soluciones

### Problema 1: "No tengo Claude Pro"
**Solución:**
- Haz el ejercicio teórico diseñando las Custom Instructions
- Considera si el costo (20 USD/mes) se justifica con el ahorro de tiempo
- Prueba Claude gratuito con conversaciones normales mientras decides

### Problema 2: "El documento es demasiado largo y no se sube"
**Solución:**
- Límite de Claude: aproximadamente 200 páginas
- Si tu documento es más largo, divídelo en partes
- O sube solo las secciones más relevantes
- Comprime el PDF si tiene muchas imágenes

### Problema 3: "Claude no encuentra información que sé que está en el documento"
**Solución:**
- Reformula la pregunta de manera más específica
- Pide que busque en una sección particular
- Verifica que el documento se haya procesado correctamente
- A veces documentos escaneados (imágenes) no se leen bien

### Problema 4: "Las respuestas no siguen las Custom Instructions"
**Solución:**
- Refuerza las instrucciones haciéndolas más específicas
- En la pregunta misma, recuérdale: "Siguiendo las instrucciones del proyecto..."
- Revisa que las instrucciones no sean contradictorias

### Problema 5: "No estoy seguro si puedo subir documentos de clientes"
**Solución:**
- Lee los términos de servicio de Claude sobre privacidad
- Para práctica, usa documentos públicos o ejemplos
- Anonimiza datos sensibles antes de subir
- Para casos ultra sensibles, considera no usar servicios cloud

---

## Checklist de Finalización

- [ ] Creé mi primer Claude Project
- [ ] Configuré Custom Instructions efectivas
- [ ] Subí un documento de 50+ páginas exitosamente
- [ ] Hice análisis con los 5 tipos de preguntas
- [ ] Comparé tiempo de análisis manual vs Claude
- [ ] Cuantifiqué el ahorro de tiempo
- [ ] [BONUS] Creé mi biblioteca legal personal
- [ ] Identifiqué 3 casos de mi práctica donde usaré Claude Projects

---

## Reflexión Final

Antes de continuar al Día 6, reflexiona:

1. **¿Cuánto tiempo me ahorraría Claude Projects en mi semana típica?**
2. **¿Qué tipo de documentos analizo regularmente que son buenos candidatos?**
3. **¿Cómo cambiaría mi capacidad de análisis si puedo procesar 10x más documentos?**
4. **¿Qué servicios podría ofrecer que antes no podía por limitaciones de tiempo?**

Claude Projects no reemplaza tu criterio profesional. Te da la capacidad de procesar información a una velocidad que manualmente sería imposible.

Tu valor como contador no está en leer documentos, está en interpretar, aplicar criterio experto y tomar decisiones informadas.

Claude lee por ti. Tú decides.

---

**¿Completaste los ejercicios?** Estás listo para el Día 6: Gemini + Google Workspace, donde aprenderás a integrar IA directamente con Drive, Sheets y Docs.
