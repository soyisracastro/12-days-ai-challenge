# Día 6: Ejercicios Prácticos
## Gemini + Google Workspace

**Tiempo estimado:** 30-45 minutos
**Objetivo:** Aprender a integrar Gemini con Google Workspace y aprovechar la conexión directa con Drive, Sheets y Docs.

---

## Requisitos Previos

### Antes de empezar:

1. **Cuenta de Google**
   - Necesitas una cuenta de Google activa
   - Puede ser personal o de Google Workspace

2. **Gemini Advanced (recomendado)**
   - Costo: 20 USD/mes
   - Para estos ejercicios puedes usar la versión gratuita con limitaciones
   - La versión Advanced tiene integración completa con Workspace

3. **Archivos en Google Drive**
   - Necesitarás archivos para practicar:
     - Una hoja de cálculo (Google Sheets) con datos
     - Un documento PDF
     - Archivos propios de trabajo (opcional)

4. **Navegador actualizado**
   - Chrome, Edge, Firefox o Safari actualizado

---

## Ejercicio 1: Activar Gemini y Extensión de Workspace (10 minutos)

### Objetivo
Configurar Gemini con acceso a tu Google Workspace.

### Paso 1: Acceder a Gemini (2 minutos)

1. Ve a https://gemini.google.com
2. Inicia sesión con tu cuenta de Google
3. Verás la interfaz de Gemini

**Si tienes Gemini Advanced:**
- Verás un indicador de "Gemini Advanced" en la interfaz
- Tienes acceso completo a integración

**Si usas versión gratuita:**
- Funcionará con limitaciones
- Algunas funciones de integración pueden estar restringidas

### Paso 2: Activar la Extensión de Google Workspace (5 minutos)

1. En la interfaz de Gemini, busca el ícono de configuración o extensiones
2. Busca "Google Workspace" o "Extensions"
3. Activa la extensión de Google Workspace
4. Gemini te pedirá permisos para acceder a:
   - Google Drive
   - Google Docs
   - Google Sheets
   - Gmail (opcional)
   - Google Calendar (opcional)
5. **Revisa los permisos cuidadosamente**
6. Acepta los permisos que te sientas cómodo otorgando

**Importante:**
- Puedes activar/desactivar la extensión cuando quieras
- Solo activa acceso a Gmail y Calendar si estás cómodo
- Para los ejercicios, Drive y Docs son suficientes

### Paso 3: Verificar la Conexión (3 minutos)

Haz una prueba simple:

```
¿Puedes ver mis archivos de Google Drive?
```

**Respuesta esperada:**
- Gemini debería confirmar que tiene acceso
- Puede listar algunos archivos recientes
- O pedirte que especifiques qué archivo quieres que vea

**Si no funciona:**
- Verifica que activaste la extensión correctamente
- Revisa que diste los permisos necesarios
- Intenta desactivar y reactivar la extensión

---

## Ejercicio 2: Analizar una Hoja de Cálculo con Datos (15 minutos)

### Objetivo
Usar Gemini para analizar datos en un Google Sheet sin descargar el archivo.

### Preparación: Crear o Usar un Sheet de Ejemplo (si no tienes uno)

**Opción A: Usar un Sheet que ya tengas**
- Cualquier hoja de cálculo con datos financieros, contables o de clientes
- Idealmente con al menos 50-100 filas

**Opción B: Crear un Sheet de práctica**

1. Abre Google Sheets
2. Crea una nueva hoja llamada "Pólizas Contables Práctica"
3. Crea estas columnas:
   - Fecha
   - Número de póliza
   - Cuenta contable
   - Descripción
   - Cargo
   - Abono
4. Llena al menos 20-30 filas con datos de ejemplo

**Opción C: Copiar datos de práctica**

Si tienes acceso a datos de práctica o muestra, úsalos.

### Paso 1: Solicitar Análisis General (5 minutos)

Una vez que tengas tu Sheet, dile a Gemini:

```
Analiza el archivo [nombre de tu Sheet] de mi Google Drive.
Proporciona un resumen que incluya:
1. Número total de registros
2. Estructura de columnas
3. Rango de fechas (si hay)
4. Totales (si hay columnas numéricas)
5. Primeras observaciones o patrones
```

**Evaluación:**
- [ ] Gemini encontró el archivo sin que lo subieras manualmente
- [ ] El análisis incluye información correcta
- [ ] Identificó columnas y estructura correctamente

### Paso 2: Identificar Anomalías o Patrones (5 minutos)

Ahora pide análisis más profundo:

```
En el mismo archivo, identifica:
1. Valores inusuales o fuera de rango
2. Registros duplicados (si los hay)
3. Celdas vacías en columnas importantes
4. Cualquier patrón o tendencia interesante
5. Registros que requieran revisión manual

Prioriza por nivel de importancia.
```

**Evaluación:**
- [ ] Gemini identificó problemas o patrones reales
- [ ] Las observaciones tienen sentido
- [ ] Priorizó correctamente por relevancia

### Paso 3: Solicitar Análisis Específico (5 minutos)

Haz una pregunta específica sobre tus datos. Ejemplos:

**Para datos contables:**
```
¿Cuál es la cuenta contable con mayor movimiento?
Lista las top 5 con totales.
```

**Para datos de clientes:**
```
¿Qué cliente tiene el mayor número de operaciones?
Lista los top 10.
```

**Para datos financieros:**
```
¿Cuál es el mes con mayor total de ingresos?
Genera una tabla por mes.
```

**Evaluación:**
- [ ] Gemini respondió la pregunta específica correctamente
- [ ] Los números son precisos (verifica manualmente algunos)
- [ ] El formato de respuesta fue claro

### Reflexión

**¿Cuánto tiempo te habría tomado hacer este análisis manualmente?**
- Análisis general: _____ minutos
- Identificar anomalías: _____ minutos
- Responder pregunta específica: _____ minutos

**Con Gemini:**
- Todo el ejercicio: ~15 minutos

---

## Ejercicio 3: Generar Documento en Google Docs desde Datos (10 minutos)

### Objetivo
Hacer que Gemini genere un documento en Google Docs directamente desde datos de un Sheet.

### Paso 1: Solicitar Generación de Reporte (5 minutos)

Usando el mismo Sheet del Ejercicio 2:

```
Lee los datos del archivo [nombre de tu Sheet] y genera un reporte
profesional en Google Docs con esta estructura:

1. RESUMEN EJECUTIVO
   - Total de registros analizados
   - Periodo cubierto
   - Principales hallazgos

2. ANÁLISIS DETALLADO
   - Totales por categoría [adapta según tus datos]
   - Tendencias identificadas
   - Puntos de atención

3. RECOMENDACIONES
   - Acciones sugeridas
   - Prioridades

4. ANEXOS
   - Tabla con top 10 registros más relevantes

Guarda el documento en mi Drive con el nombre "Reporte de Análisis [fecha de hoy]"
```

**Nota:** Adapta la estructura según tus datos específicos

### Paso 2: Verificar el Documento Generado (3 minutos)

1. Ve a tu Google Drive
2. Busca el documento que Gemini generó
3. Abre el documento
4. Revisa:
   - [ ] ¿Se generó el documento correctamente?
   - [ ] ¿Tiene la estructura solicitada?
   - [ ] ¿Los datos son correctos?
   - [ ] ¿El formato es profesional?

### Paso 3: Solicitar Ajustes (2 minutos)

Si algo no quedó como querías:

```
En el documento que acabas de generar, modifica:
- [Especifica qué cambiar]

Por ejemplo:
- Agrega una tabla de contenido al inicio
- Cambia el título a "Reporte Mensual de Análisis"
- En la sección de Anexos, incluye un gráfico de barras de los top 10
```

**Evaluación:**
- [ ] Gemini modificó el documento según tus instrucciones
- [ ] Los cambios se reflejaron en Google Docs automáticamente

### Reflexión

**Tiempo que tomaría hacer esto manualmente:**
- Copiar datos del Sheet a un Doc: _____ minutos
- Formatear el documento: _____ minutos
- Crear tablas y estructura: _____ minutos
- **Total:** _____ minutos

**Con Gemini:** ~10 minutos (y con mejor formato)

---

## Ejercicio 4: Buscar Información Fiscal Actualizada (10 minutos)

### Objetivo
Usar la capacidad de Gemini de acceder a Google Search para encontrar información fiscal reciente.

### Paso 1: Buscar Cambios Fiscales Recientes (5 minutos)

**Pregunta 1: Información de hace días/semanas**

```
Busca en internet qué cambios fiscales para personas morales se publicaron
en el Diario Oficial de la Federación (DOF) en el último mes.

Incluye:
- Fecha de publicación
- Tipo de cambio (ley, decreto, resolución)
- Resumen breve
- Link a la fuente oficial
```

**Evaluación:**
- [ ] Gemini encontró información actualizada
- [ ] La información es relevante y precisa
- [ ] Incluyó links a fuentes oficiales
- [ ] Puedes verificar la información en las fuentes

**Pregunta 2: Actualización de tablas o tarifas**

```
¿Cuál es el valor de la UMA (Unidad de Medida y Actualización) vigente en 2024?
Busca la información oficial y confirma la fuente.
```

**Evaluación:**
- [ ] El valor es correcto
- [ ] Citó la fuente oficial (INEGI)

**Pregunta 3: Criterios o resoluciones del SAT**

```
Busca si el SAT ha publicado criterios o resoluciones sobre [tema de tu interés]
en los últimos 6 meses. Por ejemplo:
- Comprobantes fiscales digitales
- Operaciones con partes relacionadas
- Deducciones para personas físicas
```

**Evaluación:**
- [ ] La búsqueda fue relevante
- [ ] La información está actualizada
- [ ] Los links funcionan

### Paso 2: Comparar con ChatGPT o Claude (5 minutos)

Para entender la diferencia:

1. Abre ChatGPT o Claude en otra pestaña
2. Haz la misma pregunta sobre cambios fiscales recientes
3. Compara las respuestas:

| Aspecto | Gemini | ChatGPT/Claude |
|---------|--------|----------------|
| ¿Tiene info actualizada? | | |
| ¿Cita fuentes? | | |
| ¿Links funcionan? | | |
| ¿Admite si no sabe? | | |

**Conclusión:**
- Gemini es superior para información reciente y actualizada
- ChatGPT y Claude son mejores para análisis profundo de info que ya conocen

---

## Ejercicio 5 (BONUS): Crear Workflow Automático (15 minutos)

### Objetivo
Crear un workflow que combine múltiples capacidades de Gemini con tus archivos.

### Workflow Sugerido: Reporte Mensual Automático

**Escenario:**
Tienes 3 archivos en tu Drive:
1. Sheet con ingresos del mes
2. Sheet con gastos del mes
3. Plantilla de reporte mensual en Docs

**Objetivo:**
Que Gemini lea los dos Sheets, analice los datos y genere el reporte mensual usando la plantilla.

### Paso 1: Preparar los Archivos (5 minutos)

Si no tienes estos archivos, créalos simples:

**Ingresos del mes (Sheet):**
- Columnas: Fecha | Cliente | Monto | Concepto
- 10-15 filas de ejemplo

**Gastos del mes (Sheet):**
- Columnas: Fecha | Proveedor | Monto | Categoría
- 10-15 filas de ejemplo

**Plantilla de reporte (Doc):**
- Crea un Doc con estructura básica que quieras llenar

### Paso 2: Solicitar el Workflow (5 minutos)

```
Necesito que hagas lo siguiente:

1. Lee el archivo "Ingresos [mes]" de mi Drive
2. Lee el archivo "Gastos [mes]" de mi Drive
3. Calcula:
   - Total de ingresos
   - Total de gastos
   - Diferencia (ingreso menos gasto)
4. Identifica:
   - Top 3 clientes por ingresos
   - Top 3 categorías de gasto
5. Abre la "Plantilla Reporte Mensual" de mi Drive
6. Llena la plantilla con todos estos datos
7. Guárdala como "Reporte [mes actual] - Generado"

Hazlo paso a paso y dime cuándo completes cada paso.
```

### Paso 3: Revisar el Resultado (3 minutos)

1. Verifica que Gemini completó todos los pasos
2. Abre el reporte generado
3. Revisa que los datos sean correctos

**Evaluación:**
- [ ] El workflow se completó automáticamente
- [ ] Los cálculos son correctos
- [ ] El formato del reporte es profesional
- [ ] Te ahorraría tiempo en tu trabajo real

### Paso 4: Guardar el Prompt del Workflow (2 minutos)

Si el workflow funciona bien, guarda el prompt para reusarlo cada mes:

1. Copia el prompt completo
2. Guárdalo en un Doc llamado "Prompts para Workflows"
3. Cada mes solo cambias las fechas y lo vuelves a usar

**Beneficio:**
- Primera vez: 15 minutos crear el workflow
- Meses siguientes: 2 minutos ejecutarlo

---

## Ejercicio 6: Integración con Gmail (BONUS - Opcional)

### Objetivo
Buscar información en correos electrónicos usando Gemini.

**Nota:** Solo si activaste el acceso a Gmail y te sientes cómodo.

### Búsquedas Útiles

**Búsqueda 1: Datos de un cliente**
```
Busca en mi Gmail correos del cliente [nombre] donde mencione
su RFC, domicilio fiscal o datos de facturación. Fueron enviados
hace aproximadamente [tiempo].
```

**Búsqueda 2: Confirmaciones de pago**
```
Busca en mi Gmail confirmaciones de pago o transferencias que hice
en el mes de [mes]. Extrae: fecha, monto, beneficiario.
```

**Búsqueda 3: Adjuntos específicos**
```
Busca en mi Gmail correos que tengan adjuntos PDF de facturas
del proveedor [nombre] en los últimos 3 meses.
```

**Evaluación:**
- [ ] Gemini encontró los correos relevantes
- [ ] Extrajo la información correctamente
- [ ] Es más rápido que buscar manualmente

---

## Problemas Comunes y Soluciones

### Problema 1: "Gemini no puede acceder a mis archivos"
**Solución:**
- Verifica que activaste la extensión de Google Workspace
- Revisa que diste los permisos necesarios
- Intenta desactivar y reactivar la extensión
- Asegúrate de que los archivos estén en Google Drive (no en tu computadora local)

### Problema 2: "Gemini no encuentra el archivo que le indico"
**Solución:**
- Usa el nombre exacto del archivo como aparece en Drive
- Si el nombre tiene caracteres especiales, ponlo entre comillas
- Intenta con: "el archivo llamado exactamente [nombre]"
- Verifica que el archivo está en "Mi unidad" no en "Compartidos conmigo"

### Problema 3: "Los cálculos de Gemini son incorrectos"
**Solución:**
- Verifica los datos manualmente
- Gemini puede equivocarse en matemáticas complejas
- Para cálculos críticos, usa fórmulas de Sheets y pide a Gemini que las interprete
- Siempre valida cálculos importantes manualmente

### Problema 4: "No tengo Gemini Advanced"
**Solución:**
- La versión gratuita funciona con limitaciones
- Puedes hacer los ejercicios pero con capacidad reducida
- Evalúa si el ahorro de tiempo justifica los 20 USD/mes
- Puedes hacer los ejercicios teóricamente y decidir después

### Problema 5: "Me preocupa la privacidad de mis archivos"
**Solución:**
- Lee los términos de servicio de Gemini completamente
- Para práctica, usa archivos de ejemplo sin datos sensibles
- Puedes desactivar la extensión cuando no la uses
- Para datos muy sensibles, considera no usar la integración
- Evalúa las políticas de tu despacho sobre datos en cloud

---

## Checklist de Finalización

- [ ] Activé Gemini (Advanced o gratuito)
- [ ] Activé la extensión de Google Workspace
- [ ] Analicé un Sheet sin descargar el archivo
- [ ] Generé un documento en Docs desde datos de Sheet
- [ ] Busqué información fiscal actualizada y verifiqué fuentes
- [ ] [BONUS] Creé un workflow automático con mis archivos
- [ ] [BONUS] Probé búsqueda en Gmail
- [ ] Identifiqué 3 casos de mi trabajo donde usaré Gemini + Workspace

---

## Reflexión Final

Antes de continuar a la Semana 3, reflexiona:

### Ahorro de Tiempo

**Calcula cuánto tiempo te ahorraría Gemini en una semana típica:**

| Tarea | Frecuencia semanal | Tiempo manual | Tiempo con Gemini | Ahorro semanal |
|-------|-------------------|---------------|-------------------|----------------|
| Analizar Sheets | ___ veces | ___ min | ___ min | ___ min |
| Generar reportes | ___ veces | ___ min | ___ min | ___ min |
| Buscar info actualizada | ___ veces | ___ min | ___ min | ___ min |
| Buscar en correos | ___ veces | ___ min | ___ min | ___ min |
| **TOTAL** | | | | **___ min** |

**Ahorro mensual:** ___ horas

**¿Justifica los 20 USD/mes de Gemini Advanced?**
- Si ahorras 2+ horas al mes: Sí
- Tu tarifa por hora: $___
- Valor del ahorro: $___

### Casos de Uso Específicos

**Identifica 3 workflows específicos de tu práctica donde usarás Gemini:**

1. **Workflow 1:**
   - Qué haces actualmente: ___________
   - Cómo lo harías con Gemini: ___________
   - Tiempo ahorrado: ___ min

2. **Workflow 2:**
   - Qué haces actualmente: ___________
   - Cómo lo harías con Gemini: ___________
   - Tiempo ahorrado: ___ min

3. **Workflow 3:**
   - Qué haces actualmente: ___________
   - Cómo lo harías con Gemini: ___________
   - Tiempo ahorrado: ___ min

### Integración con Otras Herramientas

**¿Cómo combinarás Gemini con ChatGPT y Claude?**

- Usa **ChatGPT (Custom GPTs)** para: ___________
- Usa **Claude (Projects)** para: ___________
- Usa **Gemini (Workspace)** para: ___________

---

## Recordatorio

Gemini con Google Workspace elimina la fricción entre pensar y ejecutar:
- No subes archivos → La IA lee directamente de tu Drive
- No copias respuestas → La IA genera documentos en tu Docs
- No buscas y luego preguntas → La IA busca directamente

**La integración verdadera multiplica la productividad porque usas la herramienta más.**

---

**Cierre de Semana 2 Completa**

Has completado la Semana 2: Especialización.

Herramientas dominadas:
- ✅ Custom GPTs (ChatGPT) - Especialistas rápidos
- ✅ Claude Projects - Analistas profundos
- ✅ Gemini + Workspace - Integración total

**Estás listo para la Semana 3: Herramientas Avanzadas.**

Nos vemos en el Día 7 con NotebookLM.
