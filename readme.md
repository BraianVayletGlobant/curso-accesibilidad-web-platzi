# Notas del Curso Accesibilidad Web

# Clases:

- Clase 1: [Introduccion](#intro)
- Clase 2: [Conociendo la importancia de la accesibilidad web](#conociendo-la-importancia-de-la-accesibilidad-web)
- Clase 3: [Aprendiendo sobre WCAG y sus criteros de conformidad](#aprendiendo-sobre-wcag-y-sus-criteros-de-conformidad)
- Clase 4: [Profundizando los 12 criterios de conformidad](#profundizando-los-12-criterios-de-conformidad)
- Clase 5: [Los 4 principios de WCAG](#los-4-principios-de-wcag)
- Clase 6: [Tecnología Asistivas cuáles son y cómo funcionan](#tecnologia-asistivas-cuales-son-y-como-funcionan)
- Clase 7: [Instalación del proyecto y primeros pasos](#instalación-del-proyecto-y-primeros-pasos)
- Clase 8: [Pruebas automáticas con Lighthouse](#pruebas-automáticas-con-lighthouse)
- Clase 9: [Pruebas con simuladores de discapacidades visuales](#pruebas-con-simuladores-de-discapacidades-visuales)
- Clase 10: [Pruebas manuales con tu teclado](#pruebas-manuales-con-tu-teclado)
- Clase 11: [Pruebas manuales con lectores de pantalla](#pruebas-manuales-con-lectores-de-pantalla)
- Clase 12: [Pruebas manuales con VoiceOver](#pruebas-manuales-con-voiceover)
- Clase 13: [Usando HTML semántico en el header de nuestro sitio](#usando-html-semántico-en-el-header-de-nuestro-sitio)
- Clase 14: [¿Qué es el HTML semántico y por qué es importante?](#¿qué-es-el-html-semántico-y-por-qué-es-importante?)
- Clase 15: [Usando HTML semántico en el contenido principal de nuestro sitio](#usando-html-semántico-en-el-contenido-principal-de-nuestro-sitio)
- Clase 16: [Usando HTML semántico en footer de nuestro sitio](#usando-html-semántico-en-footer-de-nuestro-sitio)
- Clase 17: [ARIA: Accessible Rich Internet Applications](#aria:-accessible-rich-internet-applications)
- Clase 18: [ARIA roles](#ARIA-roles)
- Clase 19: [ARIA properties](#ARIA-properties)
- Clase 20: [ARIA states](#ARIA-states)
- Clase 21: [Overview del proyecto con los retos resueltos](#Overview-del-proyecto-con-los-retos-resueltos)
- Clase 22: [Contrastes de color](#Contrastes-de-color)
- Clase 23: [Iconos](#Iconos)
- Clase 24: [Skip Links](#Skip-Links)
- Clase 25: [Estilos de foco y hover](#Estilos-de-foco-y-hover)
- Clase 26: [Overview retos resueltos con CSS](#Overview-retos-resueltos-con-CSS)
- Clase 27: [Manejando el foco del teclado y botones](#Manejando-el-foco-del-teclado-y-botones)
- Clase 28: [Manejando el foco del teclado y el carousel](#Manejando-el-foco-del-teclado-y-el-carousel)
- Clase 29: [Coordinando el foco del teclado con el foco de lectores de pantallas](#Coordinando-el-foco-del-teclado-con-el-foco-de-lectores-de-pantallas)
- Clase 30: [Manejando modales](#Manejando-modales)
- Clase 31: [Mejorando la accesibilidad con teclado de nuestro modal](#Mejorando-la-accesibilidad-con-teclado-de-nuestro-modal)
- Clase 32: [Ayudando a nuestros usuarios a interactuar correctamente con el sitio](#Ayudando-a-nuestros-usuarios-a-interactuar-correctamente-con-el-sitio)
- Clase 33: [Validando formularios](#Validando-formularios)
- Clase 34: [Manejando cambios dinámicos](#Manejando-cambios-dinámicos)
- Clase 35: [Resultados](#resultados)

---

# Intro

## Asociación internacional de profesionales de accesibilidad:

Es una organización sin fines de lucro que, a través de un sistema de membresías reúne a individuos y organizaciones enfocadas en la accesibilidad o que están en el proceso de desarrollar sus habilidades y estrategias de accesibilidad.

Fundada en Estados Unidos en 2014, desde el 2019 cuenta con un capítulo en América Latina cuya misión es lograr que más profesionistas en la región trabajen en temas de accesibilidad e inclusión.

## Fluent Conference:

Son conferencias que hacen en california donde se reúnen desarrolladores y desarrolladoras web de todas las áreas posibles. La idea central de estas conferencias, además de compartir conocimiento, es la de crear comunidades (algo que nuestro estimado Óscar Barajas Tavares siempre nos ha impulsado a hacer).

> ## Links:
>
> - Asociación internacional de profesionales de accesibilidad: [https://www.accessibilityassociation.org/](https://www.accessibilityassociation.org/)
> - Fluent Conference: [https://conferences.oreilly.com/fluent/fl-ca.html](https://conferences.oreilly.com/fluent/fl-ca.html)

# Conociendo la importancia de la accesibilidad web

**Accesibilidad Web:**

Es la práctica continua de asegurarnos que todo lo que creamos para la web se puede usar, interpretar y operar por una variedad de personas en una variedad de situaciones.

![a11y](https://res.cloudinary.com/practicaldev/image/fetch/s--fTNvp0i6--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/kmxci40sgem5i02k7wbe.png)
**a11y** numerónimo de accesibilidad

**¿Por qué accesibilidad?**

- Para incluir a personas en situaciones de discapacidad.
- Para mejorar la usabilidad de nuestros proyectos.
- Porque en algunos lugares es la ley.

# Aprendiendo sobre WCAG y sus criteros de conformidad

**¿Qué es WCAG?**

En inglés son las Web Content Accessibility Guidelines o en español las Pautas de Accesibilidad para el Contenido Web. Un rango de recomendaciones para crear contenido web más accesible.

**Historia de WCAG**

- **_W3C - World Wide Web Consortium_**: Creadores de los estándares que usamos para construir la web.

- **_WAI - Web Accessibility Initiative_**: Iniciativa dentro de W3C cuya meta es asegurar la accesibilidad web.

> ## Links:
>
> - [Pautas de accesibilidad para el contenido web (WCAG) 2.0](http://www.sidar.org/traducciones/wcag20/es/)

# Profundizando los 12 criterios de conformidad

Las pautas de accesibilidad de contenido web nos guían al momento de implementar la accesibilidad web. Las podemos usar durante todo el proceso de desarrollo de producto, desde que nace la idea para lo que queremos construir, durante el diseño de los estilos y las interfaces, hasta cuando escribimos código y hacemos pruebas de calidad. Nos señalan los puntos importantes para tener en cuenta con eso podemos construir páginas, productos y aplicaciones que le funcionan a todos nuestros usuarios sin importar su capacidades, dispositivos o preferencias.

Aunque las pautas (referidas también por su nombre en inglés WCAG) son muy completas y siguen creciendo a medida que nuestras tecnologías crecen, es importante conocer los 4 principios que nos guían para poder tomar decisiones puntuales a nivel de nuestros productos. Dentro de cada principio encontramos los criterios de conformidad que se pueden interpretar acorde al nivel de WCAG que le quieres o debes aplicar a tu sitio web. Recuerda que los 3 niveles son:

- **A** - nivel basico
- **AA** - nivel intermedio
- **AAA** - nivel avanzado al cual debemos apuntar si trabajamos en servicios del gobierno, universidades o servicios esenciales de la vida cotidiana.

En esta lectura vamos a profundizar sobre los criterios de conformidad para tener una idea más clara de que podemos encontrar dentro de WCAG. Podemos empezar por el primer principio:

## **1. Perceptible**:

Los criterios de conformidad bajo este principio se enfocan en asegurar que todo el contenido que es importante se pueda interpretar de varias maneras. Aqui nos queremos

- Asegurar que estamos proporcionando alternativas textuales para todo contenido no textual.
- Proporcionar alternativas para los medios tempodependientes (como videos o audios, queremos ofrecer opciones como subtítulos o guiones).
- Crear contenido que se pueda presentar de diferentes formas sin perder información o estructura.
- Facilitar a los usuarios ver y oír el contenido, incluyendo la separación entre el primer plano y el fondo

## **2. Operable**:

Cuando hablamos de ser operable, queremos asegurarnos que nuestro sitio es fácil de usar y navegar, que se puede navegar de diferentes maneras y con mouse y/o teclado

- Proporcionar acceso a toda la funcionalidad mediante del teclado
- Darle a las usuarias suficiente tiempo para leer y usar el contenido (tener esto en cuenta cuando hacemos time outs, comunicarlos y dar opciones para pedir más tiempo si es necesario)
- Tener mucho cuidado de no usar elementos que brillan o se mueven muy rápido ya que pueden provocar ataques, espasmos o convulsiones
- Asegurarnos que nuestros usuarios pueden navegar, encontrar contenido y determinar dónde se encuentran en nuestros sitios

## **3. Comprensible**:

Hacer que nuestro sitio web sea comprensible nos asegura que un rango de personas lo pueden usar desde la persona que vive con una discapacidad mental que necesita patrones comunes para saber cómo usar la web hasta la persona que va de carrera y necesita consultar algo rápido

- Tener en cuenta los tamaños de texto y contraste de colores para que los textos resulten legibles y comprensibles
- Hacer que las páginas web aparezcan y operen de manera predecible.
- Dar instrucciones para evitar errores y oportunidades para corregirlos cuando ocurren

## **4. Robusto**:

Cuando hacemos productos que funcionan en muchos lados, abrimos las posibilidades que cualquier persona los use sin importar su ubicación, máquina, navegador y mucho más

- Maximizar la compatibilidad con las aplicaciones de usuario actuales y futuras, incluyendo las tecnologías asistivas

Así son los criterios de conformidad para la version 2.0 de WCAG. Te invito a entrar a la documentación y leer sobre que es necesario a cada nivel. ¿Hay alguno que te sorprende? ¡Cuéntame en los comentarios!

> ## Links:
>
> - [http://www.sidar.org/traducciones/wcag20/es/](http://www.sidar.org/traducciones/wcag20/es/)

# Los 4 principios de WCAG

WCAG no es perfecto. Debemos asegurarnos que conocemos los principios de WCAG.

**Perceptible**

- La información y los componentes de la interfaz de usuario deben ser presentados a los usuarios de modo que ellos puedan percibirlos

_Ejemplo → Información visual en de una Web, pero los usuarios que no puedan percibir el contenido la mejor manera sería por vía del texto (Se puede leer en voz alta)_

**Operable**

- Los componentes de la interfaz del usuario y la navegación deben ser operables

_Ejemplo → Hay personas que no tienen uso de un mouse o un teclado por cualquier razón, podemos quitar esa dependencia del uso de esas herramientas para usar el sitio de manera diferente_

**Comprensible**

- La información y el manejo de la interfaz del usuario deben ser comprensibles
- El lenguaje que estamos usando debe ser variable para diferentes tipos de personas
- Cuando hablamos de este principio hablamos de que los usuarios puedan saber como usar nuestro sitio web, cómo operarlo y que es requerido de ellos

**Robusto**

- El contenido debe ser suficientemente robusto para ser interpretado de forma fiable por una amplia variedad de aplicaciones de usuario, incluyendo las ayudas técnicas
- Nuestro producto debe facilitar al usuario en poder usarlo de diferentes maneras, por diferentes personas, en diferentes situaciones (Performance).
- Accesibilidad en diferentes navegadores
- Accesibilidad en diferentes dispositivos

> ## Links:
>
> - [Guía de accesibilidad web y color (II). Recomendaciones de las WCAG 2.1 para color y contraste](https://www.nachomadrid.com/2020/05/wcag-color-contraste/#Criterio_143_Contraste_minimo_Nivel_AA)

# Tecnología Asistivas cuáles son y cómo funcionan

Las tecnologías asistivas ayudan a las personas con alguna de sus capacidades mermadas, sean visuales, auditivas o motoras, a consumir la web de la misma forma que lo hacen los demás.

Un ejemplo muy simple y común de este tipo de tecnologías son los lentes 👓. Estos permiten que personas con defectos en la visión puedan percibir el mundo igual que los demás.

**Tecnologías asistivas:**

- Visuales:

  - Lectores de pantalla.
  - Extensiones que manipulan el CSS.

- Motoras:

  - Varilla bucal.
  - Switch.

# Instalación del proyecto y primeros pasos

Clonamos el repo del curso.

# Pruebas automáticas con Lighthouse

Hacemos pruebas en ./index.html usando la herramienta **lighthouse**

# Pruebas con simuladores de discapacidades visuales

Vamos a enforcarnos en 4 discapacidades visuales:

- **Vision borrosa**.
- **Protanopia:** es la carencia de sensibilidad al color rojo, una disfunción visual relacionada con la percepción del color. Se denomina también dicromacia roja.
- **Deuteranotopia:** Es la ausencia de los fotorreceptores retinianos del color verde.
- **Acromatopsia:** es una enfermedad congénita y no progresiva que consiste en una anomalía de la visión a consecuencia de la cual sólo son percibidos los colores blanco, negro, gris y todas sus tonalidades.

Para llevar a cabo una simulacion, utilizamos una extension de Chrome llamada **NoCofee**.

> _Nota: Las DevTools de Chrome tienen un apartado **rendering** para ayudarnos a testear esto._

En esta extension usaremos alguno atributos:

**Blur** → para disfuminar la pagina.
**Color deficiency** → encontramos las demas deficiencias.

> ## Links:
>
> - [42 Browser Extensions to Perform Accessibility Testing Effectively](https://www.digitala11y.com/accessibility-plug-ins-ie-chrome-firefox-browsers/)

# Pruebas manuales con tu teclado

El teclado es muy importante en la accesibilidad web porque las tecnologías asistivas tienden a conectarse con el teclado para darle a sus usuarios diferentes maneras de navegar cuando no tienen acceso a un mouse o un teclado como nosotros.

Los elementos que reciben foco de teclado son elementos interacctivos:

- **Enlaces:** nos llevan a otra página, son para la navegación.
- **Botones:** nos ayudan a interactuar con la página de alguna manera.
- **Formularios:** requieren nuestra interacción para llenar nuestros datos.

Los **div no reciben foco porque son un elemento presentacional**, no esperan ninguna interacción a menos de que tú lo programes.

> Tips:
>
> - Para cambiar entre pestañas de Izquierda a Derecha es: **Ctrl + tab**
> - Para ir de Derecha a Izquierda es: **Ctrl + shift + tab**

# Pruebas manuales con lectores de pantalla

Los lectores de pantalla han abierto a la web a diversas personas que antes no podían usar los sitios web. Son Software que mapea las páginas que usamos y las lee en voz alta. Usadas normalmente por personas que tienen incapacidades visuales.

### Combinaciones de lectores de pantalla y navegadores

Es importante tener en cuenta cuales lectores podemos usar de manera compatible con los diferentes navegadores web

- NVDA → Mozilla Firefox
- JAWS → Microsoft Internet Explorer (EDGE)
- VoiceOver → Sfari
- ChromeVox → Google Chrome

Apartado de Chorme DevTools → En Elements → Accessibility → Accessibility Tree

> ## Links:
>
> - [ANDI - Accessibility Testing Tool](https://www.ssa.gov/accessibility/andi/help/install.html)

# Pruebas manuales con VoiceOver

Se hacen pruebas con VoiceOver, en mac.

### Comando para ChromeVox para Google Chrome:

- ChromeVox modifier key = Search
- Turn on braille captions = Search + A, B
- Show ChromeVox Menus = Search + Period
- Next heading = Search + H
- Previous heading = Search + Shift + H
- Enter Learn Mode = Search + O, K
- Next group = Search + Ctrl + Down
- Next object = Search + Right
- Next line = Search + Down
- Next word = Search + Shift + Ctrl + Right
- Next character = Search + Shift + Right

# Usando HTML semántico en el header de nuestro sitio

Un resumen de las etiquetas usadas en esta clase:

```html
<!-- Parte superior de nuestra pagina Lo primero que ve el usuario en cuanto a orden. -->
<header></header>
<!-- Etiqueta para poner imágenes, tiene el atributo alt="El lector de pantalla lee lo que esta aqui" -->
<img />
<!-- Para colocar un menú de navegación -->
<nav></nav>
<!-- Para poner una lista que no tiene un orden especifico. -->
<ul></ul>
<!-- Elemento de lista -->
<li></li>
```

# ¿Qué es el HTML semántico y por qué es importante?

El HTML semántico es un concepto para estructurar y escribir código HTML, de manera que el significado del contenido de una página web sea más claro a través de sus etiquetas.

## Cómo funciona el HTML semántico

Las etiquetas semánticas pueden utilizarse en lugar de las etiquetas de presentación estándar y esto ayuda a mejorar la legibilidad y la usabilidad, al tiempo que reduce la necesidad de datos estructurados. Esta nueva forma de concebir la programación permite crear sitios web más accesibles y más significativos para los motores de búsqueda. El marcado semántico también es beneficioso porque permite hacer hojas de estilo CSS separadas para cada sección de su sitio web.

## Ejemplos de HTML semántico

En el siguiente ejemplo, vamos a ver cómo se muestra un código HTML no semántico Vs. uno semántico. A los ojos del usuario, la información presentada en el navegador va a ser la misma, pero para legibilidad del código y SEO, la diferencia es muy marcada:

### Código sin HTML semántico

```html
<div></div>
<div><div></div></div>
<div></div>
```

### Código con HTML semántico

```html
<header></header>
<article><img /></article>
<footer></footer>
```

## ¿Cuál es la diferencia entre el HTML semántico dinámico y estático?

Una de las partes más importantes del desarrollo web son los atributos semánticos del HTML. La semántica estática es el significado de una palabra o frase que se mantiene constante independientemente del contexto, mientras que la semántica dinámica cambia en función de su uso.

### Semántica estática

La semántica estática se utiliza para definir diferentes tipos de etiquetas en HTML. No dependen de ningún otro dato contextual, sino que permanecen constantes independientemente de su uso. Por ejemplo:

Al definir una etiqueta de párrafo, el navegador sabe que es un párrafo, independientemente de si se utiliza para poesía o prosa.

### Semántica dinámica

Se utiliza para definir dinámicamente el contenido de un elemento. El significado cambia en función del texto que hay dentro y de las palabras que lo rodean. Por ejemplo, si tiene un elemento que define la ubicación de una empresa como Bogotá, el HTML mostrará “Bogotá” cuando el cursor pase por encima de ese elemento concreto en una página web o cuando se vea ese elemento en Google Maps.

> ## Links:
>
> - [Mapa para definir el texto alternativo correcto para una imagen](https://www.usableyaccesible.com/textosalternativosaccesibles/mapa_decision_texto_alternativo.php)
> - [HTML5 | SEMÁNTICA](https://www.arkaitzgarro.com/html5/capitulo-2.html)
> - [Computer says NO to HTML5 document outline](http://html5doctor.com/)

# Usando HTML semántico en el contenido principal de nuestro sitio

Hacemos actualizaciones al codigo...

# Usando HTML semántico en footer de nuestro sitio

Hacemos actualizaciones al codigo...

# ARIA: Accessible Rich Internet Applications

**ARIA ( Accessible Rich Internet Applications ):** define cómo realizar contenido Web y aplicaciones Web (especialmente las desarrolladas con Ajax y JavaScript) más accesibles a personas con discapacidades. Por ejemplo, ARIA posibilita puntos de navegación accesibles, widgets JavaScript, sugerencias en formularios y mensajes de error, actualizaciones en directo, y más.

**Atributos de ARIA:**

- Roles
- Propiedades
- Estados

> ## Links:
>
> - [Introducción a ARIA - Google Developers](https://developers.google.com/web/fundamentals/accessibility/semantics-aria?hl=es-419)
> - [Primeros pasos con ARIA - Mozilla Developers](https://developer.mozilla.org/es/docs/Web/Accessibility/ARIA)

# ARIA roles

- Definen el tipo general del objeto (como un artículo, una alerta o deslizador)
- Los roles comunican al navegador cuales son las interacciones que debería esperar y como se va usar este objeto dentro de la página o aplicación
- Se usan en ocasiones especiales es mejor usar HTML semántico para no meterse en agregar roles a todos los elementos
- Es una especificación difícil de usar y se debe saber muy bien cómo usar
- Especifican de cómo se navega en esa sección
- Los navegadores, en especial los lectores de pantalla navegan diferentes roles en diferentes estilos
- **Ejemplo** ⇒
  - _Articulo ⇒ Poca Interacción_
  - _Formulario ⇒ Mucha Interacción_

**RESUMEN:** Los ARIA roles preparan al navegador o lectores de pantalla a indicar cuales son las interacciones que debería esperar, se usan en ocasiones especiales, en la mayoría de los casos se recomienda usar HTML semántico

![PeriodicTableARIA1.0Roles](https://64.media.tumblr.com/68423fdd6093a6f281b91b28eff9097f/tumblr_inline_noery1zJyq1rbrg1w_1280.png)

# ARIA properties

Se suele usar mas seguido que los roles.

### Qué son

Comunican atributos que son esenciales para el comportamiento o significado de un elemento pero que se suelen comunicar visualmente

- Agregar significado a nuestro contenido visual

### ARIA label

- Podemos usar para agregar un string para describir un elemento de nuestro código
- ARIA _Ejemplo_:

```html
<form class="form-container">
  Nombre<input type="text" aria-label="nombre" /> <br />
  Correo<input type="text" aria-label="correo" /> <br />
  <div class="message-input">Mensaje<input type="text" /> <br /></div>
  <button class="send-button">Enviar</button>
</form>
```

# ARIA states

### Ideas/conceptos claves

Estados de ARIA comunican estados y cambios de estados en elementos que se suelen comunicar visualmente

### Apuntes

- Existen veces que mostramos casos que solo pasan cuando algo cambia en la pantalla
  - Impidiendo que personas con discapacidades visuales no podrán notar ese cambio
  - Debemos dar una experiencia del sitio a personas discapacitadas al igual que damos importancia a personas sin ningún problema
- Si tenemos un checkbox
  - Sabemos que esta seleccionado por que está marcado
  - Alguien con discapacidad quizás no pueda ver eso
- Un lector de pantalla no se dará cuenta que algunas cosas no se están mostrando
- Podemos usar el atributo aria-hidden para ocultar algunas cosas de los lectores de pantalla

```html
<li aria-hidden="true">...</li>
```

**RESUMEN:** Podemos brindar una experiencia similar a usuarios con discapacidades al igual que usuarios que tienen todos los beneficios físicos, usando estados los cuales comunicarán que cosas se estarán mostrando en pantalla

# Overview del proyecto con los retos resueltos

Refactorizamos el codigo...

# Contrastes de color

### Ideas/conceptos claves

El contraste de color es la diferencia existente entre dos o más colores que interactúan en un diseño de forma que afectan al modo en el cual se percibe. El color según sus diferentes características influye en el efecto que causa en las personas

### Apuntes

- Los contrastes de color se refieren a la diferencia del color de fondo y color del texto
- Normalmente es tarea del diseñador encargarse de este aspecto, pero como desarrolladores podemos encargarnos de detectar problemas de contraste para posteriormente comunicar el problema
- Si el contraste es muy bajo no se puede ver el texto correctamente
- Podemos usar Chrome Dev Tools para revisar el contraste de los colores de los textos
  - Nos indicaran a que nivel de WCAG estaremos llegando

**RESUMEN:** El contraste de color es importante para llegar a más personas, se trata de la diferencia del color de fondo y del color del texto. Podemos usar las Chrome Dev Tools para verificar este aspecto

# Iconos

### Apuntes

- Pensamos que los iconos son universales, pero pueden ser confusos si nunca los has visto o dependiendo de la aplicación que estas usando
- Para comunicar de una manera más eficiente se podría agregar un texto especificando el icono

**RESUMEN**: Los iconos pueden a llegar a ser confusos en algunos casos con personas con discapacidades para solucionar esta problemática es importante especificar un texto

# Skip Links

### Apuntes

- A veces tenemos una navegación inicial bastante extensa
- Para una persona con discapacidades que use un dispositivo que le facilite acceder al sitio, tendrá que pasar por todo el contenido inicial
- Podemos usar skip links facilitar la navegación ofreciendo un botón que le permita saltar al contenido principal
- Skip links son enlaces que nos dirigen a partes específicas dentro del HTML
- Son botones que a simple vista no se ven pero al momento que un software de lectura de texto los detecta aparecene, se crean poniendo un botón común y corriente:

```html
<button id="skip-link">Saltar al contenido</button>
```

Y en css le pondremos lo siguiente

```css
.skip-link{
  weight: 0; /* desaparecemos el botón a simple vista*/
}
.skip-link:focus,
.skip-link:active{
  background..
  font ...
} /* de esta forma cuando navegen con un teclado este aparecerá*/
```

### Recomendación:

Utilizar la etiqueta main

```html
<main id="tu_id">
  <!-- Tu contenido -->
</main>
```

Es lo más recomendable, gracias a ello tenemos por defecto este comportamiento habilitado.
Antes de ello, aprendan bien a posicionar la etiqueta main, semánticamente tiene un orden que hay que cumplir.

Si te preocupa la compatibilidad de Main: Incluso es aceptado por Internet Explorer 11 con la propiedad: width: tuvalor, pero para 2020 la el uso de este browser es del 2%, así que: Ni se preocupen ya por darle soporte, está “prácticamente muerto IE 11”

# Estilos de foco y hover

Refactorizamos el codigo...

# Overview retos resueltos con CSS

Refactorizamos el codigo...

# Manejando el foco del teclado y botones

Refactorizamos el codigo...

# Manejando el foco del teclado y el carousel

**Tabindex**: Indica si su elemento puede ser enfocado, y si participa en la navegación secuencial del teclado.

Valores de Tabindex:

- Valor negativo(-1): El elemento debe ser enfocado, pero no debe de ser accesible a través de la navegación.
- Valor positivo (>0): Debe poder ser enfocado y su orden relativo es definido por el valor del atributo.
- Valor de 0: Debe ser enfocado y ser accesible a través de la navegación secuencial del teclado, pero su orden relativo es definido por convención de la plataforma.

> ## Links:
>
> - [TabIndex - Google Developers](https://developers.google.com/web/fundamentals/accessibility/focus/using-tabindex?hl=es)

# Coordinando el foco del teclado con el foco de lectores de pantallas

### Ideas/conceptos claves

Tab index ⇒ indica si su elemento puede ser enfocado y si participa en la navegación secuencial del teclado

### Recursos

Uso de tabindex | Web | Google Developers

### Apuntes

#### Botones

- Hoy en día se necesita usar JS para las interacciones de usuario
- Puedes usar JS para manejar estas interacciones
- La etiqueta Button se debe usar siempre y cuando habrá una interacción

#### Carousel

- Valores de tab index
  - Valor negativo (-1) ⇒ El elemento debe ser enfocado, pero no debe de ser accesible a través de la navegación
  - Valor positivo (>0) ⇒ debe poder ser enfocado y su orden relativo es definido por el valor del atributo
  - Valor de 0 ⇒ El elemento debe ser enfocado y ser accesible a través de la navegación secuencial del teclado, pero su orden relativo es definido por convención de la plataforma
- Valores de aria hidden para los elementos que están ocultos

**RESUMEN:** Se puede dar a los websites con interacciones más accesibilidad manipulando los atributos conocidos anteriormente para mejorar la accesibilidad mediante el JS

# Manejando modales

Un modal siempre debería tener tres salidas:

- **Botón** de cerrar
- **Click** fuera del modal
- Tecla **ESC** del teclado.

Refactorizamos el codigo...

# Mejorando la accesibilidad con teclado de nuestro modal

Refactorizando el codigo...

> ## Links:
>
> - [keycode](https://keycode.info/)

# Ayudando a nuestros usuarios a interactuar correctamente con el sitio

**_”El poder de la Web está en su universalidad. El acceso de todas las personas independientemente de la discapacidad es un aspecto esencial.”_**

### Apuntes

- La 3° Ley de WCAG ⇒ “Ser comprensible”
- Debemos esforzarnos, para que todas las acciones sean fáciles de entender
- Nuestras acciones deben ser predecibles es decir que estemos usando patrones que se usan en otras aplicaciones, otros contextos para unas mismas acciones

# Validando formularios

Refactorizamos el codigo...

# Manejando cambios dinámicos

Cuando surgen cambios de forma dinámica, por ejemplo: un mensaje de error por un input faltante en un formulario, o un mensaje de confirmación. Debemos ser capaces de transmitir esa información a usuarios que utilicen lectores de pantallas.

El atributo **aria-live** añade a un elemento para indicar que es una “región viva”, es decir, que su contenido se modifica y actualiza dinámicamente. En nuestro caso es la zona de “Últimas noticias”, que se actualiza cada 10 segundo automáticamente, sin intervención del usuario.

- **Off**: Es el estado predeterminado.
- **Polite**: Espera a que el lector de pantalla termine de leer el elemento actual. Se utiliza cuando el mensaje que se quiere comunicar, no es importante
- **Assertive**: Interrumpe la lectura para dar el mensaje. Se utiliza cuando se quiere dar prioridad al mensaje, por ejemplo, en el mensaje de confirmación del envío de un formulario

**Aria-live** no es el único atributo que se puede utilizar en estos casos.

> ## Links:
>
> - [Más información](https://www.usableyaccesible.com/ejemplo_aria_live/ejemplo_liveregions.html)

# Resultados

Sin considerar la Accesibilidad.

![inicio](https://raw.githubusercontent.com/BraianVayletGlobant/curso-accesibilidad-web-platzi/main/images/accessibility-index.jpg)

Haciendo foco en la mejora de la Accesibilidad.

![final](https://raw.githubusercontent.com/BraianVayletGlobant/curso-accesibilidad-web-platzi/main/images/accessibility-final.jpg)
