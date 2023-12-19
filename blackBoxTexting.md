## Enfoque Desktop-First:

En este proyecto, optamos por seguir la metodología "desktop-first". Esta elección se fundamenta en la predominancia de equipos de escritorio en nuestro entorno laboral. Nos esforzamos por ofrecer la mejor experiencia posible a la mayoría de nuestros usuarios, capitalizando la amplitud y comodidad de las pantallas más grandes para optimizar el diseño y la presentación del contenido. En nuestro entorno, donde las computadoras de escritorio son la norma, consideramos esencial que la versión principal del sitio esté perfectamente adaptada a estas pantallas.

---

## Pruebas de Caja Negra para el Uso de Media Queries:

**Contexto:** Se implementaron media queries para establecer un diseño específico en pantallas más pequeñas. Se realizaron pruebas de caja negra para evaluar la efectividad y la consistencia de estas media queries.

**Problema:** Implementación de Media Queries

### Pruebas:

1. **Diseño en Pantallas de Menos de 768px:**
   - **Entrada:** Visualizar la página en dispositivos con pantallas de menos de 768px.
   - **Resultado Esperado:** Verificar que el diseño se ajuste correctamente según las especificaciones establecidas en las media queries.

2. **Consistencia Visual y de Contenido:**
   - **Entrada:** Navegar por la página en diferentes tamaños de pantalla.
   - **Resultado Esperado:** Confirmar que la transición entre los diseños sea suave y que el contenido se presente de manera coherente.

3. **Pruebas de Rendimiento:**
   - **Entrada:** Evaluar el rendimiento de la página con y sin media queries.
   - **Resultado Esperado:** Confirmar que las media queries no afecten negativamente el rendimiento y que se mejore la experiencia en pantallas más pequeñas.

**Conclusión:** Las media queries implementadas han demostrado ser efectivas en ajustar el diseño según las dimensiones de la pantalla, mejorando la experiencia del usuario en dispositivos más pequeños. Se sugiere mantener la consistencia y realizar pruebas continuas.

---

## Pruebas de Caja Negra para el Uso Incorrecto de Valores Absolutos:

**Contexto:** Se identificó el uso incorrecto de valores absolutos en el proyecto web, lo que puede tener implicaciones en la responsividad y adaptabilidad del diseño. Se llevan a cabo pruebas de caja negra para evaluar estas problemáticas.

**Problema:** Uso Incorrecto de Valores Absolutos

### Pruebas:

1. **Responsividad en Diferentes Dispositivos:**
   - **Entrada:** Visualizar la página en dispositivos con diferentes resoluciones.
   - **Resultado Esperado:** Problemas de adaptación debido al uso de valores absolutos, generando desbordamientos y pérdida de contenido en dispositivos más pequeños.

2. **Accesibilidad:**
   - **Entrada:** Utilizar herramientas de accesibilidad en la página.
   - **Resultado Esperado:** Dificultades de navegación y lectura asistida debido a la falta de flexibilidad en el diseño.

3. **Consistencia Visual en Navegadores:**
   - **Entrada:** Probar la página en navegadores diversos, aumentando y reduciendo el ancho del navegador.
   - **Resultado Esperado:** Inconsistencias visuales y de diseño debido a la rigidez de los valores absolutos.

4. **Pruebas de Rendimiento:**
   - **Entrada:** Evaluar el rendimiento de la página en términos de velocidad de carga.
   - **Resultado Esperado:** Impacto negativo en el rendimiento debido a la carga ineficiente en dispositivos con capacidades variadas.

**Conclusión:** El uso incorrecto de valores absolutos en el diseño ha generado problemas significativos en la responsividad y adaptabilidad del proyecto. Se recomienda una revisión y corrección de estos valores para mejorar la experiencia del usuario en diferentes contextos.

---

## Resumen Corporativo de Pruebas de Caja Negra para el Proyecto Web:

Este resumen destaca las pruebas de caja negra llevadas a cabo para evaluar el proyecto web, centrándose en dos problemáticas principales: el uso incorrecto de la etiqueta "include" y la multiplicidad de etiquetas `<body>`, `<header>`, y `<footer>`.

**Problema: Uso Incorrecto del Tag "include"**

**Contexto:** La etiqueta "include" se implementó para importar secciones de código HTML desde archivos externos, pero su uso incorrecto generó inconvenientes que afectan la eficiencia y escalabilidad del proyecto.

### Pruebas:

1. **Modularidad:**
   - **Entrada:** Revisar la estructura de archivos del proyecto.
   - **Resultado Esperado:** Falta de modularidad complicando la comprensión del código.

2. **Coherencia Visual:**
   - **Entrada:** Examinar la página en diferentes resoluciones y dispositivos.
   - **Resultado Esperado:** Inconsistencias visuales debido a la importación desorganizada de secciones.

3. **Rendimiento:**
   - **Entrada:** Medir los tiempos de carga de la página.
   - **Resultado Esperado:** Aumento del tiempo de carga debido a la carga de múltiples archivos.

4. **Mantenimiento:**
   - **Entrada:** Realizar cambios en una sección importada.
   - **Resultado Esperado:** Cambios afectan todas las instancias importadas, complicando la personalización y mantenimiento.

5. **Trazabilidad:**
   - **Entrada:** Buscar la definición de una sección específica en el código.
   - **Resultado Esperado:** Dificultad para identificar y rastrear secciones específicas.

**Conclusión:** El uso incorrecto de la etiqueta  "include" ha introducido problemas de modularidad, coherencia visual, rendimiento y mantenimiento en el proyecto.

**Problema 2: Multiplicidad de Etiquetas `<body>`, `<header>`, y `<footer>`**

**Contexto:** En la misma página HTML, se han colocado múltiples etiquetas `<body>`, `<header>`, y `<footer>`, lo que puede conducir a inconsistencias y errores de renderización.

### Pruebas:

1. **Consistencia de Renderización:**
   - **Entrada:** Visualizar la página en navegadores diferentes.
   - **Resultado Esperado:** Diferencias notables en la apariencia y estructura de la página.

2. **Accesibilidad:**
   - **Entrada:** Utilizar herramientas de accesibilidad en la página.
   - **Resultado Esperado:** Problemas de navegación y lectura asistida debido a la presencia de varias etiquetas.

3. **Rendimiento:**
   - **Entrada:** Cargar la página en dispositivos con capacidades variadas.
   - **Resultado Esperado:** La presencia de múltiples etiquetas afecta el rendimiento, especialmente en dispositivos con recursos limitados.

**Conclusión:** El uso incorrecto de la etiqueta "include" y la multiplicidad de etiquetas `<body>`, `<header>`, y `<footer>` pueden resultar en una serie de problemas, desde redundancias y dificultades de mantenimiento hasta impactos negativos en la experiencia del usuario y el rendimiento general. Se recomienda una revisión exhaustiva del código y la implementación de prácticas más eficientes y modularizadas para abordar estas problemáticas y mejorar la calidad del proyecto.
