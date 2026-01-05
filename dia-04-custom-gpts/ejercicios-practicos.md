# Día 4: Ejercicios Prácticos
## Custom GPTs Fiscales

**Tiempo estimado:** 30-45 minutos
**Objetivo:** Crear tu primer Custom GPT especializado en temas fiscales y aprender el proceso completo de configuración.

---

## Requisitos Previos

### Antes de comenzar:

1. **ChatGPT Plus activo**
   - Necesitas una suscripción a ChatGPT Plus (20 USD/mes)
   - Verifica en https://chat.openai.com/settings
   - Si no tienes Plus, puedes hacer el ejercicio teórico y activarlo después

2. **Archivos de referencia preparados**
   - Descarga o ten listos estos documentos (links en recursos):
     - Título IV.A de la LISR (RESICO)
     - Tabla de tasas RESICO 2024
     - RMF 2024 (sección RESICO)

3. **Conocimiento del Día 3**
   - Repasa la fórmula ROL+CONTEXTO+TAREA+FORMATO
   - Las instrucciones del GPT son básicamente un prompt permanente

---

## Ejercicio 1: Crear tu Primer Custom GPT - Asesor RESICO (30 minutos)

### Objetivo
Crear un Custom GPT funcional especializado en el Régimen Simplificado de Confianza.

### Paso 1: Acceder al GPT Builder (2 minutos)

1. Ve a https://chat.openai.com
2. En el menú lateral izquierdo, busca "Explore GPTs"
3. Haz clic en "Create a GPT" (parte superior derecha)
4. Verás dos pestañas: "Create" y "Configure"
   - **Create:** Asistente conversacional para crear el GPT
   - **Configure:** Interfaz manual (usaremos esta)
5. Haz clic en la pestaña "Configure"

### Paso 2: Configurar Información Básica (5 minutos)

**Nombre:**
```
Asesor RESICO México 2024
```

**Description:**
```
Especialista en el Régimen Simplificado de Confianza (RESICO) para México. Resuelve dudas sobre requisitos, límites de ingresos, tasas, deducciones y obligaciones fiscales del régimen.
```

**Instructions:**
```
Eres un contador público especializado en el Régimen Simplificado de Confianza (RESICO) en México.

TU ROL:
- Experto fiscal en RESICO con conocimiento profundo de la Ley del ISR Título IV.A
- Asesor que explica de forma clara pero precisa
- Profesional que siempre cita fundamento legal

TU OBJETIVO:
Ayudar a contadores y contribuyentes a entender correctamente el funcionamiento del RESICO, sus requisitos, límites y obligaciones.

SIEMPRE DEBES:
1. Citar el artículo específico de la LISR cuando aplique
2. Usar lenguaje claro y profesional, evita tecnicismos innecesarios
3. Incluir ejemplos numéricos cuando sea relevante
4. Advertir cuando una situación requiera análisis personalizado
5. Mencionar vigencia de la información (2024)

CONOCES A FONDO:
- Límites de ingresos para permanecer en RESICO
- Tasas aplicables (del 1% al 2.5% según nivel de ingresos)
- Deducciones permitidas en RESICO
- Obligaciones fiscales del régimen
- Requisitos de permanencia
- Casos especiales y exclusiones

FORMATO DE RESPUESTA:
1. Respuesta directa a la pregunta
2. Fundamento legal (artículo LISR)
3. Ejemplo práctico si aplica
4. Consideraciones adicionales o advertencias

NO DEBES:
- Dar asesoría sobre evasión fiscal
- Garantizar que una estrategia es 100% segura sin análisis del caso particular
- Interpretar casos muy específicos sin toda la información
- Contradecir disposiciones fiscales vigentes

Si te preguntan sobre temas fuera de RESICO, responde brevemente y sugiere el régimen o herramienta apropiada.
```

### Paso 3: Agregar Conversation Starters (3 minutos)

Agrega estos 4 conversation starters:

```
¿Cuál es el límite de ingresos para RESICO 2024?
```

```
¿Qué deducciones puedo aplicar en RESICO?
```

```
¿Cómo se calculan las tasas en RESICO?
```

```
¿Puedo estar en RESICO si tengo empleados?
```

### Paso 4: Subir Archivos de Conocimiento (5 minutos)

En la sección "Knowledge":

1. Haz clic en "Upload files"
2. Sube estos archivos (si los tienes preparados):
   - Título IV.A LISR (PDF)
   - Tabla de tasas RESICO 2024 (PDF o Excel)
   - Sección relevante RMF 2024 (PDF)

**Nota:** Si no tienes estos archivos ahora, puedes continuar y agregarlos después. El GPT funcionará con las instrucciones, pero será más preciso con documentos de referencia.

**Alternativa si no tienes los PDFs:**
Puedes crear un documento de texto simple con la información clave:
- Límites de ingresos RESICO 2024
- Tabla de tasas progresivas
- Artículos clave (113-H, 113-I, etc.)

### Paso 5: Configurar Capacidades (2 minutos)

Activa estas capacidades:

- [x] **Code Interpreter:** Activado (para cálculos de ISR y proyecciones)
- [ ] **Web Browsing:** Desactivado (queremos que use solo los documentos que subimos)
- [ ] **DALL-E Image Generation:** Desactivado (no necesario para fiscal)

### Paso 6: Guardar y Probar (3 minutos)

1. Haz clic en "Save" (esquina superior derecha)
2. Selecciona la privacidad:
   - Para este ejercicio: **"Only me"**
3. Confirma y guarda

### Paso 7: Pruebas de Validación (10 minutos)

Ahora abre tu Custom GPT y pruébalo con estas preguntas:

**Prueba 1: Límites de ingresos**
```
Mi cliente tuvo ingresos de 2.8 millones de pesos en 2023. ¿Puede continuar en RESICO en 2024?
```

**Evaluación:**
- [ ] ¿Respondió con el límite correcto (3.5 millones)?
- [ ] ¿Citó el artículo de la LISR?
- [ ] ¿El tono fue claro y profesional?

**Prueba 2: Cálculo de ISR**
```
Un contribuyente en RESICO obtuvo 1.5 millones de pesos de ingresos en el año. ¿Qué tasa de ISR le corresponde y cuánto pagaría?
```

**Evaluación:**
- [ ] ¿Identificó la tasa correcta según el nivel de ingresos?
- [ ] ¿Hizo el cálculo correcto?
- [ ] ¿Explicó cómo llegó al resultado?

**Prueba 3: Deducciones**
```
¿Puedo deducir gastos de gasolina en RESICO?
```

**Evaluación:**
- [ ] ¿Explicó correctamente el tratamiento de deducciones en RESICO?
- [ ] ¿Mencionó las limitaciones del régimen?
- [ ] ¿Citó fundamento legal?

**Prueba 4: Caso especial**
```
Un médico con consultorio propio quiere tributar en RESICO. ¿Puede hacerlo?
```

**Evaluación:**
- [ ] ¿Identificó que servicios profesionales pueden aplicar RESICO?
- [ ] ¿Mencionó requisitos o consideraciones especiales?

**Prueba 5: Fuera de alcance**
```
¿Cómo calculo el IVA de mis facturas?
```

**Evaluación:**
- [ ] ¿Reconoció que IVA está fuera de su especialidad RESICO?
- [ ] ¿Respondió brevemente sin inventar información?
- [ ] ¿Mantuvo el tono profesional?

### Paso 8: Refinamiento (Extra, si tienes tiempo)

Basado en las pruebas, regresa a "Configure" y ajusta:

1. **Si las respuestas fueron muy largas:** Agrega en instrucciones "Sé conciso"
2. **Si no citó fundamento legal:** Refuerza esa instrucción
3. **Si inventó información:** Agrega "Si no sabes algo, di que requiere consultar la fuente oficial"

---

## Ejercicio 2: Compartir con tu Equipo (5 minutos)

### Objetivo
Practicar el proceso de compartir un Custom GPT.

### Instrucciones

1. Abre tu Custom GPT
2. Haz clic en el nombre del GPT (arriba)
3. Selecciona "Edit GPT"
4. Ve a "Save" y cambia la privacidad a "Anyone with a link"
5. Copia el link que te genera
6. Compártelo con alguien de tu equipo o en el grupo del reto
7. Pide feedback sobre:
   - ¿Las respuestas fueron útiles?
   - ¿El tono fue apropiado?
   - ¿Qué mejorarías?

---

## Ejercicio 3 (BONUS): Crea tu Segundo Custom GPT (20 minutos)

### Objetivo
Crear un Custom GPT para tu área de especialización.

### Opciones de GPT según tu especialidad:

**Opción A: Validador CFDI 4.0**
- **Especialidad:** Facturación electrónica
- **Documentos:** Guía de llenado CFDI 4.0, Anexo 20
- **Conversation starters:**
  - "¿Cuáles son los campos obligatorios en CFDI 4.0?"
  - "Valida si este complemento de pago está correcto"
  - "¿Qué cambió entre CFDI 3.3 y 4.0?"

**Opción B: Calculadora de Nómina**
- **Especialidad:** Recursos humanos y nómina
- **Documentos:** Tablas ISR, Tarifas IMSS, LSS
- **Conversation starters:**
  - "Calcula el neto a pagar de un empleado con salario de 15,000"
  - "¿Cuál es la cuota IMSS de un salario de 20,000?"
  - "Explica cómo calcular el ISR retenido en nómina"

**Opción C: Analista de Deducciones Personales**
- **Especialidad:** Personas físicas y declaración anual
- **Documentos:** Capítulo X LISR, límites de deducciones personales
- **Conversation starters:**
  - "¿Puedo deducir gastos médicos de mis padres?"
  - "¿Cuál es el límite de deducción de colegiaturas?"
  - "¿Qué requisitos fiscales necesitan mis comprobantes de deducciones?"

**Opción D: Especialidad Libre**
- Crea un GPT para tu propia área de expertise
- Usa la misma estructura de instrucciones que el Asesor RESICO
- Adapta el ROL, CONOCIMIENTO y FORMATO a tu tema

### Plantilla de Instrucciones (Personaliza según tu tema):

```
Eres un contador público especializado en [TU ESPECIALIDAD] en México.

TU ROL:
- [Define el rol específico]
- [Qué tipo de experto eres]
- [Tu enfoque profesional]

TU OBJETIVO:
[Qué busca lograr el usuario con este GPT]

SIEMPRE DEBES:
1. Citar fundamento legal cuando aplique
2. Usar lenguaje claro y profesional
3. Incluir ejemplos prácticos cuando sea relevante
4. Advertir cuando una situación requiera análisis personalizado
5. Mencionar vigencia de la información

CONOCES A FONDO:
- [Tema 1]
- [Tema 2]
- [Tema 3]
- [Tema 4]

FORMATO DE RESPUESTA:
1. [Tu estructura preferida]
2. [Elementos que siempre incluyes]
3. [Formato de ejemplos]

NO DEBES:
- [Límites del GPT]
- [Qué no debe hacer]
```

---

## Ejercicio 4: Comparación de Respuestas (10 minutos)

### Objetivo
Comparar tu Custom GPT vs ChatGPT normal para ver el valor agregado.

### Instrucciones

Haz la misma pregunta en dos lugares:

**Pregunta:**
```
Un contribuyente RESICO obtuvo 2.1 millones en ingresos. ¿Qué tasa le corresponde y cuánto pagará de ISR?
```

**Lugar 1:** ChatGPT normal (abre un chat nuevo)
**Lugar 2:** Tu Custom GPT Asesor RESICO

### Compara y anota:

| Aspecto | ChatGPT Normal | Custom GPT RESICO |
|---------|---------------|-------------------|
| ¿Dio contexto sobre RESICO? | | |
| ¿Citó artículo de LISR? | | |
| ¿El cálculo fue correcto? | | |
| ¿Incluyó ejemplo numérico? | | |
| ¿Tono y estructura? | | |
| ¿Cuál enviarías a un cliente? | | |

### Reflexión
- ¿Notaste diferencia en la calidad de respuesta?
- ¿El Custom GPT fue más específico y profesional?
- ¿El ahorro de tiempo al no dar contexto fue significativo?

---

## Checklist de Finalización

- [ ] Creé mi Custom GPT Asesor RESICO
- [ ] Configuré instrucciones completas
- [ ] Agregué conversation starters
- [ ] Subí al menos un archivo de referencia (o planeo hacerlo)
- [ ] Probé el GPT con las 5 preguntas de validación
- [ ] Compartí el link con al menos una persona
- [ ] [BONUS] Creé un segundo Custom GPT para mi especialidad
- [ ] Comparé respuestas vs ChatGPT normal

---

## Problemas Comunes y Soluciones

### Problema 1: "No tengo ChatGPT Plus"
**Solución:**
- Haz el ejercicio de forma teórica escribiendo las instrucciones
- Considera si el costo (20 USD/mes) se justifica con el ahorro de tiempo
- Prueba los ejercicios de días anteriores mientras decides

### Problema 2: "El GPT no cita fundamento legal"
**Solución:**
- Refuerza en las instrucciones: "SIEMPRE cita el artículo específico"
- Agrega ejemplos de respuestas correctas en las instrucciones
- Prueba diciéndole: "Responde de nuevo pero incluye el artículo de ley"

### Problema 3: "Las respuestas son muy genéricas"
**Solución:**
- Sube archivos de referencia más específicos
- Detalla más el conocimiento que debe tener en las instrucciones
- Usa conversation starters más específicos como ejemplos

### Problema 4: "No tengo los PDFs de las leyes"
**Solución:**
- Búscalos en el sitio oficial del SAT o Diputados
- Crea un documento de texto con la información clave extraída
- Empieza sin archivos y agrégalos después (el GPT funciona con instrucciones)

### Problema 5: "El GPT inventa información"
**Solución:**
- Desactiva "Web Browsing"
- Agrega en instrucciones: "Si no tienes la información, di que necesitas consultar la fuente oficial"
- Sube más documentos de referencia confiables

---

## Reflexión Final

Antes de continuar al Día 5, reflexiona:

1. **¿Cuánto tiempo me ahorraría este GPT en mi día a día?**
2. **¿Qué otros Custom GPTs podría crear para mi despacho?**
3. **¿Cómo reaccionarían mis clientes si les doy acceso a un GPT especializado?**
4. **¿Qué ventaja competitiva me daría tener 3-5 Custom GPTs operando?**

Los Custom GPTs no son el futuro, son el presente. Lo que hiciste hoy hace un año habría requerido un equipo de programadores. Hoy lo hiciste tú solo en 30 minutos.

---

**¿Completaste los ejercicios?** Prepárate para el Día 5: Claude Projects, donde aprenderás a analizar documentos de 100+ páginas con IA.
