# Notas del Curso Accesibilidad Web

## Clases:

- Clase 1: [Introduccion](#intro)
- Clase 2: [Conociendo la importancia de la accesibilidad web](#conociendo-la-importancia-de-la-accesibilidad-web)
- Clase 3: [Aprendiendo sobre WCAG y sus criteros de conformidad](#aprendiendo-sobre-wcag-y-sus-criteros-de-conformidad)
- Clase 4: [Profundizando los 12 criterios de conformidad](#profundizando-los-12-criterios-de-conformidad)
- Clase 5: [Los 4 principios de WCAG](#los-4-principios-de-wcag)
- Clase 6: [Tecnología Asistivas cuáles son y cómo funcionan](#tecnologia-asistivas-cuales-son-y-como-funcionan)

---

## Intro

### Asociación internacional de profesionales de accesibilidad:

Es una organización sin fines de lucro que, a través de un sistema de membresías reúne a individuos y organizaciones enfocadas en la accesibilidad o que están en el proceso de desarrollar sus habilidades y estrategias de accesibilidad.

Fundada en Estados Unidos en 2014, desde el 2019 cuenta con un capítulo en América Latina cuya misión es lograr que más profesionistas en la región trabajen en temas de accesibilidad e inclusión.

### Fluent Conference:

Son conferencias que hacen en california donde se reúnen desarrolladores y desarrolladoras web de todas las áreas posibles. La idea central de estas conferencias, además de compartir conocimiento, es la de crear comunidades (algo que nuestro estimado Óscar Barajas Tavares siempre nos ha impulsado a hacer).

> ### Links:
>
> - Asociación internacional de profesionales de accesibilidad: [https://www.accessibilityassociation.org/](https://www.accessibilityassociation.org/)
> - Fluent Conference: [https://conferences.oreilly.com/fluent/fl-ca.html](https://conferences.oreilly.com/fluent/fl-ca.html)

## Conociendo la importancia de la accesibilidad web

**Accesibilidad Web:**

Es la práctica continua de asegurarnos que todo lo que creamos para la web se puede usar, interpretar y operar por una variedad de personas en una variedad de situaciones.

![a11y](https://res.cloudinary.com/practicaldev/image/fetch/s--fTNvp0i6--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/kmxci40sgem5i02k7wbe.png)
**a11y** numerónimo de accesibilidad

**¿Por qué accesibilidad?**

- Para incluir a personas en situaciones de discapacidad.
- Para mejorar la usabilidad de nuestros proyectos.
- Porque en algunos lugares es la ley.

## Aprendiendo sobre WCAG y sus criteros de conformidad

**¿Qué es WCAG?**

En inglés son las Web Content Accessibility Guidelines o en español las Pautas de Accesibilidad para el Contenido Web. Un rango de recomendaciones para crear contenido web más accesible.

**Historia de WCAG**

- **_W3C - World Wide Web Consortium_**: Creadores de los estándares que usamos para construir la web.

- **_WAI - Web Accessibility Initiative_**: Iniciativa dentro de W3C cuya meta es asegurar la accesibilidad web.

> ### Links:
>
> - [Pautas de accesibilidad para el contenido web (WCAG) 2.0](http://www.sidar.org/traducciones/wcag20/es/)

## Profundizando los 12 criterios de conformidad

Las pautas de accesibilidad de contenido web nos guían al momento de implementar la accesibilidad web. Las podemos usar durante todo el proceso de desarrollo de producto, desde que nace la idea para lo que queremos construir, durante el diseño de los estilos y las interfaces, hasta cuando escribimos código y hacemos pruebas de calidad. Nos señalan los puntos importantes para tener en cuenta con eso podemos construir páginas, productos y aplicaciones que le funcionan a todos nuestros usuarios sin importar su capacidades, dispositivos o preferencias.

Aunque las pautas (referidas también por su nombre en inglés WCAG) son muy completas y siguen creciendo a medida que nuestras tecnologías crecen, es importante conocer los 4 principios que nos guían para poder tomar decisiones puntuales a nivel de nuestros productos. Dentro de cada principio encontramos los criterios de conformidad que se pueden interpretar acorde al nivel de WCAG que le quieres o debes aplicar a tu sitio web. Recuerda que los 3 niveles son:

- **A** - nivel basico
- **AA** - nivel intermedio
- **AAA** - nivel avanzado al cual debemos apuntar si trabajamos en servicios del gobierno, universidades o servicios esenciales de la vida cotidiana.

En esta lectura vamos a profundizar sobre los criterios de conformidad para tener una idea más clara de que podemos encontrar dentro de WCAG. Podemos empezar por el primer principio:

### **1. Perceptible**:

Los criterios de conformidad bajo este principio se enfocan en asegurar que todo el contenido que es importante se pueda interpretar de varias maneras. Aqui nos queremos

- Asegurar que estamos proporcionando alternativas textuales para todo contenido no textual.
- Proporcionar alternativas para los medios tempodependientes (como videos o audios, queremos ofrecer opciones como subtítulos o guiones).
- Crear contenido que se pueda presentar de diferentes formas sin perder información o estructura.
- Facilitar a los usuarios ver y oír el contenido, incluyendo la separación entre el primer plano y el fondo

### **2. Operable**:

Cuando hablamos de ser operable, queremos asegurarnos que nuestro sitio es fácil de usar y navegar, que se puede navegar de diferentes maneras y con mouse y/o teclado

- Proporcionar acceso a toda la funcionalidad mediante del teclado
- Darle a las usuarias suficiente tiempo para leer y usar el contenido (tener esto en cuenta cuando hacemos time outs, comunicarlos y dar opciones para pedir más tiempo si es necesario)
- Tener mucho cuidado de no usar elementos que brillan o se mueven muy rápido ya que pueden provocar ataques, espasmos o convulsiones
- Asegurarnos que nuestros usuarios pueden navegar, encontrar contenido y determinar dónde se encuentran en nuestros sitios

### **3. Comprensible**:

Hacer que nuestro sitio web sea comprensible nos asegura que un rango de personas lo pueden usar desde la persona que vive con una discapacidad mental que necesita patrones comunes para saber cómo usar la web hasta la persona que va de carrera y necesita consultar algo rápido

- Tener en cuenta los tamaños de texto y contraste de colores para que los textos resulten legibles y comprensibles
- Hacer que las páginas web aparezcan y operen de manera predecible.
- Dar instrucciones para evitar errores y oportunidades para corregirlos cuando ocurren

### **4. Robusto**:

Cuando hacemos productos que funcionan en muchos lados, abrimos las posibilidades que cualquier persona los use sin importar su ubicación, máquina, navegador y mucho más

- Maximizar la compatibilidad con las aplicaciones de usuario actuales y futuras, incluyendo las tecnologías asistivas

Así son los criterios de conformidad para la version 2.0 de WCAG. Te invito a entrar a la documentación y leer sobre que es necesario a cada nivel. ¿Hay alguno que te sorprende? ¡Cuéntame en los comentarios!

> ### Links:
>
> - [http://www.sidar.org/traducciones/wcag20/es/](http://www.sidar.org/traducciones/wcag20/es/)

## Los 4 principios de WCAG

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

> ### Links:
>
> - [Guía de accesibilidad web y color (II). Recomendaciones de las WCAG 2.1 para color y contraste](https://www.nachomadrid.com/2020/05/wcag-color-contraste/#Criterio_143_Contraste_minimo_Nivel_AA)

## Tecnología Asistivas cuáles son y cómo funcionan

Las tecnologías asistivas ayudan a las personas con alguna de sus capacidades mermadas, sean visuales, auditivas o motoras, a consumir la web de la misma forma que lo hacen los demás.

Un ejemplo muy simple y común de este tipo de tecnologías son los lentes 👓. Estos permiten que personas con defectos en la visión puedan percibir el mundo igual que los demás.

**Tecnologías asistivas:**

- Visuales:

  - Lectores de pantalla.
  - Extensiones que manipulan el CSS.

- Motoras:

  - Varilla bucal.
  - Switch.
