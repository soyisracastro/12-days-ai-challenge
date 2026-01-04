# Caso Práctico: Análisis Comparativo de CFDI 4.0
## Día 2 - Reto 12 Días de IA para Contadores

---

## El Escenario

Tu cliente, **Comercializadora del Bajío SA de CV** (persona moral, régimen general), te envía una factura que recibió de un proveedor nuevo. Antes de autorizar el pago y registrarla para deducción, quiere que la revises.

---

## Datos del CFDI

```
═══════════════════════════════════════════════════════════════
                         CFDI - FACTURA
═══════════════════════════════════════════════════════════════

EMISOR:
  Razón Social: Distribuidora de Oficinas del Norte SA de CV
  RFC: DON180523AB1
  Régimen Fiscal: 601 - General de Ley Personas Morales
  Domicilio Fiscal: Monterrey, Nuevo León

RECEPTOR:
  Razón Social: Comercializadora del Bajío SA de CV
  RFC: CBA200115XY9
  Régimen Fiscal: 601 - General de Ley Personas Morales
  Uso CFDI: G03 - Gastos en general
  Domicilio Fiscal: León, Guanajuato

───────────────────────────────────────────────────────────────
CONCEPTOS:
───────────────────────────────────────────────────────────────

Cantidad  Unidad   Descripción                    Precio Unit.    Importe
────────  ──────   ───────────────────────────    ────────────    ─────────
   5      Pieza    Escritorio ejecutivo           $5,000.00       $25,000.00
                   madera-metal modelo EJ-500

  10      Pieza    Silla ergonómica               $2,000.00       $20,000.00
                   modelo SE-200 con ruedas

───────────────────────────────────────────────────────────────
                                          Subtotal: $45,000.00
                                          IVA 16%:   $7,200.00
                                          ─────────────────────
                                          TOTAL:    $52,200.00
───────────────────────────────────────────────────────────────

DATOS DE PAGO:
  Método de Pago: PPD - Pago en parcialidades o diferido
  Forma de Pago: 99 - Por definir
  Condiciones de Pago: 30 días

DATOS FISCALES:
  Fecha de Emisión: [Fecha actual]
  Folio Fiscal (UUID): 8A5C7D9E-1234-5678-ABCD-EF0123456789
  Certificado SAT: 00001000000XXXXXX

═══════════════════════════════════════════════════════════════
```

---

## Las Preguntas del Cliente

1. ¿Esta factura está correctamente emitida según CFDI 4.0?
2. ¿El uso de CFDI "G03 - Gastos en general" es el correcto?
3. ¿El método PPD y forma de pago 99 están bien?
4. ¿Puedo deducir esta compra? ¿Qué necesito?
5. ¿Ves algún problema o riesgo con esta factura?

---

## El Prompt para las 3 Herramientas

Copia exactamente este prompt y úsalo en ChatGPT, Claude y Gemini:

```
Actúa como contador fiscal especialista en CFDI 4.0 en México.

Mi cliente (Comercializadora del Bajío SA de CV, persona moral régimen general)
recibió esta factura de un proveedor:

DATOS DEL CFDI:
- Emisor: Distribuidora de Oficinas del Norte SA de CV
- RFC Emisor: DON180523AB1
- Régimen Emisor: 601 - General de Ley PM

- Receptor: Comercializadora del Bajío SA de CV
- RFC Receptor: CBA200115XY9
- Uso CFDI: G03 - Gastos en general

- Conceptos:
  * 5 escritorios ejecutivos a $5,000 c/u = $25,000
  * 10 sillas ergonómicas a $2,000 c/u = $20,000

- Subtotal: $45,000.00
- IVA: $7,200.00
- Total: $52,200.00

- Método de Pago: PPD - Pago en parcialidades o diferido
- Forma de Pago: 99 - Por definir
- Condiciones: Pago a 30 días

ANALIZA Y RESPONDE:
1. ¿El CFDI cumple con los requisitos de CFDI 4.0?
2. ¿El uso de CFDI G03 es el correcto para mobiliario de oficina?
3. ¿El método PPD y forma 99 son apropiados para esta operación?
4. ¿Qué debe hacer mi cliente para poder deducir este gasto?
5. ¿Qué banderas rojas o puntos de atención identificas?
6. ¿Qué documentación adicional recomiendas solicitar?

Sé específico y práctico en tus recomendaciones.
```

---

## Qué Esperar de Cada Herramienta

### ChatGPT Típicamente:
- Respuesta estructurada y numerada
- Lenguaje claro y directo
- Explica cada punto de forma accesible
- Buena para compartir con el cliente
- Puede no profundizar en matices técnicos

### Claude Típicamente:
- Análisis más profundo y técnico
- Identifica que G03 podría no ser el uso óptimo
- Menciona implicaciones de activo fijo vs gasto
- Cita fundamentos legales cuando es relevante
- Matiza las respuestas considerando casos especiales

### Gemini Típicamente:
- Puede sugerir verificar RFC en portal SAT
- Menciona herramientas de validación oficial
- Acceso a información actualizada del SAT
- Puede buscar si hay alertas sobre el emisor
- Complementa con recursos y links

---

## El Punto Clave de Este Caso

### El "Truco" del Caso:

El uso de CFDI **G03 - Gastos en general** probablemente **NO es el más adecuado** para esta compra.

**¿Por qué?**

Los escritorios y sillas son **mobiliario de oficina**, que se considera **activo fijo**. El uso correcto sería:

- **I02 - Mobiliario y equipo de oficina por inversiones**

**Implicaciones:**
- Con G03: Se trata como gasto deducible inmediato
- Con I02: Se trata como inversión, deducible vía depreciación (10% anual)

**¿Es grave el error?**
- El CFDI es válido y deducible de cualquier forma
- Pero el tratamiento fiscal debería ser como activo fijo
- El SAT podría cuestionar la deducción inmediata de $45,000

**Este es exactamente el tipo de detalle que Claude suele identificar mejor que las otras herramientas.**

---

## Tabla de Comparación (Para Llenar)

Usa esta tabla para registrar tus observaciones:

| Criterio | ChatGPT | Claude | Gemini |
|----------|---------|--------|--------|
| ¿Identificó el problema del uso G03? | | | |
| ¿Explicó la diferencia gasto vs activo fijo? | | | |
| ¿Mencionó la necesidad del complemento de pago? | | | |
| ¿Sugirió verificar RFC del emisor? | | | |
| ¿Citó fundamento legal? | | | |
| ¿La respuesta era clara para el cliente? | | | |
| Tiempo aproximado de respuesta | | | |
| Calificación general (1-5) | | | |

---

## Respuestas de Referencia

### Lo que debe mencionar una buena respuesta:

**Sobre el Uso de CFDI:**
- G03 es para gastos generales
- Para mobiliario de oficina, I02 sería más preciso
- Implicaciones fiscales de la clasificación incorrecta

**Sobre el Método de Pago:**
- PPD es correcto cuando no se paga de inmediato
- Forma de pago 99 es correcta con PPD
- Se requerirá complemento de pago al momento del pago real

**Sobre Deducibilidad:**
- La factura es deducible si cumple requisitos
- Tratamiento como activo fijo (depreciación) vs gasto
- Documentación de respaldo necesaria

**Banderas Rojas a Considerar:**
- Verificar que el emisor esté activo y no en lista 69-B
- Confirmar que la operación sea real (materialidad)
- Conservar evidencia del pago cuando se realice

---

## Prompt Adicional: Profundizar en el Problema

Si quieres profundizar en el tema del uso de CFDI incorrecto, usa este prompt en Claude:

```
Continuando con el análisis anterior:

El uso de CFDI fue G03 pero los conceptos son mobiliario de oficina
(escritorios y sillas).

Analiza:
1. ¿Cuál debería ser el uso de CFDI correcto según el Anexo 20?
2. ¿Qué implicaciones fiscales tiene usar G03 vs I02?
3. ¿El receptor puede deducir con G03 o debe solicitar corrección?
4. ¿Cómo afecta esto al tratamiento de depreciación?
5. ¿Qué riesgo existe si el SAT revisa esta deducción?

Incluye fundamento en LISR y resolución miscelánea.
```

---

## Conclusión del Caso

Este caso demuestra por qué es valioso usar múltiples herramientas:

1. **ChatGPT** → Respuesta rápida y clara para la mayoría de las preguntas
2. **Claude** → Identificó el matiz técnico del uso de CFDI incorrecto
3. **Gemini** → Puede verificar estatus del proveedor en tiempo real

**La combinación de las tres te da un análisis completo.**

---

*Caso Práctico Día 2 - Reto 12 Días de IA para Contadores*
*TodoConta.com*
