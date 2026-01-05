# Día 4: Custom GPTs Fiscales
## Slides con Script para Teleprompter

---

## SLIDE 1: Portada

**Visual:** Título grande "Custom GPTs Fiscales" + Logo del reto

### Script:
> Bienvenidos al Día 4 del Reto de 12 Días de IA para Contadores. Hoy entramos a la Semana 2: Especialización. Ya conoces las tres herramientas principales, ya sabes crear prompts efectivos. Ahora vamos a dar el siguiente paso: crear tus propios asistentes especializados sin escribir una sola línea de código. Los Custom GPTs son como tener empleados virtuales entrenados específicamente para las tareas que tú defines.

---

## SLIDE 2: Resumen Semana 1

**Visual:** Iconos de los 3 días anteriores

**Contenido:**
- Día 1: Mentalidad IA-First
- Día 2: Comparación ChatGPT vs Claude vs Gemini
- Día 3: Fórmula de Prompts (ROL+CONTEXTO+TAREA+FORMATO)

### Script:
> Antes de continuar, un rápido repaso. En la Semana 1 adoptamos la mentalidad IA-First, comparamos las tres herramientas principales y aprendimos a crear prompts efectivos con la fórmula ROL+CONTEXTO+TAREA+FORMATO. Todo lo que aprendiste hasta ahora se va a aplicar en lo que veremos hoy. Los Custom GPTs son básicamente prompts permanentes que no tienes que repetir cada vez.

---

## SLIDE 3: El Problema que Resuelven los Custom GPTs

**Visual:** Imagen de persona copiando y pegando el mismo prompt muchas veces

### Script:
> Imagina que cada semana te llegan tres clientes con dudas sobre RESICO. Cada vez tienes que abrir ChatGPT, escribir o pegar el mismo prompt largo que incluye el contexto del régimen, las especificaciones, los límites de ingresos, y después hacer tu pregunta específica. Es tedioso, verdad. Los Custom GPTs resuelven exactamente este problema. Son asistentes que ya tienen todo ese contexto precargado. Tú solo abres el GPT y haces tu pregunta específica.

---

## SLIDE 4: ¿Qué es un Custom GPT?

**Visual:** Diagrama: ChatGPT normal vs Custom GPT

### Script:
> Un Custom GPT es una versión personalizada de ChatGPT que tú mismo configuras. Le das instrucciones permanentes sobre cómo comportarse, qué conocimiento priorizar, qué tono usar, qué formato seguir. Puedes subirle documentos de referencia como leyes, reglamentos o tus propias guías. Y puedes compartirlo con tu equipo o incluso publicarlo para que otros lo usen. Lo más importante: no necesitas programar nada. Todo se hace desde una interfaz visual.

---

## SLIDE 5: Requisitos

**Visual:** Lista de requisitos simple

**Requisitos:**
- Cuenta de ChatGPT Plus (20 USD/mes)
- No requiere conocimientos de programación
- Acceso a GPT Builder en ChatGPT

### Script:
> Para crear Custom GPTs necesitas una cuenta de ChatGPT Plus que cuesta 20 dólares al mes. Es el único requisito. No necesitas saber programar, no necesitas conocimientos técnicos avanzados. Si sabes escribir un prompt, puedes crear un Custom GPT. En el Día 3 aprendiste a crear prompts efectivos, esa misma habilidad es todo lo que necesitas aquí.

---

## SLIDE 6: Casos de Uso para Contadores

**Visual:** Lista con iconos

**Casos de Uso:**
1. Asesor RESICO
2. Validador de CFDI 4.0
3. Calculadora de Nómina
4. Analista de Deducciones
5. Generador de Oficios SAT
6. Revisor de Contratos

### Script:
> Los casos de uso son prácticamente infinitos. Puedes crear un asesor especializado en RESICO que conozca todos los límites de ingresos, deducciones y obligaciones. Un validador de CFDI 4.0 que revise si un comprobante cumple con todos los requisitos técnicos y fiscales. Una calculadora de nómina que te ayude con percepciones, deducciones y cálculo del ISR. Un analista de deducciones que determine si un gasto específico es deducible. Un generador de oficios para el SAT con el formato y lenguaje correcto. O un revisor de contratos que identifique cláusulas con implicaciones fiscales. Hoy vamos a crear tres de estos juntos.

---

## SLIDE 7: Estructura de un Custom GPT

**Visual:** Diagrama de componentes

**Componentes:**
1. Nombre y descripción
2. Instrucciones (el prompt permanente)
3. Conversation starters (preguntas sugeridas)
4. Conocimiento (archivos de referencia)
5. Capacidades (navegación web, generación de imágenes, análisis de datos)

### Script:
> Todo Custom GPT tiene cinco componentes principales. Primero, el nombre y descripción que le ayudan al usuario entender para qué sirve. Segundo, las instrucciones, que son básicamente el prompt permanente que define cómo se comporta. Tercero, los conversation starters, que son preguntas sugeridas para ayudar al usuario a comenzar. Cuarto, el conocimiento, que son archivos que puedes subir como referencia: leyes, reglamentos, guías internas. Y quinto, las capacidades especiales como navegación web, generación de imágenes o análisis de datos con Python. Vamos a ver cada componente en detalle.

---

## SLIDE 8: Componente 1 - Nombre y Descripción

**Visual:** Ejemplo de nombre y descripción

**Ejemplo:**
- **Nombre:** Asesor RESICO México
- **Descripción:** Especialista en Régimen Simplificado de Confianza. Resuelve dudas sobre requisitos, límites y obligaciones.

### Script:
> El nombre debe ser claro y específico. No pongas solo "Asistente Fiscal", eso no dice nada. Mejor "Asesor RESICO México" o "Validador CFDI 4.0". La descripción debe explicar en una o dos oraciones qué hace este GPT y para quién es. Esto es importante si lo vas a compartir con tu equipo o clientes.

---

## SLIDE 9: Componente 2 - Instrucciones (El Prompt Permanente)

**Visual:** Ejemplo de instrucciones usando la fórmula del Día 3

**Ejemplo:**
```
Eres un contador especializado en el Régimen Simplificado de
Confianza (RESICO) en México.

Tu objetivo es ayudar a contadores y contribuyentes a entender
sus obligaciones, límites de ingresos, deducciones permitidas
y requisitos de este régimen.

Siempre debes:
1. Citar el fundamento legal específico
2. Usar lenguaje claro y profesional
3. Incluir ejemplos prácticos cuando sea relevante
4. Advertir cuando una situación requiera consulta profesional

Conoces a fondo:
- Límites de ingresos RESICO
- Tasas aplicables
- Deducciones permitidas
- Obligaciones fiscales
```

### Script:
> Las instrucciones son el corazón del Custom GPT. Aquí usas todo lo que aprendiste en el Día 3 sobre prompts. Defines el rol, das contexto, estableces el comportamiento esperado. Nota cómo estamos usando la estructura ROL+CONTEXTO+TAREA+FORMATO que ya conoces. Este prompt se aplicará en cada conversación sin que tengas que repetirlo. Es como contratar a alguien y darle su manual de operaciones una sola vez.

---

## SLIDE 10: Componente 3 - Conversation Starters

**Visual:** Ejemplos de conversation starters

**Ejemplos para Asesor RESICO:**
- "¿Cuál es el límite de ingresos para RESICO 2024?"
- "¿Qué deducciones puedo aplicar en RESICO?"
- "¿Cómo se calcula el ISR en RESICO?"
- "¿Puedo facturar con RESICO si tengo empleados?"

### Script:
> Los conversation starters son botones con preguntas pregeneradas que aparecen cuando abres el GPT. Ayudan al usuario a entender qué tipo de preguntas puede hacer y a comenzar rápidamente. Piensa en las cuatro o cinco preguntas más comunes que te hacen sobre ese tema y ponlas aquí. No son obligatorias, pero hacen que el GPT sea mucho más fácil de usar.

---

## SLIDE 11: Componente 4 - Conocimiento (Knowledge)

**Visual:** Lista de tipos de archivos que puedes subir

**Archivos permitidos:**
- PDFs (leyes, reglamentos, criterios)
- Documentos Word/Docs
- Hojas de cálculo
- Archivos de texto
- Presentaciones

**Límite:** Hasta 20 archivos

### Script:
> Esta es una de las funciones más poderosas. Puedes subir hasta 20 archivos que el GPT usará como referencia. Por ejemplo, para un Asesor RESICO podrías subir la Ley del ISR actualizada, la Resolución Miscelánea Fiscal, criterios no vinculativos del SAT sobre RESICO, o incluso tus propias guías internas. Cuando el usuario hace una pregunta, el GPT primero busca en estos documentos antes de responder. Esto reduce significativamente las alucinaciones y asegura respuestas basadas en información correcta.

---

## SLIDE 12: Componente 5 - Capacidades

**Visual:** Iconos de capacidades

**Capacidades disponibles:**
- **Web Browsing:** Buscar información actualizada en internet
- **DALL-E:** Generar imágenes
- **Code Interpreter:** Analizar datos, hacer cálculos, procesar archivos

### Script:
> Las capacidades son funciones adicionales que puedes activar. Web Browsing permite que el GPT busque información actualizada en internet, útil para un GPT que necesite conocer cambios fiscales recientes. DALL-E genera imágenes, probablemente no muy útil para contadores pero está disponible. Y Code Interpreter es extremadamente útil: permite al GPT hacer cálculos complejos, procesar archivos Excel, generar gráficas. Para un GPT de nómina o análisis de deducciones, esta capacidad es esencial.

---

## SLIDE 13: Proceso de Creación Paso a Paso

**Visual:** Flujo de creación en 5 pasos

**Pasos:**
1. Acceder a GPT Builder
2. Configurar nombre y descripción
3. Escribir las instrucciones
4. Agregar conversation starters
5. Subir archivos de conocimiento
6. Configurar capacidades
7. Probar y ajustar
8. Publicar

### Script:
> Crear un Custom GPT es un proceso de ocho pasos simples. Primero accedes al GPT Builder desde ChatGPT Plus. Segundo, configuras nombre y descripción. Tercero, escribes las instrucciones que definen el comportamiento. Cuarto, agregas los conversation starters. Quinto, subes los archivos de referencia. Sexto, activas las capacidades que necesites. Séptimo, lo pruebas con varias preguntas y ajustas lo que no funcione. Y octavo, lo publicas para tu uso personal, para tu equipo o para el público. En los ejercicios prácticos vas a hacer esto paso a paso.

---

## SLIDE 14: Ejemplo 1 - Asesor RESICO

**Visual:** Screenshot del GPT de RESICO

**Configuración:**
- **Nombre:** Asesor RESICO México 2024
- **Instrucciones:** Especialista en RESICO con conocimiento de límites, tasas y obligaciones
- **Conocimiento:** Título IV.A LISR + RMF 2024
- **Capacidades:** Code Interpreter para cálculos

### Script:
> Veamos el primer ejemplo concreto. El Asesor RESICO México 2024. Este GPT está configurado como especialista en el Régimen Simplificado de Confianza. Las instrucciones le indican que siempre debe citar fundamento legal, usar lenguaje claro y advertir cuando una situación requiere asesoría personalizada. Le subimos el Título IV.A de la Ley del ISR que regula RESICO y la Resolución Miscelánea Fiscal actualizada. Activamos Code Interpreter para que pueda hacer cálculos de ISR y proyecciones de ingresos. Este GPT puede responder sobre límites de ingresos, deducciones permitidas, tasas aplicables y requisitos de permanencia en el régimen.

---

## SLIDE 15: Ejemplo 2 - Validador CFDI 4.0

**Visual:** Screenshot del GPT de CFDI

**Configuración:**
- **Nombre:** Validador CFDI 4.0
- **Instrucciones:** Revisor técnico y fiscal de comprobantes digitales
- **Conocimiento:** Guía de llenado CFDI 4.0 + Anexo 20
- **Capacidades:** Code Interpreter para validar estructuras XML

### Script:
> El segundo ejemplo es el Validador CFDI 4.0. Este GPT está entrenado para revisar si un comprobante fiscal cumple con todos los requisitos técnicos y fiscales. Las instrucciones le indican que debe revisar estructura XML, campos obligatorios, complementos requeridos y validaciones del SAT. Le subimos la Guía de llenado oficial del CFDI 4.0 y el Anexo 20 con los catálogos actualizados. Activamos Code Interpreter para que pueda procesar y validar archivos XML. Este GPT puede identificar errores comunes, campos faltantes, valores inválidos en catálogos y problemas que causarían rechazo en la validación del SAT.

---

## SLIDE 16: Ejemplo 3 - Calculadora de Nómina

**Visual:** Screenshot del GPT de Nómina

**Configuración:**
- **Nombre:** Calculadora Nómina México
- **Instrucciones:** Especialista en cálculo de percepciones, deducciones e ISR
- **Conocimiento:** Tablas ISR + Tarifas IMSS + Guía práctica
- **Capacidades:** Code Interpreter para cálculos

### Script:
> El tercer ejemplo es la Calculadora de Nómina México. Este GPT ayuda con el cálculo de percepciones, deducciones, ISR retenido, cuotas IMSS e INFONAVIT. Las instrucciones le indican el proceso paso a paso para calcular un recibo de nómina completo. Le subimos las tablas de ISR vigentes, las tarifas del IMSS actualizadas y una guía práctica de nómina. Code Interpreter es esencial aquí para hacer todos los cálculos. Este GPT puede calcular el neto a pagar, determinar el ISR retenido, calcular cuotas obrero-patronales y generar desglose completo del recibo.

---

## SLIDE 17: Ventajas de los Custom GPTs

**Visual:** Lista con iconos

**Ventajas:**
1. **Consistencia:** Siempre responde de la misma forma
2. **Especialización:** Conocimiento profundo en un tema específico
3. **Ahorro de tiempo:** No repites el mismo contexto cada vez
4. **Escalabilidad:** Puedes compartirlo con todo tu equipo
5. **Actualizable:** Cambias las instrucciones cuando cambien las leyes
6. **Sin código:** No necesitas ser programador

### Script:
> Las ventajas son múltiples. Primero, consistencia: todos en tu despacho usan el mismo asistente con el mismo criterio. Segundo, especialización: es un experto en ese tema específico, no un generalista. Tercero, ahorro de tiempo: no tienes que dar contexto cada vez. Cuarto, escalabilidad: lo creas una vez y lo usa todo el equipo. Quinto, es actualizable: cuando cambien las leyes o procedimientos, solo actualizas las instrucciones o archivos. Y sexto, no necesitas saber programar, si sabes crear un prompt, puedes crear un GPT.

---

## SLIDE 18: Limitaciones y Consideraciones

**Visual:** Lista de advertencias

**Limitaciones:**
- Requiere ChatGPT Plus (20 USD/mes)
- Máximo 20 archivos de conocimiento
- El GPT puede olvidar instrucciones en conversaciones muy largas
- No reemplaza el criterio profesional del contador
- Requiere mantenimiento cuando cambien leyes

### Script:
> También es importante conocer las limitaciones. Primero, requiere ChatGPT Plus que cuesta 20 dólares mensuales. Segundo, solo puedes subir hasta 20 archivos de referencia. Tercero, en conversaciones muy largas el GPT puede empezar a olvidar las instrucciones iniciales, aunque esto es raro. Cuarto y más importante: un Custom GPT no reemplaza tu criterio profesional. Es una herramienta de apoyo, no un sustituto del contador. Y quinto, cuando cambien leyes fiscales debes actualizar los archivos y las instrucciones. No es crear y olvidar, requiere mantenimiento.

---

## SLIDE 19: Custom GPTs vs ChatGPT Normal

**Visual:** Tabla comparativa

| Aspecto | ChatGPT Normal | Custom GPT |
|---------|---------------|------------|
| Contexto | Se pierde entre sesiones | Permanente |
| Especialización | Generalista | Experto en un tema |
| Archivos de referencia | Subes en cada chat | Precargados siempre |
| Compartir | Debes copiar el prompt | Compartes el link |
| Consistencia | Varía según el prompt | Siempre igual |

### Script:
> La diferencia entre usar ChatGPT normal y un Custom GPT es como la diferencia entre explicarle el contexto a un freelancer cada vez versus tener un empleado que ya conoce el proceso. Con ChatGPT normal, cada vez empiezas de cero. Con un Custom GPT, el contexto es permanente. ChatGPT normal es generalista, el Custom GPT es especialista. En ChatGPT normal subes archivos en cada conversación, en el Custom GPT están precargados. Para compartir con tu equipo usando ChatGPT normal tendrías que copiar y pegar el prompt, con un Custom GPT solo compartes el link. Y la consistencia: con prompts normales cada persona puede escribir algo diferente, con un Custom GPT todos obtienen el mismo comportamiento.

---

## SLIDE 20: Compartir Custom GPTs

**Visual:** Opciones de privacidad

**Opciones:**
1. **Solo yo:** Privado, solo tú puedes usarlo
2. **Anyone with a link:** Cualquiera con el link puede usarlo
3. **Public:** Aparece en la tienda de GPTs de OpenAI

### Script:
> Cuando publicas un Custom GPT tienes tres opciones de privacidad. Solo yo: es completamente privado, solo tú puedes accederlo. Anyone with a link: cualquier persona que tenga el link puede usarlo, útil para compartir con tu equipo o clientes específicos. Y Public: se publica en la GPT Store de OpenAI donde cualquier usuario de ChatGPT Plus puede encontrarlo y usarlo. Para uso interno del despacho normalmente usarás "Anyone with a link". Para positioning y marketing podrías publicar uno público que demuestre tu experiencia.

---

## SLIDE 21: Monetización de Custom GPTs

**Visual:** Modelos de negocio

**Posibilidades:**
1. Crear GPTs públicos y ganar revenue share (OpenAI)
2. Vender acceso a GPTs especializados (tu plataforma)
3. Incluir GPTs como valor agregado en paquetes de servicio
4. Usar GPTs para automatizar servicios y escalar

### Script:
> OpenAI anunció un programa de revenue share para creadores de GPTs populares. Si creas un GPT público que muchas personas usen, puedes recibir un porcentaje de los ingresos. Pero más allá de eso, puedes crear GPTs especializados y vender acceso a través de tu propia plataforma o membresía. O incluirlos como valor agregado: imagina ofrecer a tus clientes acceso a un GPT personalizado con las particularidades de su empresa. O usarlos internamente para automatizar servicios repetitivos y escalar tu despacho sin contratar más personal. Esto lo veremos más a fondo en el Día 12 sobre monetización.

---

## SLIDE 22: Mejores Prácticas

**Visual:** Lista de mejores prácticas

**Mejores Prácticas:**
1. Prueba exhaustivamente antes de compartir
2. Actualiza cuando cambien leyes o procedimientos
3. Incluye disclaimers sobre responsabilidad profesional
4. Usa conversation starters para guiar al usuario
5. Sube documentos oficiales, no resúmenes
6. Revisa y mejora basado en feedback de usuarios

### Script:
> Algunas mejores prácticas para crear GPTs efectivos. Primero, prueba exhaustivamente con diferentes tipos de preguntas antes de compartirlo con clientes o equipo. Segundo, establece un calendario de actualización cuando cambien leyes fiscales. Tercero, siempre incluye disclaimers que aclaren que el GPT es una herramienta de apoyo y no sustituye asesoría profesional. Cuarto, usa conversation starters para guiar al usuario hacia las preguntas correctas. Quinto, cuando subas documentos de referencia, usa fuentes oficiales como la Ley del ISR, no resúmenes de internet. Y sexto, pide feedback a quienes usen el GPT y mejóralo continuamente.

---

## SLIDE 23: Casos de Éxito

**Visual:** Ejemplos de despachos usando Custom GPTs

**Ejemplos:**
- Despacho con GPT de auditoría que redujo 40% el tiempo de revisión
- Contador que ofrece GPT personalizado a cada cliente corporativo
- Despacho que creó GPT interno para onboarding de juniors
- Consultor fiscal con GPT público que genera leads calificados

### Script:
> Veamos algunos casos de éxito. Un despacho de auditoría creó un GPT especializado en revisar estados financieros bajo NIF y redujo el tiempo de revisión inicial en 40 por ciento. Un contador de empresas medianas ofrece a cada cliente un GPT personalizado con sus políticas contables específicas y catálogos de cuentas, diferenciándose completamente de la competencia. Un despacho grande creó un GPT interno con toda su metodología de trabajo para acelerar el onboarding de contadores juniors. Y un consultor fiscal independiente publicó un GPT gratuito sobre deducciones personales que genera cientos de leads calificados cada mes. Las posibilidades son enormes.

---

## SLIDE 24: Ejercicios Prácticos de Hoy

**Visual:** Lista de ejercicios

**Ejercicios:**
1. Crear tu primer Custom GPT (Asesor RESICO)
2. Configurar conversation starters efectivos
3. Subir documentos de referencia
4. Probar y refinar el GPT
5. [BONUS] Crear un segundo GPT para tu especialidad

### Script:
> En los ejercicios prácticos de hoy vas a crear tu primer Custom GPT paso a paso. Vamos a construir juntos un Asesor RESICO. Vas a configurar las instrucciones, agregar conversation starters, subir documentos de referencia y probarlo con diferentes preguntas. El ejercicio está diseñado para que lo completes en 30 a 45 minutos. Y si terminas antes, hay un ejercicio bonus: crear un segundo GPT para tu área de especialidad, ya sea nómina, CFDI, deducciones o lo que prefieras.

---

## SLIDE 25: Preparación para Mañana

**Visual:** Preview Día 5

**Día 5: Claude Projects**
- Análisis de documentos extensos
- Contratos y dictámenes
- Base de conocimiento persistente

### Script:
> Mañana en el Día 5 vamos a explorar Claude Projects. Mientras que hoy aprendiste a crear asistentes especializados en ChatGPT, mañana aprenderás a usar Claude para analizar documentos extremadamente largos: contratos de 100 páginas, dictámenes fiscales completos, toda la Ley del ISR de una vez. Claude Projects te permite crear una base de conocimiento persistente donde subes todos los documentos relevantes y haces preguntas complejas que requieren analizar múltiples fuentes simultáneamente. Si hoy creamos especialistas, mañana creamos analistas profundos.

---

## SLIDE 26: Recursos del Día 4

**Visual:** Lista de recursos

**Incluidos:**
- Plantillas de Custom GPTs (RESICO, CFDI, Nómina)
- Guía paso a paso de creación
- Ejercicios prácticos
- Checklist de mejores prácticas

### Script:
> En los recursos de hoy encontrarás plantillas completas para los tres Custom GPTs que vimos: RESICO, CFDI y Nómina. Cada plantilla incluye las instrucciones exactas, conversation starters sugeridos y lista de documentos recomendados para subir. También está la guía paso a paso de creación con screenshots y la checklist de mejores prácticas. Todo listo para que lo implementes hoy mismo.

---

## SLIDE 27: Checklist del Día 4

**Visual:** Checklist

- [ ] Vi la clase completa
- [ ] Tengo ChatGPT Plus activado
- [ ] Creé mi primer Custom GPT
- [ ] Probé el GPT con al menos 5 preguntas diferentes
- [ ] Compartí el GPT con al menos una persona de mi equipo

### Script:
> Tu checklist para hoy. Primero, ver esta clase completa. Segundo, asegúrate de tener ChatGPT Plus activado, lo necesitas para crear GPTs. Tercero, crear tu primer Custom GPT siguiendo los ejercicios. Cuarto, probarlo con al menos cinco preguntas diferentes para asegurarte que responde correctamente. Y quinto, compartir el GPT con al menos una persona de tu equipo para que también lo pruebe y te dé feedback. No tiene sentido crear una herramienta que solo tú usas.

---

## SLIDE 28: Reflexión Final

**Visual:** Imagen inspiracional + quote

> "Los Custom GPTs no son el futuro, son el presente. Los despachos que los adopten hoy tendrán ventaja competitiva mañana."

### Script:
> Para cerrar, una reflexión. Hace un año los Custom GPTs no existían. Hace seis meses muy pocos contadores los estaban usando. Hoy es una herramienta probada que está generando resultados reales en despachos de todos los tamaños. Los que adopten esta tecnología ahora, no en seis meses o un año, van a tener una ventaja competitiva significativa. Pueden ofrecer servicios más rápidos, más consistentes, más escalables. No se trata de reemplazar al contador, se trata de multiplicar su capacidad. Un Custom GPT bien diseñado es como tener un junior que nunca duerme, nunca se cansa y nunca olvida el procedimiento. Úsalo sabiamente.

---

## SLIDE 29: Cierre

**Visual:** Logo + redes sociales

**Nos vemos mañana:**
Día 5 - Claude Projects

### Script:
> Nos vemos mañana en el Día 5 donde exploraremos Claude Projects para análisis profundo de documentos extensos. No olvides hacer los ejercicios prácticos de hoy antes de mañana. Si tienes dudas, compártelas en el grupo. Y si ya creaste tu Custom GPT, comparte el link para que los demás lo prueben. Hasta mañana.

---

**Duración total estimada:** 25-30 minutos
