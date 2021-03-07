# CURSO DE FRONTEND DEVELOPER

## HTML Y CSS: DEFINICIÓN Y USOS

**Internet**
A principios de los años 80 nació esta tecnología Interconected Network o red interconectada, y esta es la que hoy en día nos permite compartir sonidos, videos e imágenes.

**WWW**
En 1990 Word Wide Web; fue creada por Tim Berners-Lee el cual también creo el consorcio de la W3C

**W3C**
Word Wide Web Consortium y es el consorcio que estandariza y supervisa las tecnologías del internet HTTP, URL Y HTML

- HTTP
Hyper Text Transfer Potocol ó protocolo de transferencia de hipertexto es la bases que permite la comunicación entre los dispositivos conectados en la red por ejemplo computadores y servidores

- URL
Uniform Resource Locator ó el localizador de rescursos uniformes más conocido como la dirección de un sitio web, es la manera que agregamos un punto a la red

- HTML
Hyper Text Markup Language ó lenguaje de marcado de hiper text esta es lo que le da la estructura un sitio web como dándonos como herramienta: o lista encabezado, párrafo etc.

- CSS
Cascade style sheets ú Hoja de estilo en cascada la cual fue creada en 1994 y son unas series de reglas que describen la apariencia de un sitio web y es el navegador que se encarga de agregar estos estilos a nuestro sitio. esta surgió por la necesidad de mejorar la apariencia de los sitios web, en ella podemos definir el estilo de los componentes html como su tamaño, color, fuente entre otras cosas.


[========]

## ¿QUÉ SON Y PARA QUÉ NOS SIRVEN HTML Y CSS?

**HTML:** Es un lenguaje de marcado usado para decirle a tu navegador cómo estructurar las páginas web que visitas. No es un lenguaje de programación.

**CSS:** Es un lenguaje que nos permite crear páginas web con un diseño agradable para los usuarios. Tampoco es un lenguaje de programación.

[========]

## DOM, CSSOM, RENDER TREE Y EL PROCESO DE RENDERIZADO DE LA WEB

- **DOM:** Document Object Model. Es una transformación del código HTML escrito por nosotros a objetos entendibles para el navegador.


- **CSSOM:** así como el DOM para el HTML, EL CSSOM es una representación de objetos de nuestros estilos en CSS.

- **Render Tree**: es la unión entre el DOM y el CSSOM para renderizar todo el código de nuestra página web.

Pasos que sigue el navegador para construir las páginas web:

1. Procesa el HTML para construir el DOM.
2. Procesa el CSS para construir el CSSOM.
3. El DOM se une con el CSSOM para crear el Render Tree.
4. Se aplican los estilos CSS en el Render Tree.
5. Se ““pintan”” los nodos en la pantalla para que los usuarios vean el contenido de la página web.

[========]

## 5 TIPS PARA APRENDER CSS
<img src="https://static.platzi.com/media/user_upload/Infografia-Frontend-Javascript-86c602ef-a014-47d7-aadd-1293726d06b2.jpg" alt="tips css">


[========]


## ANATOMÍA DE UN ELEMENTO HTML: ATRIBUTOS, ANIDAMIENTO Y ELEMENTOS VACÍOS

Nuestros elementos HTML se componen de:

**Etiqueta de apertura:** el nombre de nuestra etiqueta encerrado entre símbolos de mayor o menor. Por ejemplo: `<h1>`.

**Contenido:**  dentro de nuestras etiquetas podemos añadir texto u otros elementos HTML, lo que conocemos como anidamiento.

**Etiqueta de cierre:** son casi iguales que las etiquetas de apertura, pero también necesitan un slash (/) antes del nombre de la etiqueta. Por ejemplo: `</h1>`.

Las etiquetas de apertura también pueden tener atributos. Los atributos nos permiten definir características especiales para nuestros elementos: `<etiqueta atributo=""valor del atributo"">. Por ejemplo: <h1 class=""saludo"">.`

También existen elementos vacíos. Estos elementos no tienen contenido ni etiqueta de cierre, solo etiqueta de apertura y atributos. Por ejemplo: 
`<img src=""puppy.png"" alt=""mi mascota"">.`


[========]

## ANATOMÍA DE UN DOCUMENTO HTML: DOCTYPE, HTML, HEAD Y BODY

**Indentación del código**

Como se puede apreciar en la estructura de un documento html existen múltiples componentes html anidados en una jerarquía, es decir tenemos unos componentes html envueltos dentro de otros. Para poder identificar que componente html es el padre de otro, se debe realizar una indentación del código.

**Documento html**
Un documento html tiene una anatomía que necesita para que el navegador la pueda analizar correctamente., estas son los siguientes elementos con los cuales el navegador cuenta:
`<!DOCTYPE html>`

Indica al navegador el tipo de documento que se está mostrando y garantiza que el documento sea analizado de la misma manera en todos los navegadores

`<html lang=”es”> … </html>`

Es la etiqueta que envuelve todo el documento y es conocida como root element dentro de esta etiqueta existen dos hijos que son el head y el body:

`<head> … </head>`

La etiqueta head es la cabecera del documento y contiene etiquetas como: los metas, link de archivos css, title que describen al documento y describen que tipos de recursos se deben cargar.

`<meta charset=”Utf8”>`

hace referencia a la codificación de todos los caracteres y está incluyendo todos los idiomas.

`<title>…</title>`


hace referencia al título de nuestro documento html y que se visualiza en la pestaña de la web.

`<body>…</body>.`

Esta etiqueta es conocida como la etiqueta del cuerpo del documento y contiene otros elementos como

- article: diferentes partes del contenido que pueden vivir por sí mismas.

- nav: para hacer menús de navegación.

- aside: contenido menos relevante, como publicidad, etc.

- section: sirve para diferenciar las secciones principales del contenido.

- header: cabecera del documento.

- footer: pie de página del documento.

- h1 - h6: títulos de nuestro sitio web.

- table: tablas de contenidos, similar a la estructura de las hojas de cálculo.

- ul y ol: listas de ítems.

- div: cualquier división para organizar el contenido. El div no tiene ningún valor semántico.

### Otras conclusiones Anatomía de un Documento HTML

Es buena práctica que todas las etiquetas deben tener apertura y cierre incluso las etiquetas que se cierran en sí misma.

Es importante resaltar que la indentación es sumamente importante para saber que elemento está dentro de otro. Es una buena práctica.

Todos los elementos html tienen un modelo caja tiene tres propiedades importantes:
- Margin
- Border
- Padding en la cual se puede apreciar en la sección: 5. Tips para aprender CSS

[========]


## FUNCIONES DE LAS ETIQUETAS HTML MÁS IMPORTANTES

<img src ="https://static.platzi.com/media/user_upload/Funciones%20de%20las%20etiquetas-01-19c2a366-4d38-434c-8aaa-4b85276028dc.jpg" alt="etiquetas mas importantes">

Etiquetas vacias 

<img src ="https://static.platzi.com/media/user_upload/Funciones%20de%20las%20etiquetas-02-32fac483-1c4c-4518-8577-1c0a96103ac3.jpg" alt="Etiquetas vacias">


Descripción de las etiquetas semánticas para la estructura base de nuestra página:

<img src="https://static.platzi.com/media/user_upload/Funciones%20de%20las%20etiquetas-03-e3d21c27-3981-47fd-bdae-2df7becce6e5.jpg" alt="Etiquetas semanticas">


[========]


## LA IMPORTANCIA DEL CÓDIGO SEMÁNTICO

Es importante que como desarrolladores tengamos claro el significado de escribir código. Debes ser consciente de que la manera en la que codeas tenga sentido.

La semántica HTML no es más que darle sentido y estructura a lo que estas escribiendo. Muy importante para el navegador. No todos los elementos deberían ser un div.

[========]

## TIPOS DE ERRORES EN HTML, DEBUGGING Y SERVICIO DE VALIDACIÓN DE ETIQUETAS

Errores sintácticos: Son errores de escritura en el código y evitan que el programa funcione. Pueden ser errores de tipado.

Errores lógicos: En estos la sintaxis es correcta, pero el código no hace lo que debería. El programa funciona, pero de forma incorrecta.


[========]

## ANATOMÍA DE UNA DECLARACIÓN CSS: SELECTORES, PROPIEDADES Y VALORESANATOMÍA DE UNA DECLARACIÓN CSS: SELECTORES, PROPIEDADES Y VALORES

Nuestros estilos con CSS se componen de:

**Selector:** son la referencia a los elementos HTML que queremos estilizar. Los nombres de estas etiquetas van seguidas de una llave de apertura y otra de cierre ({}). Por ejemplo: h1 {}.

**Propiedades:** son el tipo de estilo que queremos darle a nuestros elementos. Van seguidas de dos puntos (:). Las propiedades deben estar dentro de las llaves del selector que definimos anteriormente. Podemos escribir diferentes propiedades en un mismo selector. Por ejemplo: h1 { color: }.

**Valores:** son el estilo que queremos que tomen nuestros elementos HTML con respecto a una propiedad. Van seguidas de un punto y coma (;). Por ejemplo: h1 { color: red; }.

    h1 {
      color: red;
    }
	

[========]

## Tipos de selectores, pseudo-clases y pseudo-elementos

*(asterisco): Es el selector universal. Las propiedades se aplicaran a todos los elementos de nuestro HTML.

**Tipo**: Son selectores que se aplican a cierto elemento HTML en específico. Las propiedades se aplicaran a la etiqueta que queremos, por ejemplo p, body, html, div, etc.

**Clase:** Si nuestras etiqueta de HTML tienen un atributo de class podemos usar ese valor o identificador para que los cambios en el CSS afecten únicamente a ese elemento.

**ID:** Es similar al anterior, si la etiqueta HTML tiene un ID podemos afectar solo ese elemento.

Las Pseudo-clases y Pseudo-elementos nos permiten ser aún más específicos con qué elemento o partes de nuestros elementos deben recibir los estilos.

Para usarlas debemos definir el selector base (por ejemplo, p) seguido de dos puntos y la pseudo-clase que queremos estilizar (por ejemplo: p:first-child). En el caso de los pseudo-elementos debemos usar el dos puntos 2 veces (p::first-letter).

    /* Asterisco (universal) */
    * {
      margin: 0;
    }
    
    /* Tipo */
    h1 {
      color: red;
    }
    
    /* Clase */
    .saludo {
      font-size: 2em;
    }
    
    /* ID */
    #id {
      border-radius: 20px;
    }
    
    /* Pseudo-clases */
    p:first-child {
      color: white;
    }
    
    p:last-child {
      color: purple;
    }
    
    p:nth-child(2n) {
      color: red;
    }
    

[========]

## MODELO DE CAJA

Todos los elementos de HTML tienen un modelo de caja y esta compuesto por cuatro elementos: **contenido, padding, border, margin**.

[========]

## VALORES RELATIVOS Y ABSOLUTOS

Los valores absolutos son, por ejemplo, centímetros, milímetros, pixeles y pulgadas. Se llaman de esta forma porque no tienen en cuenta a nadie más, no depende de la medida de otra unidad.

Los valores relativas, llevan este nombre porque depende de otra unidad de medida o elemento. Por ejemplo, porcentajes, vmx, em, entre otros.

Recuerda que podemos darle estilos a etiquetas HTML muy específicas indicando dónde se van a encontrar. Por ejemplo: si queremos darle estilos únicamente a la imagen que está dentro del header, podemos usar el selector css header img { ... }.


[========]


## MODELO DE CAJA

Todos los elementos de HTML tienen un modelo de caja y esta compuesto por cuatro elementos: **contenido, padding, border, margin**.

[========]


## VALORES RELATIVOS Y ABSOLUTOS

Los valores absolutos son, por ejemplo, centímetros, milímetros, pixeles y pulgadas. Se llaman de esta forma porque no tienen en cuenta a nadie más, no depende de la medida de otra unidad.

Los valores relativas, llevan este nombre porque depende de otra unidad de medida o elemento. Por ejemplo, porcentajes, vmx, em, entre otros.

Recuerda que podemos darle estilos a etiquetas HTML muy específicas indicando dónde se van a encontrar. Por ejemplo: si queremos darle estilos únicamente a la imagen que está dentro del header, podemos usar el selector css header img { ... }.

No olvides resolver el desafío: crear tu propio header con las etiquetas y estilos que más te gusten para compartirlo en la sección de discusiones.


[========]

## DISPLAY EN CSS
<img src="https://static.platzi.com/media/user_upload/Display%20en%20CSS-634bc14a-bdf5-4337-a67d-49fc74f92a60.jpg" alt= "display css">


[========]

## POSICIONAMIENTO CSS
<img src="https://static.platzi.com/media/user_upload/Posicionamiento%20en%20CSS-6477ec29-d5d2-44d0-b3f5-c2876e0ee739.jpg" alt="posicionamiento css">


[========]


## ¿QUÉ SON Y PARA QUÉ NOS SIRVEN LAS ARQUITECTURAS CSS?

Los objetivos son:

- Predecible > Escribir reglas claras.
- Reutilizable > No escribir codigo redundante.
- Mantenible > Que sea facil de leer y adaptarnos a los estandares.
- Escalable > Que pueda crecer facilmente pero sin afectar el rendimiento.

Buenas practicas

- Establecer reglas para que el equipo se entienda.
- Explicar la estructura base o dar los fundamentos del proyecto a un nuevo integrante.
- Evitar hojas de estilo muy extensas
- Tener una buena documentación explicando ciertos aspectos del codigo.


[========]

## OOCSS, BEM, SMACSS, ITCSS Y ATOMIC DESIGN

**OOCSS:** CSS Orientado a Objetos

**BEM**: Block Element Modifier

__ Para elementos

— Para modificadores

**SMACSS:** Arquitectura de CSS Escalable y Modular: Se divide en 5 pasos

1. Componentes Base
2. Layout: Header o Footer, elementos que se utilizan una sóla vez
3. Modulo: Componentes que estaríamos usando en nuestra aplicación más de una vez.
4. State/Estado: Sirven para definir el estado de un componente luego de nuestra acción, por ejemplo, un botón que cambia de color después de ser pulsado.
5. Theme/Temas: Cuando cambien los temas y cambiar los colores de nuestros elementos seleccionados para cambiar de tema.

**ITCSS:**
Inverted Triangle of CSS. Nos indica dividir nuestros archivos de CSS en ciertas partes

**Atomic Design**
Dividir nuestro CSS en pequeñas partes que van juntandose, por eso es llamado Atomic Design, desde moléculas hasta más grandes componente

[========]

## CREACIÓN DE UN CAROUSEL DE IMÁGENES CON CSS: DETALLE DE CADA ITEM

El selector ~ de CSS nos permite dar estilos a todos que cumplan los requisitos y sean “hermanos directos”, es decir, que tengan el mismo elemento padre.
Por ejemplo:



    .PrimerTitulo ~ h2 {
      background-color: red;
    }
    <article class="ContenedorPadre">
      <h2 class="PrimerTitulo">Este es el primer elemento H2</h2>
      <!-- Este título tendrá color de fondo rojo -->
      <h2>Este es el segundo elemento H2</h2>
      <div class="ElementoPadreDiferente">
          <!-- Este título NO tendrá color de fondo rojo porque su padre es diferente -->
        <h2>Este es el tercer elemento H2</h2>
      </div>
      <!-- Este título también tendrá color de fondo rojo -->
      <h2>Este es el cuarto elemento H2</h2>
    </article>


También existe el selector +. Solo aplica los estilos al primer hermano directo de nuestros elementos.
Por ejemplo:



    .PrimerTitulo + h2 {
      background-color: blue;
    }
    <article class="ContenedorPadre">
      <h2 class="PrimerTitulo">Este es el primer elemento H2</h2>
      <!-- Este título SÍ tendrá color de fondo azul -->
      <h2>Este es el segundo elemento H2</h2>
      <div class="ElementoPadreDiferente">
          <!-- Este título NO tendrá color de fondo azul -->
        <h2>Este es el tercer elemento H2</h2>
      </div>
      <!-- Este título no tendrá color de fondo azul -->
      <h2>Este es el cuarto elemento H2</h2>
    </article>

    

