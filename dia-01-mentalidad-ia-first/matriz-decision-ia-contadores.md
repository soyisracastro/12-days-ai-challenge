# Matriz de Decisión IA para Contadores
## Tu guía rápida para elegir la herramienta correcta

---

## Resumen Ejecutivo

| Herramienta | Mejor Para | Evitar Cuando |
|-------------|------------|---------------|
| **ChatGPT** | Tareas generales, redacción, explicaciones, Custom GPTs | Necesitas info actualizada 2024-2025 |
| **Claude** | Documentos largos, análisis complejo, razonamiento legal | Tareas simples y rápidas |
| **Gemini** | Info en tiempo real, integración Google, búsquedas | No usas Google Workspace |

---

## 1. Redacción y Comunicación

| Tarea Específica | Herramienta | Razón |
|------------------|-------------|-------|
| Correos a clientes | ChatGPT | Tono natural y rápido |
| Correos formales/institucionales | Claude | Mayor precisión en formalidad |
| Oficios al SAT | Claude | Cuidado con lenguaje técnico-legal |
| Respuestas a requerimientos | Claude | Análisis detallado de lo solicitado |
| Explicar conceptos a clientes | ChatGPT | Simplifica términos complejos |
| Minutas de reuniones | ChatGPT | Estructuración rápida |
| Propuestas de servicios | ChatGPT | Creatividad y persuasión |
| Avisos y comunicados | ChatGPT | Versatilidad de tono |

**Prompt base para redacción:**
```
Actúa como contador público en México. Redacta [tipo de documento] para [destinatario] sobre [tema]. El tono debe ser [formal/profesional/accesible]. Incluye [elementos específicos].
```

---

## 2. Análisis de Documentos

| Tarea Específica | Herramienta | Razón |
|------------------|-------------|-------|
| Contratos 1-10 páginas | ChatGPT | Capacidad suficiente |
| Contratos 10-50 páginas | Claude | Ventana de contexto extendida |
| Contratos 50+ páginas | Claude | Único que mantiene coherencia |
| Dictámenes fiscales | Claude | Razonamiento complejo |
| Opiniones de cumplimiento | Claude | Análisis de implicaciones |
| Estados financieros | ChatGPT/Claude | Ambos funcionan bien |
| Actas constitutivas | Claude | Documentos legales extensos |
| Revisión de facturas (CFDI) | ChatGPT | Estructura predecible |
| Análisis de XML masivo | Gemini | Si están en Drive |

**Prompt base para análisis:**
```
Analiza el siguiente [tipo de documento]. Identifica:
1. Puntos clave relevantes para efectos fiscales
2. Posibles riesgos o contingencias
3. Cláusulas que requieren atención especial
4. Recomendaciones específicas

[Pegar o subir documento]
```

---

## 3. Investigación Fiscal

| Tarea Específica | Herramienta | Razón |
|------------------|-------------|-------|
| Topes y límites vigentes | Gemini | Acceso a info actualizada |
| Criterios SAT recientes | Gemini | Búsqueda en tiempo real |
| Interpretación de artículos LISR | Claude | Análisis profundo |
| Interpretación de artículos CFF | Claude | Razonamiento legal |
| Jurisprudencia y tesis | Gemini | Búsqueda con fuentes |
| Resolución Miscelánea | Gemini | Cambios frecuentes |
| Comparativo de regímenes | ChatGPT | Estructura clara |
| Dudas fiscales generales | ChatGPT | Respuestas rápidas |
| Plazos y fechas límite | Gemini | Calendario actualizado |

**Prompt base para investigación:**
```
Necesito información sobre [tema fiscal específico] en México para [año actual].
Contexto: [situación del cliente]
Específicamente necesito saber:
1. [Pregunta 1]
2. [Pregunta 2]
Incluye fundamento legal si es posible.
```

**ADVERTENCIA:** Siempre verifica información fiscal en fuentes oficiales (SAT, DOF, SCJN).

---

## 4. Cálculos y Reportes

| Tarea Específica | Herramienta | Razón |
|------------------|-------------|-------|
| Cálculos con explicación paso a paso | ChatGPT | Pedagogía excelente |
| Cálculo de ISR personas físicas | ChatGPT | Puede mostrar procedimiento |
| Cálculo de nómina | ChatGPT | Estructurado y claro |
| Análisis de datos en Sheets | Gemini | Conexión directa |
| Proyecciones financieras | ChatGPT | Code Interpreter |
| Reportes ejecutivos | Claude | Síntesis de múltiples fuentes |
| Comparativos numéricos | ChatGPT | Tablas claras |
| Análisis de flujo de efectivo | ChatGPT/Claude | Ambos funcionan |

**Prompt base para cálculos:**
```
Calcula [tipo de cálculo] con los siguientes datos:
[Lista de datos]

Muestra:
1. El procedimiento paso a paso
2. El fundamento de cada paso
3. El resultado final
4. Verificación del cálculo
```

---

## 5. Automatización

| Tarea Específica | Herramienta | Razón |
|------------------|-------------|-------|
| Asistente de preguntas frecuentes | ChatGPT (Custom GPT) | Fácil de crear |
| Asistente especializado RESICO | ChatGPT (Custom GPT) | Personalizable |
| Asistente de nóminas | ChatGPT (Custom GPT) | Casos repetitivos |
| Flujos con Google Workspace | Gemini | Integración nativa |
| Análisis recurrente de documentos | Claude Projects | Memoria de contexto |
| Plantillas inteligentes | ChatGPT | Versatilidad |

---

## Framework de Decisión Rápida

### Las 3 Preguntas Clave

```
┌─────────────────────────────────────────────────────────┐
│  1. ¿Qué tipo de tarea es?                              │
│     → Redacción/General = ChatGPT                       │
│     → Análisis profundo = Claude                        │
│     → Búsqueda/Research = Gemini                        │
├─────────────────────────────────────────────────────────┤
│  2. ¿Necesito información de 2024-2025?                 │
│     → Sí = Gemini (o Perplexity)                        │
│     → No = ChatGPT o Claude                             │
├─────────────────────────────────────────────────────────┤
│  3. ¿Qué tan largo/complejo es?                         │
│     → Corto/Simple = ChatGPT                            │
│     → Largo/Complejo = Claude                           │
└─────────────────────────────────────────────────────────┘
```

### Árbol de Decisión Visual

```
                    ¿Necesitas info actualizada (2024-2025)?
                           /                    \
                         SÍ                      NO
                         |                        |
                      GEMINI            ¿Documento largo (+10 págs)?
                                              /          \
                                            SÍ            NO
                                            |              |
                                         CLAUDE    ¿Análisis complejo?
                                                      /        \
                                                    SÍ          NO
                                                    |            |
                                                 CLAUDE      CHATGPT
```

---

## Combinaciones Poderosas

### Para Investigación Fiscal Completa:
1. **Gemini** → Buscar información actualizada y fuentes
2. **Claude** → Analizar e interpretar la normativa encontrada
3. **ChatGPT** → Redactar explicación para el cliente

### Para Revisión de Contratos:
1. **Claude** → Análisis completo del documento
2. **ChatGPT** → Redactar resumen ejecutivo
3. **Gemini** → Verificar referencias legales actuales

### Para Responder Requerimientos SAT:
1. **Gemini** → Verificar criterios y lineamientos actuales
2. **Claude** → Analizar el requerimiento y preparar respuesta
3. **ChatGPT** → Pulir redacción final

---

## Límites y Precauciones

### ChatGPT
- Fecha de corte de conocimiento: Abril 2024 (GPT-4)
- No usar para: Información fiscal del año en curso
- Verificar siempre: Cálculos numéricos, referencias a artículos

### Claude
- Fecha de corte de conocimiento: Principios 2024
- No usar para: Búsquedas en tiempo real
- Verificar siempre: Actualizaciones de leyes, montos vigentes

### Gemini
- Tiene acceso a internet pero puede equivocarse
- No usar para: Análisis de documentos muy extensos
- Verificar siempre: Que las fuentes citadas existan y sean correctas

---

## Regla de Oro

> **"La IA es tu co-piloto, no tu piloto."**
>
> Tú tienes la responsabilidad profesional, el criterio experto y la firma.
> Usa estas herramientas para ser más eficiente, no para delegar tu juicio.

---

## Acceso Rápido

| Herramienta | URL | Versión Recomendada |
|-------------|-----|---------------------|
| ChatGPT | chat.openai.com | Plus ($20 USD/mes) o Free |
| Claude | claude.ai | Pro ($20 USD/mes) o Free |
| Gemini | gemini.google.com | Advanced ($20 USD/mes) o Free |

---

*Matriz de Decisión v1.0 - Reto 12 Días de IA para Contadores*
*TodoConta.com*
