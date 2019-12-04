# [FINAL] Sitio + Landing Page en BS4 Personalizado

Carrera: Analista de Sistemas.

Materia: Programación Web I.

en proceso
<http://bit.ly/2RkoAxJ>

## OBJETIVOS

Que el alumnx aplique las buenas prácticas vistas en clase y el correcto uso de la librería Bootstrap -herramienta de la práctica profesional <https://getbootstrap.com/> - como plantilla para maquetar las versiones móvil-tablet-escritorio de un Sitio Web informativo y una Landing Page promocional.

La temática es libre, se sugiere articular con la consigna de final para la materia de composición digital donde proponen la diagramación de un sitio web responsivo, pero tanto el sitio como la landing tienen que tener un hilo conductor

## MODALIDAD

De carácter individual ó grupal (no más de 3 alumnxs) y obligatorio.

Para la fecha de final se presentarán el proyecto para su prueba de interacción y defensa  

Para formalizar la entrega se dejará como backup una copia de los documentos que hagan a la consigna en una carpeta comprimida (formato .zip ó .rar) con el nombre **“FINAL-comision-materia-Nombre_Alumno-Nombre_otro_Alumno”** que contenga:

  - una carpeta “sitio” con los archivos correspondientes a su navegación y recursos.
  - una carpeta “landingpage” con los archivos correspondientes a su navegación y recursos.
  - una carpeta “editables” que contenga los archivos de origen (.ai, .psd) de los recursos gráficos diseñados por el alumnx, incluyendo los wireframes o mockups creados para la materia de composición digital (sólo los jpg).
  - y un archivo INFO.txt con los datos del alumnx/grupo:
    + nombre apellido.
    + carrera y comisión.
    + navegador que se usó para testear.
    + cantidad de horas aprox. dedicadas al trabajo práctico.
    + Breve descripción del objetivo del sitio y su landing.
    + URL del hosting gratuito donde queda publicado (opcional).
    + Nombre de Dominio .com.ar sugerido (no es necesario el registro).

## CONSIGNAS FINAL

**Contenidos Finales** (sin cuerpos de lorem ú otros textos ó imágenes de molde):

**Redacción de textos coherentes**
**Imágenes con formato y resolución correspondientes**

### Pauta Técnica

Sobre el desarrollo del **Sitio Informativo:**

**Secciones principales:**

* “Inicio“, El nombre y/o logo de la marca/negocio/proyecto debe estar presente, como parte de la interfaz, permite comunicarle al usuario de quién es este sitio. Debe ser claro el objetivo del sitio: es un carrito de compras? ó institucional? La sección de inicio, también conocida como “home”, generalmente funciona como un resumen del contenido en ese sitio, es la presentación de la marca/negocio/proyecto.
* +3 secciones (pueden ser más) coherentes a la temática del sitio. Por ejemplo, si se tratara de una Agencia Digital: Portfolio/Servicios/Nuestro Equipo/etc.
* 1 sección con formulario. Por ejemplo: “Contacto” ó “Presupuesto".
  
**Navegación del Sitio Informativo:**

A cada sección vinculada al menú principal del sitio, le tiene que corresponder un documento .html propio (por ejemplo: index.html, servicios.html, contacto.html, etc)
El menú principal tiene que ser consistente en todos las secciones para facilitar la navegación al usuario, las opciones no deben cambiar sus textos (rótulos) ni su orden.
usar la clase .active en el list item correspondiente, ayuda a indicarle al usuario cuál es el documento actual cargado en pantalla

Sobre el desarrollo de la **Landing Page:**

- **Áreas de la Landing Page:**
  * Titular
  * Imagen de Producto o Servicio
  * Call To Action (dependiendo la temática puede ser un simple botón o un formulario).
  * Beneficios
  * Testimonios
  * Rescate (pie de página, generalmente el enlace a las redes sociales).

- **Navegación de la Landing Page:**
  * todas las áreas/secciones se resuelven en el mismo documento index.html, el componente de barra de navegación puede llegar a ser opcional (depende de la temática).

- **Uso de la Librería Boostrap (Sitio y Landing):**

  * las hojas de estilo y javascript tienen que quedar vinculados por CDN (recurso remoto).

- **Personalizar la plantilla (Sitio y Landing):**

  * Incluir un Theme (pueden usarse los recursos online vistos en clase) y/o css adicional para personalizar cada sitio (un único “css de autor” por proyecto)

  * incorporar efectos dinámicos mediante la instalación de plugins (por ej: fancybox para la interacción de una galería de fotos)


### CRITERIOS DE EVALUACIÓN

- Recursos Gráficos optimizados para el contexto de adaptación, por ejemplo: si se implementa la etiqueta <picture>, considerar el set de imágenes necesario para los distintos contextos (movil y tablet con sus variantes para retina y escritorio)

- Uso (con criterio) de los nombres de clase y componentes interactivos que ofrece bootstrap, extendiendo los ejemplos de cursada (tienen los catálogos interactivos y atajos por extensión para alivianar la consulta a la documentación)
