# Dia 11: Ejercicios Practicos
## Diseña tu Sitio Web

**Tiempo estimado:** 30-45 minutos
**Objetivo:** Crear y publicar tu sitio web profesional usando IA para generar el codigo, sin conocimientos de programacion.

---

## Requisitos Previos

### Antes de empezar:

1. **Cuenta en ChatGPT o Claude**
   - Usa la que prefieras
   - Version gratuita funciona perfectamente

2. **Editor de texto**
   - **Opcion 1 (Recomendada):** VS Code - Descarga gratis en code.visualstudio.com
   - **Opcion 2:** Notepad++ (Windows) - notepad-plus-plus.org
   - **Opcion 3:** TextEdit (Mac) - Ya instalado
   - **Opcion 4:** Bloc de notas (cualquier sistema)

3. **Navegador web**
   - Chrome, Firefox, Safari o Edge

4. **Cuenta para hosting** (elige una):
   - **Opcion A:** GitHub - github.com (requiere registro)
   - **Opcion B:** Netlify - netlify.com (mas facil, arrastra y suelta)

5. **Preparacion de contenido**
   - Ten listos tus textos
   - Define colores corporativos
   - Datos de contacto

---

## Ejercicio 1: Planeacion de Contenido (10 minutos)

### Objetivo
Definir todo el contenido de tu sitio web antes de generar codigo.

### Plantilla de Planeacion

Completa esta plantilla con tu informacion:

#### 1. Datos Basicos

**Nombre profesional o despacho:**
```

```

**Propuesta de valor (1 frase que te diferencia):**
```
Ejemplo: "Contador especializado en RESICO y nomina que simplifica tus obligaciones fiscales"

Tu propuesta:

```

#### 2. Servicios Principales (3-5 servicios)

**Servicio 1:**
- Nombre: _________________________________
- Descripcion breve (2-3 lineas): _________________________________

**Servicio 2:**
- Nombre: _________________________________
- Descripcion breve (2-3 lineas): _________________________________

**Servicio 3:**
- Nombre: _________________________________
- Descripcion breve (2-3 lineas): _________________________________

**Servicio 4 (opcional):**
- Nombre: _________________________________
- Descripcion breve (2-3 lineas): _________________________________

**Servicio 5 (opcional):**
- Nombre: _________________________________
- Descripcion breve (2-3 lineas): _________________________________

#### 3. Sobre Ti/Tu Despacho (2-3 parrafos)

```
Parrafo 1 (Experiencia y especializacion):



Parrafo 2 (Certificaciones, estudios relevantes):



Parrafo 3 (Por que te diferencias):


```

#### 4. Datos de Contacto

- **Email:** _________________________________
- **Telefono:** _________________________________
- **WhatsApp:** _________________________________ (si es diferente)
- **Ubicacion:** _________________________________ (Ciudad, Estado)
- **Redes sociales:**
  - LinkedIn: _________________________________
  - Facebook: _________________________________
  - Otro: _________________________________

#### 5. Diseño Visual

**Colores corporativos:**
- Color principal: _________________________________ (ej: Azul oscuro)
- Color secundario: _________________________________ (ej: Blanco)
- Color de acento: _________________________________ (ej: Verde para botones)

**Estilo preferido:**
- [ ] Profesional y serio
- [ ] Moderno y minimalista
- [ ] Amigable y accesible
- [ ] Corporativo elegante

---

## Ejercicio 2: Generar el Codigo con IA (10 minutos)

### Objetivo
Usar IA para generar el codigo HTML y CSS completo de tu sitio web.

### Paso 1: Preparar el Prompt (2 minutos)

Usa esta plantilla, reemplazando con tu informacion:

```
Crea un sitio web profesional de una pagina (one-page) en HTML y CSS
para mi despacho contable con estas caracteristicas:

INFORMACION:
Nombre: [Tu nombre o nombre del despacho]
Propuesta de valor: [Tu frase diferenciadora]

Servicios:
1. [Servicio 1]: [Descripcion breve]
2. [Servicio 2]: [Descripcion breve]
3. [Servicio 3]: [Descripcion breve]

Sobre mi:
[Copia tus 2-3 parrafos]

Contacto:
- Email: [tu email]
- Telefono: [tu telefono]
- Ubicacion: [ciudad, estado]

DISEÑO:
- Estilo: Profesional y moderno
- Color principal: [tu color] (codigo hex si lo conoces)
- Color secundario: Blanco
- Responsive: Si (funciona en movil y desktop)

ESTRUCTURA:
Incluye estas secciones en orden:
1. Header con navegacion
2. Hero section con propuesta de valor
3. Servicios en tarjetas
4. Sobre mi con foto placeholder
5. Contacto con formulario (action mailto)
6. Footer con copyright

REQUISITOS TECNICOS:
- Todo en UN solo archivo HTML
- CSS incluido en <style> dentro del HTML
- Sin JavaScript complejo
- Formulario de contacto basico con mailto
- Optimizado para velocidad
- Meta tags para SEO basico

Genera el codigo completo listo para copiar y usar.
```

### Paso 2: Ejecutar en ChatGPT o Claude (3 minutos)

1. Abre ChatGPT (chat.openai.com) o Claude (claude.ai)
2. Pega el prompt completo con tu informacion
3. Envia
4. Espera a que genere el codigo completo

**La IA respondera con un bloque de codigo HTML completo.**

### Paso 3: Copiar el Codigo (2 minutos)

1. Localiza el codigo en la respuesta
2. Busca el boton "Copy code" o selecciona todo
3. Copia todo el codigo desde `<!DOCTYPE html>` hasta `</html>`

**Tip:** Asegurate de copiar TODO el codigo, no solo una parte.

### Paso 4: Revisar el Codigo Generado (3 minutos)

Antes de guardarlo, revisa rapidamente que la IA incluyo:

- [ ] Tu nombre/despacho correcto
- [ ] Tus servicios listados
- [ ] Tu informacion de contacto
- [ ] Seccion Sobre mi con tu biografia
- [ ] Colores que pediste
- [ ] Formulario de contacto

**Si falta algo:** Pide a la IA que lo corrija o agregue.

---

## Ejercicio 3: Guardar y Probar Localmente (10 minutos)

### Objetivo
Guardar el codigo como archivo HTML y probarlo en tu navegador.

### Paso 1: Abrir Editor de Texto (1 minuto)

**VS Code:**
- Abre VS Code
- File > New File
- File > Save As

**Notepad++:**
- Abre Notepad++
- Archivo > Nuevo
- Listo para pegar

**Bloc de notas:**
- Abre Bloc de notas
- Listo para pegar

### Paso 2: Pegar el Codigo (1 minuto)

1. En tu editor vacio, pega todo el codigo que copiaste
2. Verifica que se pego completo

### Paso 3: Guardar como HTML (2 minutos)

1. Crea una carpeta nueva en tu escritorio llamada "mi-sitio-web"
2. Guarda el archivo dentro de esa carpeta
3. **Nombre del archivo:** `index.html`
4. **Tipo de archivo:**
   - VS Code: Guardara automaticamente como .html
   - Notepad++: Selecciona "HTML file"
   - Bloc de notas: Asegurate que diga `index.html` (con las comillas)

**IMPORTANTE:** El nombre debe ser exactamente `index.html` en minusculas.

### Paso 4: Abrir en Navegador (2 minutos)

**Metodo 1 - Doble clic:**
- Ve a la carpeta "mi-sitio-web"
- Doble clic en `index.html`
- Se abrira en tu navegador predeterminado

**Metodo 2 - Arrastrar:**
- Abre tu navegador (Chrome, Firefox, etc)
- Arrastra el archivo `index.html` a la ventana del navegador

### Paso 5: Verificar Funcionamiento (4 minutos)

Revisa que todo funciona:

**Seccion por seccion:**
- [ ] Header: Se ve tu nombre y menu de navegacion
- [ ] Hero: Tu propuesta de valor esta visible
- [ ] Servicios: Tus 3-5 servicios se muestran
- [ ] Sobre ti: Tu biografia aparece
- [ ] Contacto: Formulario presente
- [ ] Footer: Copyright visible

**Diseño:**
- [ ] Los colores son los que pediste
- [ ] El texto es legible
- [ ] No hay textos que se enciman

**Responsive (prueba en movil):**
- Reduce el tamaño de la ventana del navegador
- [ ] El diseño se adapta a pantalla pequeña
- [ ] Todo sigue siendo legible

**Si algo no funciona:** Anota que necesitas ajustar.

---

## Ejercicio 4: Personalizar y Ajustar (15 minutos)

### Objetivo
Hacer ajustes finales al diseño y contenido.

### Ajustes Comunes

#### Ajuste 1: Cambiar Colores (Si es necesario)

Si los colores no son exactamente los que quieres:

**Pide a la IA:**
```
En el codigo que generaste, cambia el color principal azul
por verde corporativo (#2ECC71). Muestrame solo las lineas
que necesito modificar.
```

**O edita directamente:**
1. En tu editor, busca (Ctrl+F) el codigo del color actual
2. Reemplaza con tu codigo de color preferido
3. Guarda
4. Refresca el navegador (F5)

#### Ajuste 2: Modificar Textos

Para cambiar algun texto:

1. En tu editor, busca el texto que quieres cambiar
2. Modifica directamente
3. Guarda
4. Refresca navegador

**Ejemplo:**
```html
<h1>Despacho Contable XYZ</h1>
```
Cambia "Despacho Contable XYZ" por tu nombre real.

#### Ajuste 3: Agregar o Quitar Servicios

**Para agregar un servicio:**

Pide a la IA:
```
Agrega un cuarto servicio a la seccion de servicios:
Nombre: Auditoria Fiscal
Descripcion: Revision completa de cumplimiento fiscal
Muestrame solo el codigo HTML del nuevo servicio.
```

Copia y pega en la seccion de servicios.

**Para quitar un servicio:**
Simplemente borra el bloque HTML completo de ese servicio.

#### Ajuste 4: Cambiar Tamaño de Hero Section

Si quieres que la seccion principal sea mas grande:

Pide a la IA:
```
En la seccion Hero, aumenta la altura a 100vh para que
ocupe toda la pantalla. Muestrame el CSS modificado.
```

#### Ajuste 5: Agregar Logo (Si tienes)

Si tienes un logo en formato PNG o JPG:

1. Guarda tu logo en la misma carpeta que index.html
2. Nombra el archivo: `logo.png` o `logo.jpg`
3. Pide a la IA:
```
Agrega mi logo (archivo logo.png) en el header del sitio,
a la izquierda del nombre. Muestrame el codigo HTML.
```

### Iteracion

**Proceso recomendado:**
1. Identifica que quieres cambiar
2. Pregunta a la IA como hacerlo
3. Aplica el cambio
4. Guarda y refresca navegador
5. Verifica el resultado
6. Repite si necesitas mas ajustes

**Tiempo:** 2-3 ajustes en 15 minutos

---

## Ejercicio 5: Publicar en Internet (15 minutos)

### Objetivo
Subir tu sitio web a internet para que sea accesible publicamente.

### Opcion A: Netlify (Mas Facil - Recomendado)

#### Paso 1: Crear Cuenta en Netlify (3 minutos)

1. Ve a netlify.com
2. Click en "Sign up"
3. Registrate con email o GitHub
4. Verifica tu email

#### Paso 2: Subir tu Sitio (5 minutos)

1. En Netlify, busca la zona que dice "Drop your site folder here"
2. Arrastra tu carpeta "mi-sitio-web" completa a esa zona
3. Netlify la procesara automaticamente (30 segundos)
4. Te dara una URL aleatoria tipo: `https://random-name-12345.netlify.app`

#### Paso 3: Verificar tu Sitio (2 minutos)

1. Click en la URL que te dio Netlify
2. Verifica que tu sitio se ve correctamente
3. Prueba desde tu celular tambien

#### Paso 4: Cambiar Nombre del Sitio (Opcional, 3 minutos)

1. En Netlify, ve a Site settings
2. Click en "Change site name"
3. Elige un nombre (ej: `tudespacho-contable`)
4. Tu URL sera: `https://tudespacho-contable.netlify.app`

#### Paso 5: Actualizar tu Sitio (Cuando necesites)

1. Haz cambios en tu archivo index.html local
2. Guarda
3. En Netlify, arrastra la carpeta actualizada
4. Netlify actualiza automaticamente

**Tu sitio esta en linea. Comparte tu URL.**

---

### Opcion B: GitHub Pages (Mas Profesional)

#### Paso 1: Crear Cuenta en GitHub (3 minutos)

1. Ve a github.com
2. Click en "Sign up"
3. Elige un nombre de usuario (sera parte de tu URL)
4. Completa registro y verifica email

#### Paso 2: Crear Repositorio (4 minutos)

1. Click en el boton verde "New" (nuevo repositorio)
2. Nombre del repositorio: `tu-usuario.github.io`
   - **Importante:** Reemplaza "tu-usuario" con tu nombre de usuario exacto
   - Ejemplo: Si tu usuario es "jperez", nombre: `jperez.github.io`
3. Marca "Public"
4. Click en "Create repository"

#### Paso 3: Subir tu Archivo (5 minutos)

1. En la pagina del repositorio, click en "uploading an existing file"
2. Arrastra tu archivo `index.html` (solo el archivo, no la carpeta)
3. Opcionalmente agrega un mensaje: "Primer version del sitio"
4. Click en "Commit changes"

#### Paso 4: Activar GitHub Pages (2 minutos)

1. En tu repositorio, click en "Settings"
2. En el menu lateral, click en "Pages"
3. En "Source", selecciona "main" branch
4. Click en "Save"
5. Espera 1-2 minutos

#### Paso 5: Verificar tu Sitio (1 minuto)

1. Tu URL sera: `https://tu-usuario.github.io`
2. Visitala en tu navegador
3. Puede tardar 2-3 minutos en activarse la primera vez

#### Paso 6: Actualizar tu Sitio (Cuando necesites)

1. Haz cambios en tu index.html local
2. Ve a tu repositorio en GitHub
3. Click en index.html
4. Click en el icono de lapiz (editar)
5. Borra todo y pega tu codigo actualizado
6. Click en "Commit changes"
7. Espera 1 minuto, cambios estaran en linea

**Tu sitio esta en linea en una URL profesional.**

---

## Ejercicio 6 (BONUS): Optimizacion SEO Basica (10 minutos)

### Objetivo
Optimizar tu sitio para que Google lo encuentre.

### Paso 1: Verificar Meta Tags

Busca en tu codigo HTML la seccion `<head>` y verifica que tenga:

```html
<title>Tu Nombre - Contador en [Ciudad]</title>
<meta name="description" content="[Descripcion de 150 caracteres]">
<meta name="keywords" content="contador, [ciudad], RESICO, nomina">
```

**Si falta algo, pide a la IA:**
```
Agrega meta tags optimizados para SEO:
- Titulo: [Tu nombre] - Contador especializado en [servicios] en [ciudad]
- Descripcion: [Descripcion de tus servicios en 150 caracteres]
- Keywords: contador, [ciudad], [tus servicios principales]
```

### Paso 2: Optimizar Contenido

**Asegurate que tu sitio mencione:**
- [ ] Tu ciudad/ubicacion al menos 2 veces
- [ ] Tus servicios especificos (no solo "servicios contables")
- [ ] Palabras que clientes buscarian

**Ejemplo bueno:**
"Contador especializado en RESICO y nomina en Monterrey"

**Ejemplo malo:**
"Ofrezco servicios contables de calidad"

### Paso 3: Crear Sitemap (Opcional)

Para una pagina simple no es critico, pero puedes agregar:

Pide a la IA:
```
Crea un archivo sitemap.xml simple para mi sitio web
de una sola pagina. La URL es [tu-url].
```

Guarda como `sitemap.xml` en tu carpeta y sube junto con index.html.

---

## Problemas Comunes y Soluciones

### Problema 1: "El archivo no abre como pagina web"
**Causa:** No tiene extension .html
**Solucion:**
- Renombra el archivo para que termine en `.html`
- En Windows, puede estar guardado como `.txt` sin que lo veas
- Activa "Mostrar extensiones de archivo" en Windows

### Problema 2: "Los colores no son los que pedi"
**Solucion:**
- Pide a la IA que genere de nuevo con colores especificos
- O edita directamente los codigos de color en el CSS

### Problema 3: "En mi celular se ve mal"
**Solucion:**
- Verifica que el codigo tenga `<meta name="viewport"...>` en el head
- Pide a la IA: "Asegurate que sea responsive para moviles"

### Problema 4: "El formulario no envia emails"
**Causa:** `mailto:` es basico y depende del cliente de email
**Solucion:**
- Usa Formspree (formspree.io) gratis
- Pide a la IA: "Integra Formspree en el formulario de contacto"

### Problema 5: "GitHub Pages no muestra mi sitio"
**Solucion:**
- Verifica que el archivo se llame exactamente `index.html`
- Espera 5 minutos despues de subir
- Verifica en Settings > Pages que este activado

---

## Checklist de Finalizacion

- [ ] Planee todo el contenido de mi sitio web
- [ ] Genere el codigo HTML/CSS completo con IA
- [ ] Guarde el archivo como index.html
- [ ] Probe mi sitio localmente en navegador
- [ ] Hice ajustes de colores y textos
- [ ] Verifique que funciona en pantalla pequeña (responsive)
- [ ] Publique mi sitio en Netlify o GitHub Pages
- [ ] Verifique que mi URL publica funciona
- [ ] Optimice basicamente para SEO
- [ ] Compartí mi URL con al menos 1 persona

---

## Reflexion Final

### Tu Sitio Web

**URL de tu sitio web publicado:**
```

```

**¿Que fue lo mas dificil del proceso?**
```

```

**¿Que mejorarias en una proxima version?**
```

```

**¿Como usaras tu sitio web para tu practica?**
```

```

---

## Proximos Pasos Recomendados

**Esta semana:**
- Comparte tu URL en tus redes sociales
- Agregala a tu firma de email
- Actualiza tu perfil de Google My Business con el link

**Este mes:**
- Considera comprar dominio propio ($300/año)
- Agrega casos de exito o testimonios
- Crea 2-3 articulos de blog sobre temas fiscales

**Este año:**
- Expande a sitio multi-pagina
- Agrega recursos descargables
- Implementa estrategia de contenido para SEO

---

## Preparacion para Dia 12

**Mañana: Ultimo dia del reto - Monetizacion**

Veremos como monetizar todo lo aprendido:
- 4 modelos de negocio con IA
- Servicios premium que puedes ofrecer
- Como diferenciarte y cobrar mas
- Plan de implementacion

**Para prepararte:**
- Ten tu sitio web terminado
- Piensa en que servicios actuales podrias mejorar con IA
- Considera que servicios nuevos podrias ofrecer
- Reflexiona sobre tu propuesta de valor unica

---

**Felicidades por crear tu sitio web profesional.**

**Ahora tienes presencia digital 24/7 trabajando por ti.**

**Nos vemos en el Dia 12 para cerrar el reto completo.**
