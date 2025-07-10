# BRIEFING - PROGRAMA DE MANO
## DanSa - "Danzas y Sabores del Perú"

---

> **¿Qué vamos a crear?** Un programa elegante que los clientes reciban al entrar. Les explicará qué van a ver y comer esta noche.
> 
> **Instrucciones:** Responder con palabras simples. Si no sabe algo, escribe "No sé" o "Por definir".

---

> **Ya sabemos que:** DanSa presenta "Yanuq: La magia de Teresa". Es la historia de una joven que busca una receta perdida de su familia, viajando por todo el Perú. El menú tiene 6 platos y 3 tragos.

---

## 1. LA HISTORIA QUE CONTAMOS

**¿Cómo explicamos la historia de Teresa a los clientes?**
> *Ejemplo: "Una joven que busca los secretos culinarios de su abuelo"*

```
[ Respuesta: Escriba aquí la explicación de la historia... ]
```

**¿Qué mensaje queremos dar con esta historia?**
> *Ejemplo: "La importancia de preservar nuestras tradiciones"*

```
[ Respuesta: Escriba aquí el mensaje principal... ]
```

---

## 2. NUESTRAS DANZAS

> **Confirmado:** Presentamos huayno, marinera, morenada, danza de las tijeras y danzas amazónicas.

**Para cada danza, escribe UNA frase simple que explique qué representa:**

- **Huayno:** ________________________
  *(Placeholder: Danza alegre de los Andes)*

- **Marinera:** ________________________
  *(Placeholder: Baile elegante de la costa peruana)*

- **Morenada:** ________________________
  *(Placeholder: Danza tradicional con trajes coloridos)*

- **Danza de las tijeras:** ________________________
  *(Placeholder: Baile mágico de los Andes con acrobacias)*

- **Danzas amazónicas:** ________________________
  *(Placeholder: Bailes de la selva que conectan con la naturaleza)*

---

## 3. NUESTROS PLATOS

> **Confirmado:** 6 platos: conchas de abanico, ceviche de lenguado, rocoto relleno, arroz con pato, costillar de cordero, postre de cacao.

**¿Cómo llamamos exactamente a cada plato en nuestro menú?**
> *Ejemplo: ¿Se llama "Ceviche de Lenguado"?*

- **Plato 1:** ________________________
  *(Placeholder: Nombre exacto del primer plato)*

- **Plato 2:** ________________________
  *(Placeholder: Nombre exacto del segundo plato)*

- **Plato 3:** ________________________
  *(Placeholder: Nombre exacto del tercer plato)*

- **Plato 4:** ________________________
  *(Placeholder: Nombre exacto del cuarto plato)*

- **Plato 5:** ________________________
  *(Placeholder: Nombre exacto del quinto plato)*

- **Plato 6:** ________________________
  *(Placeholder: Nombre exacto del sexto plato)*

---

## 4. NUESTROS TRAGOS ESPECIALES

> **Confirmado:** "Sara" (con chicha de jora), "El dorado" (de la selva), "Flora" (con pisco y coca).

**¿Por qué se llaman así nuestros tragos?**

- **"Sara":** ________________________
  *(Placeholder: Por la diosa del maíz)*

- **"El dorado":** ________________________
  *(Placeholder: Por la leyenda de El Dorado)*

- **"Flora":** ________________________
  *(Placeholder: Por las plantas del Perú)*

---

## 5. NUESTRA ASPIRACIÓN

> **Confirmado:** DanSa quiere estar entre las mejores experiencias inmersivas de Latinoamérica.

**¿Cómo explicamos nuestro objetivo?**
> *Ejemplo: "Trabajamos cada día para ser reconocidos internacionalmente"*

```
[ Respuesta: Describa cómo comunicamos nuestra aspiración... ]
```

**¿Hemos recibido algún premio o reconocimiento? ¿Es importante para nosotros?**
> *Ejemplo: "Aún no, pero trabajamos para ello"*

```
[ Respuesta: Describa reconocimientos actuales o aspiraciones... ]
```

---

## 6. LO QUE NOS HACE ÚNICOS

**¿Qué hace diferente a DanSa de la competencia?**
> *Ejemplo: "Somos los únicos que combinan alta cocina con espectáculo cultural"*

```
[ Respuesta: Describa qué nos hace únicos frente a otros lugares... ]
```

**¿Cuál es el mensaje principal que queremos dejar a nuestros clientes?**
> *Ejemplo: "El Perú tiene la cultura y gastronomía más rica del mundo"*

```
[ Respuesta: ¿Qué queremos que recuerden nuestros clientes? ]
```

**¿Hay alguna historia curiosa sobre cómo nació DanSa?**
> *Ejemplo: "Nació del sueño de unir las dos artes más bellas del Perú"*

```
[ Respuesta: Cuente alguna anécdota sobre la creación de DanSa... ]
```

---

## FUNCIONALIDADES DE LA VERSIÓN INTERACTIVA (HTML)

### 🎛️ Botones de Acción:
- 💾 **Guardar Progreso**: Confirmación de guardado manual
- 📋 **Ver Resumen**: Vista consolidada de todas las respuestas
- 📄 **Exportar PDF**: Función de impresión/exportación  
- 🗑️ **Limpiar Todo**: Reset completo con confirmación

### ✨ Características Técnicas:
- **Barra de progreso** visual que se actualiza en tiempo real
- **Guardado automático** cada 30 segundos en LocalStorage
- **Recuperación automática** de datos al recargar página
- **Diseño responsive** para móvil, tablet y desktop
- **Efectos hover** y focus states profesionales
- **Print styles** optimizados para exportación

### 🛠️ Tecnologías Utilizadas:
- **HTML5** semántico con estructura accesible
- **CSS3** moderno con colores corporativos (#8B0000)
- **JavaScript Vanilla** sin dependencias externas
- **LocalStorage** para persistencia de datos
- **Progressive Enhancement** - funciona sin JavaScript

---

## NOTAS TÉCNICAS DEL ARCHIVO ORIGINAL

### Funciones JavaScript Principales:

```javascript
// Actualizar barra de progreso en tiempo real
function actualizarProgreso() {
    // Cuenta campos completados y actualiza porcentaje
}

// Guardar datos en navegador
function guardarProgreso() {
    // Guarda en localStorage con confirmación
}

// Recuperar datos al cargar
function cargarProgreso() {
    // Restaura respuestas guardadas automáticamente
}

// Mostrar resumen completo
function verResumen() {
    // Consolida y muestra todas las respuestas
}

// Exportar a PDF
function exportarPDF() {
    // Abre diálogo de impresión del navegador
}

// Limpiar formulario
function limpiarFormulario() {
    // Reset completo con confirmación de seguridad
}
```

### Estilos CSS Destacados:

```css
/* Colores corporativos DanSa */
--color-principal: #8B0000;  /* Rojo oscuro */
--color-hover: #A0522D;      /* Rojo claro para efectos */
--color-texto: #000;         /* Negro para legibilidad */
--color-fondo: #fff;         /* Blanco para contraste */

/* Diseño responsive */
@media print {
    .action-buttons, .progress-bar { display: none; }
    body { margin: 1cm; }
}
```

### Estructura de Datos en LocalStorage:

```json
{
  "historia_teresa": "Historia explicando a Teresa...",
  "mensaje_historia": "Mensaje principal de la narrativa...",
  "huayno": "Descripción del huayno...",
  "marinera": "Descripción de la marinera...",
  "morenada": "Descripción de la morenada...",
  "tijeras": "Descripción danza de tijeras...",
  "amazonicas": "Descripción danzas amazónicas...",
  "plato1": "Nombre exacto primer plato...",
  "plato2": "Nombre exacto segundo plato...",
  "plato3": "Nombre exacto tercer plato...",
  "plato4": "Nombre exacto cuarto plato...",
  "plato5": "Nombre exacto quinto plato...",
  "plato6": "Nombre exacto sexto plato...",
  "sara": "Razón del nombre Sara...",
  "eldorado": "Razón del nombre El dorado...",
  "flora": "Razón del nombre Flora...",
  "objetivo": "Explicación de nuestro objetivo...",
  "reconocimientos": "Premios y reconocimientos...",
  "diferenciador": "Qué nos hace únicos...",
  "mensaje_principal": "Mensaje clave para clientes...",
  "historia_dansa": "Historia curiosa de DanSa..."
}
```

---

## INFORMACIÓN DE CONTEXTO - DANSA

### 🎪 Espectáculo Actual: "Yanuq: La magia de Teresa"
- **Historia central**: Teresa recibe misión de abuelo fallecido
- **Objetivo narrativo**: Recuperar receta ancestral perdida  
- **Viaje geográfico**: Por las tres regiones del Perú (costa, sierra, selva)
- **Creadores**: Vania Masías (productora artística) y Lucho Quequezana (productor musical)

### 🏢 Información Empresarial:
- **Ubicación**: Av. Rivera Navarrete 2692, Lince, Lima
- **Capacidad**: 430 personas (platea + mezzanine)
- **Chef**: Cristian Ramírez

### 🍽️ Menú Confirmado:
- **6 platos**: Conchas de abanico, ceviche de lenguado, rocoto relleno, arroz con pato, costillar de cordero, postre de cacao
- **3 cocteles temáticos**: "Sara", "El dorado", "Flora"

### 🍹 Cocteles Temáticos Detallados:
- **"Sara"**: Whisky de maíz + chicha de jora (homenaje a la diosa del maíz)
- **"El dorado"**: Toronja + camu camu + ají (inspirado en leyenda amazónica)  
- **"Flora"**: Pisco + coca + chocolate blanco (plantas sagradas peruanas)

### 💃 Danzas Confirmadas:
- **Huayno**: Tradición andina ancestral
- **Marinera**: Elegancia costeña peruana
- **Morenada**: Colorido altiplánico boliviano-peruano
- **Danza de las tijeras**: Magia andina con acrobacias
- **Danzas amazónicas**: Conexión selvática con la naturaleza

### 🎯 Aspiraciones Empresariales:
- **Objetivo principal**: Ranking 50 Mejores Restaurantes de Latinoamérica
- **Visión**: Ser la mejor experiencia inmersiva de la región
- **Misión**: Preservar y difundir la cultura peruana a través de gastronomía y espectáculo

---

> **¡Listo!** Con estas respuestas crearemos un programa de mano que explique perfectamente la experiencia "DanSa: Danzas y Sabores del Perú".

---

## INSTRUCCIONES DE USO

### Para Completar Este Briefing:

1. **Tiempo estimado**: 10-15 minutos
2. **Instrucciones**: Responder con palabras simples y directas
3. **Si no sabe algo**: Escribir "No sé" o "Por definir"
4. **Ejemplos**: Usar como guía, no copiar exactamente
5. **Objetivo**: Generar contenido para programa de mano premium

### Para Usar la Versión Interactiva:

1. **Abrir**: `DanSa_Briefing_Interactivo.html` en navegador
2. **Completar**: Formulario con 6 secciones
3. **Guardar**: Automático cada 30 segundos + botón manual
4. **Exportar**: Usar botón "Exportar PDF" o Ctrl+P
5. **Revisar**: Botón "Ver Resumen" para consolidar respuestas

---

*Briefing interno - DanSa 2025*  
*Versión Markdown generada desde archivo HTML interactivo*

---

## ARCHIVOS DEL PROYECTO

### 📁 Archivos Principales:
- `DanSa_Briefing_Interactivo.html` - Herramienta interactiva principal
- `DanSa_Briefing_Interactivo.md` - Esta versión en Markdown  
- `README.md` - Documentación completa del proyecto
- `PROCESO_DESARROLLO.md` - Log del desarrollo (6 fases)
- `GITHUB_SETUP.md` - Guía para subir a GitHub

### 🚀 Para GitHub:
- **Repositorio sugerido**: `dansa-briefing-interactivo`
- **Demo en vivo**: Activar GitHub Pages
- **Documentación**: README.md se muestra automáticamente

**¡Proyecto listo para impresionar a la gerencia!** 🎭✨
