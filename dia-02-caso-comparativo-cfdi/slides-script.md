# Día 2: Caso Comparativo CFDI 4.0
## Slides con Script para Teleprompter

---

## SLIDE 1: Portada

**Visual:** Título "Caso Comparativo CFDI 4.0" + Logos de ChatGPT, Claude, Gemini

### Script:
> Bienvenidos al Día 2 del Reto. Ayer hablamos de teoría, hoy vamos a la práctica pura. Vamos a tomar un problema real de CFDI 4.0, el mismo problema, y lo vamos a resolver con las tres herramientas. Vas a ver con tus propios ojos las diferencias en velocidad, precisión y estilo. Al terminar, sabrás exactamente cuál usar para cada situación de facturación.

---

## SLIDE 2: ¿Por Qué Este Ejercicio?

**Visual:** Diagrama de 1 problema → 3 herramientas → 3 resultados

### Script:
> La mejor forma de aprender cuándo usar cada herramienta es verlas en acción con el mismo problema. Es como probar tres autos en la misma pista. Todos llegan a la meta, pero cada uno tiene fortalezas diferentes. Hoy vas a experimentar esto directamente, y al final podrás tomar decisiones informadas para tu práctica diaria.

---

## SLIDE 3: El Caso de Hoy

**Visual:** Icono de factura + descripción del problema

### El Problema:
Un cliente te envía una factura (CFDI) que recibió de un proveedor y te pregunta:
1. ¿Esta factura está bien emitida?
2. ¿Puedo deducirla?
3. ¿Qué debo verificar?

### Script:
> Nuestro caso es muy común. Un cliente recibe una factura de un proveedor y antes de pagarla o deducirla, te pregunta si está bien. Parece simple, pero tiene muchos ángulos: validar datos fiscales, revisar que cumpla con CFDI 4.0, verificar uso de CFDI correcto, y confirmar que sea deducible. Vamos a ver cómo cada herramienta aborda esto.

---

## SLIDE 4: El CFDI de Ejemplo

**Visual:** Imagen de una factura o representación visual de los datos

### Datos del CFDI:
```
Emisor: Distribuidora de Oficinas del Norte SA de CV
RFC Emisor: DON180523AB1
Receptor: Tu cliente (Persona Moral - Régimen General)
RFC Receptor: XYZ010101AAA
Concepto: "Mobiliario de oficina"
Subtotal: $45,000.00
IVA: $7,200.00
Total: $52,200.00
Uso CFDI: G03 - Gastos en general
Método de Pago: PPD - Pago en parcialidades o diferido
Forma de Pago: 99 - Por definir
```

### Script:
> Este es nuestro CFDI de ejemplo. Una factura por mobiliario de oficina por más de 52 mil pesos. Tiene uso de CFDI G03, método de pago PPD porque aún no se ha pagado, y forma de pago 99. A simple vista parece normal, pero hay varios puntos que debemos validar. Vamos a pedirle a cada herramienta que nos ayude a analizarla.

---

## SLIDE 5: El Prompt que Usaremos

**Visual:** Bloque de código con el prompt

### Script:
> Vamos a usar exactamente el mismo prompt en las tres herramientas. Esto es importante para que la comparación sea justa. El prompt incluye el rol, los datos del CFDI, y lo que queremos que analice. Toma nota porque vas a usarlo en tu ejercicio práctico.

---

## SLIDE 6: El Prompt Completo

**Visual:** Prompt en pantalla completa

```
Actúa como contador fiscal especialista en CFDI 4.0 en México.

Mi cliente (persona moral, régimen general) recibió esta factura de un proveedor:

DATOS DEL CFDI:
- Emisor: Distribuidora de Oficinas del Norte SA de CV
- RFC Emisor: DON180523AB1
- Concepto: Mobiliario de oficina
- Subtotal: $45,000.00
- IVA: $7,200.00
- Total: $52,200.00
- Uso CFDI: G03 - Gastos en general
- Método de Pago: PPD
- Forma de Pago: 99

ANALIZA:
1. ¿El CFDI cumple con los requisitos de CFDI 4.0?
2. ¿El uso de CFDI G03 es correcto para este tipo de gasto?
3. ¿El método PPD y forma 99 son correctos?
4. ¿Qué debe hacer mi cliente para poder deducir este gasto?
5. ¿Qué banderas rojas o puntos de atención detectas?

Sé específico y práctico en tus recomendaciones.
```

### Script:
> Este es el prompt completo. Fíjate que especificamos el rol, damos todos los datos relevantes del CFDI, y hacemos preguntas específicas. No es un prompt vago, es directo y estructurado. Ahora veamos qué nos responde cada herramienta.

---

## SLIDE 7: Respuesta de ChatGPT

**Visual:** Logo ChatGPT + Resumen de respuesta

### Características de la respuesta:
- Estructura clara con numeración
- Lenguaje accesible
- Explica conceptos mientras responde
- Buena para compartir con cliente

### Script:
> ChatGPT nos da una respuesta muy estructurada y fácil de leer. Numera cada punto, explica el porqué de cada validación, y usa un lenguaje que podrías compartir directamente con tu cliente. Destaca que el uso G03 es correcto para gastos generales, valida que PPD con forma 99 es adecuado cuando aún no se paga, y recuerda la necesidad del complemento de pago posterior. Es una respuesta sólida para el día a día.

---

## SLIDE 8: Fortalezas de ChatGPT en CFDI

**Visual:** Lista con checks verdes

✅ Respuestas rápidas y claras
✅ Lenguaje fácil de entender
✅ Buena estructura para copiar/pegar
✅ Explica el "por qué" de cada punto
✅ Ideal para comunicar a clientes

### Script:
> Las fortalezas de ChatGPT para temas de CFDI son claras. Es rápido, estructura bien la información, y el tono es perfecto si necesitas reenviar la explicación a tu cliente. No es el más técnico, pero para validaciones estándar cumple muy bien.

---

## SLIDE 9: Respuesta de Claude

**Visual:** Logo Claude + Resumen de respuesta

### Características de la respuesta:
- Análisis más profundo y técnico
- Menciona fundamentos legales
- Identifica riesgos menos obvios
- Matiza las respuestas cuando hay ambigüedad

### Script:
> Claude toma un enfoque diferente. Su análisis es más profundo y técnico. No solo dice que el uso G03 es correcto, explica cuándo podría no serlo. Menciona artículos específicos de ley. Identifica un detalle importante: que si el mobiliario supera cierto monto, podría requerir un uso de CFDI diferente relacionado con activo fijo. Es el tipo de análisis que tú como contador aprecias, aunque quizás no lo enviarías directo al cliente.

---

## SLIDE 10: Fortalezas de Claude en CFDI

**Visual:** Lista con checks verdes

✅ Análisis profundo y matizado
✅ Cita fundamentos legales
✅ Identifica riesgos no obvios
✅ Considera casos especiales
✅ Ideal para tu análisis interno

### Script:
> Claude brilla cuando necesitas profundidad. Para casos complejos donde hay zonas grises o múltiples interpretaciones, Claude te da los matices. Es como tener una segunda opinión de un colega experimentado. Úsalo cuando tú necesites entender bien el tema, no necesariamente para explicarle al cliente.

---

## SLIDE 11: Respuesta de Gemini

**Visual:** Logo Gemini + Resumen de respuesta

### Características de la respuesta:
- Incluye información actualizada del SAT
- Puede verificar vigencia de RFC
- Sugiere usar herramientas oficiales
- Links a recursos del SAT

### Script:
> Gemini aporta algo que los otros no pueden: información en tiempo real. Menciona que podemos verificar la vigencia del RFC del emisor en el portal del SAT, sugiere validar el CFDI en la página oficial, e incluso puede buscar si hay alertas recientes del SAT sobre ese tipo de operaciones. No es el análisis más profundo, pero complementa perfectamente a las otras herramientas.

---

## SLIDE 12: Fortalezas de Gemini en CFDI

**Visual:** Lista con checks verdes

✅ Acceso a información actualizada
✅ Puede verificar datos en tiempo real
✅ Sugiere herramientas oficiales del SAT
✅ Útil para validar RFCs y estatus
✅ Complemento ideal, no sustituto

### Script:
> La fortaleza de Gemini es la actualidad. Cuando necesitas verificar si algo cambió recientemente, si un RFC está activo, o si hay nuevos criterios del SAT, Gemini es tu herramienta. No lo usaría como única fuente para análisis de CFDI, pero como complemento para validaciones es muy valioso.

---

## SLIDE 13: Comparativa Lado a Lado

**Visual:** Tabla comparativa de las 3 herramientas

| Aspecto | ChatGPT | Claude | Gemini |
|---------|---------|--------|--------|
| Velocidad | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ |
| Profundidad | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ |
| Fundamento legal | ⭐⭐ | ⭐⭐⭐ | ⭐⭐ |
| Info actualizada | ⭐ | ⭐ | ⭐⭐⭐ |
| Claridad | ⭐⭐⭐ | ⭐⭐ | ⭐⭐ |
| Para cliente | ⭐⭐⭐ | ⭐⭐ | ⭐⭐ |

### Script:
> Veamos la comparación lado a lado. ChatGPT gana en velocidad y claridad, es el más fácil de usar para comunicación con clientes. Claude gana en profundidad y fundamento legal, ideal para tu análisis interno. Gemini gana en información actualizada, perfecto para verificaciones en tiempo real. No hay un ganador absoluto, cada uno tiene su lugar.

---

## SLIDE 14: ¿Cuándo Usar Cada Una para CFDI?

**Visual:** Diagrama de flujo o escenarios

### Script:
> Entonces, ¿cuándo usar cada una? Si un cliente te pregunta si su factura está bien y necesitas responderle rápido con algo que pueda entender, usa ChatGPT. Si tienes un caso complejo, una factura grande, o algo que huele a problema fiscal, usa Claude para tu análisis. Y si necesitas verificar que el proveedor esté activo, que no haya alertas del SAT, o cualquier dato actual, complementa con Gemini.

---

## SLIDE 15: Escenario 1 - Validación Rápida

**Visual:** Icono de velocidad + ChatGPT

### Situación:
Cliente envía factura por WhatsApp: "¿Está bien esta factura?"

### Recomendación:
**ChatGPT** → Respuesta rápida y clara que puedes reenviar

### Script:
> Escenario uno: validación rápida. El cliente te manda la factura por WhatsApp y quiere saber si está bien. No es un caso complejo, solo necesitas validar lo básico. ChatGPT te da una respuesta en segundos que puedes copiar y enviar. Eficiencia pura.

---

## SLIDE 16: Escenario 2 - Factura de Monto Alto

**Visual:** Icono de dinero + Claude

### Situación:
Factura por $500,000+ de un nuevo proveedor

### Recomendación:
**Claude** → Análisis profundo de riesgos y requisitos

### Script:
> Escenario dos: factura de monto alto. Cuando hay mucho dinero en juego, no quieres respuestas superficiales. Claude te ayuda a identificar todos los requisitos, los riesgos potenciales, y las validaciones adicionales que debes hacer. Es tu due diligence con ayuda de IA.

---

## SLIDE 17: Escenario 3 - Proveedor Desconocido

**Visual:** Icono de lupa + Gemini

### Situación:
Primera factura de un proveedor que no conoces

### Recomendación:
**Gemini** → Verificar RFC, estatus, y posibles alertas

### Script:
> Escenario tres: proveedor desconocido. Primera vez que ves a este proveedor y quieres asegurarte de que no sea una empresa fantasma o que esté en lista negra del SAT. Gemini puede ayudarte a verificar el estatus del RFC y buscar si hay alertas recientes. Es tu capa de verificación antes de procesar.

---

## SLIDE 18: El Flujo Ideal para CFDI Importantes

**Visual:** Flujo de 3 pasos

```
PASO 1: Gemini
→ Verificar RFC emisor
→ Buscar alertas SAT

PASO 2: Claude
→ Análisis profundo del CFDI
→ Identificar riesgos

PASO 3: ChatGPT
→ Redactar resumen para cliente
→ Comunicar hallazgos
```

### Script:
> Para facturas importantes, te recomiendo este flujo de tres pasos. Primero, Gemini para verificar que el emisor está limpio. Segundo, Claude para hacer el análisis profundo del CFDI y detectar cualquier problema. Tercero, ChatGPT para redactar el resumen o comunicación al cliente. Es como tener un equipo de tres especialistas trabajando para ti.

---

## SLIDE 19: Errores Comunes en CFDI 4.0

**Visual:** Lista con iconos de alerta

### Los que la IA te ayuda a detectar:
- ❌ Uso de CFDI incorrecto (G01 vs G03 vs I01)
- ❌ Método de pago incompatible con la operación
- ❌ Falta de complemento de pago en PPD
- ❌ RFC del receptor con errores
- ❌ Datos del emisor inconsistentes

### Script:
> Aprovechemos para repasar errores comunes en CFDI 4.0 que la IA te ayuda a detectar. El uso de CFDI incorrecto es muy frecuente, especialmente confundir gastos en general con adquisición de mercancías. El método de pago PPD sin complemento posterior es otro clásico. Y errores en RFC, tanto del emisor como del receptor. Las tres herramientas pueden identificar estos problemas si les das los datos correctos.

---

## SLIDE 20: Usos de CFDI Más Comunes

**Visual:** Tabla de referencia rápida

| Código | Descripción | Cuándo Usar |
|--------|-------------|-------------|
| G01 | Adquisición de mercancías | Compra de inventario para venta |
| G03 | Gastos en general | Servicios, materiales, consumibles |
| I01 | Construcciones | Obras y edificaciones |
| I02 | Mobiliario y equipo de oficina | Activo fijo de oficina |
| I03 | Equipo de transporte | Vehículos |
| I04 | Equipo de cómputo | Computadoras, servidores |
| D01 | Honorarios médicos | Gastos médicos personales |
| P01 | Por definir | Cuando no aplica deducción |

### Script:
> Aquí tienes una referencia rápida de los usos de CFDI más comunes. Nota algo importante: en nuestro caso de ejemplo, el mobiliario de oficina por 45 mil pesos probablemente debería usar I02, no G03. Este es exactamente el tipo de detalle que Claude identificó en su análisis. G03 es para gastos generales, pero mobiliario es activo fijo. Esta distinción importa para efectos de depreciación fiscal.

---

## SLIDE 21: Prompt Avanzado para CFDI

**Visual:** Prompt mejorado

```
Actúa como auditor fiscal especializado en CFDI 4.0.

CFDI A ANALIZAR:
[Datos del CFDI]

CONTEXTO:
- Giro del receptor: [Industria/Comercio/Servicios]
- Relación con emisor: [Primera vez/Recurrente]
- Monto vs operaciones típicas: [Normal/Alto/Inusual]

ANÁLISIS REQUERIDO:
1. Validación de estructura CFDI 4.0
2. Verificación de uso de CFDI correcto
3. Consistencia método/forma de pago
4. Análisis de deducibilidad
5. Banderas rojas y riesgos
6. Documentación complementaria necesaria
7. Recomendaciones específicas

FORMATO: Resumen ejecutivo + detalle por punto
```

### Script:
> Para análisis más completos, puedes usar este prompt avanzado. Incluye más contexto sobre la operación, lo que permite a la IA darte recomendaciones más precisas. El giro del negocio, si es primera vez con ese proveedor, y si el monto es inusual, todo esto ayuda a obtener mejores respuestas.

---

## SLIDE 22: Limitaciones Importantes

**Visual:** Iconos de advertencia

### Recuerda:
- La IA NO puede validar el CFDI en el SAT
- La IA NO verifica sellos digitales
- La IA puede tener información desactualizada (ChatGPT/Claude)
- La IA NO sustituye tu criterio profesional

### Script:
> Es crucial recordar las limitaciones. La IA puede analizar los datos que le das, pero no puede entrar al portal del SAT a validar que el CFDI realmente exista o que los sellos sean válidos. Para eso necesitas las herramientas oficiales. La IA es tu asistente de análisis, no tu sistema de validación oficial.

---

## SLIDE 23: Herramientas Oficiales que Complementan

**Visual:** Logos/iconos de herramientas SAT

### Siempre usa también:
- **Verificador de CFDI del SAT:** verificacfdi.facturaelectronica.sat.gob.mx
- **Consulta de RFC:** sat.gob.mx
- **Lista negra 69-B:** sat.gob.mx/consulta/operaciones-inexistentes

### Script:
> Estas son las herramientas oficiales que siempre debes usar como complemento. El verificador de CFDI para confirmar que la factura existe y es válida. La consulta de RFC para verificar estatus del emisor. Y la lista del 69-B para asegurarte de que no estés recibiendo facturas de operaciones inexistentes. La IA te ayuda a analizar, pero la validación oficial es insustituible.

---

## SLIDE 24: Tu Tarea de Hoy

**Visual:** Checklist de ejercicios

### Ejercicio Principal (30 min):
1. Usa el prompt del caso con las 3 herramientas
2. Compara las respuestas lado a lado
3. Identifica fortalezas de cada una

### Ejercicio Avanzado (15 min):
4. Usa una factura real de tu trabajo
5. Aplica el flujo de 3 pasos
6. Documenta qué herramienta usarías para qué

### Script:
> Ahora es tu turno de experimentar. El ejercicio principal es replicar lo que hicimos hoy con las tres herramientas y comparar. El ejercicio avanzado es usar una factura real de tu trabajo y aplicar el flujo de tres pasos. Esto te va a dar experiencia práctica que no se obtiene solo viendo la clase.

---

## SLIDE 25: Recursos del Día 2

**Visual:** Lista de recursos con iconos

📥 Caso práctico completo con prompts
📥 Guía de Usos de CFDI
📥 Checklist de validación de CFDI
📥 Plantilla de comparación de herramientas

### Script:
> En tu área de recursos tienes todo lo necesario. El caso práctico con los prompts listos para copiar. Una guía de usos de CFDI para referencia rápida. Un checklist de validación que puedes usar con cualquier factura. Y una plantilla para documentar tu comparación de hoy.

---

## SLIDE 26: Mañana - Día 3

**Visual:** Preview del Día 3

### Día 3: Prompts Universales
- La fórmula ROL + CONTEXTO + TAREA + FORMATO
- 10 plantillas copy-paste para contadores
- Adaptables a cualquier herramienta

### Script:
> Mañana cerramos la semana de fundamentos con Prompts Universales. Vas a llevarte 10 plantillas listas para usar que funcionan en cualquier herramienta. Es la base que vas a usar durante todo el reto y en tu práctica profesional.

---

## SLIDE 27: Cierre

**Visual:** Mensaje clave + logo del reto

### Script:
> Hoy viste en acción las diferencias reales entre las herramientas. ChatGPT para rapidez y claridad, Claude para profundidad y análisis, Gemini para información actualizada. No hay una mejor, hay una más adecuada para cada situación. Practica con tus propias facturas y desarrolla tu criterio. Nos vemos mañana en el Día 3.

---

## Notas de Producción

**Duración estimada:** 25-28 minutos
**Ritmo sugerido:** Pausar en slides 7, 9, 11 para mostrar respuestas reales
**Interactividad:** Considera mostrar las herramientas en vivo si es posible

**Tips:**
- Tener las 3 herramientas abiertas para demo en vivo
- Preparar capturas de pantalla como respaldo
- El caso de mobiliario con G03 vs I02 es un buen punto de discusión
