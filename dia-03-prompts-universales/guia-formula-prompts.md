# Guía Completa: La Fórmula del Prompt Perfecto
## ROL + CONTEXTO + TAREA + FORMATO

---

## La Fórmula

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│    ROL + CONTEXTO + TAREA + FORMATO = Prompt Efectivo      │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

Cada elemento tiene un propósito específico:

| Elemento | Propósito | Pregunta que responde |
|----------|-----------|----------------------|
| **ROL** | Define la perspectiva | ¿Quién me está respondiendo? |
| **CONTEXTO** | Proporciona información | ¿Cuál es la situación? |
| **TAREA** | Especifica la acción | ¿Qué necesito exactamente? |
| **FORMATO** | Define la presentación | ¿Cómo lo quiero recibir? |

---

## Elemento 1: ROL

### ¿Qué es?
El papel, especialidad o perspectiva desde la cual quieres que la IA responda.

### ¿Por qué importa?
- Ajusta el vocabulario y nivel técnico
- Define el enfoque de la respuesta
- Establece la "personalidad" profesional

### Estructura básica:
```
Actúa como [PROFESIÓN] especialista en [ÁREA] en [UBICACIÓN]
```

### Ejemplos para Contadores:

**Nivel básico:**
```
Actúa como contador en México.
```

**Nivel intermedio:**
```
Actúa como contador fiscal especialista en personas físicas en México.
```

**Nivel avanzado:**
```
Actúa como contador fiscal con 15 años de experiencia, especializado
en planeación fiscal para PyMEs del sector comercio en México.
```

### Catálogo de Roles Útiles:

| Situación | Rol Sugerido |
|-----------|--------------|
| Consultas fiscales generales | Contador fiscal especialista en México |
| Deducciones específicas | Contador especializado en deducciones fiscales |
| Temas de nómina | Especialista en nóminas y seguridad social en México |
| Contratos y legales | Abogado fiscalista con experiencia en contratos |
| Análisis financiero | Analista financiero corporativo |
| Comunicación a clientes | Contador con habilidades de comunicación clara |
| Defensa fiscal | Contador especialista en defensa y procedimientos ante SAT |
| Comercio exterior | Especialista en comercio exterior y aduanas |
| Precios de transferencia | Especialista en precios de transferencia |
| Auditoría | Auditor financiero con experiencia en PyMEs |

### Tips para el ROL:
- **Siempre incluye "en México"** para temas fiscales
- **Agrega años de experiencia** para parecer más senior
- **Combina roles** si necesitas múltiples perspectivas

---

## Elemento 2: CONTEXTO

### ¿Qué es?
Toda la información relevante sobre la situación, el cliente, los antecedentes.

### ¿Por qué importa?
- Evita respuestas genéricas
- Permite recomendaciones específicas
- Reduce la necesidad de preguntas de seguimiento

### Estructura básica:
```
CONTEXTO:
- Tipo de contribuyente: [PF/PM]
- Régimen fiscal: [RÉGIMEN]
- Giro o actividad: [DESCRIPCIÓN]
- Situación específica: [DETALLES]
```

### ¿Qué incluir según el tema?

**Para consultas fiscales:**
- Tipo de contribuyente (PF/PM)
- Régimen fiscal
- Giro o actividad
- Ingresos aproximados (si es relevante)
- Situación específica

**Para deducciones:**
- Todo lo anterior PLUS:
- Descripción del gasto
- Monto involucrado
- Frecuencia (único, mensual, etc.)
- Relación con la actividad

**Para nómina:**
- Número de empleados
- Tipo de contratación
- Prestaciones ofrecidas
- Situación específica del empleado

**Para requerimientos SAT:**
- Tipo de requerimiento
- Fechas (emisión y notificación)
- Lo que solicitan
- Antecedentes del contribuyente
- Si existe o no la irregularidad

### Ejemplo de contexto completo:

```
CONTEXTO:
Mi cliente es una persona moral (SA de CV) en régimen general de ley.
Se dedica a la comercialización de productos de tecnología (mayorista).
Tiene 25 empleados y factura aproximadamente $15 millones anuales.

Situación específica:
Está considerando abrir una sucursal en otro estado y quiere entender
las implicaciones fiscales de tener operaciones en dos ubicaciones.
Ya tiene registrada su matriz en el RFC en CDMX.
```

### Tips para el CONTEXTO:
- **Más contexto = mejor respuesta** (pero no te excedas)
- **Incluye solo lo relevante** para la pregunta
- **Menciona antecedentes** si afectan la respuesta
- **Indica lo que NO sabes** si te falta información

---

## Elemento 3: TAREA

### ¿Qué es?
La acción específica que quieres que la IA realice.

### ¿Por qué importa?
- Define claramente lo que esperas
- Evita respuestas vagas o incompletas
- Permite obtener exactamente lo que necesitas

### Estructura básica:
```
TAREA:
[VERBO DE ACCIÓN] [QUÉ] considerando [CRITERIOS]

NECESITO QUE:
1. [Primera cosa específica]
2. [Segunda cosa específica]
3. [Tercera cosa específica]
```

### Verbos de Acción Efectivos:

| Verbo | Cuándo Usarlo |
|-------|---------------|
| **Analiza** | Revisar algo en detalle |
| **Calcula** | Obtener números o montos |
| **Compara** | Ver opciones lado a lado |
| **Explica** | Entender un concepto |
| **Redacta** | Crear texto o documentos |
| **Resume** | Condensar información |
| **Identifica** | Encontrar elementos específicos |
| **Recomienda** | Obtener una sugerencia |
| **Evalúa** | Juzgar pros y contras |
| **Lista** | Obtener enumeraciones |

### Ejemplos de tareas bien definidas:

**Vago (evitar):**
```
Ayúdame con el ISR de mi cliente.
```

**Específico (usar):**
```
Calcula el ISR mensual de enero 2025 considerando:
1. Los ingresos acumulados que te proporcioné
2. Las deducciones autorizadas del período
3. Los pagos provisionales anteriores

Muestra el procedimiento paso a paso.
```

**Aún mejor (tareas numeradas):**
```
ANALIZA Y RESPONDE:
1. ¿Cuál es la base gravable del período?
2. ¿Qué tasa de ISR aplica según la tarifa?
3. ¿Cuánto es el ISR causado?
4. ¿Cuánto es el ISR a pagar después de acreditamientos?
5. ¿Hay alguna consideración especial que deba tomar en cuenta?
```

### Tips para la TAREA:
- **Usa verbos de acción** al inicio
- **Numera** si hay múltiples solicitudes
- **Sé específico** sobre qué quieres
- **Indica prioridad** si algo es más importante

---

## Elemento 4: FORMATO

### ¿Qué es?
Cómo quieres que se presente la respuesta.

### ¿Por qué importa?
- Evita reformatear después
- Facilita usar la respuesta directamente
- Mejora la claridad de la información

### Estructura básica:
```
FORMATO:
- Estructura: [TIPO DE ESTRUCTURA]
- Longitud: [EXTENSIÓN DESEADA]
- Elementos: [QUÉ INCLUIR]
- Estilo: [CARACTERÍSTICAS]
```

### Opciones de formato comunes:

**Estructuras:**
- Lista numerada
- Lista con viñetas
- Tabla comparativa
- Párrafos
- Resumen ejecutivo + detalle
- Paso a paso

**Longitudes:**
- Breve (1-2 párrafos)
- Medio (3-4 párrafos)
- Extenso (sin límite)
- Específico (máximo X palabras)

**Elementos a incluir:**
- Fundamento legal
- Ejemplos
- Números/cálculos
- Pros y contras
- Advertencias/riesgos

### Ejemplos de formatos:

**Para análisis:**
```
FORMATO:
- Resumen ejecutivo (1 párrafo)
- Análisis detallado en lista numerada
- Conclusión con recomendación
- Incluye fundamento legal en cada punto
```

**Para comunicación a cliente:**
```
FORMATO:
- Máximo 3 párrafos
- Lenguaje simple (sin tecnicismos)
- Termina con próximos pasos claros
```

**Para cálculos:**
```
FORMATO:
- Paso a paso numerado
- Muestra fórmulas utilizadas
- Incluye verificación al final
- Listo para explicar al cliente
```

**Para comparativos:**
```
FORMATO:
- Tabla comparativa con columnas para cada opción
- Fila por cada criterio de evaluación
- Resumen de pros y contras debajo
- Recomendación final justificada
```

### Tips para el FORMATO:
- **Pide tablas** para comparaciones
- **Pide listas** para pasos o elementos
- **Especifica longitud** para controlar extensión
- **Pide fundamento** cuando lo necesites

---

## Ejemplo Completo Paso a Paso

### Situación:
Un cliente persona física en RESICO quiere saber si puede deducir una laptop.

### Construyendo el prompt:

**Paso 1 - ROL:**
```
Actúa como contador fiscal especialista en RESICO en México.
```

**Paso 2 - CONTEXTO:**
```
CONTEXTO:
- Mi cliente es persona física
- Régimen: RESICO
- Actividad: Consultoría de negocios
- Compró una laptop de $25,000 para usar en su trabajo
- La laptop la pagó con transferencia y tiene factura (CFDI)
```

**Paso 3 - TAREA:**
```
ANALIZA:
1. ¿Puede deducir esta laptop en RESICO?
2. Si no puede deducirla como tal, ¿qué tratamiento tiene?
3. ¿Cómo afecta a su base de ISR?
4. ¿Qué documentación debe conservar?
```

**Paso 4 - FORMATO:**
```
FORMATO:
- Respuesta directa primero
- Luego explicación con fundamento (artículos)
- Lista de documentos a conservar
- Máximo 4 párrafos
```

### Prompt Final Completo:

```
Actúa como contador fiscal especialista en RESICO en México.

CONTEXTO:
- Mi cliente es persona física
- Régimen: RESICO
- Actividad: Consultoría de negocios
- Compró una laptop de $25,000 para usar en su trabajo
- La laptop la pagó con transferencia y tiene factura (CFDI)

ANALIZA:
1. ¿Puede deducir esta laptop en RESICO?
2. Si no puede deducirla como tal, ¿qué tratamiento tiene?
3. ¿Cómo afecta a su base de ISR?
4. ¿Qué documentación debe conservar?

FORMATO:
- Respuesta directa primero
- Luego explicación con fundamento (artículos)
- Lista de documentos a conservar
- Máximo 4 párrafos
```

---

## Errores Comunes y Cómo Evitarlos

### Error 1: Prompt de una línea
```
❌ "¿Es deducible el auto?"
✅ [Usar plantilla completa con contexto del cliente y tipo de auto]
```

### Error 2: Olvidar el contexto geográfico
```
❌ "Actúa como contador fiscal"
✅ "Actúa como contador fiscal en México"
```

### Error 3: Tareas vagas
```
❌ "Ayúdame con los impuestos"
✅ "Calcula el ISR del mes con estos datos: ..."
```

### Error 4: No especificar formato
```
❌ "Explica las deducciones"
✅ "Explica las 5 deducciones principales en lista con ejemplos"
```

### Error 5: Pedir demasiado en un prompt
```
❌ [Prompt de 500 palabras con 15 preguntas]
✅ [Dividir en 2-3 prompts más enfocados]
```

---

## Potenciadores Avanzados

Agrega al final de cualquier prompt:

### Para precisión:
```
Sé específico y práctico. Si hay ambigüedad, indícalo.
```

### Para seguridad fiscal:
```
Dame la postura más conservadora fiscalmente.
```

### Para honestidad:
```
Si no estás seguro o te falta información, dilo en lugar de adivinar.
```

### Para fundamentación:
```
Incluye fundamento legal (artículos específicos) en cada punto.
```

### Para actualidad:
```
Nota: Estamos en [año]. Si tu información puede no estar actualizada, indícalo.
```

---

## Checklist Antes de Enviar un Prompt

- [ ] ¿Tiene ROL definido?
- [ ] ¿Menciona "en México" para temas fiscales?
- [ ] ¿Incluye contexto del cliente?
- [ ] ¿Especifica tipo de contribuyente y régimen?
- [ ] ¿La tarea es específica con verbos de acción?
- [ ] ¿Está claro qué formato quiero?
- [ ] ¿Pedí fundamento legal si lo necesito?
- [ ] ¿El prompt es claro y no ambiguo?

---

*Guía de Fórmula v1.0 - Reto 12 Días de IA para Contadores*
*TodoConta.com*
