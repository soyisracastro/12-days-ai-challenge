# Día 2: Ejercicios Prácticos
## Caso Comparativo CFDI 4.0

**Tiempo estimado:** 30-45 minutos
**Objetivo:** Experimentar las diferencias entre las 3 herramientas analizando el mismo CFDI.

---

## Ejercicio 1: Comparación del Caso Base (20 minutos)

### Objetivo
Replicar el análisis del caso práctico y documentar las diferencias.

### Instrucciones

**Paso 1:** Abre las 3 herramientas en pestañas diferentes
- ChatGPT: chat.openai.com
- Claude: claude.ai
- Gemini: gemini.google.com

**Paso 2:** Copia y pega este prompt en las 3 herramientas:

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

**Paso 3:** Compara las respuestas y llena esta tabla:

| Pregunta | ChatGPT | Claude | Gemini |
|----------|---------|--------|--------|
| ¿Identificó que G03 podría no ser el uso óptimo? | Sí / No / Parcial | Sí / No / Parcial | Sí / No / Parcial |
| ¿Mencionó que debería ser I02 para activo fijo? | | | |
| ¿Explicó la diferencia entre gasto y activo fijo? | | | |
| ¿Indicó la necesidad del complemento de pago? | | | |
| ¿Mencionó verificar RFC del emisor? | | | |
| ¿Citó artículos de ley o fundamento legal? | | | |
| ¿Sugirió herramientas oficiales del SAT? | | | |
| ¿La respuesta es clara para el cliente? | 1-5 | 1-5 | 1-5 |
| Tiempo de respuesta (aprox) | seg | seg | seg |

**Paso 4:** Reflexiona y anota:

1. ¿Cuál herramienta dio la respuesta más completa?
   ```

   ```

2. ¿Cuál herramienta usarías para responder rápido al cliente?
   ```

   ```

3. ¿Cuál herramienta usarías para tu análisis interno?
   ```

   ```

---

## Ejercicio 2: Tu Propio CFDI (15 minutos)

### Objetivo
Aplicar lo aprendido con una factura real de tu trabajo.

### Instrucciones

**Paso 1:** Selecciona una factura real (o usa este ejemplo alternativo si no tienes una a la mano)

**Ejemplo alternativo:**
```
Emisor: Sistemas Digitales de México SA de CV
RFC: SDM150612TK8
Concepto: 3 laptops HP modelo X para uso administrativo - $45,000 c/u
Subtotal: $135,000
IVA: $21,600
Total: $156,600
Uso CFDI: G03
Método: PUE
Forma: 03 - Transferencia
```

**Paso 2:** Adapta el prompt base con los datos de tu factura:

```
Actúa como contador fiscal especialista en CFDI 4.0 en México.

Mi cliente recibió esta factura:

DATOS DEL CFDI:
- Emisor: [NOMBRE]
- RFC Emisor: [RFC]
- Concepto: [DESCRIPCIÓN]
- Subtotal: $[MONTO]
- IVA: $[MONTO]
- Total: $[MONTO]
- Uso CFDI: [USO]
- Método de Pago: [PUE/PPD]
- Forma de Pago: [CÓDIGO]

Mi cliente es: [PERSONA FÍSICA/MORAL] [RÉGIMEN]

ANALIZA:
1. ¿El uso de CFDI es correcto para este concepto?
2. ¿El método y forma de pago son adecuados?
3. ¿Es deducible? ¿Bajo qué tratamiento?
4. ¿Qué puntos de atención identificas?

Sé específico.
```

**Paso 3:** Usa el flujo recomendado:

1. **Gemini primero:** Verifica el RFC del emisor
   ```
   Busca información sobre el RFC [RFC] en México.
   ¿Está activo? ¿Hay alertas del SAT?
   ```

2. **Claude segundo:** Análisis profundo del CFDI
   ```
   [Tu prompt adaptado]
   ```

3. **ChatGPT tercero:** Redacta respuesta para cliente
   ```
   Basándote en este análisis: [pegar puntos clave de Claude]

   Redacta una respuesta breve y clara para mi cliente explicando
   si la factura está correcta y qué debe hacer.

   Tono: profesional pero accesible.
   Longitud: 2-3 párrafos máximo.
   ```

**Paso 4:** Documenta tu experiencia:

| Herramienta | ¿Qué te aportó? | ¿Lo usarías de nuevo para esto? |
|-------------|-----------------|--------------------------------|
| Gemini | | |
| Claude | | |
| ChatGPT | | |

---

## Ejercicio 3: Casos de Uso Rápidos (10 minutos)

### Objetivo
Practicar la decisión de cuál herramienta usar.

### Instrucciones

Para cada situación, elige la herramienta más adecuada y justifica brevemente.

#### Caso A
> Un cliente te manda por WhatsApp una foto de una factura y pregunta: "¿Puedo deducir esto?"

**Herramienta:** ____________
**Justificación:**
```

```

#### Caso B
> Recibes un CFDI de un proveedor nuevo por $800,000 de maquinaria. Nunca has trabajado con este proveedor.

**Herramienta(s):** ____________
**Justificación:**
```

```

#### Caso C
> Un cliente pregunta si el tope de deducción de automóviles cambió para este año.

**Herramienta:** ____________
**Justificación:**
```

```

#### Caso D
> Necesitas analizar un contrato de arrendamiento de 30 páginas para verificar implicaciones fiscales del CFDI que recibirás mensualmente.

**Herramienta:** ____________
**Justificación:**
```

```

#### Caso E
> Quieres crear un documento estándar que explique a tus clientes los usos de CFDI más comunes.

**Herramienta:** ____________
**Justificación:**
```

```

<details>
<summary>Ver respuestas sugeridas</summary>

- **Caso A:** ChatGPT - Respuesta rápida y clara para reenviar
- **Caso B:** Gemini (verificar proveedor) + Claude (análisis profundo del CFDI)
- **Caso C:** Gemini - Información actualizada del año en curso
- **Caso D:** Claude - Documentos largos y análisis complejo
- **Caso E:** ChatGPT - Bueno para crear contenido estructurado y claro

</details>

---

## Ejercicio 4: Checklist de Validación (5 minutos)

### Objetivo
Crear tu propia rutina de validación de CFDI con IA.

### Tu Checklist Personal

Basándote en lo aprendido, completa tu checklist de validación:

#### Para CFDI Rutinarios (montos menores, proveedores conocidos):
- [ ] Herramienta a usar: ____________
- [ ] Tiempo estimado: ____________
- [ ] Validaciones mínimas:
  - [ ] ____________
  - [ ] ____________
  - [ ] ____________

#### Para CFDI de Monto Alto o Proveedor Nuevo:
- [ ] Paso 1 con ____________: ____________
- [ ] Paso 2 con ____________: ____________
- [ ] Paso 3 con ____________: ____________
- [ ] Validaciones adicionales:
  - [ ] ____________
  - [ ] ____________

#### Herramientas Oficiales a Usar Siempre:
- [ ] Verificador CFDI SAT: ____________
- [ ] Consulta 69-B: ____________
- [ ] Otro: ____________

---

## Checklist de Cierre del Día 2

Antes de terminar, verifica que hayas completado:

- [ ] Ejecuté el prompt base en las 3 herramientas
- [ ] Documenté las diferencias en la tabla comparativa
- [ ] Probé con una factura real (o el caso alternativo)
- [ ] Apliqué el flujo de 3 pasos (Gemini → Claude → ChatGPT)
- [ ] Completé los casos de decisión rápida
- [ ] Creé mi checklist personal de validación

---

## Prepárate para el Día 3

Mañana aprenderemos **Prompts Universales**: la fórmula definitiva y 10 plantillas listas para copiar.

**Opcional para mañana:**
Piensa en 3 tareas que haces frecuentemente donde podrías usar un prompt estandarizado.

---

## Recursos Adicionales

### Links Oficiales del SAT:
- Verificador CFDI: https://verificacfdi.facturaelectronica.sat.gob.mx/
- Lista 69-B: https://www.sat.gob.mx/consulta/76674/consulta-la-relacion-de-contribuyentes-incumplidos
- Consulta RFC: https://www.sat.gob.mx/aplicacion/operacion/31274/consulta-tu-informacion-fiscal

### Prompts Guardados del Día 2:

**Prompt: Análisis Rápido de CFDI**
```
Analiza este CFDI y dime en 3 puntos:
1. ¿Está correctamente emitido?
2. ¿Es deducible?
3. ¿Qué debo verificar?

Datos: [pegar datos del CFDI]
```

**Prompt: Verificar Uso de CFDI**
```
¿El uso de CFDI [CÓDIGO] es correcto para [CONCEPTO]?
Si no es el correcto, ¿cuál debería ser y por qué?
```

**Prompt: Redactar Respuesta a Cliente**
```
Redacta un mensaje breve (2-3 párrafos) para mi cliente explicando
que su factura por [CONCEPTO] está/no está correcta porque [RAZÓN].

Tono: profesional pero amigable.
```

---

*Ejercicios Día 2 - Reto 12 Días de IA para Contadores*
*TodoConta.com*
