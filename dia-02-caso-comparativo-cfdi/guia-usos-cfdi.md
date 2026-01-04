# Guía de Usos de CFDI 4.0
## Referencia Rápida para Contadores

---

## Catálogo Completo de Usos de CFDI

### Gastos (Clave G)

| Clave | Descripción | Cuándo Usar | Ejemplo |
|-------|-------------|-------------|---------|
| **G01** | Adquisición de mercancías | Compra de inventario para reventa | Compra de productos para tienda |
| **G02** | Devoluciones, descuentos o bonificaciones | Notas de crédito por devoluciones | NC por mercancía devuelta |
| **G03** | Gastos en general | Servicios, consumibles, gastos operativos | Papelería, limpieza, servicios |

### Inversiones (Clave I)

| Clave | Descripción | Cuándo Usar | Ejemplo |
|-------|-------------|-------------|---------|
| **I01** | Construcciones | Edificaciones, obras civiles | Construcción de bodega |
| **I02** | Mobiliario y equipo de oficina | Muebles, equipo de oficina como activo | Escritorios, sillas, archiveros |
| **I03** | Equipo de transporte | Vehículos de la empresa | Automóvil, camioneta de reparto |
| **I04** | Equipo de cómputo y accesorios | Hardware, servidores, laptops | Computadoras, impresoras |
| **I05** | Dados, troqueles, herramental | Equipo de manufactura | Moldes para producción |
| **I06** | Comunicaciones telefónicas | Equipo de telecomunicaciones | Conmutador, equipo de red |
| **I07** | Comunicaciones satelitales | Equipo de comunicación satelital | Antenas satelitales |
| **I08** | Otra maquinaria y equipo | Maquinaria industrial | Tornos, fresadoras |

### Deducciones Personales (Clave D)

| Clave | Descripción | Cuándo Usar | Ejemplo |
|-------|-------------|-------------|---------|
| **D01** | Honorarios médicos, dentales y gastos hospitalarios | Gastos de salud deducibles | Consulta médica, hospitalización |
| **D02** | Gastos médicos por incapacidad o discapacidad | Gastos médicos especiales | Tratamientos, aparatos ortopédicos |
| **D03** | Gastos funerales | Servicios funerarios | Funeraria |
| **D04** | Donativos | Donativos a instituciones autorizadas | Donación a fundación |
| **D05** | Intereses por créditos hipotecarios | Intereses de hipoteca casa habitación | Crédito Infonavit, bancario |
| **D06** | Aportaciones voluntarias al SAR | Ahorro para el retiro | Aportaciones adicionales Afore |
| **D07** | Primas de seguros de gastos médicos | Seguros de salud | Póliza de gastos médicos mayores |
| **D08** | Gastos de transportación escolar | Transporte escolar obligatorio | Camión escolar |
| **D09** | Depósitos en cuentas de ahorro | Cuentas especiales de ahorro | Cuenta de ahorro educativo |
| **D10** | Pago de servicios educativos | Colegiaturas en niveles autorizados | Colegiatura primaria a bachillerato |

### Sin Efectos Fiscales (Clave S)

| Clave | Descripción | Cuándo Usar | Ejemplo |
|-------|-------------|-------------|---------|
| **S01** | Sin efectos fiscales | Comprobantes sin deducción | Gastos personales no deducibles |

### Por Definir (Clave P)

| Clave | Descripción | Cuándo Usar | Ejemplo |
|-------|-------------|-------------|---------|
| **P01** | Por definir | Cuando el receptor no especifica uso | Ventas al público en general |

### Pagos (Clave CP)

| Clave | Descripción | Cuándo Usar | Ejemplo |
|-------|-------------|-------------|---------|
| **CP01** | Pagos | Complementos de pago | REP para facturas PPD |

### Nómina (Clave CN)

| Clave | Descripción | Cuándo Usar | Ejemplo |
|-------|-------------|-------------|---------|
| **CN01** | Nómina | Recibos de nómina | Pago de sueldos y salarios |

---

## Errores Frecuentes y Cómo Evitarlos

### Error 1: G03 para Todo
**Problema:** Usar "Gastos en general" para cualquier compra.
**Corrección:**
- Mercancía para venta → G01
- Activos fijos → I01, I02, I03, I04, etc.
- Solo servicios y consumibles → G03

### Error 2: Confundir G01 con G03
**Problema:** No distinguir entre mercancía y gastos.
**Regla:**
- G01: Lo que compras para VENDER
- G03: Lo que compras para USAR en la operación

### Error 3: No usar claves I para inversiones
**Problema:** Deducir como gasto lo que es activo fijo.
**Consecuencia:** El SAT puede rechazar la deducción inmediata.
**Regla:** Si el bien durará más de un año, probablemente es inversión.

### Error 4: Uso incorrecto de D para empresas
**Problema:** Personas morales usando claves D.
**Corrección:** Las claves D son para deducciones PERSONALES de personas físicas.

---

## Matriz de Decisión Rápida

```
¿Qué estás comprando?
│
├── Productos para vender ────────────────────► G01
│
├── Servicios o consumibles ──────────────────► G03
│
├── Bienes que durarán más de 1 año:
│   ├── Muebles de oficina ───────────────────► I02
│   ├── Computadoras ─────────────────────────► I04
│   ├── Vehículos ────────────────────────────► I03
│   ├── Construcciones ───────────────────────► I01
│   └── Otra maquinaria ──────────────────────► I08
│
├── Gastos médicos (persona física) ──────────► D01
│
├── Colegiaturas (persona física) ────────────► D10
│
└── Sin deducción / público general ──────────► S01 o P01
```

---

## Personas Físicas: ¿G03 o Claves D?

### Para Actividad Empresarial/Profesional:
- Gastos del negocio → G03, I02, etc.
- Son deducciones autorizadas de la actividad

### Para Deducciones Personales (Declaración Anual):
- Gastos médicos → D01
- Colegiaturas → D10
- Intereses hipotecarios → D05
- Son deducciones personales del Título IV LISR

**Importante:** Una persona física puede tener ambos tipos de gastos.

---

## Relación Uso CFDI - Método de Pago

| Uso CFDI | Método PUE | Método PPD |
|----------|------------|------------|
| G01, G03 | ✅ Válido | ✅ Válido |
| I01-I08 | ✅ Válido | ✅ Válido |
| D01-D10 | ✅ Válido | ⚠️ Poco común |
| P01 | ✅ Válido | ✅ Válido |
| CP01 | N/A | N/A (es complemento) |

---

## Implicaciones Fiscales por Tipo de Uso

### Claves G (Gastos)
- Deducción: Inmediata en el ejercicio
- Requisitos: Factura, pago, estrictamente indispensable
- Limitaciones: Algunas tienen topes (autos, comidas, etc.)

### Claves I (Inversiones)
- Deducción: Vía depreciación (MOI - deducciones acumuladas)
- Tasas: Varían según tipo de activo (5% a 100% según art. 34 LISR)
- Requisitos: Registro en activo fijo, control de depreciación

| Tipo de Inversión | Tasa de Depreciación |
|-------------------|---------------------|
| Construcciones | 5% |
| Mobiliario y equipo | 10% |
| Equipo de cómputo | 30% |
| Automóviles | 25% |
| Maquinaria | 10% (varía por industria) |

### Claves D (Deducciones Personales)
- Deducción: En declaración anual de PF
- Límite: 5 UMAs anuales o 15% de ingresos
- Requisitos: Pago con medios bancarizados

---

## Validación de Uso CFDI: Checklist

Antes de aceptar una factura, verifica:

- [ ] ¿El uso de CFDI corresponde al tipo de bien/servicio?
- [ ] ¿Es consistente con tu régimen fiscal?
- [ ] ¿Coincide con el tratamiento fiscal que darás?
- [ ] ¿El emisor usó el régimen fiscal correcto?
- [ ] ¿Los datos del receptor están correctos?

---

## Prompt para Validar Uso de CFDI con IA

```
Actúa como contador fiscal especialista en CFDI 4.0.

Recibí una factura con estos datos:
- Concepto: [DESCRIPCIÓN DEL BIEN O SERVICIO]
- Uso CFDI asignado: [USO ACTUAL]
- Receptor: [PERSONA FÍSICA/MORAL] [RÉGIMEN]

Analiza:
1. ¿El uso de CFDI es el correcto para este concepto?
2. Si no es correcto, ¿cuál debería ser?
3. ¿Qué implicaciones fiscales tiene el uso asignado?
4. ¿Debo solicitar corrección al emisor?

Fundamenta tu respuesta en el Anexo 20 y LISR.
```

---

*Guía de Usos CFDI v1.0 - Reto 12 Días de IA para Contadores*
*TodoConta.com*
