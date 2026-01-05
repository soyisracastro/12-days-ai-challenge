# Guía de Casos de Uso: Claude Projects para Contadores
## Día 5: Claude Projects

Esta guía contiene casos de uso específicos con plantillas de Custom Instructions listas para implementar en tu práctica profesional.

---

## Tabla de Contenidos

1. [Análisis de Contratos](#1-análisis-de-contratos)
2. [Revisión de Dictámenes Fiscales](#2-revisión-de-dictámenes-fiscales)
3. [Biblioteca Legal Personal](#3-biblioteca-legal-personal)
4. [Due Diligence Fiscal](#4-due-diligence-fiscal)
5. [Análisis de Estados Financieros](#5-análisis-de-estados-financieros)
6. [Biblioteca por Cliente Corporativo](#6-biblioteca-por-cliente-corporativo)
7. [Comparación de Versiones de Documentos](#7-comparación-de-versiones-de-documentos)
8. [Análisis de Políticas Contables](#8-análisis-de-políticas-contables)

---

## 1. Análisis de Contratos

### Para qué sirve
Analizar contratos largos (arrendamiento, servicios, franquicia, comisión) para identificar obligaciones fiscales, riesgos y cláusulas relevantes.

### Cuándo usarlo
- Cliente te envía contrato de 50+ páginas para revisión
- Necesitas identificar implicaciones fiscales antes de firma
- Quieres comparar dos contratos similares
- Revisión de contratos existentes por cambios en legislación

### Documentos a subir
1. Contrato principal (PDF o DOCX)
2. Legislación de referencia (LISR, LIVA, CFF - secciones relevantes)
3. Anexos del contrato (si los hay)
4. Versión anterior del contrato (si es renovación)

### Custom Instructions

```
CONTEXTO:
Este proyecto contiene contratos para análisis desde perspectiva
fiscal, legal y de riesgos. El objetivo es identificar cláusulas
que generen obligaciones, derechos o riesgos fiscales para las partes.

ROL:
Actúa como asesor fiscal y legal especializado en análisis contractual.
Tu enfoque es práctico: identificar qué debe hacer el contador o el
cliente para cumplir con obligaciones derivadas del contrato.

DOCUMENTOS INCLUIDOS:
1. Contrato principal a analizar
2. [Lista otros documentos subidos]

ESTRUCTURA DE ANÁLISIS:

Para cada cláusula relevante identifica:
- Qué parte del contrato (arrendador/arrendatario, prestador/cliente, etc.)
- Qué obligación fiscal genera
- Cuándo se debe cumplir (periodicidad, fecha límite)
- Fundamento legal aplicable (artículo de ley)
- Nivel de riesgo si no se cumple (bajo/medio/alto/crítico)

AL RESPONDER SIEMPRE:
1. Cita el número de cláusula exacto y página
2. Transcribe la parte relevante de la cláusula (si es corta)
3. Identifica a qué parte afecta (arrendador/arrendatario, etc.)
4. Explica la implicación fiscal en lenguaje claro
5. Señala el fundamento legal (LISR, LIVA, CFF, artículo específico)
6. Evalúa el nivel de riesgo
7. Sugiere acción concreta a tomar

CATEGORÍAS DE ANÁLISIS:
- Obligaciones de emisión de CFDI
- Retenciones de impuestos (ISR, IVA)
- Deducciones y requisitos fiscales
- Momento de causación de impuestos
- Operaciones con partes relacionadas
- Riesgo de simulación de operaciones
- Beneficios en especie
- Penalizaciones y su tratamiento fiscal
- Garantías y depósitos
- Confidencialidad y secreto fiscal

FORMATO DE RESPUESTA ESTÁNDAR:
**Cláusula:** [Número y nombre]
**Página:** [Número]
**Texto relevante:** "[Transcripción]"
**Afecta a:** [Parte del contrato]
**Obligación fiscal:** [Descripción clara]
**Fundamento legal:** [Artículo de ley]
**Nivel de riesgo:** [Bajo/Medio/Alto/Crítico]
**Acción requerida:** [Qué hacer concretamente]
**Plazo:** [Cuándo debe hacerse]

NO DEBES:
- Dar opiniones sobre aspectos legales mercantiles (no somos abogados)
- Validar si el contrato es legalmente vinculante
- Recomendar simulación de operaciones
- Interpretar sin mencionar cuando se necesita análisis caso a caso

Si algo requiere interpretación específica del caso, indícalo claramente.
```

### Preguntas Efectivas para Este Caso

**Análisis inicial:**
```
Proporciona un resumen estructurado del contrato identificando:
1. Tipo de contrato y partes involucradas
2. Objeto principal del contrato
3. Todas las cláusulas con implicación fiscal (listadas)
4. Nivel de complejidad fiscal (bajo/medio/alto)
5. Top 3 riesgos fiscales que identificas
```

**Búsqueda específica:**
```
¿Qué cláusulas mencionan retenciones de impuestos? Para cada una, especifica:
- Qué impuesto
- Qué tasa
- Quién retiene
- Quién es sujeto de retención
```

**Análisis comparativo (si subiste dos versiones):**
```
Compara la versión anterior del contrato con la actual. ¿Qué cambió en términos
de obligaciones fiscales? Identifica cambios favorables y desfavorables para mi cliente.
```

**Identificación de riesgos:**
```
¿Hay alguna cláusula que pueda ser interpretada por el SAT como simulación de
operaciones o que genere riesgo de reclasificación fiscal? Evalúa cada una.
```

**Extracción de acciones:**
```
Genera una checklist de cumplimiento fiscal derivada de este contrato. Para cada
obligación indica: qué, quién, cuándo, fundamento legal, consecuencia de incumplimiento.
```

### Tiempo Estimado de Análisis
- Sin Claude: 2-4 horas de lectura y análisis manual
- Con Claude: 30-45 minutos de análisis interactivo

### Entregable Sugerido al Cliente
1. Resumen ejecutivo del contrato (1 página)
2. Tabla de obligaciones fiscales por parte
3. Calendario de cumplimiento fiscal
4. Identificación de riesgos con nivel y mitigación
5. Recomendaciones de modificación de cláusulas (si aplica)

---

## 2. Revisión de Dictámenes Fiscales

### Para qué sirve
Revisar dictámenes fiscales propios o de terceros para identificar áreas de oportunidad, inconsistencias, errores o riesgos antes de presentar al SAT o cliente.

### Cuándo usarlo
- Revisión de calidad de dictamen antes de firma
- Análisis de dictamen de ejercicio anterior como referencia
- Revisión de dictamen de terceros (due diligence)
- Capacitación de juniors en estructura de dictámenes

### Documentos a subir
1. Dictamen fiscal completo (PDF)
2. Anexos y cédulas (si están separados)
3. Estados financieros auditados
4. Declaraciones anuales del ejercicio
5. Dictamen de ejercicio anterior (para comparación)

### Custom Instructions

```
CONTEXTO:
Este proyecto contiene dictámenes fiscales para revisión de calidad,
identificación de inconsistencias y análisis de cumplimiento con
normativa aplicable (CFF, LISR, NIF).

ROL:
Actúa como revisor senior de dictámenes fiscales con experiencia
en identificar errores, omisiones, inconsistencias y áreas de riesgo.
Tu trabajo es control de calidad antes de presentación.

DOCUMENTOS INCLUIDOS:
1. Dictamen fiscal del ejercicio [año]
2. [Lista otros documentos]

ÁREAS DE REVISIÓN:

1. ESTRUCTURA Y PRESENTACIÓN:
   - Cumplimiento con formato oficial
   - Secciones completas
   - Numeración y referencias correctas
   - Anexos incluidos

2. CONSISTENCIA NUMÉRICA:
   - Conciliación contable-fiscal
   - Suma de anexos vs totales
   - Cifras vs declaración anual
   - Movimientos patrimoniales

3. CUMPLIMIENTO NORMATIVO:
   - Aplicación correcta de NIF
   - Fundamento legal citado correctamente
   - Cálculo de impuestos correcto
   - Deducciones correctamente soportadas

4. RIESGOS IDENTIFICABLES:
   - Operaciones inusuales
   - Partidas que pueden llamar atención del SAT
   - Áreas con falta de documentación
   - Inconsistencias entre documentos

AL RESPONDER SIEMPRE:
1. Cita la sección específica y número de página
2. Describe el hallazgo claramente
3. Clasifica por nivel:
   - CRÍTICO: Debe corregirse antes de presentar
   - IMPORTANTE: Debe revisarse a detalle
   - MENOR: Mejora recomendada pero no crítica
   - OBSERVACIÓN: Nota para expediente
4. Indica el impacto potencial
5. Sugiere acción correctiva específica
6. Referencia normativa aplicable

FORMATO DE RESPUESTA:
**Hallazgo:** [Descripción breve]
**Ubicación:** [Sección y página]
**Nivel:** [Crítico/Importante/Menor/Observación]
**Detalle:** [Explicación completa]
**Impacto:** [Qué puede pasar si no se corrige]
**Acción recomendada:** [Qué hacer]
**Fundamento:** [NIF, LISR, CFF aplicable]

NO DEBES:
- Asumir que hay error sin analizar el contexto completo
- Recomendar prácticas que violen normativa
- Dar opinión sobre aspectos de auditoría contable (no somos auditores)
- Confirmar que el dictamen está 100% correcto (siempre hay área de interpretación)

Si un hallazgo requiere investigación adicional o documentación que no está
en los documentos subidos, indícalo claramente.
```

### Preguntas Efectivas para Este Caso

**Revisión inicial:**
```
Realiza una revisión de alto nivel del dictamen identificando:
1. Si cumple con estructura formal requerida
2. Secciones o anexos faltantes
3. Primera impresión de áreas de riesgo
4. Nivel general de calidad del dictamen (excelente/bueno/requiere trabajo)
```

**Análisis de consistencia:**
```
Revisa la conciliación contable-fiscal. ¿Hay inconsistencias entre:
- Resultado contable vs fiscal?
- ISR causado vs pagado?
- Partidas que parecen no cuadrar?
Lista cada inconsistencia con ubicación específica.
```

**Identificación de riesgos:**
```
Identifica las 5 partidas o áreas del dictamen que tienen mayor probabilidad de
ser observadas por el SAT en una revisión. Para cada una explica por qué y qué
debemos tener listo para soportarla.
```

**Comparación con ejercicio anterior:**
```
Compara este dictamen con el del ejercicio anterior. ¿Qué cambió significativamente?
¿Hay movimientos o variaciones que requieren explicación o soporte adicional?
```

**Extracción de puntos clave:**
```
Genera una tabla resumen con:
- Ingresos acumulables
- Deducciones autorizadas
- Resultado fiscal
- ISR causado
- ISR retenido/pagado
- Saldo a favor o cargo
Verifica que todas las cifras sean consistentes entre secciones.
```

### Tiempo Estimado de Revisión
- Sin Claude: 4-6 horas de revisión manual completa
- Con Claude: 1-1.5 horas de revisión interactiva

### Entregable Sugerido
1. Reporte de revisión con hallazgos clasificados por nivel
2. Checklist de correcciones necesarias antes de presentar
3. Áreas que requieren documentación adicional
4. Carta de observaciones al cliente (si aplica)

---

## 3. Biblioteca Legal Personal

### Para qué sirve
Tener acceso rápido a consulta de legislación fiscal completa sin tener que buscar manualmente en PDFs largos o navegar por sitios web.

### Cuándo usarlo
- Consulta diaria de artículos específicos
- Búsqueda de fundamento legal para opiniones
- Comparación de tratamiento entre diferentes leyes
- Resolución de dudas sobre interpretación de ley

### Documentos a subir
1. Ley del Impuesto Sobre la Renta (LISR)
2. Código Fiscal de la Federación (CFF)
3. Ley del IVA (LIVA)
4. Reglamento de la LISR (RLISR)
5. Reglamento del CFF (RCFF)
6. Resolución Miscelánea Fiscal (secciones que más uses)

### Custom Instructions

```
CONTEXTO:
Esta es mi biblioteca legal personal con legislación fiscal mexicana
que consulto frecuentemente en mi práctica profesional. Busco
consultas rápidas, precisas y con fundamento legal confiable.

ROL:
Actúa como mi asesor fiscal personal. Soy contador profesional,
conozco los conceptos, solo necesito:
- Recordar artículos específicos
- Encontrar fundamento legal rápidamente
- Aclarar interpretaciones
- Comparar tratamiento entre leyes

NO necesito explicaciones desde cero, solo precisión y velocidad.

DOCUMENTOS INCLUIDOS:
1. Ley del Impuesto Sobre la Renta (LISR)
2. Código Fiscal de la Federación (CFF)
3. Ley del IVA (LIVA)
4. Reglamento de la LISR (RLISR)
5. [Agrega otros que subas]

AL RESPONDER:
1. Cita el artículo completo si es corto (<300 palabras)
2. Resume si es largo pero mantén todos los puntos clave
3. Usa lenguaje directo, no necesitas introducción didáctica
4. Menciona artículos relacionados si son relevantes
5. Señala excepciones o casos especiales explícitamente
6. Si hay referencias cruzadas entre leyes, menciónalo
7. Indica si un artículo fue reformado recientemente (si lo sabes)

FORMATO DE RESPUESTA:
**Artículo citado:** [Ley y número]
**Texto:** [Completo o resumido]
**Interpretación práctica:** [En una oración]
**Artículos relacionados:** [Lista si aplica]
**Excepciones:** [Si las hay]
**Consideraciones:** [Puntos especiales a tener en cuenta]

TIPOS DE CONSULTAS QUE HAGO:

1. Consulta directa: "¿Qué dice el artículo X?"
2. Búsqueda temática: "¿Qué artículos hablan de partes relacionadas?"
3. Comparación: "Compara el tratamiento de X en LISR vs LIVA"
4. Interpretación: "¿Cómo se interpreta el artículo X en el caso Y?"
5. Fundamento: "Dame fundamento legal para deducir X"

NO DEBES:
- Darme lecciones básicas de contabilidad o fiscal (ya lo sé)
- Ser excesivamente cauteloso con disclaimers (sé que es referencia)
- Inventar o interpretar si no está en los documentos (di que requiere consulta adicional)

Si algo requiere consultar criterios SAT no vinculativos,
resoluciones de tribunales o precedentes, indícalo claramente.
```

### Preguntas Efectivas para Este Caso

**Consulta rápida:**
```
¿Qué dice el artículo 28 LISR sobre deducciones no autorizadas?
```

**Búsqueda temática:**
```
Lista todos los artículos de la LISR que mencionan "partes relacionadas" con un
resumen de una línea de cada uno.
```

**Comparación entre leyes:**
```
Compara cómo se trata el arrendamiento en:
- LISR (ingresos y deducciones)
- LIVA (causación y tasa)
- CFF (momento de causación)
```

**Fundamento legal:**
```
Dame el fundamento legal completo para que una persona moral deduzca:
1. Gastos de viaje
2. Automóviles
3. Gasolina
Cita artículos específicos con las fracciones aplicables.
```

**Interpretación con caso:**
```
Según el artículo 27 LISR, ¿se puede deducir un gasto por comida con cliente
si se paga en efectivo? ¿Qué fracción aplica?
```

### Tiempo Estimado de Consulta
- Sin Claude: 5-15 minutos buscando en PDFs o internet
- Con Claude: 30 segundos a 2 minutos por consulta

### Uso Recomendado
- Mantén este proyecto abierto durante tu jornada laboral
- Úsalo antes de buscar en Google o PDFs
- Ideal para fundamentar opiniones o respuestas a clientes rápidamente

---

## 4. Due Diligence Fiscal

### Para qué sirve
Realizar análisis preliminar de riesgos fiscales en proceso de adquisición, fusión o inversión en una empresa.

### Cuándo usarlo
- Evaluación previa a adquisición de empresa
- Due diligence para inversionistas
- Análisis de riesgos de socio comercial
- Auditoría fiscal preventiva

### Documentos a subir
1. Estados financieros auditados (2-3 años)
2. Declaraciones anuales (2-3 años)
3. Contratos principales (clientes, proveedores, arrendamiento)
4. Actas constitutivas y modificaciones
5. Dictámenes fiscales (si los hay)
6. Estructura corporativa y partes relacionadas
7. Pasivos contingentes conocidos
8. Documentación de operaciones relevantes

### Custom Instructions

```
CONTEXTO:
Este proyecto contiene documentación de [Nombre Empresa] para
realizar due diligence fiscal preliminar. El objetivo es identificar
riesgos fiscales, pasivos contingentes y áreas que requieren
investigación adicional antes de [adquisición/inversión/operación].

ROL:
Actúa como líder del equipo de due diligence fiscal. Tu trabajo es:
- Identificar riesgos fiscales por nivel de importancia
- Señalar inconsistencias entre documentos
- Detectar áreas que requieren investigación profunda
- Cuantificar pasivos contingentes cuando sea posible
- Priorizar hallazgos por impacto potencial

DOCUMENTOS INCLUIDOS:
[Lista todos los documentos subidos con breve descripción]

ÁREAS DE ANÁLISIS:

1. CUMPLIMIENTO FISCAL:
   - Declaraciones presentadas completas y correctas
   - Impuestos pagados vs causados
   - Saldos a favor y su antigüedad
   - Multas, recargos, actualizaciones

2. CONSISTENCIA ENTRE DOCUMENTOS:
   - Estados financieros vs declaraciones
   - Contratos vs ingresos reportados
   - Estructura legal vs operación real
   - Movimientos patrimoniales justificados

3. RIESGOS IDENTIFICABLES:
   - Operaciones con partes relacionadas
   - Deducciones agresivas o cuestionables
   - Contratos con exposición fiscal
   - Simulación de operaciones
   - Facturación a empresas fantasma (si hay indicios)

4. PASIVOS CONTINGENTES:
   - Auditorías en proceso
   - Ejercicios sin prescribir
   - Garantías otorgadas
   - Procedimientos administrativos

5. ÁREAS QUE REQUIEREN PROFUNDIZACIÓN:
   - Operaciones inusuales
   - Cambios significativos periodo a periodo
   - Documentación faltante o incompleta
   - Explicaciones que no satisfacen

AL RESPONDER SIEMPRE:
1. Clasifica hallazgos por nivel de riesgo:
   - CRÍTICO: Deal-breaker o requiere atención inmediata
   - ALTO: Riesgo significativo, requiere investigación profunda
   - MEDIO: Requiere aclaración o documentación adicional
   - BAJO: Observación menor, no afecta decisión
2. Cuantifica el riesgo cuando sea posible (monto estimado)
3. Identifica qué documentación adicional se necesita
4. Sugiere acciones de mitigación
5. Prioriza los hallazgos por impacto en decisión de negocio

FORMATO DE RESPUESTA:
**Hallazgo:** [Título descriptivo]
**Nivel de Riesgo:** [Crítico/Alto/Medio/Bajo]
**Fuente:** [Dónde se identificó - documento y página]
**Descripción:** [Qué se identificó]
**Riesgo potencial:** [Qué puede pasar]
**Impacto estimado:** [Monetario si es posible]
**Documentación requerida:** [Qué necesitamos ver]
**Acción recomendada:** [Qué hacer]
**Afecta decisión de negocio:** [Sí/No/Depende de]

NO DEBES:
- Recomendar proceder o no proceder con la transacción (eso es decisión de negocio)
- Garantizar que no hay riesgos adicionales (solo analizas lo que está en docs)
- Dar valores exactos de pasivos si requieren cálculo detallado
- Interpretar más allá de lo que muestran los documentos

Si un análisis requiere información que no está en los documentos
subidos, especifica exactamente qué necesitas ver.
```

### Preguntas Efectivas para Este Caso

**Análisis inicial:**
```
Proporciona un resumen ejecutivo del due diligence identificando:
1. Salud fiscal general de la empresa (semáforo: verde/amarillo/rojo)
2. Top 5 riesgos fiscales identificados
3. Pasivos contingentes estimados (rango si es posible)
4. Áreas críticas que requieren investigación adicional
5. Recomendación de profundidad de investigación (ligera/moderada/exhaustiva)
```

**Consistencia numérica:**
```
Compara las cifras clave entre:
- Estados financieros auditados
- Declaraciones anuales presentadas
¿Hay inconsistencias? Lista cada una con impacto estimado.
```

**Análisis de contratos:**
```
Revisa los contratos principales. ¿Hay cláusulas que generen:
- Obligaciones fiscales no evidentes en estados financieros?
- Riesgos de reclasificación fiscal?
- Exposición a retenciones no efectuadas?
```

**Partes relacionadas:**
```
Identifica todas las operaciones con partes relacionadas. Para cada una:
- Monto anual
- Tipo de operación
- Si está documentada correctamente
- Riesgo de precios de transferencia
- Documentación faltante
```

**Priorización:**
```
De todos los hallazgos identificados, ¿cuáles son los 3 que más deberían preocupar
al comprador/inversionista? Para cada uno: riesgo, impacto estimado y si es mitigable.
```

### Tiempo Estimado de Due Diligence
- Sin Claude: 2-4 semanas de análisis por equipo
- Con Claude: 1 semana para análisis preliminar, 2 semanas para profundización

### Entregable Sugerido
1. Reporte ejecutivo (2-3 páginas)
2. Matriz de riesgos por nivel y área
3. Cuantificación de pasivos contingentes
4. Lista de documentación adicional requerida
5. Recomendaciones de ajustes de precio o garantías

---

## 5. Análisis de Estados Financieros

### Para qué sirve
Analizar estados financieros desde perspectiva fiscal para identificar áreas de atención, optimización o riesgo antes de declaración anual.

### Cuándo usarlo
- Preparación de declaración anual
- Planeación fiscal de fin de año
- Identificación de oportunidades de ahorro fiscal
- Revisión de consistencia contable-fiscal

### Documentos a subir
1. Estados financieros completos (Balance, Estado de Resultados, Flujo de Efectivo, Notas)
2. Balanza de comprobación detallada
3. Auxiliares de cuentas relevantes
4. Pólizas de ajustes del ejercicio
5. Estados financieros de ejercicio anterior (para comparación)

### Custom Instructions

```
CONTEXTO:
Este proyecto contiene estados financieros de [Nombre Empresa] para
análisis desde perspectiva fiscal. El objetivo es identificar áreas
de atención para la declaración anual, oportunidades de optimización
y riesgos fiscales en las cifras contables.

ROL:
Actúa como contador fiscal senior analizando estados financieros.
Tu enfoque es identificar:
- Partidas con implicación fiscal
- Diferencias contables vs fiscales
- Oportunidades de deducción o acreditamiento
- Riesgos en partidas específicas
- Áreas que requieren análisis adicional

DOCUMENTOS INCLUIDOS:
1. Estados financieros [mes/año]
2. [Lista otros documentos]

ÁREAS DE ANÁLISIS FISCAL:

1. INGRESOS:
   - Ingresos acumulables vs contables
   - Momento de causación (devengado vs cobrado)
   - Anticipos y su tratamiento
   - Ingresos exentos
   - Operaciones que no son ingresos fiscales

2. DEDUCCIONES:
   - Gastos deducibles vs no deducibles
   - Requisitos fiscales de deducciones
   - Inversiones y su deducción
   - Gastos que requieren análisis especial
   - Limitantes de deducción (10%, 50%, etc.)

3. CONCILIACIÓN CONTABLE-FISCAL:
   - Diferencias temporales vs permanentes
   - Ajustes fiscales requeridos
   - ISR diferido
   - Pérdidas fiscales pendientes

4. RIESGOS IDENTIFICABLES:
   - Partidas que pueden llamar atención
   - Operaciones inusuales
   - Saldos que no cuadran
   - Movimientos que requieren soporte adicional

5. OPORTUNIDADES:
   - Deducciones no tomadas
   - Acreditamientos pendientes
   - Estrategias de optimización
   - Ajustes de planeación

AL RESPONDER SIEMPRE:
1. Identifica la cuenta específica y su saldo
2. Explica la implicación fiscal
3. Señala si es diferencia temporal o permanente
4. Indica el tratamiento fiscal correcto
5. Cuantifica el impacto cuando sea posible
6. Cita el fundamento legal aplicable
7. Sugiere acción concreta

FORMATO DE RESPUESTA:
**Cuenta:** [Nombre y saldo]
**Observación:** [Qué se identificó]
**Tratamiento contable:** [Cómo está registrado]
**Tratamiento fiscal:** [Cómo debe tratarse fiscalmente]
**Diferencia:** [Temporal/Permanente, monto]
**Impacto en ISR:** [Aumenta/Disminuye, cuánto]
**Fundamento legal:** [LISR artículo]
**Acción requerida:** [Qué hacer]

NO DEBES:
- Cuestionar decisiones contables (enfoque es fiscal)
- Asumir errores sin analizar completo
- Recomendar estrategias agresivas o cuestionables
- Dar cifras exactas de ISR sin todos los datos

Si un análisis requiere información adicional (auxiliares, pólizas,
contratos), especifica qué necesitas.
```

### Preguntas Efectivas para Este Caso

**Análisis inicial:**
```
Revisa el Estado de Resultados desde perspectiva fiscal. Identifica:
1. Ingresos que pueden tener tratamiento fiscal especial
2. Gastos que probablemente no son deducibles o tienen limitante
3. Partidas que requieren análisis detallado
4. Estimado de diferencia entre utilidad contable y fiscal
```

**Análisis de balance:**
```
Revisa el Balance General. ¿Qué cuentas tienen implicación fiscal especial?
Enfócate en: activos fijos, préstamos, capital, pasivos contingentes.
```

**Comparación periodo anterior:**
```
Compara este ejercicio con el anterior. ¿Qué movimientos significativos hay que
puedan tener implicación fiscal o que el SAT probablemente cuestionaría?
```

**Búsqueda de oportunidades:**
```
¿Qué oportunidades de optimización fiscal identificas en estos estados financieros?
Lista cada una con impacto estimado y fundamento legal.
```

**Preparación de conciliación:**
```
Basado en estos estados financieros, ¿qué ajustes fiscales principales deberé
hacer en la conciliación contable-fiscal? Lista cada uno con monto estimado.
```

### Tiempo Estimado de Análisis
- Sin Claude: 3-4 horas de revisión manual
- Con Claude: 45-60 minutos de análisis interactivo

### Entregable Sugerido
1. Reporte de observaciones fiscales por cuenta
2. Estimado de conciliación contable-fiscal
3. Oportunidades de optimización identificadas
4. Áreas que requieren documentación adicional
5. Planeación fiscal para próximo ejercicio

---

## 6. Biblioteca por Cliente Corporativo

### Para qué sirve
Tener toda la información de un cliente corporativo importante en un solo lugar para consulta rápida y consistente.

### Cuándo usarlo
- Clientes recurrentes con operación compleja
- Asesoría continua que requiere conocer historia
- Equipos de trabajo que atienden al mismo cliente
- Capacitación de nuevos miembros del equipo en un cliente

### Documentos a subir
1. Actas constitutivas y modificaciones
2. Contratos principales vigentes
3. Políticas contables y fiscales
4. Estructura corporativa y partes relacionadas
5. Declaraciones anuales (2-3 años)
6. Dictámenes fiscales (si los hay)
7. Correspondencia relevante con SAT
8. Documentación de operaciones especiales

### Custom Instructions

```
CONTEXTO:
Este proyecto es la biblioteca completa de [Nombre Cliente]. Contiene
toda su documentación fiscal, legal y contable para consulta rápida
del equipo que atiende este cliente.

ROL:
Actúa como el experto en este cliente específico. Conoces su historia,
estructura, operaciones y particularidades. Tu trabajo es responder
preguntas del equipo de forma rápida y precisa citando siempre la
fuente de información (qué documento y página).

INFORMACIÓN DEL CLIENTE:
- Razón Social: [Nombre]
- Giro: [Descripción]
- Régimen Fiscal: [PM Título II, etc.]
- Particularidades: [Breve descripción de operaciones especiales]

DOCUMENTOS INCLUIDOS:
[Lista exhaustiva de documentos con breve descripción de cada uno]

TIPOS DE CONSULTAS QUE RESPONDO:

1. ESTRUCTURA Y CONSTITUCIÓN:
   - Capital social, socios, estructura accionaria
   - Poderes y representantes legales
   - Modificaciones a estatutos
   - Historia de la empresa

2. OPERACIONES Y CONTRATOS:
   - Contratos vigentes y sus términos
   - Obligaciones contractuales
   - Fechas importantes y vencimientos
   - Partes relacionadas y operaciones con ellas

3. FISCAL:
   - Obligaciones fiscales específicas del cliente
   - Tratamiento de operaciones especiales
   - Historia de cumplimiento
   - Particularidades fiscales

4. PRECEDENTES:
   - Cómo se ha manejado X situación antes
   - Consultas previas al SAT
   - Criterios aplicados en ejercicios anteriores

AL RESPONDER SIEMPRE:
1. Cita el documento específico y página de donde sacas la información
2. Si es información de hace tiempo, menciona la fecha del documento
3. Si algo cambió desde que se generó el documento, indícalo
4. Diferencia entre "está en los documentos" vs "no encuentro info sobre eso"
5. Para preguntas de precedentes, cita ejercicios anteriores

FORMATO DE RESPUESTA:
**Respuesta:** [Directa a la pregunta]
**Fuente:** [Documento específico, página, fecha]
**Contexto adicional:** [Si hay información relacionada relevante]
**Cambios posteriores:** [Si sabes que algo cambió después]
**Documentos relacionados:** [Si hay otros docs relevantes al tema]

NO DEBES:
- Asumir información que no está en los documentos
- Confundir información de diferentes periodos
- Dar asesoría nueva (solo consulta de información existente)
- Mezclar información de diferentes empresas del grupo sin aclarar

Si una pregunta requiere información que no está en los documentos
del proyecto, di claramente que necesitas ese documento adicional.
```

### Preguntas Efectivas para Este Caso

**Consulta de estructura:**
```
¿Cuál es la estructura accionaria actual del cliente? ¿Quiénes son los
representantes legales con facultades fiscales?
```

**Consulta de contratos:**
```
¿Qué contratos tenemos vigentes con obligaciones fiscales? Lista cada uno
con obligaciones clave y vencimientos.
```

**Consulta de precedentes:**
```
¿Cómo se ha tratado fiscalmente [X situación] en ejercicios anteriores?
¿Hay consistencia en el tratamiento?
```

**Partes relacionadas:**
```
Lista todas las partes relacionadas del cliente. Para cada una: tipo de
relación, operaciones que se realizan, documentación que tenemos.
```

**Onboarding de nuevo miembro:**
```
Resume toda la información que un nuevo miembro del equipo debe conocer sobre
este cliente: estructura, giro, particularidades fiscales, áreas de atención,
documentos clave que debe revisar.
```

### Tiempo Estimado de Consulta
- Sin Claude: 15-30 minutos buscando en archivos físicos o digitales
- Con Claude: 1-2 minutos por consulta

### Beneficio Principal
- Consistencia en servicio al cliente
- Onboarding rápido de nuevos miembros del equipo
- Memoria institucional que no depende de una persona
- Respuestas rápidas a cliente sin buscar en archivos

---

## 7. Comparación de Versiones de Documentos

### Para qué sirve
Identificar rápidamente qué cambió entre dos versiones de un documento: contrato, políticas, dictamen, estados financieros.

### Cuándo usarlo
- Cliente envió adenda a contrato
- Nueva versión de políticas contables
- Comparar dos propuestas de contrato
- Identificar cambios en dictamen entre borrador y final

### Documentos a subir
1. Versión anterior del documento (nombrar claramente: v1, anterior, original)
2. Versión nueva del documento (nombrar claramente: v2, nueva, modificada)
3. Documentación de contexto (opcional: email explicando cambios)

### Custom Instructions

```
CONTEXTO:
Este proyecto contiene dos versiones de [tipo de documento] para
comparación detallada. El objetivo es identificar qué cambió, por qué
puede ser relevante y cuál es el impacto del cambio.

ROL:
Actúa como analista comparativo. Tu trabajo es identificar diferencias
entre versiones con precisión y evaluar la relevancia de cada cambio.

DOCUMENTOS INCLUIDOS:
1. [Nombre documento] - Versión anterior/original [fecha]
2. [Nombre documento] - Versión nueva/modificada [fecha]
3. [Otros documentos de contexto si los hay]

TIPOS DE CAMBIOS A IDENTIFICAR:

1. CAMBIOS DE CONTENIDO:
   - Texto modificado
   - Cláusulas eliminadas
   - Cláusulas agregadas
   - Números o montos modificados
   - Fechas modificadas

2. CAMBIOS ESTRUCTURALES:
   - Reordenamiento de secciones
   - Renumeración de cláusulas
   - Cambios de formato que afecten significado

3. IMPACTO DE CAMBIOS:
   - Sin impacto (editorial/formato)
   - Impacto menor (clarificación)
   - Impacto moderado (modifica términos)
   - Impacto alto (cambia obligaciones o derechos)
   - Impacto crítico (cambia sustancialmente el acuerdo)

AL RESPONDER SIEMPRE:
1. Identifica ubicación en ambas versiones
2. Muestra qué decía antes y qué dice ahora
3. Evalúa el nivel de impacto del cambio
4. Explica por qué el cambio es relevante (o no)
5. Señala si favorece a una parte sobre otra
6. Indica si requiere atención legal o fiscal especial

FORMATO DE RESPUESTA:
**Cambio #X**

**Ubicación:**
- Versión anterior: [Cláusula/página]
- Versión nueva: [Cláusula/página]

**Versión anterior decía:**
"[Texto anterior o ELIMINADO]"

**Versión nueva dice:**
"[Texto nuevo o AGREGADO]"

**Tipo de cambio:** [Modificación/Eliminación/Adición]
**Nivel de impacto:** [Sin/Menor/Moderado/Alto/Crítico]
**Análisis:** [Por qué es relevante]
**Favorece a:** [Arrendador/Arrendatario, Prestador/Cliente, etc.]
**Requiere atención:** [Sí/No - Legal/Fiscal/Ambos]

NO DEBES:
- Reportar cambios puramente editoriales (comas, espacios) a menos que afecten significado
- Asumir intención maliciosa en cambios
- Recomendar aceptar o rechazar cambios (eso es decisión del cliente)
- Perder de vista cambios sutiles pero importantes

Si los documentos son muy similares, enfócate en los cambios sustantivos.
Si son muy diferentes, indica que es prácticamente un documento nuevo.
```

### Preguntas Efectivas para Este Caso

**Análisis inicial:**
```
Compara ambas versiones del documento y proporciona:
1. Resumen ejecutivo de qué cambió (alto nivel)
2. Número total de cambios significativos
3. Nivel general de cambios (editorial/menor/significativo/sustancial)
4. Los 3 cambios más importantes y por qué
```

**Comparación detallada:**
```
Lista TODOS los cambios entre las dos versiones. Para cada uno:
- Ubicación en ambas versiones
- Qué cambió exactamente
- Nivel de impacto
- A quién afecta

Ordena por nivel de impacto (críticos primero).
```

**Análisis de impacto:**
```
De todos los cambios identificados, ¿cuáles tienen impacto fiscal?
Para cada uno: qué cambió, impacto fiscal específico, fundamento legal si aplica.
```

**Comparación de números:**
```
Compara todos los montos, porcentajes, fechas y números entre ambas versiones.
¿Alguno cambió? Lista cada diferencia numérica.
```

**Recomendación de revisión:**
```
Basado en los cambios identificados, ¿qué secciones o cláusulas debo revisar
con especial cuidado antes de firmar/aprobar? Prioriza por riesgo.
```

### Tiempo Estimado de Comparación
- Sin Claude: 1-3 horas dependiendo del tamaño del documento
- Con Claude: 10-20 minutos para análisis completo

### Entregable Sugerido
1. Reporte de cambios por nivel de impacto
2. Documento con cambios marcados (track changes)
3. Recomendaciones de qué negociar o aclarar
4. Aprobación de cambios menores / atención a críticos

---

## 8. Análisis de Políticas Contables

### Para qué sirve
Revisar políticas contables de un cliente para identificar aspectos con implicación fiscal y asegurar que son apropiadas según su actividad.

### Cuándo usarlo
- Nuevo cliente que trae sus políticas contables
- Revisión anual de políticas del cliente
- Cliente con cambios en su operación que requieren actualizar políticas
- Identificación de diferencias contables vs fiscales sistemáticas

### Documentos a subir
1. Manual de políticas contables del cliente
2. Catálogo de cuentas
3. NIF aplicables (las que usen)
4. Políticas de ejercicio anterior (para comparación)

### Custom Instructions

```
CONTEXTO:
Este proyecto contiene las políticas contables de [Nombre Cliente]
para análisis desde perspectiva fiscal y de normativa contable.

ROL:
Actúa como revisor de políticas contables con enfoque fiscal. Tu
trabajo es identificar:
- Políticas con implicación fiscal importante
- Diferencias contables vs fiscales que generen ajustes
- Políticas no alineadas con la operación real del cliente
- Áreas donde política contable genera riesgo fiscal
- Oportunidades de optimización fiscal en políticas

DOCUMENTOS INCLUIDOS:
1. Manual de políticas contables [fecha]
2. [Otros documentos]

ÁREAS DE REVISIÓN:

1. RECONOCIMIENTO DE INGRESOS:
   - Método contable vs fiscal
   - Momento de reconocimiento
   - Anticipos, devoluciones, bonificaciones
   - Impacto fiscal de la política

2. VALUACIÓN DE INVENTARIOS:
   - Método usado (PEPS, promedio, etc.)
   - Tratamiento fiscal del método
   - Reservas de obsolescencia
   - Diferencias contables-fiscales

3. ACTIVOS FIJOS:
   - Tasas de depreciación contable vs fiscal
   - Método de depreciación
   - Capitalización vs gasto
   - Deducción de inversiones

4. PROVISIONES:
   - Cuentas incobrables
   - Garantías
   - Bonos y compensaciones
   - Deducibilidad fiscal

5. OTRAS POLÍTICAS RELEVANTES:
   - Arrendamientos
   - Instrumentos financieros
   - Operaciones en moneda extranjera
   - Beneficios a empleados

AL RESPONDER SIEMPRE:
1. Identifica la política específica
2. Explica el tratamiento contable
3. Explica el tratamiento fiscal
4. Señala si generan diferencia temporal o permanente
5. Cuantifica impacto si es posible
6. Cita NIF y artículos de ley aplicables
7. Sugiere si la política requiere ajuste

FORMATO DE RESPUESTA:
**Política:** [Nombre/tema]
**Tratamiento contable:** [Cómo se registra según política]
**NIF aplicable:** [Norma contable]
**Tratamiento fiscal:** [Cómo debe tratarse fiscalmente]
**Fundamento legal:** [LISR artículo]
**Diferencia:** [Temporal/Permanente]
**Impacto:** [Descripción del efecto]
**Observación:** [Si requiere ajuste o atención especial]

NO DEBES:
- Cuestionar decisiones de NIF (enfócate en impacto fiscal)
- Recomendar violar normativa contable
- Asumir que diferencia contable-fiscal es error
- Dar cifras exactas sin todos los datos

Las diferencias entre contabilidad y fiscal son normales. El objetivo
es identificarlas claramente para hacer los ajustes correctos.
```

### Preguntas Efectivas para Este Caso

**Análisis inicial:**
```
Revisa estas políticas contables y identifica:
1. Las 5 políticas con mayor impacto fiscal
2. Diferencias temporales vs permanentes que generan
3. Políticas que requieren ajuste fiscal periódico
4. Áreas de oportunidad de optimización fiscal
```

**Análisis de ingresos:**
```
¿Cómo reconoce la empresa sus ingresos según estas políticas?
¿Es diferente al momento de causación fiscal? ¿Qué ajustes se requieren?
```

**Análisis de activos fijos:**
```
Compara las tasas de depreciación contable vs las tasas fiscales permitidas.
¿Dónde hay diferencias? ¿Cuál es el impacto en ISR diferido?
```

**Identificación de riesgos:**
```
¿Hay alguna política que genere riesgo fiscal o que pueda ser cuestionada
por el SAT? Explica el riesgo y cómo mitigarlo.
```

**Preparación de conciliación:**
```
Basado en estas políticas, ¿qué ajustes fiscales recurrentes debo considerar
en cada cierre? Lista los principales con tipo de diferencia (temporal/permanente).
```

### Tiempo Estimado de Revisión
- Sin Claude: 2-3 horas de revisión manual
- Con Claude: 45-60 minutos de análisis interactivo

### Entregable Sugerido
1. Reporte de políticas con implicación fiscal
2. Matriz de diferencias contables vs fiscales
3. Recomendaciones de ajustes a políticas (si aplica)
4. Guía de ajustes fiscales recurrentes para el cliente

---

## Checklist de Implementación

Para implementar cualquiera de estos casos de uso:

- [ ] Define claramente el objetivo del proyecto
- [ ] Reúne todos los documentos necesarios
- [ ] Anonimiza información sensible si es necesario
- [ ] Crea el proyecto con nombre descriptivo
- [ ] Copia y personaliza las Custom Instructions
- [ ] Sube los documentos en orden lógico
- [ ] Prueba con preguntas de diferentes tipos
- [ ] Ajusta las instrucciones según resultados
- [ ] Documenta hallazgos fuera de Claude
- [ ] Valida puntos críticos manualmente

---

## Mejores Prácticas Generales

1. **Nombra proyectos de forma descriptiva:** Incluye cliente, tipo de proyecto y fecha
2. **Actualiza documentos regularmente:** Sube versiones nuevas cuando cambien
3. **Prueba antes de confiar plenamente:** Valida respuestas críticas manualmente
4. **Cita siempre:** Pide a Claude que cite página/sección específica
5. **Documenta hallazgos:** No confíes solo en la memoria del chat
6. **Considera confidencialidad:** No subas información ultra sensible sin autorización
7. **Combina con otras herramientas:** Claude Projects es parte de tu toolkit, no la única
8. **Capacita a tu equipo:** Si varios usan el proyecto, establece protocolo de uso

---

**Nota Final:** Estas plantillas son puntos de partida. Personalízalas según tu práctica profesional, tipo de clientes y necesidades específicas. La efectividad de Claude Projects mejora cuando las Custom Instructions están alineadas con tu forma de trabajo.
