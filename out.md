images [**here**](https://drive.google.com/file/d/1e35_3z3mzMrMLWKYuKPk6-x6rPtT_kQu/view?usp=drive_link)

Guia para aprender ReactJS desde cero
Carlos Azaustre

A la venta en http://leanpub.com/cazaustre-react
Esta versión se publicé en 08/09/2023

Este es un libro de Leanpub. Leanpub anima a los autores y publicadoras con el proceso de publicación. Lean Publishing es el acto de publicar un libro en progreso usando herramientas sencillas y muchas iteraciones para obtener retroalimentación del lector hasta conseguir el libro adecuado.

© 2023 Carlos Azaustre por la obra y la edición.

A mi hija, Aroa.
Para que sea lo que ella quiera ser.

TOC

Sobre el autor
Prefacio

Capitulo 1: Introducción a React
Introducción
¿Qué es React?
Historia de React
Por qué usar React?
Conclusión
Referencias

Capitulo 2: Fundamentos de React
Configuración del entorno de dev
SX: Sintaxis de JS y XML
Creación de un proyecto de React
Componentes: Clases vs Funciones
Props y Estado en los componentes
Manejo de eventos
Profundizando en Props y Eventos: Props Drilling y Event Bubbling
Conclusión
Referencias

Capitulo 3: Ciclo de vida de los componentes
El Virtual DOM
Métodos del Ciclo de Vida
React Hooks
Conclusión
Referencias

Capitulo 4: Gestión de estados globales
Introducción
Context API
Redux: Introducción y principios basicos
Integracion de Redux en un proyecto de React
Comparación de soluciones de manejo de estado
Conclusión
Referencias

Capitulo 5: React Router y Navegacion
Introducción
Instalación y configuración
Creación de rutas y enrutado dinamico
Novedades en React Router v6
Alternativas a React Router
Conclusión
Referencias

Capitulo 6: Estilos y diseño
Introducción
Formas de usar CSS en React
CSS Modules
CSS en JS: Styled-components y otras soluciones
Grid y Flexbox en React Conclusión
Diseño responsive y adaptativo
Integración de bibliotecas de componentes UI 
Material UI
Referencias

Capitulo 7: Consumo de APIs y comunicación con el Servidor 
Fetch y Axios: Realizar peticiones HTTP Referencias
React Query (TanStack Query)
Manejo de errores y estado de carga 
Autenticación y autorizacion 
Conclusión 
Referencias

Capitulo 8: Optimización y Rendimiento 
Introducción.
Paginación de listas 
Memoización de componentes
Code Splitting y Lazy Loading
Uso eficiente de Context y Redux en React
Conclusión

Capitulo 9: Pruebas y calidad del codigo
Material UI Introducción al Testing
Conclusión lest y Vitest: Pruebas unitarias y de integración
Referencias React Testing Library: Pruebas de componentes
ESlint y Prettier
Análisis de cobertura de pruebas
Introducción Cypress y Playwright: Pruebas de extremo a extremo
Referencias

Capitulo 10: Despliegue y Entornos de Producción
Introducción
Creación de un entorno de producción optimizado
Referencias Despliegue en plataformas populares (Netlify, Vercel, Firebase...
SEO y rendimiento en aplicaciones de React
Referencias

Epilogo

Sobre el autor

Carlos Azaustre nacié en Madrid, Espafia, en 1984. Es Ingeniero en Telematica por
la Universidad Carlos III de Madrid, con una década de experiencia alternando la
Ingenieria de sw y como Developer Relations en empresas como Google, IBM
Research y Eventbrite.

Actualmente, Carlos comparte su experiencia en el campo del dev de sw como Profesor Asociado en la Universidad Europea de Madrid, impartiendo clases en el Master de dev Web. Siempre comprometido con la educación y la divulgación tecnoldégica, tambión dirige un popular canal de YouTube (https://youtube.com/@carlosazaustre) donde ha cultivado
una comunidad de mas de 125,000 suscriptores. En su canal, aborda temas relacionados con la programación y el dev web con JS, proporcionando información valiosa y consejos practicos a su audiencia.

Carlos es autor del libro Aprendiendo JS, un recurso esencial para cualquiera que desee incursionar en la programación con este lenguaje. Con mas de 2000 ejemplares vendidos en Amazon, este libro ha sido varias veces el mas vendido en las categorias de dev de sw.

El trabajo de Carlos ha sido reconocido por empresas lideres en tecnologia: Google lo ha designado como GDE (Google Developer Expert) en Tecnologias Web desde 2019 y Microsoft lo ha premiado con el titulo de MVP (Most Valuable Professional) en Tecnologias de dev en 2022 y 2023.

Ahora, con el lanzamiento de su nuevo libro Aprendiendo React, Carlos busca compartir su conocimiento de esta popular biblioteca JS con un ptblico atin mds amplio, ayudando a los desarrolladores a aprovechar al maximo las funcionalidades de React en sus propios proyectos.

Prefacio

En el mundo del dev web de hoy, es importante mantenerse al tanto de las tendencias y tecnologias emergentes. Aqui entra React,js, una biblioteca JS creada por FB, que ha capturado la atención de la comunidad de desarrolladores en todo el mundo. Su naturaleza flexible y robusta la hace preferible para el dev de interfaces de usuario en aplicaciones web y de alto rendimiento.

A medida que avanza el tiempo, la popularidad de React ha crecido exponencialmente, y hasta 2023 ha demostrado ser una herramienta invaluable en el conjunto de herramientas de cualquier desarrollador. Con su creciente ecosistema de soluciones y proyectos de terceros, React ha seguido siendo una opción relevante y potente para desarrolladores frontend.

Este libro esta destinado a programadores que ya estan familiarizados con JS y estan interesados en dar sus primeros pasos con React. El propésito es proporcionarte una guia sdlida y detallada que te ayude a comprender y dominar los conceptos clave de React. No sdlo aprenderas los fundamentos basicos, sino tambión las técnicas avanzadas y las mejores practicas que te permitiran escribir aplicaciones de React eficientes y de alto rendimiento.

Empezaremos con una introducción a React, explorando su historia, sus fortalezas y por qué tiene la atención de la comunidad de dev web. A continuación, nos sumergiremos en los fundamentos de React, incluyendo la configuración del entorno de dev, la sintaxis JSX, y cémo crear y estructurar un  proyecto. Tambión aprenderas sobre los componentes, el manejo de eventos, y las complejidades del ciclo de vida de los componentes y como React las maneja.

A medida que avanzamos, exploraremos temas mas complejos como la gestión del estado global utilizando la API Context y Redux, enrutamiento con React Router, y como aplicar estilos y disefio en tus proyectos de React. En las etapas posteriores del libro, cubriremos cémo consumir APIs y comunicarse con un servidor, como optimizar el rendimiento de tu app de React, y cémo probar y mantener la calidad de tu cédigo.

Por ultimo, te guiaré a través de los pasos para desplegar tus aplicaciones de React en un entorno de producción, y te proporcionaré consejos sobre SEO y rendimiento para asegurar que tus aplicaciones no sdlo funcionen bien, sino que tambión sean encontrables por los buscadores y accesibles.

Al final de este libro, no sdlo tendras un conocimiento sdlido de React, sino que tambión habrds adquirido habilidades y conocimientos que te haran un mejor desarrollador.

Bienvenido a tu viaje para aprender y dominar React.js, Espero que este libro te ayude a alcanzar tus objetivos como desarrollador frontend.

A darle al código !

*Carlos Azaustre*

Capitulo 1: Introduccion a React

Introduccion

Biblioteca o libreria? técnicamente React es biblioteca; a menudo 'framework' por popularidad y cantidad de herramientas que lo rodean.

React -libreria- utiliza el LP JS. Desarrollado por Meta (antes FB) ha revolucionado la forma en que se construyen las apps web.

Desde lanzamiento en 2013, React ha ganado una inmensa popularidad debido a 

¿Qué es React?

Como se comenta en la introdución, React es una biblioteca de JS para construir interfaces de usuario. A diferencia de frameworks completos como por ejemplo Angular, React se centra en una sola cosa: la capa de vista. Esto significa que React se ocupa principalmente de lo que el usuario ve y cémo interacttia con su app.

React introduce el concepto de componentes. Un componente en React es una pieza independiente de código que controla una parte de la interfaz de usuario. Estos componentes son reutilizables y pueden combinarse para formar aplicaciones completas.

Historia de React

React fue creado por Jordan Walke, ingeniero de sw en FB, en 2011. Walke se inspiró en XHP, una biblioteca de PHP para la creación de componentes HTML, y queria llevar un enfoque similar a JS. El resultado fue una biblioteca que permitia a los desarrolladores construir interfaces de usuario dinamicas y eficientes con JS.

El primer producto de FB que utilizé React fue el feed de noticias -2011-. El éxito de React en el “muro” llevó a FB a utilizarlo en mas productos, incluyendo Instagram, que FB adquiere en 2012.

FB decidié liberar React como proyecto de código abierto en mayo de 2013 durante la conferencia JSConf US. La decisión de hacer de React un proyecto open source fue motivada: Primero, FB queria compartir su enfoque innovador para la construcción de UIs con la comunidad de desarrolladores. Segundo, FB esperaba que al hacer de React un proyecto de código abierto, otros desarrolladores contribuirian a su dev y ayudarian a mejorar la biblioteca.

A pesar de su popularidad, React no estuvo exento de controversia. En 2017, FB se encontró en medio de un problema sobre su licencia. La original, 'BSD + Patent', fue criticada -daba a FB el derecho de revocarla si una empresa demandaba a FB por infracción de patentes-.

Esta cláusula provocṕ preocupación en la comunidad de dev, y algunas empresas, incluyendo WordPress, decidieron alejarse de React. En respuesta a la reacción de la comunidad, FB decidió cambiar la licencia de React a 'MIT' en septiembre de 2017. Esta es de código abierto y muy popular; no tiene la clausula de patentes que originçó todo el debate.

Hoy React es una de las bibliotecas de JS mas populares para construcción de UIs. Es utilizado por muchas empresas grandes y pequefias (Netflix, Airbnb, Uber, NYT y la propia Meta) y tiene comunidad muy activa. React ha seguido evolucionado desde su lanzamiento en 2013, con nuevas caracteristicas y mejoras introducidas de forma regular.

La Hª de React es un testimonio del poder de la innovación y la colaboración en la comunidad de dev de sw. A través de su enfoque en la eficiencia, la reutilización de componentes y la facilidad de uso, React ha cambiado la forma en que construimos y pensamos interfaces de usuario.

¿Por qué usar React?

React tiene varias ventajas que lo hacen atractivo para los desarrolladores. Algunas:

- **Componentes reutilizables**: React se basa en componentes y son reutilizables: puedes escribir un componente una vez y reusarlo en diferentes partes de tu app. Esto ahorra tiempo y aumenta el orden.

- **Virtual DOM**: React introduce este concepto: una representación ligera del DOM (Document Object Model) real. Cuando el estado de un componente cambia, React primero actualiza el Virtual DOM y luego compara la versión actualizada con la anterior. Luego, solo actualiza las
partes del DOM real que necesiten cambiar. Es este proceso (“reconciliación”) lo que hace que React sea tan rapido.

- **Unidireccionalidad de los datos**: React sigue un flujo de datos unidireccional: en una app React los datos fluyen desde componentes padres a componentes hijos. ,, seguimiento de
cambios en el estado de la app mas facil. código mas predecible y facil de entender.

- **Ecosistema y comunidad**: React tiene un ecosistema robusto y una comunidad activa. Hay una gran cantidad de bibliotecas de terceros disponibles que puedes usar para agregar funcionalidad a tus aplicaciones React. Ademas, si te encuentras con un problema, es probable que alguien mas ya haya encontrado una solución.

Conclusión

React es una gran herramienta para construir UIs. Su enfoque en: *componentes reutilizables*, el *Virtual DOM* y el *flujo de datos unidireccional* lo hacen muy atractivo para nosotros como desarrolladores.

profundizaremos en estos conceptos y aprenderemos a construir tus propias apps con React.

Referencias

+ Azaustre, C. (2021) Aprendiendo JS. Independently Published.

«Banks, A., y Porcello, E. (2020). Learning React: Modern Patterns for Developing
React Apps. O'Reilly Media.

+ Axel, R. (2018). JS: The Definitive Guide. O'Reilly Media.

+ FB Inc. (2013). React - A JS library for building user interfaces.
GitHub. https://github.com/FB/react

«Walke, J. (29 de mayo de 2013). React: Rethinking best practices.
JsConf. https://2013.jsconf.eu/speakers/ pete-hunt-react-rethinking-best-
practices.html

+Mardan, A. (2019). React.js For Beginners. RWieruch. _https://
www.robinwieruch.de/react-hooks

+ Mozilla Developer Network. (2023). JS Guide. MDN Web Docs. https://
developer.mozilla.org/en-US/docs/Web/JS/Guide

Capitulo 2: Fundamentos de React
Configuración del entorno de dev

Este libro, aunque expliquemos la teoria, es bastante practico, por tanto tener

preparado el entorno de trabajo necesario es esencial.

Antes de comenzar a desarrollar aplicaciones con React, necesitaremos configurar
nuestro entorno de dev. Esto implica instalar algunas herramientas y
configurar algunas configuraciones en nuestro sistema. Aunque puede parecer un
proceso complicado al principio, una vez que lo hayas hecho una vez, te resultara
mis facil en el futuro.

Conocimientos Previos

Aunque este libro no pretende que sepas y conozcas React, ya que el propésito
del mismo es que lo aprendas después de leerlo, si que se necesita tener unos
conocimientos basicos previos.

React es una herramienta potente y flexible, pero tambión puede ser compleja si no
se tiene una base sdlida en ciertos conceptos y tecnologias.

+ JS: React utiliza JS, por lo que un conocimiento sdlido de JS
es esencial. Deberias estar comodo con los conceptos de JS moderno,
como las funciones flecha (Arrow functions), las promesas, la desestructuración
de objetos y arrays, y las clases. Tambión es util entender cémo funciona el
modelo de eventos de JS, ya que React hace un uso intensivo de los
mismos.

- HTML y CSS: React se utiliza para construir interfaces de usuario, por lo que
un buen entendimiento de HTML y CSS es crucial. Deberias estar familiarizado
con la estructura basica de un documento HTML, cémo se utilizan las etiquetas
para definir la estructura y el contenido de una pagina, y cémo se utiliza CSS
para estilizar ese contenido.

-Node.js y npm: React se desarrolla y se gestiona a través de Node.js y NPM
(Node Package Manager). Necesitaras un entendimiento basico de como instalar
y usar paquetes npm, y como se utilizan las herramientas de linea de comandos
de Nodejs. Aunque Node.js se emplea en sistemas Backend y creación de APIs
REST, no necesitas tener ese conocimiento, ya que Node abarca mucho mas y se
emplea tambión como herramienta de dev como veremos a lo largo del
libro.

+ ES6: React hace un uso intensivo de las caracteristicas de ES6 (la sexta versión
de ECMAScript, la especificación que define JS). Deberias familiarizarte
con las caracteristicas que hemos comentado anteriormente.

Si te sientes a gusto con estos conceptos, estaras en una buena posición para
empezar a trabajar con React. Si no es asi, te aconsejo dedicar un tiempo para
familiarizarse con ellos antes de seguir adelante. Existen numerosos recursos
disponibles en linea para aprender estos conceptos, y una inversión de tiempo en
esta etapa puede resultar en un ahorro significativo de tiempo y frustración en el
futuro.

Requerimientos

+ Node.js (v16 0 v18 que es la mas reciente)
- NPM (ya viene con Node.js)
-Vite (Herramienta de Scaffolding o generador de archivos, directorios y
condfiguraciones basicas)

- Un navegador, con sus Developer Tools. Chrome, Firefox, ... el que prefieras

«La extensión de React Developer Tools

+El editor de texto o el IDE (Integrated Developer Enviroment: Entorno de
dev Integrado) que prefieras. Yo utilizo VSCode, pero sirve cualquier otro
(Atom, SublimeText, WebStorm, etc...).

Instalación de Node.js y npm

React es una biblioteca de JS, por lo que necesitaremos un entorno
de JS para desarrollar nuestras aplicaciones. Node.js es un entorno de
ejecución de JS que nos permite ejecutar JS en nuestro sistema.
NPM (Node Package Manager) es un gestor de paquetes que viene con Node.js y nos
permite instalar y administrar bibliotecas de JS.

Node.js lo puedes instalar desde su pagina web. Dirigete a la web https: //
node js.org y descarga la versión LTS (Long-Term Support: Versión de Soportada a
largo plazo) o la mas actual. El instalador tambión instalara npm.

Node.js* isa JS runtime built on Chrome’s V8 JS engine.

Node.js 18 is now available!

Download for macOS (x64)

Or have a look at the Long Term Support (LTS) schedule

Pagina de descarga de Node,js

Instalación de Vite

La herramienta que utilizaremos para hacer el setup del proyecto sera Vite.

Vite es una herramienta que te permite crear un proyecto de JS (Vanilla,
con TypeScript, Vue, Svelte, React...), generar los archivos y carpetas necesarias, asi
como un servidor web de dev para probarlo en local.
Vite
Next Generation
Frontend Tooling

Get ready for a development environment that can finally
catch up with you.

Why Vite? View on GitHub

Pagina oficial del proyecto Vite

En los siguientes capitulos veremos como instalarlo y ejecutarlo.

React Developer Tools

Este plugin o extension de navegador lo puedes enontrar aqui: https://github.com/
FB/react-devtools/tree/v3

o en los diferentes marketplaces de los navegadores.

ome > Extensions > Reset Developer Tool

React Developer Tools
@ remrea

ee eH He 1371 | Developer Toots | 3:000.000+ vsers

Extension React Developer Tools en la Chrome Store

Esta herramienta nos sera muy util para depurar nuestras aplicaciones web.
Podremos inspeccionar el arbol de componentes de React, visualizar el estado y las
props de los componentes, etc.

En préximos apartados veremos como generar un proyecto de React, su estructura
y primera aplicacion. Pero antes, veamos una caracteristica principal de la libreria:
JSX.
JSX: Sintaxis de JS y XML

éQué es JSX?

Esta sintaxis especial que utiliza React, sirve para entre otras cosas, ahorrarnos

tiempo y sobretodo proporcionarnos una mejor experiencia de dev.

Aqui tienes un ejemplo de cémo se ve el cédigo JSX:

1 const element = <h1>Hola, mundo</h1>;

Aprimera vista, la impresión es que estamos escribiendo codigo HTML y lo estamos
mezclando dentro del cédigo JS, algo que es una muy mala practica y que no
se deberia hacer.

Pero esto no es asi. Esta sintaxis parecida a HTML es en realidad codigo JS,
bueno, realmente cddigo JSX que se traduce en JS. Tambión tiene algunas
diferencias clave que debes tener en cuenta. Por ejemplo, debido a que class1 es
una palabra reservada en JS, debes usar className en lugar de class
para asignar una clase CSS a un elemento.

éPor qué usar JSX?

JSX tiene varias ventajas que lo hacen util para desarrollar interfaces de usuario con
React:

+Legibilidad: El cddigo JSX se parece mucho al HTML, lo que hace que sea
facil de leer y entender. Esto es especialmente util cuando estds desarrollando
interfaces de usuario complejas con muchos elementos y componentes.

+ Potencia de JS: Aunque el cédigo JSX se parece a HTML, tiene todo el
poder de JS detras de él. Puedes insertar cualquier expresión JS
valida dentro de llaves {} en tu cédigo JSX.

+ Optimizacion de rendimiento: Las herramientas de compilación como Babel
transforman el cédigo JSX en llamadas a React. createElement, que es una
forma eficiente de crear elementos de React.

Uso de JSX en React

éPor qué hacemos esto? Basicamente, React, a diferencia de otras bibliotecas como
Vue o frameworks como Angular, utiliza JS para todo. Para renderizar el
codigo HTML, para manegjar la légica e incluso tambien para manejar estilos. Por
tanto, cuando estamos componiendo la plantilla HTML que tendra un componente,
en lugar de usar templating como en los otros recursos que hemos mencionado,
utilizamos JS.

Esto complicaria mucho la escritura y sobre todo la lectura del cdédigo
implementado. La forma mas facil de entender esto es usando el transpilador online
de Babel.

Babel es una biblioteca de JS que nos permite usar las Ultimas novedades
que incorporan las versiones mas recientes de JS antes de que estas sean
implementadas en el navegador. Entre ellas la sintaxis JSX que transpila el cddigo a
una version que actualmente entiendan los navegadores.
Esta biblioteca no hay que instalarla manulamente, ya que diversas herramientas
de hoy en dia como Vite, create-react-app o create-next-app ya las

incorporan y es una cosa menos a la hora de empezar a trabajar con React.

Este proyecto tiene una herramienta online que nos permite ver como se traduce 0

transpila el cidigo y comprobar su version en el navegador.

Dirigete a la siguiente pagina web: https://babeljs.io/repl y asegurate que esta
marcada la opción del preset “react”.

Herramienta web Babel para transpilacion a JS

Ahora vamos a probar a escribir cédigo JSX, por ejemplo el siguiente:

1 <div>
2 <h1>Hola mundo</h1>
3 </div>

Este es el resultado que nos arroja el intérprete:

1 "use strict

5 React.createElement("div", null,
4 React.createElement("hi", null, "Hola mundo")
5s

Vamos a explicarlo. La herramienta ha traducido o transpilado el cédigo JSX
a cédigo JS. Cada elemento “HTML” se ha sustituido por la función

React. createElement propia de la biblioteca React.

Esta funcidn, como su propio nombre indica, crea un elemento de HTML. Recibe 3
parametros:

+ Elelemento a crear,
+ Un objeto con propiedades (clases, atributos o props)
- Yuna lista de elementos hijos.

Parece facil y que no hay necesidad de usar JSX, podemos escribir el cédigo en

JS puro. Bueno, vamos a complicar un poco mis el cdigo JSX:

1 <div class="header">
2 <hi class="header__title">Hola mundo</h1>
3 <button onclick="open" class="header__button">Menu</
button>

4 <a href="/about" class="header__link">Sobre mi</a>

5 </div>

Este es el cédigo que tendriamos que escribir si lo hicieramos en JS plano:

1 “use strict";

3 React.createElement("div", {

4 class: "header"

5 3,

6 React.createElement("hi", {

7 class: "header_title"

8 3,

9 "Hola mundo"

10 »

11 React.createElement("button", {
12 onclick: "open",

43 class: "header__button"
14 3,

15 "Menu"

16 >

17 React.createElement("a", {

18 href: "/about",

19 class: "header__link"
20 },

"Sobre mi"

eCémo lo ves? Se podria hacer, pero ¢Te resulta practico? ¢Es legible? Personalmente
prefiero JSX para codificar el templating de mis componentes, si no es muy dificil de
mantener y afiadir o cambiar elementos con el paso del tiempo.

Es comprensible que si llevas tiempo en el mundo del dev web, te “eche un
poco para atras” el tener que escribir algo que parece HTML en cidigo JS. No
te preocupes, yo pensaba lo mismo y fue una de las causas por las que en un inicio
rechazaba a React.

Pero una vez se ve el punto, que realmente es JS y que es para facilitarnos la

vida como desarrolladores, me cambié el chip.

Por supuesto, no todo el cédigo que vas a emplear en React es JSX. En React lo
que mas vas a usar es JS. y Vanilla. React sdlo aporta ciertos métodos y
estructura, pero practicamente todo el cédigo que escribirds es JS. JSX sdlo se utiliza
para el maquetado o plantilla que tendran tus componentes. Pero no te preocupes
que vamos air viendo todo esto.
Creación de un proyecto de React

Setup del proyecto con Vite

Ya hemos visto JSX que es una de las tecnologias o caracteristicas que distinguen
a React y ahora podemos ponernos manos a la obra a crear lo que seria nuestra
primera app web con esta biblioteca.

No vamos a hacer nada del otro mundo, simplemente algo muy sencillo pero a la
vez necesario para entender el flujo de la programación, las herramientas y diversas
cosas a tener en cuenta que la primera vez pueden ser un poco liosas, pero luego ya
se hacen de forma sistématica y dejamos de tenerlas en cuenta.

Hay diversas formas de crear una app con React desde cero. Ninguna es mejor
ni peor, inicamente cambia la forma de configurar todo antes de empezar.

Podemos hacerlo de forma “manual”, para ello necesitariamos instalar y configurar
Webpack u otra herramienta de empaquetado y transpilación de cddigo JSX y
JS moderno a cédigo comprensible por el navegador, ademas de varios
plugins para que esto funcione correctamente y por supuesto, las bibliotecas o
paquetes react y react -dom necesarias para poder utilizar sus funciones.

Puede ser interesante de hacer esto si quieres comprender “la magia” detras de las
herramientas actuales, pero hoy en dia, en mi opinion, si es tu primera vez en este
ecosistema de dev web con React, son mas trabas y frustaciones a llevarse,
que arrancar con algo mas configurado por defecto y que te permite centrarte en
aprender la librerfa y forma de trabajar con ella.

Por ello existen 3 alternativas. El propio equipo de React creé create-react-
app una herramienta de scaffolding que te instala todo lo necesario y genera la
estructura de archivos y carpetas de un “Hola Mundo” con React que hoy dia ya se
encuentra deprecada.

Otra muy extendida es create -next - app creada por el equipo detras de Next.js,
un framework basado en React pero que se escapa del ambito de este libro.

Y por ultimo tenemos a Vite, una herramienta muy veloz que hace lo mismo
que create-react - app pero utilizando ESBuild en lugar de Webpack para el
empaquetado, reduciendo asi los tiempos de transpilación, y tambión es multi-
libreria. No solo sirve para React, sino tambión para Vue, Svelte, Lit incluso Vanilla
JS, y sus versiones con TypeScript.

En este momento es la herramienta mas popular y que mejores valoraciones tiene
segun la ultima encuesta sobre el “Estado de JS” y vaa ser la que utilicemos

en este libro. De esta manera pondremos todas nuestras energias en React dejando
de un lado configuraciones tediosas.
3 vue

RATIOS OVER TIME vonne peace

6 lit
svelte

Elegimos la variante sin TypeScript

? Select a variant: >» - Use arrow-keys. Return to submit.
2» react
react-ts

Y ya sdlo tenemos que ir al directorio que se acaba de crear y ejecutar los comandos
que nos indica para que se instalen las dependencias y se ejecute el cédigo en un
servidor de dev local:

Encuesta del Estado de JS 2022
av Select a framework: > react

v Select a variant: >» react
Para poder usar Vite, necesitamos tener Node.js instalado como dijimos en 3
el capitulo donde comentabamos el entorno de dev. Si ya lo tienes, 4 Scaffolding project in /Users/carlosazaustre/Books/react-
practico\
/code/my-app.

simplemente has de correr el siguiente comando en la terminal:

1 $ npm create vite@latest my-app > Done. Now run:

cd my-app
10 mpm install
npm run dev

Seleccionamos la opción de React:

1? Select a framework: > - Use arrow-keys. Return to submit.
vanilla
Al ejecutar el comando de dev, si vamos a nuestro navegador a la URL
http://localhost:5173 (0 el puerto en el que esté corriendo) veremos lo
siguiente:

Hello Vite + React!

Edit App. j Sx and save to test HMR updates.

Hola Mundo con React y Vite

Nuestro primer “Hola Mundo” con React! Con un logo en SVG rotando, un poco de
texto y un boton con un contador para probar estados y eventos.

Estructura de archivos y carpetas

Pasemos a ver que cédigo nos generé. Esta es la estructura de archivos y carpetas si

abrimos nuestro editor de cédigo:

1 - node_modules
2 - sre
3 - App.css
4 - App. jsx
- favicon. svg
6 - index.css
- logo.svg
8 - main. jsx
9 - eslintre.cjs
- .gitignore
- index.html
- package-lock. json
- package. json
, - vite.config.js

Parecen muchos archivos pero en realidad no son tantos. Te paso a comentar cada
uno de ellos:

node_modules

Este directorio alberga todos los paquetes que estan instalados, como react y
react-domyasu vez todos los que dependan de ellos. Es una carpeta que debemos
tener apuntada en nuestro fichero . git ignore para evitar que se suba a nuestro
repositorio. ¢Por qué? pues, entre otras cosas, porque ocupan mucho espacio y
gracias al fichero package. json siempre tendremos el registro de cudles y qué
versiones son.
package.json

Este fichero es el manifiesto de nuestra app. Contiene algo de metadata, las
dependencias que usamos en el proyecto, asi como las dependencias de dev.
Tambión tiene los alias para ejecutar ciertos scripts:

af

2 "name": "my-app",

3 “private”: true,

4 "version": "0.0.0",

"module",

{
"vite",
“vite build",
"“eslint sre --ext js,jsx --report-unused-disable-

dire\

10 ctives --max-warnings 0",

14 "preview": "vite preview"

12},

13. "dependencies": {

14 "react": "18.2.0",

45 "“react-dom": "*18.2.0"

16},

17 “devDependencies": {

18 "@types/react": "*18.0.37",

19 "@types/react-dom": "18.0.11",
20 "@vitejs/plugin-react": "*4.0.0",
24 "eslint": "8.38.0",

22 “eslint-plugin-react": "*7.32.2",

23 “eslint-plugin-react-hooks":

"44.6.0",
"40.3.4",

slint-plugin-react-refresh":

vite 4.3.9"

El script dev ejecuta un servidor local de dev para probar nuestra app
en el navegador e incorpora hot reloading. Esto quiere decir que a cada cambio que
hagamos en nuestro cédigo, se vera reflejado en el navegador inmediatamente sin
necesidad de tener que recargarlo manualmente.

El script build prepara nuestro cédigo para ser desplegado en un entorno de

producción.

preview ejecuta un servidor local pero el cédigo que emplea para ello es el cddigo
ya listo para producción.

Y por ultimo lint ejecuta el linter para verificar que nuestro cédigo sigue las
normas de estilo especificadas en el ficheroeslintre.cjs.

vite.config.js

Este fichero contiene la configuración de Vite y de las herramientas de dev.
Es muy sencillo y practicamente no hay que tocar nada a no ser que quieras algo
mis especifico. Con su Zero-Config, Vite ya esta listo para ser usado. Y como en el
menu de la terminal, cuando estabamos creando el proyecto, elegimos la opción
de react, esta ya incorpora los plugins necesarios para entender JSX y JS
moderno.
1 import { defineConfig } from ‘vite’
2 import react from '@vitejs/plugin-react'

4 // https://vitejs.dev/config/

5 export default defineConfig({
6 plugins: [react()],

index.HTML.

El fichero index.htm] es el unico documento HTML que tendremos como cédigo
fuente. Silo abres verds que es sumamente sencillo

1 <!DOCTYPE htm1>
2 <html lang="en">

3 <head>
4 <meta charset="UIF-8" />

5 <link rel="icon" type="image/svg+xml" href="/vite.svg" />
6 <meta name="viewport" content="width=device-width,

initial-sc\

7 ale=1.0" />

8 <title>Vite + React</title>

9 </head>

10 <body>

11 <div id="root"></div>

12 <script type="module" src="/sre/main. jsx"></script>

13. </body>

14 </htm1>

Tiene algunas etiquetas de metadatos en el elemento head y en el body sdlo hay un
div con el id root que sera donde se incruste o renderice toda nuestra app

gracias a React.

Para que funcione, necesitamos incorportar el fichero de entrada de la app en
JS, que es el main. jsx que se encuentra en la carpeta src. Los afiadimos
como script al HTML y le indicamos que sera de tipo médulo para poder utilizar
los ESModules e imports que JS introdujo en su version ES6.

src

Esta es la carpeta que alberga todo el cédigo fuente de nuestra app. Verds que
hay varios archivos pero los que nos interesan son el main. jsx y el App. jsx. El
resto son ficheros de estilos css y algunas imagenes.

main.JSX

El fichero principal de la app. Si te das cuenta, tiene extensión JSX. Puedes
usar la extension . js, va a funcionar igual, aunque por convención, si el fichero es
un componente de React y/o utiliza cédigo JSX lo ideal es que lo nombremos como
tal.

Ademis si utilizas un theme en tu editor para mostrar iconos diferentes segtin el

tipo de archivo, los ficheros . jsx los muestra con el icono de React.
Estructura de archivos y carpetas en VSCode utilizando la extensión File-Icons

Este es su contenido y ahora lo explicamos:

1 import React from ‘react’

2 import ReactDOM from 'react-dom/client'

3 import App from './App.jsx'

import

./index.css'

6 ReactDOM. createRoot (document. getElementById('root')).render(
7 <React.StrictMode>
<App />

</React. StrictMode>,
o)

Las primeras lineas son la importación de diferentes médulos y archivos para
ser utilizados. Las dos primeras son las importaciones de react y react-
dom. La primera nos permite usar las funciones de la biblioteca como el
React. StrictMode que es una etiqueta que permite que nuestra aplicacion sea
mas segura. Esto quiere decir que si algo falla en la aplicacion, no se ejecutaré nada
més que el cédigo que esté dentro de la etiqueta.

Y la segunda, nos permite usar el método ReactDOM.createRoot para
renderizar y construir el componente App que contiene toda la légica de nuestra
app.

Este método acepta un parametro, que sera el elemento donde se renderizara. En
este caso el resultado de document. getElementById('root') es el elemento
donde se renderizar4 nuestra app. Despues usamos el método render que se
le pasa el componente o conjunto de componentes a renderizar en formato JSX. En
este caso<App /> entre los componentes de <StrictMode>.

Las ultimas importaciones son el fichero index. css que contiene el cddigo de
estilos CSS que se aplicara a toda la app. Y aunque no lo usemos directamente
en este archivo, Vite lo que hace despues es afiadirlo como link de estilo al head del
HTML.
Y por ultimo elcomponente <App /> que el componente principal de la app
yloimportamos como médulo.

App.jsx

Nuestro componente principal. Normalmente seran varios componentes los que
formen nuestra app. En este caso sélo tenemos uno, pero podriamos tener

varios.

Veamos lo que contiene este fichero y expliquemos como funciona:

1 import { useState } from ‘react’

2

3 function App() {

% const [count, setCount] = useState(0)

6 return (

7 <div className="App">

8 (ye... #7}

9 <button type="button" onClick={() => setCount((count)

=\
10 > count + 1)}>

re count is {count}
12 </button>

45 on. */}

14 </div>

us)

as }

18 export default App

En la primera linea, importamos la función useState de React. Esta función nos
permite crear un estado en nuestra app. En este caso, el estado es un number
y el valor inicial es 0.

Usamos la destructuracón de objetos de JS para no tener que utizar
React.useState cada vez que se necesite, sino simplemente useState.

Lo siguiente es la creación de la función App. Esto es un componente en React.
Todos los componentes en React son funciones, con cierta légica si la tuvieran y
devuelven una plantilla escrita en JSX que contiene elementos HTML y tambión
otros componentes de React.

En versiones anteriores de React, los componentes podian ser de tipo class o
function. La principal razón era, que si el componente tenia que manejar estado,
era necesario que fuera de tipo clase, tuviera un constructor, metodos de ciclo
de vida y un método render. Los componentes de tipo funcion se dejaban para
componentes mas representacionales, es decir, que Unicamente recibieran props y
devolvieran una plantilla con esos datos.

Con la llegada de los Hooks, este paradigma cambié, ya que nos permitié poder
usar el estado y los métodos de ciclo de vida de los componentes en funciones, sin
necesidad de usar clases. Esto supuso un gran avance y una mayor adopción de
React como biblioteca para proyectos frontend. Las clases hacian la app mas
pesada y no toda la gente entendia bien su funcionamiento y sintaxis. Actualmente,
con los Hooks, se elimina esa duda de cuando usar funciones o cuando usar clases.

Las aplicaciones han reducido su peso y performance al no usar clases.

Dentro de la función, lo ultimo que se hace es devolver la plantilla, simplemente con
un return y el cédigo JSX que represente el componente. Aqui recuerda siempre
enviar al menos un elemento como padre que englobe al resto de elementos, por lo
que vimos en el capitulo de JSX.

Para mejor lectura del cddigo, lo conveniente es engloblar toda el cédigo JSX entre
paróntesis (...), ano ser que sea tnicamente una linea y en ese caso se podria
devolver directamente. Pero por buenas practicas y prevención de errores a futuro,
lo mejor es que lo afiadas siempre.

Como hemos dicho, lo tiltimo que se hace es devolver el template, pero lo primero
seria hacer la configuración de los estados que pudiera tener nuestro componente
asi como otros hooks que empleemos. En este caso, vamos a usar un estado para
contabilizar un contador, y que cada vez que se haga click en un botón, ese se
incremente en uno.

Para ello, todo hook useState devuelve un array con dos elementos. El primero de
ellos es el propio estado, donde esta almacenado el valor. Y el segundo es la función
que nos permite cambiar ese valor. No podemos modificar directamente el valor,
debemos hacerlo a través de la función que nos provee para ello. Esto es asi, porque
el estado es inmutable. y por el funcionamiento interno de React, debe ser asi para
que los cambios hagan que se ponga en marcha todo el mecanismo para renderizar
el componente.

Esta es una de las bases fundamentales de React. Es una biblioteca reactiva y
eso significa que a cada cambio que hagamos en la información y estado del
componente, React se encargard de volver a renderizar o “repintar” la plantilla con
esos nuevos datos y asi se vera reflejado en el DOM.

Estos dos elementos que nos devuelve en array el hook de useState puedes

llamarlos como quieras. Por buenas practicas, llama siempre a la función que
permite cambiarlo como set seguido del nombre que le hayas puesto al estado.
Por ejemplo aqui estamos Ilamando al estado: count, por lo que su función de
cambio debe llamarse setCount. Tambión cuando se instancia el hook, podemos
pasarle un valor inicial. En este caso puedes ver que le hemos dado el valor de 0 con
useState(0).

éY cémo cambiamos éste estado? gDónde podemos llamar a la función setCount?
En este caso, en el botón que hemos creado, le hemos afiadido un evento de escucha
onClick. Cuando se haga clic en el botón, se ejecutard la función que le pasemos.

() => setCount((count) => count + 1)

Utilizamos la sintaxis de funciones flecha para que sea mAs sencillo de incorporar y
como puedes ver, no podemos pasarle directamente la función set Count al evento
onClick Tenemos que usar una función de callback, si no lo podra ejecutar. Esto es
un error bastante comun, el poner directamente la función y que el componente no
haga nada y no encontrar el error.

Para eso, siempre es recomendable, sacar esta función fuera del cédigo JSX y tratarla
como un manejador. Te muestro el cédigo:

1 const handleClick = () => setCount((count) => count + 1)
2

3 return (
4 {/* 22. */}
5 <button type="button" onClick={handleClick}>

6 count is: {count}
7 </button>
8 (/* 22. */3

Y esto seria basicamente lo que haria nuestra app “Hola Mundo con React”.
Puedes ejecutarla de nuevo con el comando npm run dev y probarla en el
navegador. Cuando hagas clic en el botón y veas que el valor cambia, comprenderas
cémo esta funcionando el cdigo que hemos visto.
Componentes: Clases vs Funciones

En React podemos crear componentes de 2 maneras principalmente. Con Clases de
JS, que puedes encontrar su nombre de varias formas: Smart Components,
Container Components, Statefull Components, Componentes de clases, etc...

Y los componentes de tipo función, cuyos sinónimos serian: Stateless Components,

Representational Components, Dumb Components, etc...

Desde la llegada de los Hooks en la versión 16.8 de React, todo esto se unificé y
particularidades de los componentes de clase como el estado ya pueden usarse en
los de tipo función.

Pero no te preocupes por esto ahora mismo, lo explicaremos mas adelante. En
esta sección, exploraremos las diferencias entre los componentes de clase y los
componentes funcionales, y discutiremos cuando podrias querer usar uno sobre el

otro.
Componentes de Clase

Los componentes de clase son definidos utilizando la sintaxis de clase de ES6. Un
componente de clase debe incluir al menos un método, llamado render (), que

devuelve JSX. Aqui tienes un ejemplo de un componente de clase:

1 import React from ‘react’;

2

5 class Saludo extends React.Component {
4 constructor(props) {

5 this.props = props;

render() {

return <h1>Hola, {this.props.nombre}</h1>;

13 export default Saludo;

En este ejemplo, Saludo es un componente de clase que acepta una prop nombre
y devuelve un elemento h1 que contiene un saludo personalizado.

Los componentes de clase tienen algunas caracteristicas que no estan disponibles
en los componentes funcionales, como los métodos del ciclo de vida y el estado
local. Sin embargo, con la introducción de los Hooks en la versión de React numero
16. 8, ahora puedes usar el estado y otros aspectos de React sin escribir una clase.

Componentes funcionales

Los componentes funcionales son simplemente funciones de JS que
aceptan props como argumento y devuelven JSX. Aqui tienes un ejemplo de un

componente funcional:

1 import React from ‘react’;

3 function Saludo(props) {
4 veturn <h1>Hola, {props.nombre}</h1>;
5}

) export default Saludo;
En este ejemplo, Saludo es un componente funcional que hace exactamente lo
mismo que el componente de clase Saludo que definimos anteriormente.

Los componentes funcionales son més simples y faciles de entender que los
componentes de clase. No necesitas entender la sintaxis de clase de JS 0
cémo funciona this en JS para usar componentes funcionales. Ademas,
los componentes funcionales te permiten usar Hooks, haciendo mas sencillo y
potente la forma de reutilizar la logica del estado entre los componentes.

Clases o Funciones ;Cual deberias usar?

En versiones anteriores de React, los componentes de clase eran la unica forma de
tener estado local y métodos del ciclo de vida. Sin embargo, como hemos citado,
con la introducción de los Hooks en React 16.8, ahora puedes usar el estado y otros
aspectos de React en los componentes funcionales.

Por lo tanto, a menos que estés trabajando en un cédigo base antiguo que atin use
componentes de clase, es probable que quieras usar componentes funcionales en
la mayoria de los casos. Los componentes funcionales son mas faciles de leer y
entender, y los Hooks te permiten reutilizar la légica del estado de una manera mas
eficiente que los métodos del ciclo de vida en los componentes de clase.

Por eso mi recomendación y como buena practica actual, es que uses siempre
componentes funcionales. Tambión el tamazio final de tu app lo agradecera

ya que las clases son mas pesadas.

En frameworks como Next, hay todavia componentes especiales del propio
framework que estan definidos como clase. Pero salvo esas excepciones, lo ideal son
las funciones.
Props y Estado en los componentes

En este apartado, vamos a explorar dos conceptos fundamentales en React: las
propiedades (props) y el estado (state). Estos son los dos tipos principales de datos
que los componentes de React manejan y manipulan. Comprender cémo funcionan
y como se utilizan es clave para desarrollar aplicaciones con React.

Propiedades (Props)

Las propiedades, o props, son una forma de pasar datos de los componentes padres
alos componentes hijos.

En otras palabras, las props son como los argumentos de una funcidn en JS.
Son inmutables, lo que significa que un componente no puede cambiar sus props.

Veamos un ejemplo de cémo se utilizan las props en componentes de tipo función:

1 function Saludo(props) {
2 return <h1>Hola, {props.nombre}</h1>;

5 function App() {
6 return <Saludo nombr

Mundo" />;

Eneste ejemplo, el componente Saludo recibe una prop llamada nombre.

Cuando se utiliza el componente Saludo en el componente App, le pasamos la
prop nombre con el valor “Mundo”. El resultado es que la app muestra “Hola,

Mundo’ en el navegador.

Ahora que has visto un ejemplo sencillo, vamos a explicar mas en detalle como
funciona esta caracteristica de React.

Pasando Props
Las props se pasan a los componentes de la misma manera que se pasan los

atributos a los elementos HTML. Por ejemplo, si tienes un componente Usuario
que acepta una prop nombre, puedes pasarle esa prop de la siguiente manera:

1 <Usuario nombre="Carlos" />

En este caso, “Carlos” es el valor de la prop nombre que se pasa al componente
Usuario.

Accediendo a Props

Dentro del componente, puedes acceder a las props a través del objeto props que se
pasa como argumento a la función del componente. Por ejemplo:

1 function Usuario(props) {
2  veturn <h1i>Hola, {props.nombre}</h1>;
En este caso, estamos accediendo a la prop nombre a través del objeto props y la
estamos utilizando para renderizar un saludo.

Props por defecto

En algunos casos, es posible que quieras establecer valores por defecto para ciertas
props. Esto se puede hacer utilizando defau1tProps. Por ejemplo:

1 function Usuario(props) {
2  veturn <hi>Hola, {props.nombre}</h1>;

5 Usuario.defaultProps = {
6 nombre: "Desconocido"
745

En este caso, si el componente Usuario se utiliza sin pasarle una prop nombre,
utilizara “Desconocido” como valor por defecto.

Aunque esta forma ya no se utiliza tanto, desde que aparecid la caracteristica
Default Properties en la versión 6 de ECMAScript. Utilizandolo de esta manera, en
conjunción con el destructuring de objetos de JS, el codigo quedaria asi:

1 function Usuario({ nombre = "Desconocido" }) {
2 return <hi>Hola, {nombre}</h1>;

Hemos realizado un destructuring del objeto props, dejandolo en el argumento
de la función/componente como {nombre} para asi acceder directamente a las
propiedades del objeto. De esta manera, con el operador = podemos indicarle un
valor por defecto en el caso de no se le asigne ninguno desde nuestra app.

Props y Componentes Hijos

Las props tambión se pueden utilizar para pasar componentes hijos a otros
componentes. Esto se hace a través de la prop especial children. Por ejemplo:

1 function Panel(props) {
2 return <div className="panel">{props.children}</div>;

5 function App() {
6 return (

<Panel>
8 <hi>Hola Mundo</h1>
9 </Panel>

10)

1}

En este caso, el componente Pane] esta recibiendo un componente h1 como hijo
a través de la prop children. De esta manera podemos “incrustar” componentes
o elementos HTML dentro de nuestros propios componentes si el disefio asi lo
requiere.
Las props son una herramienta muy potente y esencial en React que te permite crear
componentes reutilizables y componibles.

Asegtrate de entender cémo funcionan antes de pasar al siguiente apartado, donde
discutiremos el estado.

Estado (State)

El estado es una caracteristica que permite a los componentes de React mantener
y manipular datos que pueden cambiar con el tiempo. A diferencia de las props,
que son inmutables y se pasan de los componentes padres a los hijos, el estado es
privado y completamente controlado por el componente.

Estado en los componentes de Clase

En los componentes de clase, el estado se inicializa en el constructor de la clase
y se accede a través de this. state. Para cambiar el estado, se utiliza la función
this.setState(), que tambión le indica a React que debe volver a renderizar el

componente.

Aqui tienes un ejemplo de cémo se utiliza el estado en un componente de clase:

1 class Contador extends React.Component {
2 constructor(props) {

3 super(props) ;

4 this.state = { contador: 0 };

6 this.incrementar = this. incrementar.bind(this) ;

incrementar() {
this.setState({ contador: this.state.contador + 1 });

a 45

3 vrender() {
14 return (
15 <div>
<p>Has hecho click {this.state.contador} veces</p>
<button onClick={this.incrementar}>
Haz click aqui

</button>
20 </div>

21 5

22 «3

23}

Eneste ejemplo, el componente Contador tiene un estado llamado contador que
se inicializa a 0 en el constructor. Cuando se hace clic en el botón, se llama a la
función incrementar, que incrementa el valor de contador en 1 y provoca que el
componente se vuelva a renderizar.

En los componentes de clase de React, los métodos no estan automaticamente
vinculados al contexto de la clase. Esto significa que si intentas acceder a this
dentro de un método (como incrementar), this sera undefined, a menos que
explicitamente vincules el método al contexto de la clase.

Las nuevas caracteristicas de ECMAScript permiten definir el estado y los métodos
de la clase directamente en el cuerpo de la clase, fuera del constructor. Este seria
el componente de clase Contador reescrito utilizando estas caracteristicas:
1 class Contador extends React.Component {
2 state = { contador: 0 };

3

4 incrementar = () => {

this.setState({ contador:

this.state.contador + 1 });
6 4

8  render() {

9 return (

10 <div>

11 <p>Has hecho clic {this.state.contador} veces</p>
12 <button onClick={this. incrementar}>

43 Haz click aqui

14 </button>

45 </div>

16 5

7}

1s }

En este ejemplo, el estado se inicializa directamente en el cuerpo de la clase, y el
método incrementar se define como una arrow function, que automaticamente
vincula this al contexto de la clase. Esto elimina la necesidad de un constructor
explicito solo para inicializar el estado y vincular los métodos.

Estado en Componentes Funcionales con Hooks

Con la introducción de los Hooks en React 16.8, ahora es posible utilizar el estado
en los componentes funcionales. El Hook useState es una función que acepta un

valor inicial para el estado y devuelve un array con dos elementos: el valor actual
del estado y una función para actualizarlo.

Aqui tienes un ejemplo de como se utiliza el estado en un componente funcional
con Hooks:

1 import { useState } from ‘react

2
3 function Contador() {
4 const [contador, setContador] = useState(0);
6 return (
<div>
<p>Has hecho click {contador} veces</p>
<button onClick={() => setContador(contador + 1)}>
Haz click aqui

</button>

</div>

En este ejemplo, el componente Contador utiliza el Hook useState para crear un
estado llamado contador con un valor inicial de 0. La función setContador se
utiliza para actualizar el valor de contador cuando se hace clic en el botón.

Introducción a los Hooks

COmo hemos comentado ya varias veces, Los Hooks son una caracteristica que
se introdujo en React 16.8 que permite a los componentes funcionales utilizar
caracteristicas que antes sdlo estaban disponibles en los componentes de clase,
como el estado y los métodos del ciclo de vida. Los Hooks son funciones que
“enganchan” (Hook es “anzuelo” en inglés) los componentes funcionales a las
caracteristicas de React.

En este apartado, hemos visto cémo se utiliza el Hook useState para manejar el
estado en los componentes funcionales. En los préximos apartados, exploraremos
otros Hooks y cémo se pueden utilizar para hacer que los componentes funcionales
sean atin ms flexibles.
Manejo de eventos

En este apartado, nos centraremos en otro de los aspectos mas importantes y
fundamentales de cualquier app interactiva: el manejo de eventos. En React,
los eventos son acciones que ocurren en la app, como clics del mouse,
pulsaciones de teclas, cambios de estado, entre otros.

Eventos en React

React tiene un sistema de eventos propio que es compatible con el modelo de
eventos W3C (World Wide Web Consortium). Esto significa que, aunque estés
trabajando con una biblioteca JS, los eventos en React funcionan de manera
muy similar a cémo lo hacen en HTML plano.

Por ejemplo, un evento de clic en un botón en HTML se mangjarfa de la siguiente

manera:

1 <button onclick="handleClick()">
2 Haz clic en mi
3 </button>

En React, la sintaxis es muy similar, pero con algunas diferencias clave. Primero,
en lugar de onc lick, usariamos onClick (Date cuenta del formato camelCase de
la palabra). Esto se debe a que estamos trabajando en JSX, que es una extensión
de JS, no HTML. En segundo lugar, en lugar de un string, pasariamos una
función al manejador de eventos:

1 <button onClic
2 Haz clic en mi

handleClick}>

3 </button>

Creando un manejador de eventos

Un manejador de eventos es simplemente una función que se ejecuta en respuesta
aun evento. En React, puedes definir estos manejadores de eventos como métodos
en tu componente de clase o como funciones dentro de tu componente funcional.

Aqui hay un ejemplo de como podrias crear un manejador de eventos en un

componente de clase:

1 class MyButton extends React.Component {
2  handleClick() {
3 console.log('El botón fue clickado!');

6 vender() {

7 return <button onClick={this.handleClick}>Haz clic en mi</
but\

8 ton>;

s }

10 }

Y aqui hay un ejemplo de como podrias hacerlo en un componente funcional:
1 function MyButton() {
2 const handleClick = () => {

3 console.log('El botón fue clickeado!');

a 45

6 return <button onClick={handleClick}>Haz clic en mi</
button>;

oy

Eventos sintéticos

React, en su intento de proporcionar una experiencia de dev uniforme entre
diferentes navegadores, implementa un sistema de eventos sintéticos. Un evento
sintético es basicamente un objeto que simula un evento nativo del navegador,
proporcionando la misma interfaz, independientemente del navegador que estés
utilizando. Esto es especialmente util para manejar las inconsistencias entre los
diferentes navegadores.

Los eventos sintéticos en React son instancias de la clase SyntheticEvent, que
es una envoltura alrededor del evento nativo del navegador. Tienen la misma
interfaz que los eventos nativos del navegador, incluyendo stopPropagation()
y preventDefault(), excepto que funcionan de manera idóntica en todos los

navegadores.

Un beneficio mas de los eventos sintéticos es que React puede reutilizar las
instancias de eventos para mejorar el rendimiento y reducir la carga de memoria.
Después de que el evento se ha procesado y los callbacks han sido invocados, React

limpia automaticamente las propiedades del evento sintético. Esto significa que no
puedes acceder a las propiedades del evento de forma asincrona.

‘Aqui hay un ejemplo de cémo se ve un evento sintético en React:

function MyButton() {
const handleClick = (event) => {

3 event. preventDefault();
4 console.log('E1l botón fue clickado!');
5 }

? return <button onClick={handleClick}>Haz click en mi</

button>;
6}
En este ejemplo, event es un evento sintético. Al lamar a

event .preventDefault (), estamos evitando que el navegador realice la acción
predeterminada asociada con el clic en el botdn. Esto es util, por ejemplo, cuando
tienes un botón en un formulario y no quieres que el formulario se envie cuando se
hace clic en él.

Como mencionamos antes, es importante recordar que debido a la naturaleza de
los eventos sintéticos en React, no puedes acceder a las propiedades del evento
de forma asincrona. Si necesitas acceder a un evento de forma asincrona, deberas
llamar a event . persist () paraeliminar el evento sintético del “pool” de eventos

y evitar que React lo limpie:
1 function MyButton() {
2 const handleClick = (event) => {

3 event.persist();

4 setTimeout(() => {

5 console.log('El botón fue clickeado!', event);
6 }, 1000);

9 return <button onClick={handleClick}>Haz clic en mi</
button>;

10}

En este ejemplo, estamos usando setTimeout para acceder al evento de forma
asincrona. Sin event.persist(), React limpiaria el evento antes de que
setTimeout se ejecutara, y no podriamos acceder a las propiedades del evento.
Profundizando en Props y Eventos:
Props Drilling y Event Bubbling

Props Drilling

“Props Drilling” es un término que se utiliza para describir el proceso de pasar datos
de un componente a otro a través de la estructura del arbol de componentes. Esto se
hace a través de las props.

Imagina que tienes una estructura de componentes en la que un componente
madre tiene varios componentes hijos, y algunos de esos hijos tienen sus propios
hijos. Si el componente mis interno necesita acceder a los datos del componente
madre, esos datos tendrian que “perforar” todos los niveles de componentes hasta
llegar al componente mas interno.

Aqui tienes un ejemplo de cémo se veria esto:

1 function Madre({ datos }) {

2  veturn <Hijo datos={datos} />;

3}

5 function Hija({ datos }) {

6 veturn <Nieto datos={datos} />;

2}

9 function Nieta({ datos }) {

10 // Ahora nieta tiene acceso a los datos
11}

Aunque el props drilling puede ser Util en algunos casos, puede volverse
problematico cuando tienes una estructura de componentes grande y compleja. En
estos casos, puede ser dificil rastrear cémo se estan pasando los datos y puede llevar
aun cédigo innecesariamente complicado.

Event Bubbling

“Event Bubbling” es un término que se utiliza para describir cémo los eventos en
React (y en el DOM en general) se propagan a través de la estructura del arbol
de componentes. Cuando se dispara un evento (como un clic 0 un cambio de
entrada), ese evento se propaga hacia arriba a través de la estructura del Arbol de

componentes, comenzando por el componente en el que se disparé el evento y
continuando hasta el componente mas alto.

< div >
div onFocus >| (
< button
onClick >

Event Bubbling

< button
onClick >

Esto puede ser util porque te permite manejar un evento en un componente de alto En este ejemplo, el evento de clic se dispara en el componente Hija, pero se maneja
nivel, incluso si el evento se disparé en un componente de bajo nivel. Aquitienesun —_ enel componente Madre.
ejemplo de cémo se veria esto:

Es importante tener en cuenta que, aunque el “event bubbling” puede ser

1 function Madre() ( util, tambión puede llevar a comportamientos inesperados si no se maneja
2 function handleClick() { correctamente. Por ejemplo, si tienes varios manejadores de eventos en diferentes
3 console.log('Se hizo clic!'); niveles de tu estructura de componentes, todos ellos se activaran cuando se dispare
a} un evento, a menos que detengas explicitamente la propagación del evento.

6 veturn <Hija onClick={handleClick} />;

9 function Hija({ onClick }) {
10 return <button onClick={onClick}>Haz clic en mi</button>;

a1}
Conclusión

El manejo de eventos es una parte fundamental de la creación de aplicaciones
interactivas con React. Aunque la sintaxis puede parecer un poco diferente al
principio, especialmente si tienes constumbre de trabajar con HTML y JS
puros, te acostumbraras rapidamente a cémo funcionan los eventos en React.
Recuerda, los eventos en React son simplemente funciones que se Ilaman en
respuesta a acciones del usuario, y puedes manejar estos eventos de la misma
manera que manejarias cualquier otra función en JS.

En los siguientes apartados, exploraremos mas a fondo cémo podemos utilizar los

eventos para controlar el estado de nuestra app y crear interacciones mas
complejas. Pero por ahora, te animo a que juegues con los ejemplos de cédigo que
hemos visto en este apartado. Intenta crear tus propios manejadores de eventos, y
observa cémo puedes usarlos para cambiar el comportamiento de tus componentes
de React.

Ahora continuaremos con el ciclo de vida de los componente. Algo esencial para
entender los tiempos y los datos a los que podemos acceder en cada momento de la

renderización del componente.
Referencias

- Bank, A., Porcello, E. (2017). Learning React: Functional Web Development with
React and Redux. O'Reilly Media.

+ FB Inc. (2023). Your first component. https://react.dev/learn/your-first-
component

+ FB Inc. (2023). Passing Props to a Component. https://react.dev/learn/

passing-props-to-a-component

Capitulo 3: Ciclo de vida de los componentes
El Virtual DOM

Antes de adentrarnos en el ciclo de vida de los componentes en React, es importante
entender el concepto del Virtual DOM.

El Virtual DOM (V-DOM) es una caracteristica fundamental de React que permite a
la biblioteca ser rapida y eficiente en la actualización de la interfaz de usuario. Es
una abstracción del DOM (Document Object Model) real, una representación ligera de
éste en memoria.

Cuando se crea una interfaz de usuario en React, en realidad se esta creando una
estructura de datos en memoria que representa esa interfaz. Esta estructura de
datos es el V-DOM.

El V-DOM tiene la misma forma que el DOM real, pero carece de la capacidad de
cambiar directamente lo que se muestra en la pantalla. En lugar de eso, React utiliza
el V-DOM para determinar qué partes del DOM real necesitan cambiar cuando

ocurre un evento, como una interacción del usuario o una actualizacion de datos.

El proceso funciona de la siguiente manera:

Component B

Component A & ( A | Ros
>

Component C React B ec] Som

+Creacion del V-DOM: Cuando se renderiza un componente de React, se crea
una representación del V-DOM para ese componente y sus hijos. Este V-DOM
representa el estado actual de la interfaz de usuario.

- Actualizacion del estado: Cuando cambia el estado de un componente (por
ejemplo, debido a una interacción del usuario), React crea un nuevo V-DOM que
refleja el nuevo estado de la interfaz de usuario.

+ Diferenciación (Diffing): React compara el nuevo V-DOM con el antiguo
V-DOM. Este proceso se conoce como “diferenciación” o “diffing”. React
determina exactamente qué partes del V-DOM han cambiado.

+Reconciliación: React actualiza el DOM real para reflejar los cambios
identificados en el paso de diferenciación. Este proceso se conoce como
“reconciliación”. React es muy eficiente en este proceso, actualizando solo las
partes del DOM que necesitan cambiar.

- Renderizado: Finalmente, el navegador renderiza los cambios en la pantalla.

El V-DOM permite a React minimizar las operaciones costosas de manipulación del
DOM y optimizar las actualizaciones de la interfaz de usuario, lo que resulta en un
rendimiento mejorado y una experiencia de usuario mas fluida.

Una vez aprendido esto, podemos pasar a detallar el ciclo de vida de un
componente.
Métodos del Ciclo de Vida

El ciclo de vida de un componente en React es una serie de etapas que atraviesa
desde su creación hasta su eliminación del DOM. Estas etapas nos permiten a los
desarrolladores controlar cémo se comporta un componente en diferentes puntos
de su existencia.

El ciclo de vida de un componente se puede dividir en tres fases principales:

1. Montaje (Mounting): Esta es la fase en la que el componente se esta creando e
insertando en el DOM. Comienza con el constructor del componente, seguido
por el método render, y finalmente el método componentDidMount. Durante
esta fase, se establecen las props y el estado inicial, se crea el V-DOM y se inserta en
el DOM real.

2. Actualizacion (Updating): Esta fase ocurre cuando cambian las props 0 el estado
de un componente, lo que provoca que el componente se vuelva a renderizar. Los
métodos que se ejecutan durante esta fase incluyen shouldComponentUpdate,
render y componentDidUpdate. React compara el nuevo V-DOM con el antiguo
y realiza las actualizaciones necesarias en el DOM real.

3. Desmontaje (Unmounting): Esta es la fase final del ciclo de vida de un
componente, cuando el componente se elimina del DOM. El método que se
ejecuta durante esta fase es componentWil1Unmount. Aqui es donde se realiza
la limpieza, como cancelar solicitudes de red, invalidar temporizadores o eliminar

suscripciones.

Mounting Updlosting
vo
Lila see ste) trained H
y yy wv :

YY III ) :
2

‘Métodos del ciclo de vida de un componente

Ademas de estas tres fases, hay una fase adicional llamada “Error Handling” que
se utiliza para manejar cualquier error que ocurra durante el renderizado, en un
método del ciclo de vida, o en el constructor de un componente hijo. Los métodos
que se ejecutan durante esta fase son static getDerivedStateFromError y
componentDidCatch.

Cada uno de estos métodos del ciclo de vida ofrece un “gancho” que podemos
utilizar para controlar lo que sucede antes, durante y después de que un
componente se renderice en el DOM. Esto proporciona un gran control sobre la
légica de la app y permite optimizaciones de rendimiento, como evitar
renderizados innecesarios.
Todos estos métodos pueden utilizarse en los componentes de tipo Clase. En los
componentes de tipo función no es posible, pero silo es acceder a estos “momentos”

utilizando hooks como useEf fect que veremos en el siguiente apartado.

Montaje

El montaje es la fase en la que el componente se esta creando e insertando en el
DOM. Este proceso se realiza en tres pasos:

1. Constructor: Aqui es donde se inicializa el estado del componente y se enlazan
los métodos del evento.

1 constructor(props) {

2 super(props) ;

3 this.state = { counter: 0 };

4  this.handleClick = this.handleClick.bind(this) ;

1. render: Este método devuelve el JSX que se renderizara en el DOM como HTML

1 render() {
2 return (

3 <button onClick={this.handleClick}>
4 Clicked {this.state.counter} times
5 </button>

6 YS

2}

1. componentDidMount: Este método se ejecuta después de que el componente
se haya renderizado en el DOM. Es un buen lugar para realizar solicitudes de red
(lamadas a APIs externas por ejemplo) o establecer cualquier suscripción a un
evento.

1 componentDidMount() {
2 console.log('Component mounted');

Actualiza

Laactualización ocurre cuando cambia el estado o las props de un componente. Esto
desencadena una serie de métodos de ciclo de vida:

+ 1. shouldComponentUpdate: Este método decide si el componente necesita

ser renderizado de nuevo. Devuelve un valor booleano.

1 shouldComponentUpdate(nextProps, nextState) {
2  veturn nextState.counter !== this.state.counter;
3}

+ 2. render: Al igual que en la fase de montaje, este método devuelve el JSX que
se renderizara.

+ 3.componentDidUpdate: Este método se ejecuta después de que el
componente se haya actualizado en el DOM. Es un buen lugar para realizar
operaciones entrada/salida y llamadas a servicios externos, basadas en el
cambio de props o estado.
1 componentDidUpdate(prevProps, prevState) {
2 if (prevState.counter !== this.state.counter) {

3 console.log('Counter updated’);

Desmontaje

El desmontaje es la fase final del ciclo de vida de un componente, cuando el
componente se elimina del DOM. En esta etapa es donde se realiza la limpieza de

eventos, manejadores, timeouts,...

+ 1. componentWillUnmount: Este método se ejecuta justo antes de que el
componente se desmonte y se destruya. Es un buen lugar para realizar la
limpieza necesaria, como invalidar temporizadores o cancelar solicitudes
de red.

componentWillUnmount() {
2 console.log('Component will unmount');

Como he mencionado, estos métodos solo pueden usarse en componentes de clase,
ahora pasamos a la versión mas actual de React, que es acceder a estos momentos
del ciclo de vida utilizando los llamados Hooks.
React Hooks

Los Hooks son una adición relativamente nueva a React. Nos permite usar el estado
y otras caracteristicas de React en componentes funcionales, en lugar de tener que
convertirlos en clases.

Los Hooks representan una evolución en la forma en que se manejan los
componentes y el estado en React, y han sido ampliamente adoptados por la
comunidad de dev debido a las ventajas que ofrecen.

Motivaciones para los Hooks

Antes de la introducción de los Hooks, los componentes funcionales en React
eran bastante limitados en comparación con los componentes de clase. No podian
manejar su propio estado ni utilizar caracteristicas como el ciclo de vida del
componente. Esto nos llevé a utilizar componentes de clase para casos mas
complejos, lo que a su vez introdujo una serie de problemas:

+ Complejidad de las clases: Las clases en JS pueden ser dificiles de
entender y manejar para los desarrolladores, especialmente para aquellos que
vienen de lenguajes que no utilizan el modelo de clases basado en prototipos de
JS.

+ Reutilización de légica de estado: Antes de los Hooks, la reutilización de la
légica de estado entre componentes implicaba patrones de alto orden (HOCs)
y render props, que podian resultar en arboles de componentes anidados y
dificiles de seguir.

-Componentes gigantes: A menudo, los componentes de clase se volvian
demasiado grandes, ya que la ldgica relacionada se agrupaba en métodos del
ciclo de vida, en lugar de dividirse en funciones mas pequeiias basadas en qué
piezas estan relacionadas entre si.

Los Hooks fueron introducidos para abordar estos problemas y hacer que el
dev en React sea mas sencillo y eficiente.

Updlacting
useStateO, useRe }
am eS)

useCallback®
:
{ React actualiza el BOM y las Refs
Y
( wsekfRectO, useLayoutefPect© 7}
if Cleanup Effect |
1 J

Hooks y Ciclo de vida del componente
Ventajas de los Hooks

Los Hooks ofrecen varias ventajas sobre los componentes de clase:

+ Simplicidad: Los Hooks permiten trabajar con el estado y otras caracteristicas
de React sin tener que entender la complejidad de las clases en JS. Esto
hace que el cédigo sea mas facil de leer y escribir.

-Reutilización de légica de estado: Los Hooks permiten extraer la légica
de estado de un componente, de modo que pueda ser probada de forma
independiente y reutilizada. Los Hooks personalizados ofrecen la posibilidad de
compartir légica de estado entre multiples componentes.

+ Separación de preocupaciones: A diferencia de los métodos del ciclo de vida
en los componentes de clase, que agrupan diferentes tipos de légica (datos de
busqueda, configuracion de suscripciones, etc.) en bloques de cddigo, los Hooks
permiten separar la légica basada en el tipo de operación que se esta realizando,
lo que lleva a un cddigo mas limpio y facil de seguir y mantener.

-Optimizacion del rendimiento: Algunos Hooks, como useMemo y
useCallback, permiten optimizar el rendimiento al evitar operaciones
costosas o renderizados innecesarios.

Ahora que hemos cubierto las motivaciones y ventajas de los Hooks, vamos a
profundizar en algunos de los mas comunes.

Hooks mas comunes

Estos son varios de los Hooks mas utilizados en React. Hay muchos mas, y tambión
el equipo de dev de React va incorporando mas con las nuevas versiones.

useState

El Hook useState es uno de los Hooks mas utilizados en React. Permite afiadir
estado local alos componentes funcionales de una manera muy sencilla y directa.

La sintaxis basica de useState es la siguiente:

1 const [state, setState] = useState(initialState) ;

Aqui, useState es una función que acepta un Unico argumento, que es el estado
inicial. Devuelve un array con dos elementos: el valor actual del estado y una
función para actualizar ese estado.

Aqui vemos el ejemplo més basico de cémo se utiliza useState:

1 import { useState } from ‘react’;

2

3 function Counter() {

4 const [count, setCount] = useState(0);

6 return (

<div>
<p>You clicked {count} times</p>

9 <button onClick={() => setCount(count + 1)}>

10 Click me

14 </button>

12 </div>

ODS
En este ejemplo, useState inicializa count en 0. Cuando se hace clic en el botón,
se llama a setCount con el nuevo valor de count.

useState permite diferentes formas de inicializar el estado. Como hemos visto
en el ejemplo anterior, puedes pasar un valor directamente como argumento a
useState. Sin embargo, si la inicialización del estado requiere algun cdlculo
costoso, puedes pasar una función a useState. Esta función se ejecutara sdlo en el
primer renderizado.

i const [state, setState] = useState(() => {
2 const initialState = someExpensiveComputation(props) ;
3 return initialState;

a})5

El valor de inicializacin del estado no tiene porque ser un tipo tinico como un string
o un number. Puede ser un objeto con varias propiedades, como por ejemplo los
diferentes campos de un formulario:

1 import { useState } from ‘react’;

2

3 function Form() {

4 const [form, setForm] = useState({ name: '', age: '' });

6 const handleChange = (e) => {

7 setForm({
8 ...form,
9 [e.target.name]: e.target.value

10 y5

12

13 «return (

<div>

15 <input name="name" value={form.name}
onChange={handleChange\
16 } placeholder="Name" />
17 <input
onChange={handleChange} \

18 placeholder="Age" />

name="age" value={form. age}

En este ejemplo, useState se utiliza para manejar el estado de un formulario.
Cuando el usuario escribe en los campos de entrada, la función handleChange se
llama para actualizar el estado del formulario.

Es importante fijarse que useState no fusiona automaticamente el objeto antiguo
y elnuevo como lo hacia this . setStateen un componente de clase. Por lo tanto,
es necesario hacerlo manualmente utilizando el operador de propagación o spread

operator (...),como hemos hechoen . . . form.

useEffect

El Hook useEffect permite realizar efectos secundarios en los componentes
funcionales. Puedes pensar en useEffect como una combinacidn de los métodos
componentDidMount, componentDidUpdate, y componentWil1Unmount de
las clases de React que vimos antes.
La sintaxis basica de useEffect es la siguiente:

1 useEffect(() => {
2 // Efecto secundario
3}, [dependencias]) ;

El primer argumento de useEffect es una función que contiene el cddigo del
efecto secundario. Este cédigo se ejecutara después de que se haya completado el
renderizado.

El segundo argumento es un array de dependencias. React rastreard las
dependencias y solo ejecutar el efecto secundario si una de las dependencias ha
cambiado desde el ultimo renderizado. Si el array de dependencias esta vacio ([ ]),
el efecto secundario se ejecutara una vez después del primer renderizado, similar a
como hacia componentDidMount.

Veamos un ejemplo basico de cémo se utiliza useEffect:

1 import { useState, useEffect } from ‘react’;
2

3 function Counter() {

4 const [count, setCount] = useState(0);

6 useEffect(() => {
7 document.title = “You clicked ${count} times®;
6 3, [eount]);

10 «return (
11 <div>

12 <p>You clicked {count} times</p>

13 <button onClick={() => setCount(count + 1)}>
14 Click me

45 </button>

16 </div>

2 5

e}

En este ejemplo, useEf fect actualiza el titulo de la pagina web (el que aparece en
la pestaria del navegador) después de que React actualiza el DOM. Como count esta
en el array de dependencias, el efecto secundario se ejecutard cada vez que count
cambie.

1 import { useState, useEffect } from ‘react';
2

3 function App() {

4 const [data, setData] = useState(nul1);

6 useEffect(() => {

7 fetch('/api/data')

8 .then(response => response. json())

9 -then(data => setData(data));

so}, £0)

return (
<div>

14 {data ? “Data: ${data}~ ‘Loading...'}
45 </div>

v5

Eneste ejemplo, useEffect se utiliza para hacer una solicitud de red para obtener
algunos datos cuando el componente se monta. Como la URL de la API no cambia,
no necesitamos ejecutar el efecto secundario mas de una vez, por lo que el array de
dependencias esta vacio.

Es importante tener en cuenta que si omites el array de dependencias por completo,
el efecto secundario se ejecutaré después de cada renderizado, no solo después del
primero. Por lo tanto, si quieres que el efecto secundario se ejecute sdlo una vez,

debes proporcionar un array de dependencias vacio.

Aligual que los métodos del ciclo de vida de las clases de React permiten la limpieza
en componentWillUnmount, useEffect tambión permite la limpieza. Para
hacerlo, la función pasada a useEf fect puede devolver una función de limpieza.

1 useEffect(() => {
2 const subscription = props.source.subscribe();

4 peturn () => {

5 // Limpieza

6 subscription. unsubscribe () ;
7 45

s }, [props.source]);

En este ejemplo, useEffect se utiliza para suscribirse a una fuente de datos
cuando el componente se monta y desuscribirse cuando el componente se
desmonta. La función de limpieza se ejecutara cuando el componente se desmonte
y tambión antes de cada renderizado posterior (si props . source cambia).

useContext

El Hook useContext permite acceder al valor actual de un contexto de React sin
tener que envolver un componente en un componente Context . Consumer.

useContext acepta un objeto de contexto (el valor devuelto por
React.createContext) y devuelve el valor actual del contexto, como lo haria

Context.Consumer.

No te preocupes si esto te suena raro, mas adelante en el libro vamos a entrar mas
en profundidad en los contextos de React y la gestión de estados globales y mas
complejos. Pero es interesante ver en este apartado el hook que se utiliza con ésta
caracteristica para tenerlo ubicado correctamente.

La sintaxis basica de useContext es la siguiente:

1 const value = useContext (MyContext) ;
Aqui, useContext es una función que acepta un objeto de contexto y devuelve su
valor actual.

Veamos un ejemplo basico de cémo se utiliza useContext:

1 import React, { useContext } from ‘react’;
2 const ThemeContext = React.createContext('light');

4 function ThemedButton() {
5 const theme = useContext(ThemeContext) ;
6 return <button theme={theme}>I am styled by theme context! </
but\
? ton>;

8}

En este ejemplo, useContext se utiliza para acceder al valor actual del contexto
ThemeContext. El componente ThemedButton utilizara el valor del tema actual
para estilizar el botón.

Para proporcionar un valor al contexto, debes usar un componente
Context.Provider. useContext siempre devolvera el valor actual del
contexto mas cercano Context. Provider hacia arriba en el arbol. Si no hay
Context. Provider en el arbol de componentes, useContext devolvera el valor
por defecto que se pas6 a React.createContext.

1 import React, { useContext } from 'react';

2 const ThemeContext = React.createContext('light');
3

4 function ThemedButton() {

5 const theme = useContext(ThemeContext) ;

6 return <button theme={theme}>Tengo estilo por el theme
context! \

7 </button>;

8}

9

10 function App() {
return (
12 <ThemeContext. Provider value="dark">
13 <ThemedButton />

14 </ThemeContext. Provider>
i )S

En este ejemplo, para ilustrar como se combina el hook con la creación de
contextos, ThemeContext. Provider proporciona el valor “dark” al contexto.
ThemedButton, que esta dentro de ThemeContext. Provider, utilizara este
valor en lugar del valor por defecto “light”.

useContext es un Hook muy potente que simplifica el uso de los contextos
en React. Permite acceder a los valores de contexto sin tener que envolver los
componentes en Context . Consumer, lo que lleva a un cddigo mas limpio y facil
de seguir.

useRef

El Hook useRef devuelve un objeto mutable cuyo campo .current se inicializa
con el argumento pasado (initialValue). El objeto devuelto persistira durante

toda la vida del componente.

La sintaxis basica de useRef es la siguiente: Una función que acepta un valor
inicial y devuelve un objeto de referencia.

1 const refContainer = useRef(initialValue) ;

Veamos un ejemplo basico de cémo se utiliza useRef:
1 import React, { useRef } from ‘react’;
2

3 function TextInputWithFocusButton() {
4 const inputEl = useRef(null);

5

6 const onButtonClick = () => {

7 // ‘current’ apunta al campo de texto montado en el DOM
8 inputE1. current. focus() ;
2 45

a1 return (

12 <>
43 <input ref={inputE1} type="text" />

14 <button onClick={onButtonClick}>Focus the input</button>
45 </>

En este ejemplo, useRef se utiliza para almacenar una referencia al campo de
entrada. Cuando se hace clic en el botón, la función onButtonC lick se llama para
enfocar el campo de entrada.

Ademads de mantener referencias a los nodos del DOM, useRef tambión
puede utilizarse para almacenar variables de instancia. Esto es util cuando se

necesita compartir valores mutables entre multiples renderizados que no deben
desencadenar una actualización del componente.

1 import { useRef, useState, useEffect } from 'react';
2

3 function Timer() {

4 const intervalRef = useRef();

5 const [timer, setTimer] = useState(0);

6

7 useEffect(() => {

8 intervalRef.current = setInterval(() => {
9 setTimer((timer) => timer + 1);
10 }, 1000);

return () => {
clearInterval(intervalRef.current) ;

35

m3, 05
return (

<div>
18 Timer: {timer}
19 <button
20 onClick={() => clearInterval(intervalRef.current)}
21 >
22 Stop Timer
23 </button>
24 </div>

25 YG

26}

En este ejemplo, useRef se utiliza para almacenar el ID del intervalo. Esto permite
que el intervalo se limpie cuando el componente se desmonta y cuando se hace clic
en el botón “Stop Timer”.
useRef es un Hook muy ttil que permite mantener referencias a los nodos del
DOM y almacenar variables de instancia en los componentes funcionales de React.
Es utilizado mucho en formularios para mantener la referencia a los distintos
campos que lo componen y poder acceder a sus cambios.

useld

El Hook useId es un Hook de React para generar IDs tnicos que pueden ser pasados
a atributos de accesibilidad. Este Hook es especialmente util cuando se necesita
asignar un ID unico a un elemento en el DOM, como un campo de entrada o un
elemento de lista.

La sintaxis bdsica de useId es la siguiente: Una función que no acepta ningin
argumento y devuelve un ID unico asociado a esta llamada particular de useId en
este componente particular.

1 const id = useId();

Veamos un ejemplo basico de como se utiliza useId:

1 import { useId } from ‘react';

2

3 function PasswordField() {

4 const passwordHintId = useId();
5

6 return (

7 <->

8 <input type="password" —aria-

describedby={passwordHintId} />
9 <p id={passwordHintId}>
The password should contain at least 18 characters

</p>
12 </>

En este ejemplo, useId se utiliza para generar un ID unico para el parrafo que
describe el campo de entrada de la contrasefia. El ID generado se pasa al atributo
aria-describedby del campo de entrada y al atributo id del parrafo.

Si necesitas asignar IDs a varios elementos relacionados, puedes llamar a useId
para generar un prefijo compartido para ellos:

1 import { useId } from 'react';

2

3 export default function Form() {
4 const id = useId();

6 return (

7 <form>

8 <label htm1For={id + '-firstName'}>First Name:</label>
9 <input id={id + '-firstName'} type="text" />

10 <hr />

11 <label htmlFor={id + '-lastName'}>Last Name:</label>
12 <input id={id + '-lastName'} type="text" />

13 </form>

4 (5

15 }
En este ejemplo, useId se utiliza para generar un prefijo de ID compartido para los
campos de entrada del nombre y del apellido.

Si renderizas varias aplicaciones de React independientes en una sola pagina,
puedes pasar ident ifierPrefix como una opcióna tus llamadas createRoot
o hydrateRoot. Esto asegura que los IDs generados por las dos aplicaciones
diferentes nunca choquen, ya que cada identificador generado con useId
comenzar con el prefijo distinto que has especificado.

1 import { createRoot } from 'react-dom/client';

import App from './App.js';

const rooti = createRoot (document. getElementById('root1'), {
5  identifierPrefix: 'my-first-app-'

6 3)5

7 rooti.render(<App />);

9 const root2 = createRoot (document. getElementById('root2'), {
10 identifierPrefix: ‘my-second-app-'

11 3)5

12 root2.render(<App />);

En este ejemplo, createRoot se utiliza para renderizar dos aplicaciones de React
en la misma pagina con diferentes prefijos de ID.

Por favor, ten en cuenta que useId no debe ser utilizado para generar claves
en una lista. Las claves deben ser generadas a partir de tus datos.

useCallback

El Hook useCallback devuelve una versión memorizada de la función que solo
cambia si una de las dependencias ha cambiado. Es util cuando pasas callbacks a
componentes optimizados que dependen de la igualdad de referencia para evitar
renderizados innecesarios.

La sintaxis basica de useCallback es la siguiente:

1 const memoizedCallback = useCallback(
2 Of

3 // Función

a},

5 [dependencias],
65

Veamos un ejemplo basico de cémo se utiliza useCallback:

1 import { useState, useCallback } from ‘react';

2

3 function Counter() {

4 const [count, setCount] = useState(0);

6 const increment = useCallback(() => {
setCount(count + 1);

e 3}, [eount]);

10 «return (
11 <div>
12 <p>You clicked {count} times</p>

13 <button onClick={increment}>
14 Click me

45 </button>

16 </div>

aw DS

18 }

En este ejemplo, useCal1back se utiliza para memorizar la función increment.
Como count estd en el array de dependencias, increment cambiar cada vez que

count cambie.

useCallback es especialmente util en combinacion con React.memo.
React.memo es una función de orden superior que memoriza un componente,
pero solo se renderizar si las props han cambiado.

Sin embargo, si pasas una función de callback como prop a un componente
memorizado, ese componente se renderizara cada vez que se renderice el

componente padre, a menos que esa función de callback esté memorizada.

En el siguiente ejemplo, Button es un componente memorizado que sélo se
renderizara si sus props cambian. Sin useCallback, Button se renderizaria cada
vez que Counter se renderiza, porque increment seria una nueva función en
cada renderizado. Con useCallback, increment sdlo cambia cuando count

cambia, por lo que Button solo se renderiza cuando count cambia.

1 import React, { useState, useCallback } from 'react';
2

3 const Button = React.memo(({ onClick, children }) => {
4 console. log('Button rendered');
5  veturn <button onClick={onClick}>{children}</button>;

635

function Counter() {
const [count, setCount] = useState(0);

const increment = useCallback(() => {
12 setCount(count + 1);
}, [Leount]);

return (
16 <div>
7 <p>You clicked {count} times</p>
18 <Button onClick={increment}>
19 Click me
20 </Button>
21 </div>
22 (5
23}
useMemo

El Hook useMemo devuelve un valor memorizado. useMemo acepta dos
argumentos: una función y una lista de dependencias.

useMemo ejecutara la función y devolverd su resultado si la lista de dependencias
cambia. Sino cambia entre renderizados, useMemo devolvera el valor memorizado
del ultimo renderizado en lugar de ejecutar la función de nuevo.
La sintaxis basica de useMemo es la siguiente:

1 const memoizedValue = useMemo(() => computeExpensiveValue(a,
b), \
2[a, b]);

Veamos un ejemplo basico de cémo se utiliza useMemo:

1 import { useMemo } from ‘react’;

2

5 function MyComponent({ list }) {

4 const sortedList = useMemo(() => {
5 const sorted = [...list];

6 sorted. sort();

7 return sorted;

es }, [list]);

10 return (

11 <div>
12 {sortedList.map(item => (

13 <div key={item}>{item}</div>
14 3

45 </div>

16)

a7}

En este ejemplo, useMemo se utiliza para memorizar una lista ordenada. La lista se
ordena sdlo cuando cambia list. Si list no cambia entre renderizados, useMemo

devolvera la lista ordenada del ultimo renderizado en lugar de ordenar la lista de
nuevo.

useMemo es util cuando tienes funciones costosas que no quieres ejecutar en cada
renderizado. Al memorizar el resultado de la función, puedes evitar su ejecución en
cada renderizado y mejorar asi el rendimiento de tu app.

Por ejemplo:

1 import { useMemo } from ‘react’;
2

3 function MyComponent({ a, b }) {
4 const result = useMemo(() => {

5 let sum = 0;

6 for (let i = 0; i < 1000000000; i++) {
? sum += i;

8 }

9 return sum + a + b;

}, [a, b]);

42 veturn <div>{result}</div>;

En este ejemplo, useMemo se utiliza para memorizar el resultado de una función
costosa. La función se ejecuta sdlo cuando cambian a 0 b. Si a y b no cambian entre
renderizados, useMemo devolvera el resultado del ultimo renderizado en lugar de
ejecutar la función de nuevo.
Por favor, ten en cuenta que useMemo es una optimización, y no una
garantia. React puede decidir “olvidar” algunos valores memorizados para
liberar memoria. Usa useMemo como una sugerencia, no como una garantia
semantica. Esto significa que puedes usar useMemo para optimizar el
rendimiento, pero no debes confiar en él para la semantica.

éQué diferencias y similitudes hay entre useMemo y React ..memo?

useMemo y React..memo son dos técnicas de optimización en React que ayudan
a evitar renderizados innecesarios, pero se utilizan en diferentes contextos y para
diferentes propésitos.

1. useMemo

Es un Hook que se utiliza para memorizar el resultado de una función costosa, de
modo que el resultado se pueda reutilizar sin tener que volver a ejecutar la función
en cada renderizado. useMemo se utiliza dentro de un componente para evitar la
reevaluacion de partes costosas de la función de renderizado.

1 const memoizedValue = useMemo(() => computeExpensiveValue(a,
b), \
2a, b]);

2. React.memo

Es una función de orden superior que memoriza un componente, de modo que
si las props del componente no cambian, React reutilizara el resultado del ultimo
renderizado en lugar de volver a renderizar el componente.

const MyComponent = React.memo(function MyComponent (props) {
2 /* render using props */

3 3)5

¢Cuando usar uno u otro?

Deberias usar useMemo cuando tienes una función costosa en tu función de
renderizado que quieres evitar que se ejecute en cada renderizado.

Deberias usar React . memo cuando tienes un componente que se renderiza con las
mismas props repetidamente y quieres evitar que se vuelva a renderizar en cada
renderizado.

useReducer
El Hook useReducer es una alternativa a useState. Acepta un reducer de tipo

(state, action) => newState y devuelve el estado actual emparejado con

un método dispatch.

La sintaxis basica de useReducer es la siguiente: Una función que acepta un
reducer y un estado inicial. Devuelve el estado actual y una función dispatch

1 const [state, dispatch] = useReducer(reducer, initialState);

Veamos un ejemplo basico de cémo se utiliza useReducer:
1 import { useReducer } from 'react';
2

3 const initialState = {count: 0};

4

5 function reducer(state, action) {
6 switch (action.type) {

7 case ‘increment’:

8 return {count: state.count + 1};

9 case ‘decrement’:

10 return {count: state.count - 1};
a1 default:

42 throw new Error();

13 CU}

a4}

16 function Counter() {

17 const [state, dispatch] = useReducer(reducer, initialState) ;
18 return (

19 <->

20 Count: {state.count}

24 <button onClick={() => dispatch({type: ‘decrement '})}>-
</bu\

22 tton>

23 <button onClick={() => dispatch({type: ‘increment'})}
>+</bu\

24 tton>

25 </>

27}

En este ejemplo, useReducer se utiliza para manejar el estado de un contador. El
estado inicial es {count: 0}, y el reducer maneja dos acciones: ‘increment’
y ‘decrement’. Cuando se hace clic en los botones, se despachan acciones para
incrementar o decrementar el contador.

useReducer es util cuando tienes un estado complejo que implica multiples
subvalores, o cuando el siguiente estado depende del anterior. useReducer
tambión permite optimizar el rendimiento para componentes que activan
actualizaciones profundas porque puedes pasar dispatch hacia abajo en lugar de
callbacks.

Ejemplo:

1 import { useReducer } from ‘react’;

2

3 const initialState = {count: 0, step: 1};
4

5 function reducer(state, action) {

6 switch (action.type) {

case ‘increment

8 return {count: state.count + state.step, step:
state. step};

9 case ‘decrement

10 return {count: state.count - state.step, step:

state.step};
case 'setStep':
return {count: state.count, step: action.step};
13 default:
14 throw new Error();
16 }

18 function Counter() {

19 const [state, dispatch] = useReducer(reducer, initialState) ;
20 return (

21 <->

22 Count: {state.count}

23 <button onClick={() => dispatch({type: ‘decrement! })}>-
</bu\

24 tton>

25 <button onClick={() => dispatch({type: ‘increment'})}
>+</bu\

26 tton>

27 Step: <input value={state.step} onChange={e =>
dispatch({ty\

28 pe: ‘setStep', step: Number(e.target.value)})} />

29 </>

30S

31}

En este ejemplo, useReducer se utiliza para manejar un estado mas complejo que
incluye un contador y un paso (step). Elestadoiniciales {count: 0, step: 1},
y el reducer mangja tres acciones: ‘increment’, ‘decrement’, y ‘setStep’. Cuando
se hace clic en los botones, se despachan acciones para incrementar o decrementar
el contador. Cuando se cambia el campo de entrada, se despacha una acción para
establecer el paso.
Conclusión

En este capitulo, hemos explorado en profundidad el ciclo de vida de los
componentos en React y cémo los Hooks nos permiten interactuar con él. Hemos
aprendido que los Hooks son funciones que nos permiten “enganchar” el estado de
React y el ciclo de vida de los componentos desde funciones en lugar de clases.
Hemos explorado varios Hooks incorporados en React, incluyendo useState,
useEffect, useContext, useCallback, useMemo, useRef, useId, y
useReducer, y hemos visto cémo cada uno de ellos puede ser utilizado para
manejar diferentes aspectos del estado y el ciclo de vida de los componentes.

Los Hooks son una parte muy importante y flexible del React moderno que nos
permite escribir componentes mas limpios y reutilizables sin la necesidad de clases.

Sin embargo, es importante recordar que los Hooks son sdlo herramientas, y como
todas las herramientas, deben ser utilizadas con cuidado y entendimiento. No
todos los problemas requieren Hooks, y no todos los componentes los necesitan.
Como siempre, la clave para escribir buen cédigo en React es entender las
necesidades de tu app y utilizar las herramientas adecuadas para el trabajo.

En el proximo capitulo, cambiaremos de enfoque y nos adentraremos en el mundo
del estado global y su gestión en React. Exploraremos cémo podemos manejar
el estado que necesita ser compartido entre multiples componentes, o incluso
entre toda la app. Veremos diferentes enfoques y técnicas, desde el uso del
Contexto de React hasta bibliotecas de gestion de estado mas sofisticadas.
Referencias

- Banks, A., y Porcello, E. (2020). Learning React: Functional Web Development
with React and Redux. O’Reilly Media.

+ Stefanov, S. (2016). React: Up & Running: Building Web Applications. O'Reilly
Media.

+ Accomazzo, A., Murray, N., y Lerner, A. (2017). Fullstack React: The Complete
Guide to ReactJS and Friends. Fullstack.io.

«Larsen, J. (2020). React Hooks in Action. Manning Publications.

+ FB Inc. (2023). Built-in React Hooks. https://react.dev/reference/react

+ Dodds, K. C. (2023). Epic React. https://epicreact.dev

+ Bos, W. (2023). React for Beginners. https://reactforbeginners.com

Capitulo 4: Gestidn de estados globales
Introducción

En el dev de aplicaciones web modernas, uno de los desaffos mas comunes
es la gestidn del estado. El estado de una app se refiere a los datos
que se mantienen y cambian a lo largo del tiempo y que pueden afectar el
comportamiento y la representación de la app. En una app React, el
estado puede existir a nivel de componente individual, pero tambión puede existir
a nivel global, siendo accesible y modificable por cualquier componente en la
app.

El estado global de una app es un concepto importante en React. Imagina de
nuevo una app como un arbol, donde cada componente es un nodo. Algunos
nodos (componentes) pueden necesitar compartir información entre ellos. Esta
información compartida es lo que llamamos estado global.

Por ejemplo, en una app de comercio electrónico, el carrito de compras puede
ser considerado como un estado global, ya que muchos componentes diferentes,
como la pagina de detalles del producto, la barra de navegación y la pagina de pago,
pueden necesitar acceder y modificar el carrito de compras. Otro ejemplo podria ser
el theme que se muestra en la UI (modo “claro”, modo “oscuro’,...)

La gestion del estado global se refiere a cémo se organiza, almacena y manipula este
estado global. Una gestión adecuada del estado global puede hacer que tu aplicacion
sea mas predecible, facil de entender y de mantener. Sin embargo, una mala gestion
del estado puede llevar a errores dificiles de rastrear y a un cédigo complejo y dificil
de manejar.

En React, hay varias formas de manejar el estado global. Algunas de las mas
populares incluyen la Context API y Redux, que seran los temas principales de este
capitulo, Ambas ofrecen formas de compartir y manipular el estado global, pero
cada una tiene sus propias ventajas y desventajas, y puede ser mas adecuada para
diferentes tipos de aplicaciones.

Antes de adentrarnos en estas soluciones, es importante tener una sdlida
comprensión de los conceptos basicos de JS y React. Si necesitas repasar
estos conceptos, te invito a que consultes mi libro anterior, Aprendiendo JS,
donde explico estos temas en detalle.

Ahora, vamos a por el fascinante (y complejo) mundo de la gestión del estado global
en React.
Context API

La Context API es una caracteristica incorporada en React que permite compartir
valores entre componentes sin tener que pasar props explicitamente a través de
cada nivel del arbol de componentes.

Esto es bastante util para compartir datos que pueden considerarse “globales” para
un arbol de componentes, como el usuario autenticado actual, el tema preferido, o
lainformación del carrito de compras en una app de comercio electrónico.

Diferencias entre una app con y sin Context API
Creando un contexto

Para empezar a usar la Context API, primero necesitamos crear un contexto. Esto se
hace utilizando React. createContext (). Aqui tienes un ejemplo:

1 const MyContext = React.createContext (defaultValue) ;

El argumento defaultValue es el valor que se utilizara si el contexto no esta
envuelto en un Provider. Es opcional y normalmente se deja vacio.

Context.Provider

Una vez que hemos creado un Context, podemos usar el componente
Context. Provider para envolver partes de nuestro arbol de componentes que
necesiten acceso a los valores del Contexto. El componente Context. Provider
acepta una prop value, que es el valor actual del contexto.

1 <MyContext.Provider value={/* algun valor */}>
2  {/* children */}
3 </MyContext.. Provider>

Todos los componentes hijos del Context . Provider tendran acceso al valor del

contexto.
Esto normalmente lo tendras que envolver en el componente raiz de tu app,
o en aquella parte de tu app dónde tenga sentido tener acceso a la informacion que

guardes en el contexto.

Context.Consumer

Dentro de los componentes hijos del Context.Provider, podemos usar el
componente Context.Consumer para acceder al valor del contexto. Aqui hay un

ejemplo de como se hace:

1 <MyContext.Consumer>
2 {value => /* renderiza algo basado en el valor del contexto
“/}

3 </MyContext.Consumer>

Hook useContext

Ya lo introdujimos en los capitulos anteriores, a partir de React version 16.8,
tambión podemos usar el Hook useContext para acceder al valor del contexto.

Esto puede hacer que nuestro cédigo sea mas limpio y facil de entender.

Ya lo vimos antes, pero te vuelvo a compartir un ejemplo de como se usa
useContext:

1 const value = useContext (MyContext) ;

Ejemplo practico

Vamos a ver un ejemplo practico de cémo se puede usar la Context API para
compartir el estado global. Imagina que estamos construyendo una app de
comercio electrónico (tipica tienda online) y queremos compartir la informacion

del carrito de compras entre varios componentes.

Primero, creamos un Context para el carrito de compras:

1 const CartContext = React.createContext();

Luego, en nuestro componente principal, utilizamos el CartContext. Provider
para compartir el estado del carrito de compras:

1 function App() {

2 const [cart, setCart] = useState([]);

3

4 return (

5 <CartContext.Provider value={{ cart, setCart }}>
6 {/* otros componentes */}

7 </CartContext. Provider>

8)

Dentro de otros componentes, podemos usar CartContext.Consumer o
useContext para acceder al estado del carrito de compras:
1 function Cart() {
2 const { cart } = useContext(CartContext) ;

3

4 return (

5 <div>
6 {eart.map(item => (

7 <div key={item. id}>{item.name}</div>
8 3

9 </div>

10 DS

11}

Como puedes ver, la Context API proporciona una forma flexible de compartir el
estado global en una app React. Sin embargo, tambión tiene sus limitaciones.

Por ejemplo, puede ser menos eficiente para grandes aplicaciones con muchos
cambios de estado, y puede ser mas dificil de manejar para estados complejos o
légicas de negocio. Ademas, el uso excesivo de la Context API puede hacer que
el cédigo sea més dificil de entender y mantener, ya que el estado se comparte
implicitamente a través del arbol de componentes.

A pesar de estas limitaciones, la Context API sigue siendo una buena opción para
muchos casos de uso, especialmente cuando se trata de compartir datos que no
cambian con frecuencia o que no requieren ldgicas complejas, como el usuario
autenticado actual o el tema preferido.

Creando un Custom Hook para el Contexto

Los custom hooks son una potente caracteristica de React que nos permite extraer
légica de los componentes para reutilizarla en diferentes partes de nuestra
app. Podemos crear un custom hook para nuestro contexto, lo que nos
permitira acceder al valor del contexto y a las funciones asociadas a este de una
manera mas limpia y reutilizable.

Imaginemos que estamos construyendo una app que permite a los usuarios
cambiar el tema entre claro y oscuro. Podriamos tener un ThemeContext
que almacene el tema actual y una función para cambiarlo. Aqui tienes como
podriamos definirlo:

1 const ThemeContext = React.createContext();

2

3 function ThemeProvider({ children }) {

4 const [theme, setTheme] = React.useState('light');

6 const toggleTheme = () => {
7 setTheme(prevTheme => prevTheme =

‘light' ? ‘dark'

so
10
return (
12 <ThemeContext.Provider value={{ theme, toggleTheme }}>
13 {children}

</ThemeContext . Provider>

v5
En este cédigo, ThemeProvider es un componente que utiliza el
ThemeContext.Provider para compartir el estado del tema y la función

toggleTheme con sus componentes hijos.

Ahora, podriamos crear un custom hook llamado useTheme que nos permita

acceder a este contexto de una manera mas sencilla:

1 function useTheme() {
2 const context = React.useContext (ThemeContext) ;
3 if (!context) {

4 throw new Error('useTheme must be used within a
ThemeProvider\

5 ')5

« 3}

7 return context;
8}

Este custom hook hace uso del hook useContext para acceder al ThemeContext.
Si intentamos usar este hook fuera de un ThemeProvider, lanzara un error, lo que
nos ayuda a evitar errores dificiles de rastrear.

Ahora, en cualquier parte de nuestra app, podemos usar el hook useTheme
para acceder al tema actual y a la función toggleTheme, sin tener que importar
ThemeContext o usar ThemeContext. Consumer:

1 function ThemedButton() {
2 const { theme, toggleTheme } = useTheme();
5 return (

4 <button

5 style={{ backgroundColor: theme ‘light’ ? '#£ff'
"#00\
60° 3}
onClick={toggleTheme}
8 >
9 Toggle Theme
10 </button>
a5
a2}

Como puedes ver, el uso de custom hooks con la Context API puede hacer que
nuestro cédigo sea mas limpio, mas facil de entender y mis reutilizable. Nos
permite encapsular la ldgica de acceso al contexto en un solo lugar, lo que facilita el
mantenimiento y las pruebas de nuestro cédigo.

En el siguiente apartado, exploraremos otra solución popular para la gestidn del
estado global en React: Redux. Esta herramienta puede ser un poco mas compleja
de entender y usar que la Context API, pero ofrece mas control y puede ser mas
eficiente para grandes aplicaciones con muchos cambios de estado.
Redux: Introduccion y principios basicos

Redux es una biblioteca de JS para la gestión del estado de las aplicaciones.
Aunque se utiliza comtinmente con React, Redux es agnéstico del framework y
puede utilizarse con cualquier biblioteca 0 framework de JS. Redux se basa
en los principios del flujo de datos unidireccional y la inmutabilidad del estado, lo
que puede hacer que las aplicaciones sean mas predecibles y faciles de entender.
FB, en su momento, lo llamé “Flux Pattern”.

>) )
( Action Rr Dispatcher _— Store nf View 4

Patrón Flux

Principios basicos de Redux

Redux se basa en tres principios basicos:

1. El estado de toda tu app se almacena en un Arbol de objetos dentro de
un unico store. Esto hace que sea mas facil de depurar y de inspeccionar, ya que
puedes ver todo el estado de tu aplicacion en un solo lugar.

2. El estado es de solo lectura. La unica forma de cambiar el estado es emitiendo
una acción, que es un objeto que describe qué sucedié. Esto asegura que ni los

componentes ni las llamadas a la API pueden modificar el estado directamente,
lo que puede hacer que tu app sea mas predecible y facil de entender.

3. Los cambios se realizan con funciones puras. Para especificar como el estado
del Arbol se transforma por las acciones, se utilizan reducers, que son funciones

puras que toman el estado anterior y una accion, y devuelven un nuevo estado.
Store

El store es el objeto que retine el estado de la app, los reducers y las acciones.
Puedes pensar en el store como un contenedor del estado de tu app. Redux
proporciona una función createStore para crear el store. Aqui tienes un ejemplo
de cémo se hace esto:

import { createStore } from

‘redux';

2 import rootReducer from './reducers'

3
4 const store = createStore(rootReducer) ;

En este ejemplo, rootReducer es una combinación de diferentes reducers, que se
explicard mas adelante.

Actions

Las acciones son objetos de JS que representan un cambio en el estado de
la aplicacion. Las acciones deben tener una propiedad type que indique el tipo de
accion a realizar. Aqui hay un ejemplo de una acción:
1 const action = {
type: 'ADD_TODO',
3 payload: {

4 id: 4,

5 title: 'Aprender Redux',
6 completed: false

> 3

835

En este ejemplo, la acción representa el afiadido de una nueva tarea.

Reducers

Los reducers son funciones que toman el estado actual y una acción, y devuelven un
nuevo estado. Los reducers deben ser funciones puras, lo que significa que no deben
modificar el estado actual, sino que deben devolver un nuevo objeto de estado. Por
ejemplo:

1 function todosReducer(state = [], action) {
2 switch (action.type) {

3 case 'ADD_TODO':
4 return [...state, action.payload];
5 default:

6 return state;

7 3

En este ejemplo, el reducer todosReducer maneja la acción ADD_TODO afiadiendo
la tarea del payload de la acción al estado actual.

Ejemplo practico

Vamos a ver un ejemplo practico de cémo se puede usar Redux para gestionar el
estado global de una app. Imagina que estamos construyendo una app
de lista de tareas. Vamos a reutilizar el cddigo de los ejemplos vistos arriba.

Podriamos tener un store que almacene la lista de tareas, una acción para afiadir

una nueva tarea, y un reducer para manejar esta acción.

Primero, definamos la acción para afiadir una nueva tarea. En Redux, es comin

definir funciones Ilamadas “action creators” que crean las acciones por nosotros:

1 let nextTodoId = 0;

2

3 function addTodo(text) {
4 return {

5 type: 'ADD_TODO',
6 payload: {

id: nextTodold++,
8 text
9 }
105
1}
En este cédigo, addTodo es un action creator que crea una acción con el tipo
ADD_TODO y el texto de la tarea.

A continuación, definamos el reducer para manejar esta acción. En este caso,
nuestro estado ser un array de tareas, y cada tarea sera un objeto con idy text:

Podemos usar el mismo cédigo del ejemplo del apartado anterior:

1 function todosReducer(state = [], action) {
2 switch (action.type) {

3 case 'ADD_TODO':
4 return [...state, action.payload];
5 default:

6 return state;

2 }

a}

Finalmente, podemos crear el store de Redux y usarlo para manejar el estado de
nuestra app:

1 import { createStore } from 'redux';

2

5 const store = createStore(todosReducer) ;

4

5 // Muestra por consola el estado inicial

© console. log(store.getState());

8 // Cada vez que el estado cambia, lo muestra en consola
9 store.subscribe(() => console. log(store.getState()));

10
11 // Despacha algunas acciones

12 store.dispatch(addTodo('Aprender React'));
13 store.dispatch(addTodo('Aprender Redux'));

En este cédigo, creamos el store de Redux con todosReducer, registramos un
listener que se ejecuta cada vez que el estado cambia, y despachamos algunas
acciones para afiadir tareas.

Aqui tienes el cddigo completo del ejemplo para que puedas practicar desde la
terminal, usando Node.js

1 // Importa Redux
2 const redux = require('redux');

4 // Action creator
5 let nextTodoId = 0;
6 function addTodo(text) {

? return {

8 type: 'ADD_TODO',

9 payload: {
id: nextTodoId++,
text

12 }

34S

a}

16 // Reducer
const initialstate = [];
is function todosReducer(state = initialState, action) {
19 switch (action.type) {
20 case 'ADD_TODO':

21 return [...state, action.payload];
22 default:

23 return state;

on

as}

27 // Crea el store
28 const store = redux. createStore(todosReducer) ;

30 // Log el estado inicial
31 console. log(store.getState());

33 // A cada cambio de estado, se esribe en consola
34 store. subscribe(() => console. log(store.getState()));

36 // Dispath de las acciones
37 store.dispatch(addTodo('Aprender React'));
38 store.dispatch(addTodo('Aprender Redux'));

Este cédigo hace lo siguiente:

- Importa Redux.

+ Define un action creator para afiadir tareas.

+ Define un reducer para manejar las acciones de afiadir tareas.

+ Crea un store Redux con el reducer.

+ Registra un listener que se ejecuta cada vez que el estado cambia.

« Despacha algunas acciones para afiadir tareas.

Puedes ejecutar este cédigo en un entorno de Node.js después de instalar Redux con

npm install redux.

La salida que se mostraria en la terminal seria la siguiente:

0]
2[ { id: 0, text: ‘Aprender React’ } ]
3 [ { id: 0, text: 'Aprender React' }, { id: 1, text: 'Aprender
Red\

4ux' } ]

Esto es lo que sucede:

1. Cuando se crea el store, se imprime el estado inicial, que es un array vacio ([ ]).

2. Luego, se despacha la acción addTodo('Aprender React' ),queafiade una
nueva tarea al estado, El nuevo estado se imprimeyes:[ { id: 0, text:
'Aprender React' } ].

3. Después, se despacha la acción addTodo('Learn React’ ), que ajiade otra
tarea al estado. El nuevo estado se imprime yes:[ { id: 0, text:
‘Aprender React' }, { id: 1, text: 'Aprender Redux' } ].

Asi, puedes ver como el estado de la app cambia a medida que se despachan
las acciones.

Como puedes ver, Redux proporciona una forma estructurada y predecible de
manejar el estado global de una app. Sin embargo, tambión puede ser mas
complejo y verboso que otras soluciones como la Context API.
En el siguiente apartado, exploraremos cémo integrar Redux en una app
React y cémo puede ayudarnos a manejar el estado de una manera més eficiente y
escalable. Tambión veremos la version de Redux Toolkit que hace mas sencillo poder
utilizar Redux sin tanto cddigo.
Integraciédn de Redux en un proyecto de React

Ahora mostraré cémo integrar Redux en un proyecto de React desde cero.

Explicaremos cémo configurar el store de Redux, cémo conectar componentes de
React al store y cémo pueden los componentes interactuar con el estado a través de
acciones. En lugar de usar la biblioteca Redux tradicional, utilizaremos el proyecto
Redux Toolkit que simplifica mucho mas el cddigo.

Vamos a crear una app de carrito de compras simple utilizando React y
Redux.

Creación del proyecto

Primero, necesitamos crear un nuevo proyecto de React. Para ello, utilizaremos
Vite, como vimos en el inicio del segundo capitulo. Puedes instalar Vite
globalmente y crear un nuevo proyecto de React con los siguientes comandos:

1 $ npm install -g create-vite
2 $ create-vite my-app --template react

Luego, navega al directorio del proyecto:

1 $ cd my-app

Instalación de dependencias

Necesitaremos Redux para la gestión del estado y @reduxjs/toolkit para
simplificar la configuración de Redux. Instala estas dependencias con el siguiente
comando:

1 $ npm install redux @reduxjs/toolkit react-redux

Creación de archivos

Vamos a crear una estructura de archivos basica para nuestra app. Dentro del
directorio src, crea los siguientes archivos:

-srce/features/cart/cartSlice. js: Este archivo contendra nuestro slice
de Redux para el carrito de compras. Esto lo explicamos mas adelante.

-sre/features/cart/Cart.js: Este contendra
componente de carrito de compras.

+srce/App. js: Este archivo contendra nuestro componente principal de la
app.

archivo nuestro

Configuración de Redux

Primero, vamos a configurar nuestro slice de Redux para el carrito de compra. En
srce/features/cart/cartSlice. js, agrega el siguiente cddigo:

1 import { createSlice } from '@reduxjs/toolkit';

3 const initialState = [];
5 const cartSlice = createSlice({
6 mame: ‘cart’,

? initialstate,

8 reducers: {

9 addToCart: (state, action) => {

10 state.push(action. payload) ;

11 3,

12 removeFromCart: (state, action) => {

43 return state.filter(item => item.id
action. payload. id);

14 }

a}

16 })5

17

18 export const { addToCart, removeFromCart: } =

cartSlice.actions;
19
20 export default cartSlice.reducer;

En este cddigo, utilizamos createSlice de @reduxjs/toolkit paracrear un
slice de Redux para el carrito de compras.

Un slice incluye el reducer y las acciones, lo que simplifica la configuración de
Redux. Definimos dos acciones, addToCart y removeFromCart, que afiaden y

eliminan articulos del carrito, respectivamente.

Acontinuación, vamos a configurar el store de Redux. En sre/store. js, agregael
siguiente cédigo:

1 import { configureStore } from '@reduxjs/toolkit';

2 import cartReducer from './features/cart/cartSlice';
3

4 export default configureStore({

5 reducer: {

6 cart: cartReducer

? +}

8 3)5

En este cédigo, utilizamos configureStore de @reduxjs/toolkit para crear
el store de Redux. Pasamos nuestro cartReducer al store como un reducer.

Creacion de los componentes

Ahora, vamos a crear nuestro componente de carrito de compras. En src/
features/cart/Cart. js, agrega el siguiente cddigo:

1 import React from ‘react’;

2 import { useSelector, useDispatch } from ‘react-redux';
3 import { addToCart, removeFromCart } from './cartSlice';
5 function Cart() {

6 const cart = useSelector(state => state.cart);

7? const dispatch = useDispatch();

8

9 const handleAddToCart = item => {

10 dispatch(addToCart (item));

as

12
13
14
15
16
17
18
19
20
21
22
23

const handleRemoveFromCart = item => {

35

dispatch (removeFromCart (item) );

return (

>Elim\

<div>
<h2>Shopping Cart</h2>
{cart.map(item => (
<div key={item. id}>
<p>{item.name}</p>

<button onClick={() => handleRemoveFromCart (item) }

24 inar del carrito</button>

25
26
27
28
29
=>\
30
31
32
33
n\

34 ame:

35
36
37
38
39
40 }

5

</div>
3
<div>
<h2>Productos</h2>
{['Manzanas', 'Naranjas', 'Pld4tano'].map((item,

<div key={index}>
<p>{item}</p>
<button onClick={() => handleAddToCart({ id:

item })}>Afiadir al carrito</button>
</div>
3
</div>

</div>

index)

index,

at
42 export default Cart;

Eneste cédigo, utilizamos useSe lector para seleccionar el estado del carrito dela
tienda Redux, y useDispatch para despachar acciones.

Cuando el usuario hace clic en el botón “Add to cart”, despachamos la acción
addToCart con el articulo. Cuando el usuario hace clic en el botón “Afiadir al

carrito”, despachamos la acción removeFromCart con el articulo.

Finalmente, vamos a utilizar nuestro componente de carrito de compras en nuestro
componente principal de la app. En src/App.js, agrega el siguiente
cédigo:

1 import React from ‘react’;
2 import { Provider } from 'react-redux';

3 import store from './store';

4 import Cart from './features/cart/Cart';
6 function App() {

7 return (

8 <Provider store={store}>

9 <Cart />

10 </Provider>

14 export default App;
En este cédigo, utilizamos el componente Provider de react-redux para
proporcionar el store de Redux a nuestra app. Luego, utilizamos nuestro
componente Cart.

Ejecución y prueba de la aplicacion
Ahora, puedes ejecutar tu app con el siguiente comando:

1 $ npm run dev

Abre tu navegador y ve a http: //localhost: 5000 (0 el puerto donde se esté
ejecutando). Deberias ver tu app de carrito de compras en funcionamiento.

Este es un ejemplo basico de cémo puedes utilizar Redux en una app React.
A medida que tu app crece, puedes aiiadir mas slices a tu store para manejar
diferentes partes del estado de tu app.
Comparación de soluciones de manejo de estado

En el mundo de React, existen varias soluciones para manejar el estado global
de una app. En este capitulo, hemos explorado en detalle dos de las
mas populares: Context API y Redux. Sin embargo, existen otras alternativas que
tambión son dignas de consideración.

Acontinuación, haremos una breve comparación de estas soluciones.
Context API

La Context API es una solución incorporada en React que permite compartir estado
y funciones entre componentes sin necesidad de pasar props de forma manual a
través de la jerarquia de componentes.

Es facil de usar y no requiere la instalacin de librerias adicionales. Sin embargo,
puede ser menos eficiente para grandes aplicaciones con muchos cambios de
estado, y puede ser mas dificil de manejar para casos de uso mas complejos.

Redux

Redux es una libreria externa que proporciona un contenedor de estado predecible
para aplicaciones JS. Es muy poderoso y flexible, y tiene una gran
comunidad y ecosistema de middleware y extensiones.

Sin embargo, Redux puede ser excesivo para aplicaciones pequefias o sencillas, y su
API puede ser un poco complicada para los principiantes. Su versión Redux Toolkit

mejora esto y lo hace mas amigable.

Mobx

MobX es una libreria de gestión de estado que se centra en la programacion reactiva
funcional. Permite escribir c6digo minimalista y libre de boilerplate.

MobX es muy eficiente en cuanto a rendimiento y ofrece una gran libertad de
arquitectura, permitiendo manejar el estado de la app fuera de cualquier
framework de interfaz de usuario. Esto hace que tu cédigo sea desacoplado, portatil

y, sobre todo, facilmente testeable.

Jotai

jotai toma un enfoque atémico para la gestión del estado global de React.
Puedes construir el estado combinando “atomos” y los renders se optimizan
automaticamente basandose en la dependencia de los Atomos.

Esto resuelve el problema de re-renderizado extra del contexto de React y elimina la
necesidad de memoización. Jotai escala desde un simple reemplazo de useState hasta
una app TypeScript empresarial con requisitos complejos.

Zustand
Zustand es una solución de gestión de estado pequefia, répida y escalable. Zustand

tiene una API cémoda basada en hooks. No es boilerplate y no es “opinionado”, pero
tiene suficiente convención para ser explicito y parecido a Flux.
Aunque es sencillo, Zustand ha dedicado mucho tiempo a lidiar con problemas
comunes, como el temido problema del “zombie child”, la concurrencia de React, y la

pérdida de contexto entre renderizadores mixtos.
0 Mobx.

Conclusión

Jotai, por otro lado, ofrece un enfoque atémico que puede ser ttil para ciertos casos
La elección de la solución de manejo de estado depende en gran medida de las ge uso, En tiltima instancia, la mejor solución es la que mejor se adapta a tus
necesidades especificas de tu proyecto. Para aplicaciones pequefias 0 proyectos con —_recesidades y te resulta mas cémoda de usar

requisitos sencillos, la Context API o Zustand pueden ser suficientes.

Para aplicaciones mas grandes o complejas, es posible que desees considerar Redux
Referencias

+ Porcello, E., & Banks, A. (2020). Learning React: Modern Patterns for Developing
React Apps. O'Reilly Media.

+Porcello, E., & Banks, A. (2017). Learning React: Functional Web Development
with React and Redux. O'Reilly Media.

- Abramov, D., & Clark, M. (2016). Redux Documentation. https://redux.js.org/

+ FB. (2023). Passing Data Deeply with Context. https://react.dev/learn/
passing-data-deeply-with-context

+Michel Weststrate. (2020). MobX Documentation. https://mobx.js.org/
README.html

+ Daishi Kato. (2021). Jotai Documentation. https://jotai.org/

+ Poimandres. (2021). Zustand Documentation. https://docs.pmnd.rs/zustand

Capitulo 5: React Router y Navegacion
Introducción

En este capitulo, nos centraremos en un aspecto crucial de cualquier app web
moderna: La navegación entre diferentes pantallas, vistas o paginas dentro de un
mismo sitio web.

En particular, exploraremos cémo React Router puede ayudarnos a manejar la
navegacion en nuestras aplicaciones React.

Pero antes de sumergirse en React Router, es importante entender el contexto en
el que se utiliza. Especificamente, necesitamos entender la diferencia entre una
“aplicacion de pagina tinica” (SPA o Single Page Application) y una app de
“renderizado del lado del servidor” (SSR 0 Server-Side Rendering).

SPA vs SSR

Una SPA, 0 Single Page Application, es una app web que carga una sola
pagina HTML y luego actualiza dinamicamente esa pagina a medida que el usuario
interacttia con la app. En lugar de enviar una nueva solicitud al servidor cada
vez que el usuario navega a una nueva pagina, una SPA simplemente actualiza la
pagina actual en el navegador del usuario. Esto puede hacer que las SPAs sean mas
rapidas y proporcionar una experiencia de usuario mas fluida. Tambión se conoce
como client-side rendering (CSR 0 renderizado del lado del cliente).

Por otro lado, una app de renderizado del lado del Ssrvidor (SSR), como
su nombre indica, genera el contenido de la pagina en el servidor cada vez que
se solicita una nueva pagina. Esto puede ser beneficioso para el SEO, ya que los

motores de busqueda pueden rastrear el contenido de la pagina mas facilmente.
Sin embargo, puede resultar en tiempos de carga ms lentos y una experiencia de
usuario menos fluida en comparación con una SPA.

Enrutamiento en SPA vs SSR

El enrutamiento es el proceso de determinar cémo responder a una solicitud de
un cliente a una determinada ruta (0 URL). En una aplicacin SSR, cada vez que el
usuario navega a una nueva pagina, el servidor genera y devuelve una nueva pagina
HTML. En una SPA, sin embargo, el enrutamiento se maneja completamente en el
cliente. Cuando el usuario navega a una nueva pagina, la SPA simplemente actualiza
la pagina actual en lugar de solicitar una nueva pagina al servidor.

React Router es una biblioteca que nos permite manejar el enrutamiento en
nuestras aplicaciones React de una manera que es eficiente y facil de entender. En
los siguientes apartados, aprenderemos cémo instalar y configurar React Router,
como crear rutas y manejar el enrutamiento dinamico, y como navegar de forma

programatica entre paginas.

Es importante recordar que, aunque React Router es una herramienta muy util, no
es la unica opción para el enrutamiento en React. Al final de este capitulo, tambión
exploraremos algunas alternativas a React Router como Wouter.

Ahora que hemos establecido el contexto, estamos listos para sumergirnos en React
Router.
Instalación y configuración

Para comenzar a utilizar React Router, primero debemos instalarlo en nuestro
proyecto. React Router se distribuye a través de npm (Node Package Manager), por lo
que podemos instalarlo facilmente con elcomandonpm install.

Abre tu terminal y navega hasta el directorio de tu proyecto React. Luego, ejecuta el
siguiente comando:

1 $ npm install react-router-dom

Este comando instalara React Router y agregar4 una entrada en tu archivo
package. json, indicando que React Router es una dependencia de tu proyecto.

Una vez que hayas instalado React Router, puedes comenzar a usarlo en tu
app. Para hacerlo, necesitards importar los componentes que proporciona
React Router. Los més comunes son BrowserRouter, Routes, Route y Link.

Aqui tienes un ejemplo de cémo podrias configurar React Router en tu app:

1 import React from ‘react’;

2 import { BrowserRouter as Router, Routes, Route, Link } from
‘rea\

3 ct-router-dom';

5 function App() {

6 return (

? <Router>

8 <div>

9 <nav>
<ul>
<li>
<Link to="/">Home</Link>
3 </li>
14 <li>
<Link to="/about">About</Link>
</li>
<li>
<Link to="/users">Users</Link>
</li>
20 </ul>
21 </nav>
22 <Routes>
23 <Route path="/" exact component={Home} />
24 <Route path="/about" component={About} />
25 <Route path="/users" component={Users} />
</Routes>
</div>
28 </Router>
29 5
30 }

31
52 export default App;

En este ejemplo, BrowserRouter (alias Router) es un componente que envuelve
nuestra app y la dota de la funcionalidad de enrutamiento. Link es un
componente que nos permite crear enlaces a diferentes rutas en nuestra app,
y Route es un componente que nos permite definir las diferentes rutas de nuestra

app.
En el siguiente apartado, profundizaremos en cémo crear rutas y manejar el
enrutamiento dinamico con React Router.
Creacion de rutas y enrutado dinamico

Ahora que hemos instalado y configurado React Router, podemos comenzar a
definir rutas en nuestra app. Como vimos en el ejemplo anterior, utilizamos
el componente Route para definir una ruta. Cada Route tiene una prop path que
determina la URL de la ruta, y una prop component que determina el componente
que se renderizar4 cuando se visite esa ruta.

1 <Route path="/about" component={About} />

En este ejemplo, cuando un usuario visita la URL / about, React Router renderizara
el componente About.

Enrutamiendo dinamico

Hasta ahora, hemos estado definiendo rutas estaticas. Sin embargo, a menudo
necesitaremos definir rutas dindmicas, es decir, rutas que dependen de algun tipo
de parametro. Por ejemplo, podriamos tener una ruta para mostrar el perfil de un
usuario, y la URL de esa ruta podria depender del ID del usuario.

Para definir una ruta dinamica, podemos incluir un parametro en la prop path
de nuestro componente Route. Los pardmetros se definen con dos puntos (:)

seguidos del nombre del parametro.

1 <Route path="/users/:userId" component={UserProfile} />

En este ejemplo, :userId es un pardémetro. Cuando un usuario visita una URL
como “/users/123”, React Router renderizar4 el componente UserProfile, y el

valor del parametro userld sera “123”.

Dentro de nuestro componente UserProfile, podemos acceder al valor del
parametro userId utilizando el hook useParams que proporciona React Router.

1 import { useParams } from ‘react-router-dom';

3 function UserProfile() {

4 const { userId } = useParams();

5 // Ahora puedes usar el userId para cargar datos del usuario,
e\

6 te.

23

En el siguiente apartado, aprenderemos sobre la navegacion programatica, es decir,
cémo cambiar de ruta mediante cédigo en lugar de hacer clic en un enlace.

Navegación programatica

Hasta ahora, hemos estado navegando entre rutas utilizando el componente Link
que proporciona React Router. Sin embargo, a veces necesitaremos cambiar de
ruta programaticamente, es decir, mediante cédigo. Por ejemplo, podriamos querer

redirigir al usuario a una pagina diferente después de que envie un formulario.
React Router nos proporciona el hook useHistory para este propdsito.
useHistory nos da acceso al historial de navegación, que podemos usar para
navegar a diferentes rutas.

Aqui tienes un ejemplo de cémo podriamos usar useHistory para redirigir al
usuario a la ruta principal / después de enviar datos a través de un formulario:

1 import { useHistory } from 'react-router-dom';

3 function Form() {
4 const history = useHistory();

6 const handleSubmit = () => {
7 // Simula el envto del formutario

8 IT vee

9

10 // Redirige al usuario a la pagina de inicio
14 history.push('/');

12 5

14 return (

45 <form onSubmit={handleSubmit}>

16 {/* Campos del formulario */}

17 <button type="submit" >Enviar</button>
18 </form>

19 DS

Es importante tener en cuenta que history.push agrega una nueva entrada
al historial de navegación. Esto significa que si el usuario presiona el botón
de retroceso en su navegador, volver a la pagina del formulario. Si en cambio
quieres reemplazar la entrada actual en el historial de navegación (es decir, si
no quieres que el usuario pueda volver a la pagina del formulario), puedes usar
history.replace en lugar de history. push.

1 history.replace('/');
Novedades en React Router v6

El cambio principal en la versión 6 de React Router es que ahora se basa en
componentes y hooks, en lugar de utilizar la configuración de rutas como un objeto.
Esto permite un enrutamiento mds dinamico y flexible. Ademas, la History API del
DOM se utiliza para gestionar la pila de historial y actualizar la URL, lo que permite
una mejor integración con las caracteristicas nativas del navegador.

Aqui estd el ejemplo anterior actualizado a la versión 6 de React Router:

1 import * as React from ‘react';

2 import * as ReactDOM from ‘react-dom'

3 import { createBrowserRouter, RouterProvider, Route, Link }
from \

4 ‘react-router-dom';

5

6 function Home() {/* Componente Home */}

7

e function About() {/* Componente About */}
9

10 function Users() {/* Componente Users */}
11

12 const routes = [

a

14 path: "/",

15 element: <Home />,
16},

17 {

18 path: "/about",

30
34

element: <About />,

path: "/users",
element: <Users />,
3,
15

const router = createBrowserRouter (routes) ;

9 function App() {

return (
<RouterProvider router={router}>
<nav>
<ul>
<li>
<Link to="/">Home</Link>
</li>
<li>
<Link to="/about">About</Link>
</li>
<1i>
<Link to="/users">Users</Link>
</li>
</ul>
</nav>
</RouterProvider>
v5
ReactDOM. createRoot (document. getElementByTd('root')).render(<Ap
p\
50 />);

En este cédigo, primero importamos los componentes necesarios de react -
router-dom. Luego, definimos nuestros componentes de ejemplo para las rutas
(Home, About, Users).

Después, creamos un array de objetos de ruta, donde cada objeto tiene un path y
un element. El path es la ruta en la URL y el element es el componente que se

renderizara cuando se visite esa ruta.

Luego, creamos un router utilizando createBrowserRouter y pasamos
nuestras rutas como argumento.

Finalmente, en nuestro componente App, utilizamos RouterProvider para
proporcionar el router a nuestra app. Dentro de RouterProvider,
definimos nuestros enlaces utilizando el componente Link y nuestras rutas

utilizando el componente Route.

Este cambio a un enfoque basado en componentes y hooks hace que React Router
sea mas coherente con el resto de la biblioteca React y permite un enrutamiento
mis dinamico y flexible.

Si queremos utilizar rutas dinamicas, haremos uso de los loaders que incorporan
en la nueva version.

1 createBrowserRouter ([
2 ¢{
3 // Define una ruta que incluye un pardmetro de ruta

dindmico \

4 “userId*

5 path: "/users/:userId",

6  // La función ‘toader* se utiliza para cargar datos basados
e\

7 n los parémetros de ruta

8 loader: ({ params }) => {

9 // Aqut, ~params.userId* se refiere al ‘userId* en La
URL

10 // ~getUser> es una función hipotética que carga los
datos \

11 del usuario basado en el ‘userId*
return getUser(params.userId) ;

En este ejemplo, si visitas la URL /users/123, React Router v6 llamara a la
'123' } 3. Luego, la función
getUser se llama con 123 como argumento para cargar los datos del usuario

función loadercon{ params: { userId:

correspondiente.

Esto es util cuando necesitas cargar diferentes datos basados en la URL. Por
ejemplo, podrias tener una pagina de perfil de usuario que carga diferentes datos de
usuario basados en el ID de usuario en la URL.
Hasta aqui llega nuestra exploración de React Router. En el siguiente apartado,
veremos algunas alternativas a React Router.
Alternativas a React Router

Aunque React Router es una de las bibliotecas mas populares para el enrutamiento
en aplicaciones React, existen otras alternativas que podrian ser mas adecuadas
dependiendo de las necesidades especificas de tu proyecto. A continuación, te
presento tres de ellas: Wouter, React Navigation y Next Router.

Wouter

Wouter es una biblioteca de enrutamiento mas minimalista para React y Preact.
Su API es muy similar a la de React Router, pero con una diferencia clave: No
tiene dependencia del Context de React. Esto significa que Wouter es mAs ligero y
mis rapido que React Router, aunque puede que no tenga todas las caracteristicas
avanzadas que ofrece este ultimo.

Aqui tienes un ejemplo de cémo se ve el enrutamiento con Wouter:

1 import { Switch, Route } from "wouter";
2
3 function App() {

4 return (

5 <Switch>

6 <Route path="/" component={Home} />

7 <Route path="/about" component={About} />
8 </Switch>

2)

10 }

Y para el caso de rutas dinamicas seria algo asi:

1 import { Switch, Route } from "wouter";
2
3 function App() {
4 return (
5 <Switch>
6 <Route path="/users/:userId">
{(params) => <div>Hello, {params.userId}!</div>}
8 </Route>
9 </Switch>

React Navigation

React Navigation es una solución de enrutamiento para aplicaciones méviles
creadas con React Native. Aunque se sale del ambito de este libro, es importante
mencionarlo ya que es una de las soluciones mas populares para el enrutamiento en
aplicaciones méviles construidas con esta herramienta.

React Navigation proporciona una serie de navegadores incorporados que ofrecen
una experiencia fluida y lista para usar. Ademas, es completamente personalizable,
lo que significa que si sabes como escribir aplicaciones usando JS, puedes
personalizar cualquier parte de React Navigation.

Esto seria un ejemplo muy basico de React Navigation, utilizando dos screens:
1 import { NavigationContainer } from ‘@react-navigation/
native';
2 import { createNativeStackNavigator } from ‘@react-

navigation/nat\

3 ive-stack';

5 const Stack = createNativeStackNavigator();

6

7 function App() {

8 return (

9 <NavigationContainer>
10 <Stack.Navigator>

11 <Stack.Screen name="Home" component={HomeScreen} />
12 <Stack.Screen  name="Profile"
component={ProfileScreen} />

13 </Stack.Navigator>

14 </NavigationContainer>

15)

Next Router

Next Router es la solución de enrutamiento integrada en Next.js, un framework
popular para aplicaciones React con renderizado en el servidor (SSR).

Aligual que React Navigation, Next Router se sale del ambito de este libro, pero vale
la pena mencionarlo debido a su popularidad. Next Router se basa en el concepto
de “paginas”: cuando se agrega un archivo al directorio de paginas (pages), esta
automaticamente disponible como una ruta. Tambión soporta rutas dindmicas, lo
que te permite agregar parametros personalizados a tus URL.

Cada una de estas bibliotecas tiene sus propias ventajas y desventajas, y la elección
entre ellas dependera de las necesidades especificas de tu proyecto. Te recomiendo
que explores cada una de ellas para determinar cual es la mejor opción para ti.
Conclusión

En este capitulo, hemos explorado en profundidad el enrutamiento en React
utilizando React Router. Comenzamos con una introduccidn a las aplicaciones
de tinica pagina (SPA) y el renderizado del lado del servidor (SSR), y cémo
el enrutamiento funciona en cada una de ellas. Luego, nos adentramos en la
instalación y configuración de React Router, la creación de rutas estaticas y

dinamicas, y la navegación programatica.

Ademas, hemos explorado algunas alternativas a React Router, como Wouter,
React Navigation y Next Router, cada una con sus propias ventajas y desventajas.
Independientemente de la biblioteca que elijas para el enrutamiento en tu
app React, el objetivo es el mismo: proporcionar una experiencia de usuario

fluida y eficiente.

Esperamos que este capitulo te haya proporcionado una comprensión sdlida del
enrutamiento en React y cémo puedes utilizar React Router para manejar la
navegación en tus aplicaciones. Con estos conocimientos, estas bien equipado para
construir aplicaciones React mas complejas y robustas.

En el préximo capitulo, cambiaremos de marcha y nos centraremos en un
aspecto diferente pero igualmente importante de las aplicaciones React: los estilos.
Aprenderemos sobre las diferentes formas de ajiadir estilos a tu app React,
desde CSS en JS hasta médulos CSS y styled-components.
Referencias

- Banks, A., y Porcello, E. (2020). Learning React: Modern Patterns for Developing
React Apps. O'Reilly Media.

+Freeman, E., Robson, E., Nash, C. (2014). Head First HTML5 Programming:
Building Web Apps with JS. O'Reilly Media.

+ Sorhus, S. (2021). React Router: Declarative Routing for React.js. React Training.
https://reactrouter.com/

+ Molefrog. (2021). Wouter: A minimalist-friendly ~1KB routing for React and
Preact. GitHub. https://github.com/molefrog/wouter

+ Expo, sw Mansion, y Callstack. (2021). React Navigation: Routing
and navigation for your React Native apps. React Navigation. https://
reactnavigation.org/

+Vercel. (2021). Next.js Routing: The Pages Router. Nextjs. https://nextjs.org/
docs/pages/ building-your-application/routing

Capitulo 6: Estilos y disefio
Introducción

En este capitulo, exploraremos cémo React.js maneja los estilos y el diserio. React,
siendo una biblioteca de JS, ofrece varias formas de aplicar estilos CSS
a los componentes. Aunque JS y CSS son tecnologias distintas, React ha
encontrado formas de combinarlas de manera efectiva para proporcionar una

experiencia de dev mas fluida.
Formas de usar CSS en React

En el dev web tradicional, los estilos CSS se aplican a los elementos HTML a
través de hojas de estilo externas, etiquetas de estilo internas o atributos de estilo
en linea. Sin embargo, en React, tenemos mas opciones. Aqui estan las formas mas
comunes de aplicar estilos en React:

1.Estilos en linea: React permite aplicar estilos en linea (CSS inline) a los
componentes utilizando un objeto JS. Los nombres de las propiedades
CSS se convierten en camelCase en lugar de kebab-case (por ejemplo,
backgroundColor en lugar de background-color).

1 const styleObject = {
2 backgroundColor: ‘blue’,
3 color: ‘white’

ads

6 function MyComponent() {
2 return <div style={styleObject}>Hello, world! </div>;

2. Hojas de estilo CSS externas: Al igual que en el dev web tradicional,
puedes vincular una hoja de estilo CSS externa a tu componente React. Aqui se
aplicarian las reglas de cascada de CSS. Puedes importarlo en cualquier fichero,
incluso en un posible index. js, importar ahi todos ficheros CSS. Pero por
mantenibilidad es recomendable tenerlo lo mas cerca posible del componente.

1 // Fichero: MyComponent. jsx

2 import './MyComponent.css';
4 function MyComponent() {
5 return <div className="my-component">Hello, world! </div>;

6}

3. CSS Modules: Los médulos CSS son una extensión de la idea de hojas de estilo CSS.
externas. Permiten que los estilos se apliquen solo al componente que los importa,
evitando asi el problema de la colisión de nombres de clases.

1 import styles from './MyComponent.module.css';

3 function MyComponent() {
4 return <div className={styles.myComponent}>Hello, world!</
div>;

5}

4. Styled-components y CSS en JS: Las bibliotecas como styled-components
permiten definir componentes con estilos adjuntos utilizando JS. Este
enfoque combina los estilos y el componente en una sola entidad, lo que puede
hacer que el cédigo sea mas legible y manejable.

1 import styled from 'styled-components' ;
2

5 const StyledDiv = styled.div’

4 background-color: blue;

5 color: white;
eS
8 function MyComponent() {
9 return <StyledDiv>Hello, world!</StyledDiv>;

10 }

Cada uno de estos métodos tiene sus ventajas y desventajas, y la elección
entre ellos dependera de tus necesidades especificas. En los siguientes apartados,
profundizaremos en cada uno de estos métodos, y tambión exploraremos cé6mo
utilizar Grid y Flexbox en React, cémo crear disefios responsive y adaptativos, y
cémo integrar bibliotecas de componentes UI en tus proyectos de React.
CSS Modules

CSS Modules es una metodologia que permite encapsular los estilos a nivel de
componente, evitando asi los problemas de colisión de nombres de clases y la
propagación de estilos no deseados. Con CSS Modules, cada archivo de estilos se
convierte en un médulo que exporta un objeto de estilos que puedes usar en tu
componente.

Cémo usar CSS Modules

Para usar CSS Modules en un proyecto de React, debes seguir los siguientes pasos:

1. Crear un archivo de estilos: Crea un archivo de estilos con la
extensión . module. css. Por ejemplo, si tienes un componente llamado Button,

puedes crear un archivo de estilos llamado Button. module.css.

1 /* Button.module.css */
2 .button {

3 background-color: blue;
4 color: white;

5 padding: 10px 20px;

6 border: none;

7 border-radius: 5px;

8 cursor: pointer;

2. Importar el archivo de estilos: Importa el archivo de estilos en tu componente

utilizando la sintaxis de importación de ES6. El archivo de estilos se importara
como un objeto JS.

1 import styles from './Button.module.css';

3. Usar los estilos en tu componente: Puedes usar los estilos importados en tu
componente como si fueran un objeto JS. Los nombres de las clases se
convierten en las propiedades del objeto.

1 function Button() {
2 return <button className={styles.button}>Click me</button>;
3}

Ventajas de CSS Modules

1. Encapsulamiento de estilos: Con CSS Modules, los estilos de un componente
no afectaran a otros componentes. Esto evita los problemas de colisión de
nombres de clases y la propagación de estilos no deseados.

2. Reutilizacion de nombres de clases: Puedes usar el mismo nombre de clase en
diferentes archivos de estilos sin tener que preocuparte por las colisiones de
nombres.

3. Compatibilidad con CSS existente: CSS Modules utiliza CSS estandar, por lo
que no tienes que aprender una nueva sintaxis.
Inconvenientes de CSS Modules

1. No es CSS en JS: A diferencia de las soluciones de “CSS en JS” como styled-
components, CSS Modules no te permite definir estilos dinamicos basados en
las props de los componentes.

2. No es parte del estandar de CSS: CSS Modules es una extensión de CSS y no
es parte de su estandar. Esto significa que no todos los entornos de dev
admiten CSS Modules de forma predeterminada.

3.No es tan escalable: Para proyectos mas grandes, puede ser més dificil
gestionar y organizar los archivos de estilos.

Como resumen, CSS Modules es una gran opción si quieres encapsular los estilos a
nivel de componente y evitar los problemas de colisión de nombres de clases. Sin
embargo, si necesitas estilos dindmicos basados en las props de los componentes,
es posible que desees considerar una solución de “CSS en JS” como styled-
components.
CSS en JS: Styled-components y otras soluciones

“CSS en JS” es una técnica que permite escribir CSS directamente dentro de
JS. Esta técnica ha ganado popularidad en la comunidad de React debido
a su capacidad para proporcionar estilos dindmicos y encapsulados a nivel de
componente. Existen varias bibliotecas de “CSS en JS”, pero en este apartado nos
centraremos en una de las mas populares: styled-components.

Cémo usar Styled-components

Para usar styled-components en un proyecto de React, debes seguir los
siguientes pasos:

1. Instalar styled-components: Puedes instalar styled-components en tu
proyecto utilizando npm.

1 $ npm install styled-components

2. Crear un componente estilizado: Utiliza la función styled de styled-
components para crear un componente estilizado. Puedes escribir CSS normal
dentro de un Template Literal de JS.

1 import styled from 'styled-components';
2

3 const Button = styled. button”

4 background-color: blue;

5 color: white;

6 padding: 10px 20px;
7 border: none;
border-radius: 5px;

cursor: pointer;

3. Usar el componente estilizado: Puedes usar el componente estilizado como
cualquier otro componente de React.

1 function App() {
2 return <Button>Click me</Button>;
3}

Otras funcionalidades de styled-components

Una de las caracteristicas de styled-components es la posibilidad de crear
estilos dindamicos en base a las props que pasemos a los componentes. De esta forma
puedes crear componentes mas versatiles.

Veamos un ejemplo:

1 // Crear un componente de botón

2 const Button = styled.button®

3 /* Proporcionamos algunos estilos basicos */
4 background: palevioletred;

: white;

6 font-size: 1em;

5 colo:

margin: 1em;
8 padding: 0.25em 1em;
9 border: 2px solid palevioletred;
10 border-radius: 3px;

12 /* Adaptamos los estilos basados en las props */
13 ${props => props.primary && css”

14 background: white;

45 color: palevioletred;

16}

19 // Uso del componente
20 render(

21 <div>

22 <Button>Normal</Button>

23 <Button primary>Primario</Button>
24 </div>

25 )5

En este ejemplo, el botón cambiara su estilo si se le pasa la prop primary. Si
primary es true, el botón tendra un fondo blanco y el texto sera de color
palevioletred.

Ahora, veamos como extender los estilos de un componente.

1 // Crear un componente de botón
2 const Button = styled.button®

3 color: palevioletred;

4 font-size: 1em;

5 margin: 1em;

6 padding: 0.25em 1em;

7 border: 2px solid palevioletred;
8 border-radius: 3px;

11 // Extender el componente Button para crear un componente
TomatoB\

12 utton

const TomatoButton = styled(Button)~

14 color: tomato;

border-color: tomato;

18 // Uso de Los componentes
19 render (

20 <div>
2a <Button>Button</Button>
22 <TomatoButton>Tomato Button</TomatoButton>

23 </div>
26 )5

En este ejemplo, TomatoButton es una extensión de Button, pero con un color y
un borde de color tomato.

Estos son solo dos ejemplos de lo que puedes hacer con Styled Components. Te

recomiendo que consultes la documentación oficial para explorar mas a fondo sus
posibilidades.

Ventajas de styled-components

1. Estilos dinamicos: Con sty1ed- components, puedes definir estilos dinamicos
basados en las props de los componentes. Resumiendo todo, styled- components es una buena opción si necesitas estilos
dinamicos y encapsulados a nivel de componente. Sin embargo, si prefieres trabajar

1 const Button = styled.button® con archivos de estilos separados y no necesitas estilos dinamicos, es posible que
2 background-color: ${props => props.primary ? ‘blue’ : prefieras una solución como CSS Modules.

‘white'};

3 color: ${props => props.primary ? 'white' : 'blue'};

6 <Button primary>Primary Button</Button>
? <Button>Secondary Button</Button>

2. Encapsulamiento de estilos: Al igual que con CSS Modules, los estilos de un
componente estilizado no afectaran a otros componentes.

3.Eliminación automatica de CSS no utilizado: Styled-components elimina
automaticamente el CSS que no se utiliza, lo que puede ayudar a reducir el
tamaijio de tu bundle de JS.

Inconvenientes de styled-components

1. Rendimiento: Styled-components puede ser mas lento que otras soluciones de
CSS debido a su naturaleza dinamica.

2. Necesidad de aprender una nueva biblioteca: Aunque styled- components
utiliza CSS estandar, todavia necesitas aprender cémo funciona la biblioteca.

3. No es CSS estandar: Aunque styled-components utiliza CSS estandar, los
estilos se definen dentro de JS, lo que puede ser confuso para los
desarrolladores que estan acostumbrados a trabajar con archivos de estilos
separados.
Grid y Flexbox en React

Flexbox en React

Flexbox es un modelo de disefio CSS que nos permite disefiar interfaces de usuario
flexibles y eficientes.

En React, puedes usar Flexbox de la misma manera que lo harias en CSS puro. Aqui

te muestro un ejemplo de cémo puedes usar Flexbox en un componente de React:

1 import React from ‘react’;

2 import './App.css'; // Asegirate de importar tu archivo CSS
3

« function App() {

5 return (

6 <div className="flex-container">

7 <div className="flex-item">1</div>

8 <div className="flex-item">2</div>
9 <div className="flex-item">3</div>
10 </div>

a)

a2}

14 export default App;

Y en tu archivo CSS:

1 .flex-container {

2 display: flex;

3 justify-content: space-around;
4

}

6 .flex-item {

? background-color: lightblue;
8 padding: 20px;

9 margin: 10px;

10 }

En este ejemplo, flex-container es el contenedor, flex y flex- item son los
elementos flex. Los elementos se distribuyen uniformemente en el contenedor
gracias ala propiedad justify-content: space-around.

Grid en React

CSS Grid es otro modelo de disefio que permite a los desarrolladores crear interfaces
de usuario complejas y adaptables.

Al igual que Flexbox, puedes usar CSS Grid en React de la misma manera que lo
harias en CSS puro. Aqui tienes otro ejemplo:

1 import React from ‘react’;

2 import './App.css'; // Asegtrate de importar tu archivo CSS
3

4 function App() {

5 return (
6 <div className="grid-container">
7 <div className="grid-item">1</div> establece un espacio de 10px entre los elementos de la cuadricula.
8 <div className="grid-item">2</div>

9 <div classN. id-item">3</div> .
ay erassNvames Srxceeven 7 w Flexbox y Grid con Styled-Components
10 <div className="grid-item">4</div>
11 <div className="grid-item">5</div>
12 <div className="grid-item">6</div> Puedes usar Flexbox y CSS Grid con Styled Components en React. Aqui te muestro
13 </div> algunos ejemplos:
uw)
as }

1 import styled from ‘styled-components' ;
2

3 const FlexContainer = styled.div™

4 display: flex;

16
17 export default App;

5  justify-content: space-around;

Y en tu archivo CSS: 65
7

1 .grid-container { 8 const FlexItem = styled.div™

2 display: gri 9 background-color: lightblue;

3 grid-template-columns: repeat(3, 1fr); 10 padding: 20px;

4 gap: 10px; a1 margin: 10px;

5} 12 °5

6 43

7 .grid-item { 14 function App() {

8 background-color: lightblue; 15 return (

9 padding: 20px; 16 <FlexContainer>

10 text-align: center; 17 <FlexItem>1</FlexItem>

a} 18 <FlexItem>2</FlexItem>
19 <FlexItem>3</FlexItem>
20 </FlexContainer>

En este ejemplo, grid-container es el contenedor de la cuadricula y grid- a)

item son los elementos de la cuadricula. La propiedad grid-template- 22 }
columns: repeat(3, 1fr) ; creatres columnas de igual tamatio, y gap: 10px;
23
24 export default App;

En este ejemplo, FlexContainer es el contenedor flex y FlexItem son los
elementos flex. Los elementos se distribuyen uniformemente en el contenedor
gracias ala propiedad justify-content: space-around.

Ahora, veamos cémo puedes usar CSS Grid con Styled Components. Crearemos un
contenedor de cuadricula y algunos elementos de cuadricula.

1 import styled from 'styled-components
2

3 const GridContainer = styled.div™

4 display: grid;

5  grid-template-columns: repeat(3, 1fr);
6 gap: 10px;

3

8

9 const GridItem = styled.div™
10 background-color: lightblue;
41 padding: 20px;

12 text-align: center;

135

15 function App() {
16 return (

17 <GridContainer>
18 <GridItem>1</GridItem>
19 <GridItem>2</GridItem>

20 <GridItem>3</GridItem>

2a <GridItem>4</GridItem>

22 <GridItem>5</GridItem>
23 <GridItem>6</GridItem>
2h </GridContainer>

25 (5

26 }

28 export default App;

En este ejemplo, GridContainer es el contenedor de la cuadricula y GridItem
son los elementos de la cuadricula. La propiedad grid-template-columns:
repeat(3, 1fr) ; creatres columnas de igual tamafio, y gap: 10px; establece un
espacio de 10px entre los elementos de la cuadricula.

Estos son solo dos ejemplos de cémo puedes usar Flexbox y CSS Grid con Styled
Components en React. Te animo a que experimentes con estas herramientas y
veas cémo puedes usarlas para crear disefios de interfaz de usuario complejos y
adaptables.
Disefio responsive y adaptativo

El disefio responsive y adaptativo son dos enfoques para hacer que las interfaces de
usuario se vean y funcionen bien en una variedad de dispositivos y tamaios de
pantalla.

El disefio responsive utiliza CSS y HTML para redimensionar, ocultar, reducir 0
aumentar un sitio web, para que se vea bien en todos los dispositivos (escritorio,
tablet, smartphone, etc.). Un disefio responsive se “ajusta” dependiendo del tamario
de la pantalla.

Con Styled Components, puedes usar las funciones de las media queries para hacer
que tus componentes sean responsive. Aqui te muestro un ejemplo de cémo puedes
hacerlo:

1 import styled from ‘styled-components';
3 const ResponsiveDiv = styled.div™

4 width: 100%;

5 padding: 20px;

6 background-color: lightblue;

/* Cambiar el color de fondo en pantallas pequefias */
9 @media (max-width: 600px) {
10 background-color: lightcoral;

14 function App() {

15 return <ResponsiveDiv>Hola, mundo! </ResponsiveDiv>;

18 export default App;

En este ejemplo, ResponsiveDiv cambiarA su color de fondo a lightcoral en
pantallas que tengan un ancho maximo de 600px.

El disefio adaptativo, por otro lado, utiliza varias versiones de un sitio web que
estan personalizadas para diferentes tamarios de pantalla. Un disefio adaptativo “se
adapta” a la pantalla en la que se esta viendo.

Con React y Styled Components, puedes usar el estado y los eventos del ciclo de
vida de los componentes para cambiar el disefio de tus componentes en función
del tamafio de la pantalla. Aqui te muestro un ejemplo de cémo puedes hacer un
componente adaptativo con React y Styled Components:

1 import { useState, useEffect } from ‘react';
2 import styled from 'styled-components';

3

4 const AdaptiveDiv = styled.div’

5 width: 100%;

6 padding: 20px;

2 background-color:
"UN

8 ightblue'};

${props => props.isMobile ? ‘lightcoral'

10
11 function App() {
12 const [isMobile, setIsMobile] = useState (window. innerWidth
<= 6\
13 00);

15 useEffect(() => {

16 const handleResize = () => setIsMobile(window. innerWidth
<= 6\

17 00)5

18 window. addEventListener('resize', handleResize) ;

49

20 return () => window.removeEventListener('resize',
handleResiz\

21 e);

2}, —))s

23

24 return (

25 <AdaptiveDiv isMobile={isMobile}>

26 Hola, mundo!

27 </AdaptiveDiv>

28 «(5

20 }

30

31 export default App;

En este ejemplo, Adapt iveDiv cambiara su color de fondo a lightcoral si se
esta viendo en una pantalla de teléfono movil (un ancho de pantalla de 600px o
menos).

Estos son solo dos ejemplos de cémo puedes hacer que tus componentes de React
sean responsive y adaptativos con Styled Components.

Te animo a que experimentes con estas técnicas y veas cémo puedes usarlas para
mejorar la experiencia de usuario en diferentes dispositivos y tamarios de pantalla.
Integracion de bibliotecas de componentes UI

Las librerias de componentes UI son conjuntos de componentes predefinidos
que puedes usar para acelerar el dev de tus aplicaciones. Estas bibliotecas
proporcionan una amplia gama de componentes, desde botones y formularios
hasta barras de navegación y modales, todos con estilos y funcionalidades ya

implementadas.

En React, hay varias bibliotecas de componentes UI populares que puedes usar.

Aqui te presento algunas de las mas populares:
Material UI

Material-UI es una de las bibliotecas de componentes UI mAs populares para React.
Implementa el disefio Material Design de Google y proporciona una amplia gama de

componentes predefinidos.

Para usar Material UI, primero debes instalarlo en tu proyecto junto a un par de
dependencias:

1 $ npm install @mui/material @emotion/react @emotion/styled

Luego, puedes importar y usar los componentes de Material-UI que necesites en tu

app:

1 import React from ‘react’;

2 import Button from "@mui/material/Button";

3

4 function App() {

5 return <Button color="primary">Hola, mundo!</Button>;
6}

7

8 export default App;

Ant Design

Ant Design es otro conjunto de componentes UI popular para React. Proporciona
una amplia gama de componentes de alta calidad que siguen los principios de

disefio de Ant Design.

Para usar Ant Design, primero debes instalarla en tu proyecto:

1 $ npm install antd

Una vez instalada, ya puedes hacer uso de sus componentes.

1 import { Button, Space } from ‘antd';
2 const App = () => (
3 <Space wrap>

4 <Button type="primary">Primary Button</Button>
5 <Button>Default Button</Button>
6 <Button type="dashed">Dashed Button</Button>

7 <Button type="text">Text Button</Button>

8 <Button type="link">Link Button</Button>
9 </Space>
10 5

11 export default App;

Chakra UI

Y ahora te muestro mi favorita. Para usar Chakra UI en tu proyecto React, primero
necesitas instalarlo. Puedes hacerlo con npm y el siguiente comando para instalar
otro conjunto de dependencias necesarias:
1 $ npm install @chakra-ui/react @emotion/react G@emotion/styled
fra\
2 mer-motion

Ademas, necesitas envolver tu app con el ChakraProvider en tu archivo
principal (normalmente index. js oApp. js):

1 import * as React from "react";

2 import { ChakraProvider } from "@chakra-ui/react";
3 import App from './App';

5 function Main() {

6 return (

? <ChakraProvider>
8 <App />

9 </ChakraProvider>
10)

11}

12
15 export default Main;

Ahora, puedes empezar a usar los componentes de Chakra UI en tu app. Aqui
tienes un ejemplo de cémo puedes usar un botón y una caja de Chakra UI:

1 import React from ‘react’;
2 import { Box, Button } from ‘@chakra-ui/react';

3

4 function App() {

5 return (

6 <Box padding="4" bg="gray.100">

? <Button colorScheme="teal">Hola, mundo! </Button>

8 </Box>

12 export default App;

En este ejemplo, Box es un componente de caja flexible que puedes usar para
construir tus disefios. Button es un componente de botón que puedes personalizar

con la prop colorScheme.

Chakra UI tambión proporciona una amplia colección de otros componentes, como

formularios, modales, alertas y mas.

Te animo a que explores la documenta de Chakra UI para ver todos los

componentes y caracteristicas que ofrece.

Otras bi

liotecas de componentes UI

Ademas de Material-UI, Ant Design o Chakra, hay muchas otras bibliotecas de
componentes UI que puedes usar con React. Algunas de las mas populares incluyen:

+ Semantic UI React: Una biblioteca de componentes UI que sigue los principios
de diserio de Semantic UI.

+ React Bootstrap: Una versión de Bootstrap especificamente disefiada para
React.
«Grommet: Grommet es una biblioteca de componentes UI para React que se
centra en la accesibilidad y la responsividad. Proporciona una amplia gama de
componentes, desde controles de entrada y navegación hasta visualizaciones y
utilidades.

Estas son sdlo algunas de las muchos conjuntos de componentes UI disponibles
para React. Te animo a que explores estas y otras librerias para ver cual se adapta
mejor a tus necesidades.
Conclusión

En este capitulo, hemos explorado en profundidad cémo manejar los estilos y el
disefio en React. Hemos comenzado con una introducción a las diferentes formas
de aplicar estilos CSS en React.

Luego, hemos profundizado en CSS Modules y styled-components, discutiendo
sus ventajas, inconvenientes y proporcionando ejemplos de cédigo para cada uno.
Hemos explorado cémo utilizar Grid y Flexbox en React para crear disefios de
interfaz de usuario complejos y responsivos. Finalmente, hemos discutido como
integrar bibliotecas de componentes UI en tus proyectos de React, presentando

algunas de las mas populares.

Con estos conocimientos, ahora deberias ser capaz de crear interfaces de usuario
atractivas y responsive en React que se vean y funcionen bien en una variedad de
dispositivos y tamatios de pantalla.

En el préximo capitulo, cambiaremos de enfoque y nos adentraremos en cémo
consumir APIs externas desde React. Aprenderemos cémo hacer solicitudes HTTP
a APIs externas, como manejar las respuestas y los errores, y c6mo utilizar los datos

de las APIs para alimentar nuestros componentes de React.
Referencias

«Meyer, E. (2017). CSS: The Definitive Guide: Visual Presentation for the Web.
O'Reilly Media.

+ Frain, B. (2017). Responsive Web Design with HTMLS and CSS. Packt Publishing.
+ Hampton-Smith, S. (2016). Pro CSS3 Layout Techniques. Apress.

+ Mozilla Contributors. (2023). CSS: Cascading Style Sheets. MDN Web Docs.
https://developer.mozilla.org/en-US/docs/Web/CSS

-Epps, H. (2023). A Complete Guide to Flexbox. CSS-Tricks. https://css-
tricks.com/snippets/css/a-guide-to-flexbox/

+ Epps, H. (2023). A Complete Guide to Grid. CSS-Tricks. https://css-tricks.com/
snippets/css/complete-guide-grid/

+Styled-components. (2023). Documentation. Styled-components. https://
styled-components.com/docs

+ Material-UI. (2023). Getting Started. Material-UI. https://material-ui.com/
getting-started/installation/

+ Ant Design. (2023). Introduction. Ant Design. https://ant.design/docs/react/
introduce

+Chakra UI. (2023). Getting Started. Chakra UI. https://chakra-ui.com/docs/
getting-started

Capitulo 7: Consumo de APIs y comunicacion con el Servidor
Introducción

En una app web moderna, la comunicación con servidores es tambión una
parte esencial. Ya sea para obtener datos, enviar datos, autenticar usuarios, 0
realizar cualquier otra operación, las aplicaciones web necesitan interactuar con
los servidores. En este capitulo, vamos a explorar cémo podemos hacer esto en una

app React.

React.js, como biblioteca de interfaz de usuario, no tiene una forma incorporada de
interactuar con los servidores. Sin embargo, gracias a la flexibilidad de JS y
ala amplia gama de bibliotecas disponibles, tenemos varias formas de realizar estas

operaciones.

En este capitulo, vamos a explorar cuatro formas diferentes de interactuar con los

servidores desde una app React:

+ Usando la API Fetch incorporada de forma nativa en JS.
+ Usando la biblioteca Axios.

+ Creando un Custom Hook para realizar peticiones HTTP.

+ Usando la biblioteca React Query (0 TanStack Query).

Cada uno de estos métodos tiene sus propias ventajas e inconvenientes, y la
elección de uno sobre otro puede depender de las necesidades especificas de tu
proyecto. Tambión discutiremos como manejar errores y el estado de carga, y como

implementar un sistema de autenticacion y autorización.

Antes de continuar, es importante tener un buen entendimiento de JS
y de cémo funciona la comunicación HTTP y la asincronia. Si necesitas repasar

estos conceptos, te recomiendo que leas el capitulo correspondiente en mi libro,

Aprendiendo JS.

Ahora, comencemos con el primer método: el uso de Fetch y Axios para realizar

peticiones HTTP.
Fetch y Axios: Realizar peticiones HTTP

Fetch

Fetch es una API incorporada en la mayoria de los navegadores modernos que
se utiliza para hacer peticiones HTTP. Esta basada en Promesas, lo que significa
que puedes usar .then y .catch para manejar las respuestas y los errores que
devuelve.

Aqui tienes un ejemplo basico de cémo puedes usar Fetch para obtener datos de una
API:

1 fetch('https://jsonplaceholder.typicode.com/todos/')

2  .then(response => response. json())
3 .then(data => console. 1log(data))
4 ,eateh(error => console.error('Error:', error));

En este ejemplo, fetch hace una petición GET a la URL proporcionada. Cuando
la respuesta es recibida, la convertimos a JSON con response. json(), y luego
imprimimos los datos en la consola. Si ocurre un error en cualquier punto del
proceso, lo capturamos con . catch y lo imprimimos en la consola.

Axios
Axios es una biblioteca de JS que se puede usar para hacer peticiones

HTTP. A diferencia de Fetch, Axios tiene una API mas rica y es compatible
con navegadores mas antiguos. Tambión tiene algunas caracteristicas adicionales,

como la capacidad de cancelar peticiones y de establecer un tiempo de espera.
Debido a esto, es bastante utilizada.

Aqui tienes un ejemplo de cémo puedes usar Axios para obtener datos de una API:

1 import axios from 'axios';

3 axios.get('https://jsonplaceholder.typicode.com/todos/')
4 .then(response => console.log(response. data) )
5 .cateh(error => console.error('Error:', error));

En este ejemplo, axios.get hace una petición GET a la URL proporcionada.
Cuando la respuesta es recibida, imprimimos los datos en la consola. Si ocurre un
error en cualquier punto del proceso, lo capturamos y lo imprimimos en la consola.

Tanto Fetch como Axios pueden ser usados para hacer peticiones HTTP de
cualquier tipo (GET, POST, PUT, DELETE, etc.) y para enviar y recibir datos en
varios formatos, incluyendo JSON, texto plano, y FormData. La elección entre
Fetch y Axios puede depender de tus necesidades especificas y de tus preferencias
personales.

Uso en React
En React, las peticiones HTTP suelen realizarse en el ciclo de vida del componente,

especificamente en el método componentDidMount para los componentes de
clase, o en el Hook useEffect para los componentes funcionales.
Veamos un ejemplo de cédigo de cémo se hace esto con Axios (Recuerda que con
Fetch es bastante similar):

1 import React, { useState, useEffect } from ‘react’;
3 function ExampleComponent() {

4 const [data, setData] = useState(null);

5

6 useEffect(() => {

7 fetch('https://api.example.com/data')

8 .then(response => response. json())

9 .then(data => setData(data))

10 .catch(error => console.error('Error:', error));

a 3, TDs

15 return (

14 <div>

45 {

16 data

17 ? data.map(item => <div key={item. id}>{item.name}</

18 : 'Loading...'

20 </div>

24 export default ExampleComponent;

Eneste ejemplo, usamos el Hook useState para crear un estado para los datos, y el

Hook useEf fect para realizar la petición HTTP cuando el componente se monta.
Cuando los datos son recibidos, los guardamos en el estado con setData, y luego

los mostramos en el renderizado del componente.

es importante recordar que las peticiones HTTP son operaciones asincronas, lo
que significa que los datos no estardn disponibles inmediatamente. Por eso,
inicializamos el estado con null y mostramos ‘Loading. . .’ hasta que los datos
sean recibidos.

Creando un custom Hook para peticiones HTTP

Como vimos en capitulos anteriores, los Custom Hooks son una caracteristica muy
potente de React que nos permite extraer la légica del componente en funciones
reutilizables. En este caso, vamos a crear un Custom Hook llamado useHttp para
manejar las peticiones HTTP con Fetch.

Este Hook manejaraé tres estados: isLoading, error y data. El estado
isLoading sera true mientras la petición esté en curso, error contendra
cualquier error que ocurra durante la petición, y data contendra los datos
recibidos.

Ademis, este Hook realizara peticiones de tipo GET. Para ello el Hook recibe como
argumento ur1, que es la URL a la que se hard la petición.

Aqui tienes el cédigo del Hook:

1 import { useState, useEffect } from ‘react’;
2
3 export const useHttp = (url) => { Ahora, puedes usar este Hook en tus componentes para realizar peticiones HTTP de

5
6

const [isLoading, setIsLoading] = useState(false);
const [data, setData] = useState(nul1);
const [error, setError] = useState(null);

tipo GET sin tener que usar useState y useEffect. Aqui tienes un ejemplo de

cémo puedes implementarlo en tu app para obtener datos de una API:

useEffect(() => { 1 import { useHttp } from "./useHttp";
setIsLoading(true) ; 2
setError(nul1) 3 function App() {
fetch(url) 4 const { isLoading, error, data } = useHttp(
.then(response => { 5 “https://jsonplaceholder.typicode.com/todos"

if (!response.ok) { v5
setError('Failed to fetch.');

6
7

throw new Error('Failed to fetch.'); 8 return (
9
°

} <div className="App">
return response. json(); 1 <hi>Todo List</hi>
3) a4 { isLoading && <p>Loading...</p> }
-then(data => { 12 { error && <p>Error: {error}</p> }
setIsLoading (false); 13 { !isLoading && data && (
setError (null) ; 14 <ul>
setData(data) ; 15 {data.map((todo) => (
y) 16 <li key={todo. id}>{todo.title}</1i>
.catch(err => { 17 +
setError(err) ; 18 </ul>
setIsLoading(false) ; 19 )}
Ys 20 </div>
}, [ur1]); ar )S
22}
return { isLoading, error, data }; 23

24 export default App;
En este ejemplo, usamos el Hook useHttp para obtener los estados que
necesitamos y realizar la petición GET cuando el componente se monta.
Finalmente, mostramos los datos, un mensaje de carga, o un mensaje de error en el
renderizado del componente, dependiendo del estado de la petición.

Este Custom Hook es una herramienta muy util que puedes reutilizar en diferentes
partes de tu app para manejar las peticiones HTTP de una manera mas
eficiente y ordenada. Y lo mejor es que lo puedes reutilizar en cualquier parte de tu
cédigo dónde hagas peticiones de este tipo.

Para realizar una peticion POST, Si queremos reutilizar, necesitamos modificar un
poco el Custom Hook useHttp. los Hooks de React deben seguir ciertas reglas y
no pueden ser llamados condicionalmente o dentro de funciones. En lugar de eso,
podemos modificar el Hook useHttp para que devuelva una función que pueda ser

llamada cuando sea necesario. Aqui esta el cédigo modificado:

1 import { useState, useCallback } from ‘react’;

2

3 export const useHttp = () => {

4 const [isLoading, setIsLoading] = useState(false) ;
5 const [data, setData] = useState(null);

6 const [error, setError] = useState(null);

8 const sendRequest = useCallback(

9 asyne (url, method = 'GET', body = null) => {
10 setIsLoading(true) ;

11 setError(null);

12 try {

13 const response = await fetch(url, {

method: method,

body: body ? JSON.stringify(body) : null,

16 headers: body ? { ‘Content-Type’: ‘application/json' }
\

aps {},

8 3

20 if (!response.ok) {

21 throw new Error('Request failed!’

22 }

23

24 const data = await response. json();

25 setData (data) ;

26 } catch (err) {

27 setError(err.message || ‘Something went wrong!');
28 }

29 setIsLoading (false) ;

30 3, (1

Bi)

32
33 return { isLoading, data, error, sendRequest };

34 45

En este caso, el Hook useHttp devuelve una función sendRequest que puede
ser llamada para realizar una petición HTTP. Esta función es envuelta en
useCallback para evitar recreaciones innecesarias.

Aqui tienes un ejemplo de cémo puedes usar este Hook para realizar una peti
POST cuando se envian datos desde un formulario:
1 import { useState } from "react";

2
3
4

5

import { useHttp } from "./useHttp";

function App() {
const [title, setTitle] = useState("");
const [completed, setCompleted] = useState(false) ;
const { isLoading, error, data, sendRequest } = useHttp();

const handleSubmit = (event) => {
event.preventDefault();
sendRequest (
“https: //jsonplaceholder.typicode.com/todos",
"POST",
{ title, completed }
3

return (
<div className="App">
<hi>Create Todo</h1>
<form onSubmit={handleSubmit}>
<label>
Title:
<input
type="text"
value={title}
onChange={(e) => setTitle(e.target.value)}
/>
</label>
<label>

31 Completed:

32 <input

33 type="checkbox"

34 checked={completed}

35 onChange={(e) => setCompleted(e.target.checked)}
36 />

37 </label>

38 <button type="submit">Create</button>

39 </form>

40 {isLoading && <p>Loading...</p>}

at {error && <p>Error: {error}</p>}

42 {!isLoading && data && <p>Todo created with ID: {data. id}
</\

43 p>}

Ab </div>

45 dS

46 }

48 export default App;

En este ejemplo, usamos el Hook useHt tp para obtener los estados y la función
sendRequest. Cuando el formulario se envia, llamamos a sendRequest con
la URL, el método ‘POST’, y los datos del formulario. Finalmente, mostramos un
mensaje de carga, un mensaje de error, o el ID del ToDo creado, dependiendo del
estado de la peticion.

Por supuesto, esta es una forma de las muchas que existen y que puedes emplear
para realizar esta petición.

podrias utilizar otro Custom Hook diferente para las peticiones de tipos POST Y PUT,

por ejemplo.
Pero, en lugar de seguir extendiendo este ejemplo, vamos a pasar a explicar una
biblioteca que tiene una gran aceptación, se trata de TanStack Query (0 React Query)
React Query (TanStack Query)

React Query, ahora conocida como TanStack Query, es una biblioteca que se describe
como la herramienta de obtención de datos que faltaba para las aplicaciones
web. En términos mas técnicos, facilita la obtención, almacenamiento en caché,
sincronizacion y actualización del estado del servidor en tus aplicaciones web.

En un inicio, sélo podia usarse con React, pero en su cambio de nombre a TanStack
ahora se puede utilizar en Vanilla JS, TypeScript, Vue, Svelte, Solid y React.

Origen y evolución a TanStack Query

La mayoria de los frameworks web principales no vienen con una forma “opinada”
de obtener 0 actualizar datos de manera holistica. Debido a esto, los desarrolladores
terminanos construyendo meta-frameworks que encapsulan opiniones estrictas
sobre la obtención de datos, o inventamos nuestras propias formas de obtener
datos, como el Custom hook que vimos en el ejemplo anterior.

Esto generalmente significa juntar el estado y los efectos secundarios basados en
componentes, o usar bibliotecas de gestión de estado de propdsito general para

almacenar y proporcionar datos asincronos en sus aplicaciones.

React Query surgié como una solución a estos problemas, proporcionando una
forma eficiente y efectiva de manejar el estado del servidor. Con el tiempo, la
biblioteca ha evolucionado y ahora se conoce como TanStack Query.

Uso del Hook useQuery

TanStack Query proporciona dos Hooks principales para interactuar con tus APIs:
useQuery yuseMutation.

useQuery es un Hook que puedes usar para obtener datos de tu API. Vendria a
ser como el Custom Hook useHttp que hicimos anteriormente, pero con super-
vitaminas.

Aqui tienes un ejemplo de cédigo de como se usa:

1 import { QueryClient, QueryClientProvider, useQuery } from
*@tans\

2 tack/react-query'

3

4 const queryClient = new QueryClient()

6 export default function App() {

7 return (

8 <QueryClientProvider client={queryClient}>
9 <ExampleComponent />

10 </QueryClientProvider>

a)

» function ExampleComponent() {

15 const { isLoading, error, data } = useQuery({

queryKey: ['repoData'],

queryFn: () =>

18 fetch( ‘https: //api.github.com/repos/tannerlinsley/
react-que\

19 ry')

20 - then( +Creando el cliente de consulta: Creamos una nueva instancia de

2a (res) => res.json(), QueryClient y la proporcionamos a nuestros componentos a través de
22 » QueryClientProvider. Esto nos permite utilizar useQuery en cualquier
es Dy componente hijo.
. if (isLoading) return ‘Loading...’ +Usando useQuery: Dentro de nuestro componente ExampleComponent,
os if (error) return ‘An error has occurred: ' + error.message utilizamos el Hook useQuery para obtener datos de la API de GitHub.
27 useQuery recibe un objeto con dos propiedades: queryKey y queryFn.
28 return ( equeryKey: Es un identificador unico para la consulta. TanStack Query
es <div> utiliza esta clave para almacenar en caché los datos de la consulta y para
® setae deenesptieane/p> invalidar, refetch, o actualizar los datos de la consulta en el futuro. En
- estrong> {data. subscribers count}</strong>{' '} este caso, estamos utilizando la cadena ‘repoData’ como nuestra clave de
33 <strong> {data.stargazers_count}</strong>{' '} consulta.
34 <strong> {data.forks_count}</strong> + queryFn: Es una función que devuelve una promesa que eventualmente
</div> resuelve los datos que queremos. En este caso, estamos utilizando fetch
36) para obtener los datos del mismo repositorio de React Query en GitHub.
37}

+ Manejando el estado de la consulta: useQuery devuelve un objeto con varios
campos que representan el estado actual de la consulta. En este caso, estamos

Ahora te explico mAs en detalle que hace el cédigo anterior.

-Importa  TanStack Query: Primero, importamos QueryClient,
QueryClientProvider y useQuery de @tanstack/react-query.
QueryClient es una clase que se utiliza para configurar y
compartir una instancia de cliente de consulta entre tus componentes.
QueryClientProvider es un componente que proporciona el cliente de
consulta a tus componentes a través del contexto de React. useQuery es el
Hook que utilizaremos para obtener datos de nuestra API.

utilizando isLoading, error, y data.
» isLoading: Es true mientras la consulta esta en progreso y false una vez
que se ha completado o ha fallado.
error: Es null a menos que la consulta haya fallado, en cuyo caso sera el
error que se produjo durante la consulta.
« data: Son los datos obtenidos de la consulta. Es undefined hasta que la
consulta se completa con éxito.
Finalmente, en función del estado de la consulta, mostramos un mensaje de carga,
un mensaje de error, o los datos obtenidos de la API.
Uso del Hook useMutation

El Hook useMutation es otro componente esencial de TanStack Query. Este Hook
te permite realizar mutaciones (es decir, crear, actualizar o eliminar datos) en tu
API.

Aqui tienes un ejemplo de uso:

1 import { useMutation } from '@tanstack/react-query'
2

3 function App() {

4 const mutation = useMutation({

5 mutationFn: (newTodo) => fetch('/api/todos', {

6 method: ‘POST’,

7 body: JSON.stringify(newTodo),

8 ),

9 onSuccess: () => {

10 queryClient.invalidateQueries({ queryKey: ['todos'] })
a4 );

42

13 return (

44 <div>

45 {mutation.isLoading ? (

16 ‘Afiadiendo tarea...'

17 ys ¢

18 <>

19 {mutation.isError ? (

20 <div>Un Error ocurrié: {mutation.error.message}

</di\

21 v>

22 ) : null}

23

2 {mutation.isSuccess ? <div>Tarea Afiadida!</div>
nul\

25 1}

26

27 <button

28 onClick={() => {

29 mutation. mutate ({
30 id: new Date(),
31 title: ‘Aprender React’
32 d)

33 i}

34 >

35 Crear Tarea

36 </button>

37 </>

38 )}

39 </div>

40 dS

a}

- Importa useMutation: Primero, importamos useMutation de @tanstack/
react-query. useMutation es el Hook que utilizaremos para realizar
mutaciones en nuestra API.

+ Usando useMutation: Dentro de nuestro componente App, utilizamos el Hook
useMutat ion para crear un nuevo ToDo en nuestra API. useMutation recibe
dos argumentos: Una función de mutación y un objeto de opciones.
» Función de mutacin: Esta es una función que realiza la mutacion. En este
caso, estamos utilizando fetch para enviar un nuevo ToDo a nuestra API.
La función de mutación puede ser cualquier función que devuelva una
promesa.

» Objeto de opciones: Este es un objeto que puede contener varias opciones
para configurar el comportamiento de la mutación. En este caso, estamos
utilizando la opción onSuccess para invalidar y volver a buscar las
consultas ‘todos’ cuando la mutación se realiza con éxito.

+Realizando la mutacion: Para realizar la mutación, lamamos al método
mutate en el objeto devuelto por useMutation. Pasamos los datos que
queremos enviar a nuestra API como argumento a mutate.

+ Manejando el estado de la mutación: useMutation devuelve un objeto con
varios campos que representan el estado actual de la mutacion. En este caso,
estamos utilizando isLoading, error, y data.

isLoading: Es true mientras la mutación esta en progreso y fal ‘se una vez
que se ha completado o ha fallado.

» error: Es null a menos que la mutacion haya fallado, en cuyo caso sera el
error que se produjo durante la mutación.

» data: Son los datos obtenidos de la mutacion. Es undef ined hasta que la
mutación se completa con éxito.

Finalmente, en función del estado de la mutación, mostramos un mensaje de carga,
un mensaje de error, o los datos obtenidos de la API.
Manejo de errores y estado de carga

Vamos a dedicar un apartado a ver como se maneja el estado de carga y la gestion
de errores ya que son aspectos cruciales de cualquier app que interactiia con
una API.

Afortunadamente, tanto Fetch, Axios, como TanStack Query proporcionan
herramientas para manejar estos aspectos de manera eficiente.

Manejo de errores

Cuando realizamos una petición a una API, siempre existe la posibilidad de que
algo salga mal. La red podria estar caida, el servidor podria estar sobrecargado,
o podriamos haber proporcionado datos incorrectos. Por lo tanto, es importante

manejar estos errores de manera adecuada.

En el caso de Fetch y Axios, estos lanzaran una excepción si ocurre un error de red,
pero no si la petición se realiza con éxito pero el servidor devuelve un cédigo de
estado de error HTTP. Por lo tanto, debemos comprobar el cédigo de estado nosotros

mismos:

1 // Ejemplo con Fetch
2 fetch('https://api. github. com/repos/tannerlinsley/react-

query')

5 .then(response => {

4 if (!response.ok) {

5 throw new Error('Network response was not ok'

6 }

7 return response. json();

e 3)

9 .eateh(error => console.error('There has been a problem with
yo\

10 ur fetch operation: ', error));

1 // Ejemplo con Axios

2 axios.get(‘https://api.github.com/repos/tannerlinsley/react-
query\

3)

4 .then(response => {
5 if (response. status 200) {
6 throw new Error('Server response was not ok');
7 }
8 return response.data;
9 })
.catch(error => console.error('There has been a problem with
yo\
11 ur axios operation: ', error));

En el caso de TanStack Query, el manejo de errores es atin mas sencillo. Si
ocurre un error durante la consulta o la mutación, TanStack Query lo capturara
automaticamente y lo pondra a nuestra disposición a través del campo error del
objeto devuelto por useQuery ouseMutation:

1 // Ejemplo con TanStack Query

2 const { isLoading, error, data } = useQuery('repoData',
fetchRepo\
3 Data);
5 if (error) {
6 return <div>Un error ocurri:

{error.message}</div>

Estado de carga

Ademas del manejo de errores, tambión es importante proporcionar feedback al
usuario sobre el estado de carga de la petición. De nuevo, Fetch, Axios y TanStack
Query nos proporcionan las herramientas para hacer esto.

En el caso de Fetch y Axios, podemos establecer una variable de estado antes de
iniciar la petición y actualizarla cuando la petición se complete:

1 // Ejemplo con Fetch
2 const [isLoading, setIsLoading] = useState(true) ;
3

4 useEffect(() => {

5 fetch('https://api.github.com/repos/tannerlinsley/react-
query')
6 .then(response => response. json())
? -then(data => {
8 setData (data) ;
9 setIsLoading (false) ;
10 3
a}, (1)

1 // Ejemplo con Axios
2 const [isLoading, setIsLoading] = useState(true);

3
4 useEffect(() => {

5 axios.get('https://api.github.com/repos/tannerlinsley/
react-que\
6 ry')
? .then(response => {
8 setData(response.data) ;
9 setIsLoading (false) ;
10 Ys
a}, (15

En el caso de TanStack Query, el estado de carga se maneja automaticamente y se
pone a nuestra disposicion a través del campo isLoading del objeto devuelto por
useQuery ouseMutation:

1 // Ejemplo con TanStack Query

2 const { isLoading, error, data } = useQuery('repoData',
fetchRepo\
3 Data);

5 if (isLoading) {

6 return <div>Loading...</div>

Estos son solo ejemplos basicos. En una app real, probablemente querrias
proporcionar un feedback mas detallado al usuario, como mostrar un spinner de
carga, deshabilitar ciertos controles durante la carga, o mostrar mensajes de error
detallados.
Autenticacion y autorizacion

La autenticación y la autorización son aspectos muy importantes de la seguridad
en las aplicaciones web.

La autenticación se refiere al proceso de verificar la identidad de un usuario,
mientras que la autorización se refiere al proceso de verificar los permisos de un
usuario.

Implementación de la autentica

En una app React, puedes implementar la autenticación y la autorización
utilizando un API como backend. Aqui tienes un ejemplo basico de c6mo puedes
hacerlo:

1. Autenticación: Cuando un usuario intenta iniciar sesión, envias sus
credenciales (como su nombre de usuario y contrasefia) a tu API. Si las
credenciales son correctas, tu API devuelve un token de autenticación.

1 const login = async (username, password) => {
2 const response = await fetch('/api/login', {

3 method: ‘POST’,

4 headers: { ‘Content-Type’: '‘application/json' },
5 body: JSON.stringify({ username, password }),

6 5

? const data = await response. json();

9 if (response.ok) {

10 return data.token;
11} else {
12 throw new Error(data.message) ;

2. Almacenamiento del token: Almacenas el token de autenticación en el
estado de tu app (0 en el almacenamiento local del navegador) para
poder utilizarlo en futuras peticiones.

1 const [token, setToken] = useState(null);

2

3 const handleLogin = async (username, password) => {
4 try {

5 const token = await login(username, password);
6 setToken(token) ;

7 } catch (error) {

8 console.error('Login failed:', error.message) ;
s }

oO};

3. Uso del token: Cuando realizas una petición a tu API que requiere autenticación,
incluyes el token de autenticación en el encabezado Authorization de la
peticion.

1 const fetchPrivateData = async (token) => {

2 const response = await fetch('/api/private', {

3 headers: { Authorization: “Bearer ${token}> },
6 3)
6 if (response.ok) {

7 return response. json();

8 } else {

9 throw new Error('Failed to fetch private data');

4. Autorización: En tu API (Backend), verificas el token de autenticación y
compruebas los permisos del usuario antes de procesar la peticidn. Siel token
es invalido o el usuario no tiene los permisos necesarios, devuelves un cédigo
de estado de error HTTP.

Almacenamiento del token en el Web Storage

La Web Storage API proporciona dos mecanismos para almacenar datos en el
navegador del usuario: localStorage y sessionStorage.

Ambos mecanismos son similares en que permiten almacenar pares de clave-
valor y tienen una capacidad de almacenamiento mucho mayor que las cookies. La
principal diferencia entre ellos es que localStorage persiste los datos entre las
sesiones del navegador, mientras que sess ionStorage los borra cuando se cierra
la ventana o la pestafia del navegador.

Aqui tienes un ejemplo de cémo puedes almacenar el token de autenticación en
localStorage:

1 const handleLogin = async (username, password) => {
2 try {

3 const token = await login(username, password);
4 localStorage.setItem('token', token);

5} catch (error) {

6 console.error('Login failed:', error.message);
2 3

835

Y aqui tienes un ejemplo de cémo puedes recuperar el token de localStorage:

1 const token = localStorage.getItem('token');

Implementacion de un Custom Hook para el manejo del token

Podemos encapsular la légica de almacenamiento y recuperación del token en
un Custom Hook para reutilizarla en diferentes partes de nuestra app. Aqui
tienes un ejemplo de como podrias hacerlo:

1 import { useState, useEffect } from ‘react’;
2

3 const useToken = () => {

const [token, setToken] = useState(null);

6 useEffect(() => {

const storedToken = localStorage.getItem('token');
if (storedToken) {

9 setToken(storedToken) ;

10 }
a}, C05

13 const saveToken = (newToken) => {
14 localStorage.setItem('token', newToken);
15 setToken(newToken) ;

ae oS

is return {token, saveToken};
19 5

21 export default useToken;

En este Hook, utilizamos useState para almacenar el token en el estado del
componente y useEffect para recuperar el token de localStorage cuando
se monta el componente. Tambión proporcionamos una función saveToken que
almacena el token en localStorage y actualiza el estado del componente.

Aqui tienes un ejemplo de cémo podrias usar este Hook en tu componente de inicio

de sesion:

1 import useToken from './useToken';
2

3 const Login = () => {

4 const { token, saveToken } = useToken();

6 const handleLogin = async (username, password) => {
? try {
8 const newToken = await login(username, password) ;

9 saveToken(newToken) ;
10 } catch (error) {

console.error('Login failed:', error.message) ;

16 35

Con este Hook, puedes manejar el token de autenticación de manera eficiente
y reutilizar la légica de almacenamiento y recuperación del token en diferentes

partes de tu app.

Soluciones de autenticacion y autorización de terceros

Si bien puedes implementar tu propio sistema de autenticación y autorización,
existen varias soluciones de terceros que pueden facilitarte la tarea. Estas
soluciones proporcionan APIs y bibliotecas que puedes utilizar para autenticar y
autorizar usuarios sin tener que escribir mucho cédigo.

Algunas de estas soluciones incluyen:

- Auth: Auth es un servicio de autenticación y autorización que proporciona
una API y una biblioteca de JS que puedes utilizar para autenticar y
autorizar usuarios en tu app React.

-Firebase Auth: Firebase Auth es un servicio de autenticación proporcionado
por Firebase, un producto de Google. Proporciona una API y una biblioteca de
JS que puedes utilizar para autenticar usuarios con varios métodos,
incluyendo correo electrónico y contrasefia, Google, FB, GitHub y mas.
+NextAuth.js: NextAuth.js es una biblioteca de autenticación para Next.js, un
framework de React. Proporciona una API y varios componentes de React
que puedes utilizar para autenticar usuarios con varios proveedores de
autenticación, incluyendo correo electrónico y contrasefia, Google, FB, y
mas.

Estas soluciones pueden ahorrarte mucho tiempo y esfuerzo, y tambión
proporcionan caracteristicas adicionales como la autenticación en dos factores, la
recuperación de la contraseiia, y la protección contra ataques de fuerza bruta. Sin
embargo, tambión pueden ser mAs costosas y menos flexibles que implementar tu
propio sistema de autenticación y autorización.
Conclusión

En este capitulo, hemos explorado en profundidad cémo interactuar con APIs y
manejar la comunicación con el servidor en una app React. Hemos aprendido
arealizar peticiones HTTP utilizando Fetch y Axios, y a manejar el estado de la carga
y los errores. Tambión hemos explorado cémo crear y utilizar Custom Hooks para
encapsular y reutilizar la légica de las peticiones HTTP.

Ademés, hemos introducido TanStack Query, una popular biblioteca para la
obtención de datos que puede simplificar y optimizar la comunicación con
el servidor. Hemos aprendido a utilizar sus Hooks principales, useQuery y
useMutation, y hemos discutido cémo puede reemplazar a Redux para la gestion

del estado del servidor.

Finalmente, hemos discutido la autenticación y la autorización, dos aspectos
fundamentales de la seguridad en las aplicaciones web. Hemos aprendido a
implementarlas utilizando tokens, y hemos explorado algunas soluciones de

terceros que pueden facilitar esta tarea.

En el préximo capitulo, nos centraremos en la optimización y el rendimiento.
Aprenderemos cémo mejorar la velocidad y la eficiencia de nuestra app
React.
Referencias

«Choi, D. (2020). Full-Stack React, TypeScript, and Node: Build cloud-ready web
applications using React 17 with Hooks and GraphQL. Packt Publishing.

+ Alfonso, D. (2023) State Management with React Query : Improve Developer and
User Experience by Mastering Server State in React. Packt Publishing.

+ Mozilla Developer Network. (2023). Fetch API. https://developer.mozilla.org/
en-US/ docs/Web/API/Fetch_API

+ Axios. (2023). Axios Documentation. https://axios-http.com/docs/intro

+Linsley, T. (2023). React Query Overview. https://react-query.tanstack.com/
overview

+ AuthO. (2023). AuthO Documentation. https://auth0.com/

-«Firebase. (2023). Firebase Authentication. https://firebase.google.com/ docs/
auth

+ NextAuth js. (2023). NextAuth.js Documentation. https://next-authjs.org/

Capitulo 8: Optimización y Rendimiento
Introducción

Una de las razones por las que React ha ganado popularidad en el mundo
de la programación web es su enfoque en la eficiencia y el rendimiento. Sin
embargo, el rendimiento no siempre es algo que se maneja de forma éptima por
defecto. Requiere conocimientos y habilidades especificas para sacar el maximo
provecho de las herramientas que React nos proporciona para optimizar nuestras
aplicaciones.

En este capitulo, aprenderemos técnicas y mejores practicas para mejorar el

rendimiento de nuestras aplicaciones React. Desde la virtualización y paginación
de listas hasta la memoización de componentes, el code splitting y el lazy
loading, cada sección de este capitulo se centrard en una técnica especifica,
proporcionandote la teoria y ejemplos de cédigo.

Si algun concepto te resulta particularmente desafiante, te recomiendo que sigas a
joan León (@nucliweb) y a Estela Franco (@guaca). Ambos son personas expertas en
el campo de la optimización del rendimiento web y ofrecen valiosos recursos para

profundizar en estos temas.
Paginacion de listas

La paginación de listas es una técnica crucial en el dev de aplicaciones web
para gestionar grandes conjuntos de datos. En lugar de cargar y mostrar todos los
datos de una vez, que puede ser ineficiente y llevar a un pobre rendimiento de la
app, la paginación divide los datos en paginas mas manejables.

El usuario puede entonces navegar a través de estas paginas de manera
incremental. Esta técnica no sdlo mejora el rendimiento de la app al reducir
la carga inicial de datos, sino que tambión mejora la experiencia del usuario al
presentar los datos de manera ms organizada y manejable.

Paginación con React-Router-Pagination

Un paquete muy ttil para implementar la paginación en aplicaciones React
es react-router-pagination. Esta biblioteca proporciona una serie de
componentes y hooks para manejar la paginación en combinación con react-
router, el estandar de facto para la gestión de rutas en React.

Aqui te dejo un ejemplo de cémo se podria implementar la paginación de una lista

con react-router-pagination:

1 import React from ‘react’;
2 import { BrowserRouter as Router, Route } from 'react-router-

dom
3 import Pagination from ‘react-router-pagination' ;
4 import ListItem from './ListItem';

6 function App() {
7 const [items, setItems] = React.useState([]);

9 React.useEffect(() {
10 fetch('https://api.misdatos.com/lista')
1 .then(response => response. json())

12 -then(data => setItems(data.items));

21

itemsPerP\
22 age);

23

24

25

26

item=\

%, (Ds

return (
<Router>
<Route path="

age?" render={({ match }) => {

const page = parseInt(match.params.page, 10)
const itemsPerPage
const offset = (page - 1) * itemsPerPage;

const pagedItems =

return (

<div>

= 10;

items.slice(offset,

I] 45

offset +

{pagedItems.map(item => <ListItem key={item. id}

27 {item} />)}

28

5

<Pagination

total={items. length}
itemsPerPage={itemsPerPage}

currentPage=
/>
</div>

page}
35 3} />
36 </Router>

a7 OS

40 export default App;

En este ejemplo, utilizamos react-router-pagination para generar los
enlaces de paginación. Cada pagina muestra 10 elementos de la lista (definidos por
itemsPerPage). La pagina actual se determina a partir del parametro de la ruta
(match. params. page). Los elementos para la pagina actual se obtienen del array
items utilizando slice.

Por ultimo, el componente Pagination de react-router-pagination se
utiliza para mostrar los enlaces de paginación en la parte inferior de la lista.

Este es un concepto basico de la paginación en React con esta biblioteca. Te invito a

explorarla mas a fondo y practicar para dominar la paginación de listas.
Paginacion con React Query

Ya hemos visto anteriormente React Query (TanStack Query). Adems de que es una
biblioteca muy potente que provee hooks para realizar acciones asincronas y gestion
de estado; entre sus caracteristicas se encuentra la paginacion de listas.

A diferencia del ejemplo anterior donde la paginación era manejada
completamente en el cliente, React Query nos permite implementar una paginación
del lado del servidor, lo que puede ser mucho mas eficiente para conjuntos de datos

muy grandes.

Aqui te presento un ejemplo de cémo implementar la paginación de listas con React
Query:

1 import { useEffect } from ‘react’
2 import axios from 'axios'

3 import {

4 useQuery,

5  useQueryClient,

6 QueryClient,

2 QueryClientProvider,

8 } from ‘@tanstack/react-query'

9 import { ReactQueryDevtools } from '@tanstack/react-query-
devtool\

10 s'

11
12 const queryClient = new QueryClient()

13

14 export default function App() {

15 return (

16 <QueryClientProvider client={queryClient}>
17 <Example />

</QueryClientProvider>

22 asyne function fetchProjects(page = 0) {

23 const { data } = await axios.get('/api/projects?page=' +
page)

24 return data
26 55}

27 function Example() {
P En este ejemplo, se utiliza el hook useQuery para hacer la solicitud de datos a la

28 const queryClient = useQueryClient() - . we . .
API. Esta funcion toma un objeto de configuracion con varias opciones:

29 const [page, setPage] = React.useState(0)

+ queryKey: una clave unica que identifica los datos de la consulta.

const {
3 status, + queryFn: una funcion que realiza la consulta real y devuelve una promesa. Esta
33 data, función recibe la pagina actual como argumento.
34 error, + keepPreviousData: cuando cambia la clave de la consulta (en este caso, la
35 isFetching, pagina), React Query mantendré los datos antiguos hasta que la nueva consulta
36 isPreviousData
se resuelva.
37 -} = useQuery({ . . ae ‘ A
ope . . + staleTime: tiempo en milisegundos durante el cual los datos se consideraran
38 queryKey: ['projects', pagel,
39 queryFn: () => fetchProjects(page) , recientes después de una actualización. Una vez que los datos se vuelven
40 keepPreviousData: true, obsoletos, React Query refetchard automaticamente los datos en background
a1 staleTime: 5000, cuando sean requeridos.
ae })
43 El hook useQuery devuelve un objeto que contiene el estado de la consulta
4s // Hace Prefetch de la siguiente pagina! (status), los datos recuperados (data), cualquier error que ocurrié (error), una
45 useEffect(() => { indicación de si la consulta esta actualmente buscando datos (isFetching), y
46 if (data?.hasMore) { Pa Teer A ates. -
. una indicacion de si los datos de la consulta son de la ultima consulta exitosa
47 queryClient : :
as -prefetchquery( (isPreviousData).
49 ['projects', page + 1], () => fetchProjects(page +
Se usa la función set Page para cambiar la pagina actual cuando se presionan los
) botones de navegación de la pagina.
}
52 }, [data, page, queryClient]) Se usa useEffect para realizar la precarga de la siguiente pagina de datos tan

53 pronto como se cargue la pagina actual. Esto puede mejorar la experiencia del
usuario, ya que los datos de la siguiente pagina estaran listos inmediatamente
cuando se navegue ala siguiente pagina.
Memoizacion de componentes

La memoización es una técnica de optimización que se usa para acelerar las
aplicaciones al almacenar los resultados de operaciones costosas y reutilizindolos
en lugar de volver a ejecutar las operaciones. En React, la memoización puede
aplicarse a los componentes y las funciones para evitar el renderizado o los clculos

innecesarios.

En React, tenemos dos mecanismos principales para realizar la memoización:
React.memo yuseMemo.

React.memo

React. memo es un componente de orden superior que memoriza el resultado de

renderizado de un componente y lo reutiliza hasta que cambien sus props.

Veamos un ejemplo:

1 const MyComponent = React.memo(function MyComponent (props) {
20 I/we

5

En este ejemplo, React.memo envuelve el componente MyComponent. Si las
props de MyComponent no cambian entre renderizados, React reutilizaré el ultimo
resultado de renderizado, evitando asi un renderizado innecesario.

useMemo

useMemo es un hook que memoriza el resultado de una función. Es util cuando
tienes funciones costosas en cémputo que dependen de ciertos valores y no quieres

que se vuelvan a ejecutar a menos que esos valores cambien.

Aqui hay un ejemplo de cémo usar useMemo:

1 const MyComponent = (props) => {

2 const computedValue = React.useMemo(() => {

3 /* Operaciones con un coste alto de cémputo */
3, [props.value]);

6 return /* Renderizado del componente que usa computedValue */

En este ejemplo, useMemo toma dos argumentos: una función y una lista de
dependencias. La función se ejecutara y su resultado se memorizara la primera
vez que se renderice el componente. En renderizados posteriores, useMemo
comprobard si alguna de las dependencias ha cambiado. Si no han cambiado,
useMemo devolvera el valor memorizado en lugar de volver a ejecutar la función.

La memoización puede ser una herramienta muy potente para optimizar tus
componentes React y prevenir renderizados innecesarios.

Sin embargo, como cualquier herramienta de optimización, debe usarse con
cuidado. Memorizar todo puede llevar a un uso excesivo de memoria y, en realidad,
reducir el rendimiento. Por lo tanto, solo debes usar React.memo y useMemo
cuando sepas que hay un cuello de botella en el rendimiento y hayas medido que la
memoización mejora la velocidad de tu app.
Code Splitting y Lazy Loading

La optimización del rendimiento no siempre implica hacer que el cédigo existente
sea més eficiente. A veces, implica simplemente cambiar cuando y cémo se
entrega ese cédigo. Dos técnicas muy efectivas para mejorar el rendimiento de las
aplicaciones web, en particular, son el code splitting y el lazy loading.

Code Splitting

El code splitting es el proceso de dividir el cédigo de tu app en multiples
bundles (paquetes) que pueden ser cargados bajo demanda. Las herramientas
modernas como Vite y Next.js, que son cada vez mas populares para la creación de
aplicaciones React, tienen soporte incorporado para ello.

Esto significa que cada vez que un usuario carga tu app, solo se esta
descargando el cédigo necesario para la carga inicial de la pagina. El resto del
cédigo se puede cargar bajo demanda segtin sea necesario, lo que puede mejorar
significativamente los tiempos de carga, especialmente para aplicaciones grandes.

Para Vite, la configuración de code splitting puede estar en el archivo
vite.config. js. Vite divide automaticamente el cddigo cuando se utiliza
import () de forma dinamica.

1 // vite.config.js

2 export default {

5 build: {

4 rollupOptions: {
5 input: {

6 main: '/path/to/main.js',
nested: '/path/to/nested.js',

En este ejemplo, Vite creard dos bundles separados para main. js y nested. js.
Cuando se visite la ruta correspondiente, solo se cargaré el bundle correspondiente.

La app del code splitting puede tener un gran impacto en el rendimiento de
tu app, permitióndote cargar solo el cédigo que es necesario, lo que mejora la
eficiencia y la experiencia del usuario.

Lazy Loading

El lazy loading es una técnica de optimización que consiste en retrasar la
inicialización o la carga de ciertos aspectos de tu app hasta que realmente
sean necesarios. Esto puede mejorar significativamente la eficiencia de tu
app, ya que reduce la cantidad de trabajo que debe realizarse durante la carga
inicial de la pagina.

La idea detras del lazy loading es simple: En lugar de cargar todo de una vez, divide
la carga en multiples etapas, de tal manera que sdlo los componentes necesarios
para el renderizado inicial de la pagina se cargan de inmediato. El resto de los
componentes se carga en segundo plano o cuando se necesiten, lo que ayuda a
mejorar la eficiencia y la experiencia del usuario.
React incorpora una función llamada React. 1lazy() que te permite renderizar
importaciones dindmicas de manera muy sencilla, como componentes que se
cargan de manera diferida.

Veamos un ejemplo mas completo de cémo puedes usar React. lazy() y
Suspense para hacer lazy loading de un componente:

1 import React, { Suspense } from 'react';
2

3 const LazyComponent = React. lazy(

4 () => import('./LazyComponent' )

53

6

7 function MyComponent() {

8 return (

9 <div>

10 <Suspense fallback={<div>Cargando. ..</div>}>
14 <LazyComponent />

12 </Suspense>

43 </div>

14 5

as }

1? export default MyComponent;

En este ejemplo, React.lazy() esta importando dinamicamente un

componente. Esto significa que LazyComponent no se cargard hasta que
sea necesario. El componente Suspense permite especificar un contenido de
“fallback” que se mostrar mientras el componente est cargando.

Aunque este es un ejemplo basico, puedes aplicar la misma idea a cualquier
componente de tu app. Por ejemplo, podrias decidir hacer lazy loading
de ciertas partes de tu app que no son criticas para la carga inicial de
la pagina, pero que podrian ser necesarias mas adelante. Esto puede mejorar
significativamente la eficiencia y la experiencia del usuario.

Una nota adicional: React.1lazy() y <Suspense> no son atin 100%
compatibles con la renderización en el lado del servidor (SSR). Para las
bibliotecas que admiten SSR, puedes usar una solución mas tradicional como
import () para dividir el cédigo.

Next, el framework de React esta empezando a implementarlo en sus tltimas
versiones.

Para resumir, el lazy loading puede ser una potente herramienta para mejorar
el rendimiento de tu app. Al retrasar la carga de ciertos aspectos de tu
app hasta que sean necesarios, puedes reducir la cantidad de trabajo que se
debe realizar durante la carga inicial de la pagina, lo que puede resultar en una carga
de pagina mas rapida y una mejor experiencia para el usuario.
Uso eficiente de Context y Redux en React

Contexto en React

El contexto en React se utiliza para compartir datos entre componentes sin tener
que pasar explicitamente a través de cada nivel del arbol de componentes (props
drilling). Sin embargo, es importante entender que cada vez que cambia el valor
del contexto, todos los componentes que consumen ese contexto se volveran a

renderizar.

Para evitar renderizados innecesarios, se puede dividir el contexto en multiples
contextos segtin la granularidad de los datos. Es decir, en lugar de tener un sélo gran
contexto, puedes tener varios contextos mas pequefios.

Aqui te dejo un ejemplo de cémo hacerlo:

1 import React from ‘react’;

2

3 // Creamos dos contextos separados

4 const UserContext = React.createContext();

5 const ThemeContext = React.createContext();

6

7 export function App() {

8 const [user, setUser] = React.useState(null);

9° const [theme, setTheme] = React.useState('light');
10

11 return (

12 <UserContext.Provider value={{ user, setUser }}>

43 <ThemeContext.Provider value={{ theme, setTheme }}>
14 <MyComponent />
</ThemeContext . Provider>

</UserContext.Provider>

20 function MyComponent() {
21 // Ahora cada componente puede consumir solo el contexto que
ne\

22 cesita

23 const { user } = React.useContext (UserContext) ;

24 const { theme } = React.useContext(ThemeContext) ;

25

26 // Resto del componente...

2)

Redux en React

Redux es una biblioteca de manejo del estado de forma global, muy utilizada en
React. Sin embargo, al igual que el contexto, cualquier cambio en el store de Redux
puede causar un renderizado en todos los componentes que estón conectados a ese
store.

Para evitar esto, puedes dividir tu store de Redux en miltiples slices mas pequefios
usando createSlice de Redux Toolkit, y luego sdlo conectar los componentes a
los slices del store que realmente necesitan. Esto significa que solo se renderizaran
cuando los datos que estan utilizando cambien.

Aqui te dejo un ejemplo de cémo se veria:
1

toolkit

import { createSlice, configureStore } from

‘@reduxjs/

2 import { Provider, useSelector } from '‘react-redux';

3

// Creamos dos slices separados
const userSlice = createSlice({
name: ‘user’,

initialstate: null,
reducers: {
setUser: (state, action) => action.payload,
3,
ys;

const themeSlice = createSlice({
name: ‘theme’,
initialstate: ‘light’,
reducers: {
setTheme: (state, action) => action.payload,
},
v3

// Configuramos nuestro store con ambos slices
const store = configureStore({
reducer: {
user: userSlice.reducer,
theme: themeSlice.reducer,
3,
yD;

export function App() {

30 return (

31 <Provider store={store}>
32 <MyComponent />

33 </Provider>

Ba NG

35 }

36
37 function MyComponent() {

38 // Ahora cada componente solo selecciona los datos que
necesita\

39 del store

40 const user = useSelector((state) => state.user);

41 const theme = useSelector((state) => state.theme) ;

42

43 // Resto del componente...

44}

Tanto con el Contexto de React como con Redux, el objetivo es mantener los
renderizados de los componentes al minimo para optimizar el rendimiento. Esto se
logra asegurandose de que cada componente solo se suscriba a los cambios en los
datos que realmente necesita.
Conclusión

En este capitulo, hemos profundizado en los conceptos de optimización y
rendimiento en React. Hemos explorado cémo la paginación de listas puede ayudar
a manejar grandes conjuntos de datos de manera eficiente, cémo la memoización
puede prevenir renderizados innecesarios, y cémo la división de cédigo y el
lazy loading pueden mejorar el tiempo de carga de nuestra app. Ademas,
discutimos varias mejores practicas de rendimiento en React, como el uso eficiente
del Contexto y Redux.

Es importante recordar que la optimización y el rendimiento son aspectos cruciales
del dev de aplicaciones web. Asegurarse de que tu app se ejecute de
manera eficiente puede llevar a una mejor experiencia del usuario, y puede marcar
la diferencia en la percepción del usuario sobre la calidad de tu app.

En el préximo capitulo, cambiaremos nuestra atención al testing de frontend. El
testing es necesario para el dev de sw, que garantiza que tu cédigo
funcione como se espera y ayuda a prevenir bugs antes de que lleguen a producción.

Capitulo 9: Pruebas y calidad del codigo

Introducción al Testing

El dev de sw es un proceso complejo y multifacético. No solo implica
escribir cédigo que funcione, sino tambión asegurarse de que ese cédigo funcione
correctamente en todas las situaciones posibles. Aqui es donde entra en juego el
testing o las pruebas de sw.

Las pruebas de sw (tests) son una parte integral del ciclo de vida del dev
de sw. Nos permiten verificar que nuestro cédigo hace lo que se supone
que debe hacer y nos ayudan a detectar y corregir errores antes de que lleguen a
producción. En otras palabras, las pruebas nos ayudan a garantizar la calidad de
nuestro sw.

Existen varios tipos de pruebas que podemos realizar, cada una con un propésito

especifico:

E2E Tests

Integration Tests

Unit Tests

Piramide del testing

+ Pruebas unitarias (Unit tests): Estas pruebas se centran en pequefias unidades
de cédigo, como funciones o métodos individuales. El objetivo es asegurarse de
que cada parte del cédigo funcione correctamente de forma aislada.

+ Pruebas de integración (Integration Tests): Estas pruebas se centran en c6mo
diferentes partes del cédigo trabajan juntas. El objetivo es asegurarse de que el
sistema, como un todo, funcione correctamente.

- Pruebas de aceptación (Acceptance Tests): Estas pruebas se realizan desde la
perspectiva del usuario final y se aseguran de que el sistema cumpla con los
requisitos especificados.

En este capitulo, nos centraremos en las pruebas unitarias y de integración
utilizando Jest y Vitest, las pruebas de componentes con React Testing Library, y
cémo mantener nuestro cédigo limpio y de calidad con Eslint y Prettier. Tambión
cubriremos cémo realizar un anilisis de cobertura de pruebas (Code Coverage)
para asegurarnos de que todas las partes de nuestro cédigo estón adecuadamente

probadas.

Aunque este libro no trata exclusivamente de pruebas, te recomiendo el siguiente
libro si quieres profundizar en ello: Testing Frontend de Iago Lastra Rodriguez
(@iagolast).
Jest y Vitest: Pruebas unitarias y de integracion

Jest

Jest es una popular biblioteca de pruebas de JS creada por FB.
Es conocida por su simplicidad y facilidad de uso, lo que la hace ideal para
principiantes. Jest es capaz de ejecutar pruebas unitarias y de integración, y viene
con una serie de caracteristicas utiles como la simulación de funciones (mocking), la
generación de informes de cobertura de pruebas, y la capacidad de ejecutar pruebas
en paralelo para un rendimiento mas rapido.

Para instalar Jest en tu proyecto, puedes usar npm con el siguiente comando:

1 $ npm install --save-dev jest

Una vez instalado, puedes crear un archivo de prueba con la extensión . test. js.
Por ejemplo, si tienes un archivo sum. js que quieres probar, puedes crear un
archivo sum. test. js enel mismo directorio.

Aqui tienes un ejemplo de cémo podria ser una prueba unitaria basica con Jest:

1 // Fichero: sum. js

2 function sum(a, b) {
3 return a + b;

a)

5

6 module.exports = sum;

8 // Fichero: sum.test.js
9 const sum = require('./sum');

11 test('adds 1 + 2 to equal 3',
2 expect(sum(1, 2)).toBe(3);
3)3

O => {

Eneste ejemplo, test es una función global proporcionada por Jest que define una
prueba. La función expect se utiliza para hacer afirmaciones sobre lo que el cédigo
deberia hacer, y .toBe() es un “matcher” que comprueba si el valor esperado
coincide con el valor real.

Vitest

Vitest es una herramienta de pruebas para Vite, el entorno de dev y
compilador para JS. Aunque este libro se centra en React, es importante
mencionar Vitest porque es una excelente opcidn para pruebas si estas utilizando
Vite en tu proyecto.

Vitest ofrece una experiencia de pruebas similar a Jest, pero esta optimizado para

Vite y tiene algunas caracteristicas adicionales, como el soporte para pruebas
en navegadores reales y la capacidad de importar componentes Vue y React
directamente en tus pruebas.

Para instalar Vitest, puedes usar npm con el siguiente comando:

1 npm install --save-dev vitest
Aqui tienes un ejemplo de cémo podria ser una prueba unitaria con Vitest:

1 // Fichero: sum. js
2 export function sum(a, b) {
3 return a + b;

6 // Fichero: sum.test.js

7 import { it, expect } from ‘vitest';
8 import { sum } from './sum';
9

10 it('adds 1 + 2 to equal 3',
11 expect(sum(1, 2)).toBe(3);
12 3)5

Of

Como puedes ver, la sintaxis de las pruebas es muy similar a la de Jest, lo que hace
que la transición entre las dos herramientas sea bastante sencilla.

Vitest es una excelente opción para las pruebas, especialmente si estas utilizando
Vite en tu proyecto. Vite es un entorno de dev y compilador moderno y
rapido para JS, y es recomendado por el equipo de React para construir
aplicaciones de una sola pagina (SPA). Vitest esta optimizado para Vite y requiere
practicamente cero configuración, lo que facilita su uso.

Veamos algunos ejemplos mas complejos de pruebas con Vitest.
Ejemplo 1: Prueba de una función asincrona

Supongamos que tienes una función asincrona que recupera datos de una API.

Podrias querer probar que esta función devuelve los datos esperados.

1 // Fichero: api.js

2 export async function fetchData() {

3 const response = await fetch('https://api.example.com/
data’);

4 const data = await response. json();

5 return data;

8 // Fichero: api.test.js
9 import { it, expect } from 'vitest';
10 import { fetchData } from './api';

12 it('fetchData returns expected data', async () => {

13. const data = await fetchData();

14 expect (data).toEqual({ key: ‘value' });

15 // Asume que { key: ‘value’ } es la respuesta esperada

16 3)

En este ejemplo, usamos la palabra clave async en nuestra prueba para poder
usar await dentro de ella. Esto es necesario porque fetchData es una función
asincrona que devuelve una promesa.

Ejemplo 2: Prueba de un componente React.

Vitest tambión puede ser utilizado para probar componentes React con ayuda de
otra potente biblioteca: Testing Library. Supongamos que tienes un componente
Button que quieres probar.
1// Fichero: Button. js
2 import React from ‘react’;
3 import { it, vi, expect } from ‘vitest';

5 export function Button({ onClick, children }) {
6 return (

7 <button onClick={onClick}>
8 {children}
9 </button>

10 (5

a}

13 // Fichero: Button.test.js

14 import { render, fireEvent } from ‘@testing-library/react';

15 import { Button } from './Button';

17 it('Button triggers onClick when clicked’, () => {
1s // const handleClick = jest.fn();

19 const handleClick
vi.fn() .mockImplementation('handleClick');

20 const { getByText } = render(

24 <Button onClick={handleClick}>
22 Click me

23 </Button>

2)

25

26 fireEvent.click(getByText('Click me'));
27

28 expect (handleClick) .toHaveBeenCalled();
29 3);

En este ejemplo, usamos la biblioteca @testing-library/react para
renderizar nuestro componente y simular un clic en él. Luego, verificamos que la

función handleC1ick fue llamada cuando se hizo clic en el botón.

Estos son solo algunos ejemplos de lo que puedes hacer con Vitest. En los siguientes
apartados, aprenderemos mas sobre como realizar pruebas de componentes con
React Testing Library.
React Testing Library: Pruebas de componentes

React Testing Library es una biblioteca muy popular para probar componentes de
React. Su filosofia se basa en probar el sw de la misma manera que el usuario
final lo utilizaria, lo que ayuda a crear pruebas mas robustas y significativas.

Para instalar React Testing Library, puedes usar npm con el siguiente comando:

1 npm install --save-dev @testing-library/react

React Testing Library proporciona una serie de funciones utiles para interactuar con
tus componentes y verificar su comportamiento. Veamos algunos ejemplos.

Ejemplo 1: Prueba de renderizado y contenido de texto

Supongamos que tienes un componente Greet ing que muestra un saludo basado
en una prop name.

1 // Fichero: Greeting. js

2 import React from 'react';

3

4 export function Greeting({ name }) {

5 return <h1>Hello, {name}!</h1>;

6}

7

8 // Fichero: Greeting. test.js

9 import { it, expect } from ‘vitest';

10 import { render, screen } from '@testing-library/react';

import { Greeting } from './Greeting';

it('Greeting renders with correct text', () => {

render(<Greeting name="John" />);
const heading = screen. getByRole('heading', {
6 name: ‘Hello, John!"
17 ¥)S
18 expect (heading) .toBeInTheDocument () ;
19 })5

En este ejemplo, usamos la función render para renderizar nuestro componente
y screen. getByRole para seleccionar el elemento que queremos probar. Luego,
usamos expect y toBeInTheDocument para verificar que el elemento esta
presente en el documento.

Ejemplo 2: Prueba de interacción del usuario

Ahora, supongamos que tienes un componente Button que cambia su texto
cuando se hace clic en él.

1 // Fichero: Button. js

2 import React, { useState } from ‘react’;

3

4 export function Button() {

5 const [text, setText] = useState('Click me');

? const handleClick
8 setText('Clicked');
9 4s

a1 return (
12 <button onClick={handleClick}>

13 {text}
44 </button>
as 5

16 }

17

18 // Fichero: Button.test.js

19 import { it, expect } from 'vitest';

20 import { render, screen, fireEvent } from '@testing-library/
react\

21 "5

22 import { Button } from './Button';

23

24 it('Button changes text when clicked', () => {
25  vrender(<Button />);

26 const button = screen.getByRole('button', {
27 name: ‘Click me'

28)

29

30 fireEvent.click(button) ;

31

32 expect (button) .toHaveTextContent('Clicked');
33 )3

En este ejemplo, usamos fireEvent.click para simular un clic en el botón, y
luego verificamos que el texto del botón ha cambiado como se esperaba.

Ejemplo 3: Prueba de renderizado condicional

Finalmente, supongamos que tienes un componente Alert que se muestra solo si

se pasa una prop show.

1 // Fichero: Alert. js

2

3
4

import React from ‘react’;

export function Alert({ show, children }) {
if (!show) {
return null;

return <div>{children}</div>;

// Fichero: Alert.test.js

import { it, expect } from 'vitest';

import { render, screen } from '@testing-library/react';
import { Alert } from './Alert';

it('Alert shows children when show is true’, ()
render(<Alert show={true}>Test Alert</Alert>) ;
const alert = screen. getByText('Test Alert’);
expect (alert) .toBeInTheDocument () ;

Ys

it(‘Alert does not show children when show is false’, () =>
render(<Alert show={false}>Test Alert</Alert>) ;
const alert = screen.queryByText('Test Alert’);
expect (alert) .not.toBeInTheDocument() ;

Ys
En este ejemplo, usamos dos pruebas para verificar el comportamiento de
renderizado condicional de nuestro componente. Usamos screen. getByText
para seleccionar el elemento cuando esperamos que esté presente, y
screen. queryByText cuando esperamos que no lo esté.

Estos son solo algunos ejemplos de lo que puedes hacer con React Testing Library. En
el siguiente apartado, aprenderemos sobre Eslint y Prettier y como pueden ayudarte
a mantener tu cédigo limpio y ordenado.
ESlint y Prettier

Mantener un cédigo limpio y bien formateado es esencial para la calidad del
sw. No solo hace que el cddigo sea mas facil de leer y entender, sino que
tambión puede ayudar a prevenir errores. Aqui es donde entran en juego ESlint y
Prettier.

ESlint

ESlint es una herramienta de linting para JS. El “linting” es el proceso
de analizar el cédigo en busca de posibles errores 0 problemas de estilo. ESlint
viene con un conjunto de reglas predefinidas que puedes personalizar segiin tus
necesidades. Tambión es extensible, lo que significa que puedes escribir tus propias
reglas o utilizar plugins para afiadir mas funcionalidades.

Para instalar ESlint en tu proyecto, puedes usar npm con el siguiente comando:

1 mpm install --save-dev eslint

Una vez instalado, puedes crear un archivo .eslintrc. js en la raiz de tu
proyecto para configurar las reglas de ESlint. Aqui tienes un ejemplo de cémo podria
ser una configuración basica:

1 module.exports = {
2 env: {

3 browser: true,
4 es2021: true,

5},

6 extends: [

? ‘eslint: recommended’,

8 ‘plugin:react/recommended',
s 1,

0 parserOptions: {

11 ecmaFeatures: {

jsx: true,

13 },

14 ecmaVersion: 12,

45 sourceType: ‘module’,
16 6},

1” plugins: [

18 ‘react’,

sol,

20 rules: {

21 ‘react/prop-types': ‘off’,
22},

23 35

Esta configuración habilita las reglas recomendadas para JS y React, y
desactiva la reglareact/prop-types.

Prettier

Prettier es una herramienta de formateo de cédigo para JS. A diferencia
de Eslint, que se centra en la calidad del cédigo, Prett ier se centra en el estilo del
cédigo. Prettier formatea tu cddigo de manera consistente y automatica, lo que

ayuda a mantener un estilo coherente en todo el proyecto.
Para instalar Prettier en tu proyecto, puedes usar npm con el siguiente
comando:

1 $ npm install --save-dev prettier

Una vez instalado, puedes crear un archivo . prettierrc en la raiz de tu proyecto
para configurar las reglas de Prettier. Aqui tienes un ejemplo de cémo podria ser una
configuración basica:

af

2 "semi": true,

3 “trailingComma": "all",
4 "“singleQuote": true,

5 “printWidth"
6 "“tabWidth": 2
7}

80,

Esta configuración especifica que se deben usar punto y coma al final de las
sentencias, que se deben usar comillas simples en lugar de dobles, que la longitud
maxima de la linea debe ser de 80 caracteres y que se deben usar dos espacios para
laindentación.

Integración de Eslint y Prettier
ESlint y Prettier pueden trabajar juntos para proporcionar una experiencia de

dev mas fluida. Puedes configurar ESlint para que utilice Prettier como
formateador de cédigo, y para que ignore las reglas de estilo que Prettier ya maneja.

Para hacer esto, primero necesitas instalar el plugin eslint-plugin-prettier
y elconfigurador eslint-config-prettier:

1 mpm install --save-dev eslint-plugin-prettier eslint-config-
prett\
2 ier

Luego, puedes actualizar tu archivo .eslintrc. js para utilizar estos paquetes:

1 module.exports = {

2 SL ase
3 extends: [

4 ‘eslint:recommended',

5 ‘plugin: react/recommended',

6 ‘plugin:prettier/recommended', // Afiade esto
ro],

8 //...

9};

Con esta configuración, ESlint utilizara Prettier para formatear tu cdédigo y
desactivara las reglas de estilo que entran en conflicto con Prettier.

Estas son solo algunas de las cosas que puedes hacer con ESlint y Prettier. En
el siguiente apartado, aprenderemos sobre el andlisis de cobertura de pruebas y
como puede ayudarte a asegurarte de que todas las partes de tu cédigo estón
adecuadamente probadas.
Analisis de cobertura de pruebas

El andlisis de cobertura de pruebas (Code Coverage) es una medida que nos ayuda a

entender qué porcentaje de nuestro cddigo esta siendo probado o testeado.
La cobertura de pruebas se suele dividir en varias categorias:

+ Cobertura de lineas: ;Qué porcentaje de las lineas de cédigo se han ejecutado
durante las pruebas?

+Cobertura de funciones: :Qué porcentaje de las funciones se han llamado
durante las pruebas?

-Cobertura de ramas: ;Qué porcentaje de las ramas del cédigo (como las
sentencias if y switch) se han ejecutado durante las pruebas?

+ Cobertura de sentencias: ;Qué porcentaje de las sentencias se han ejecutado
durante las pruebas?

Tanto Jest como Vitest vienen con herramientas integradas para generar informes
de cobertura.

Generar un informe de cobertura con Jest

Para generar un informe de cobertura con Jest, puedes afiadir el flag - - coverage
cuando ejecutes tus pruebas:

1 $ npx jest --coverage

Generar un informe de cobertura con Vitest

Para generar un informe de cobertura con Vitest, puedes afiadir el flag --
coverage cuando ejecutes tus pruebas:

1 $ npx vitest --coverage

Al igual que con Jest, esto generara un informe de cobertura en la consola y un
directorio coverage en tu proyecto con un informe mas detallado.

Interpretar un informe de cobertura

Un informe de cobertura de pruebas tipicamente te dara un porcentaje de cobertura
para cada una de las categorias mencionadas anteriormente, tanto para cada

archivo individualmente como para todo el proyecto.

Por ejemplo, podrias ver algo como esto:

3 File | % Stmts | % Branch | % Funcs | % Lines |
Uncove\
4 red Line #s

7? All files | 98.28 | 100 | 100 | 98.25 |
9 MyComponent.js | 98.28 | 100 | 100 | 98.25 | 42

En este ejemplo, casi todas las lineas, funciones y ramas de MyComponent. js

estan cubiertas por las pruebas, excepto la linea 42.

Es importante recordar que la cobertura del 100% no siempre es necesaria, ni
siquiera siempre es deseable. Algunas partes del cédigo pueden ser dificiles de
probar, o pueden ser tan simples que las pruebas no aporten mucho valor. En lugar
de apuntar a una cobertura del 100%, es mejor utilizar la cobertura de pruebas
como una herramienta para identificar 4reas que podrian beneficiarse de mas
pruebas.
Cypress y Playwright: Pruebas de extremo a extremo

Las pruebas de extremo a extremo (E2E: end to end) son una metodologia utilizada
para probar si el flujo de una app se esta ejecutando como se espera desde el
inicio hasta el final.

El propésito de realizar pruebas de extremo a extremo es identificar problemas del
sistema y garantizar que la app funciona correctamente en su conjunto. En
este apartado, vamos a hablar de dos herramientas populares para realizar pruebas

E2E: Cypress y Playwright.
Cypress
Cypress es un framework de pruebas de extremo a extremo que hace que la

configuración, escritura, ejecución y depuración de pruebas para aplicaciones web
sea bastante sencilla. Cypress tambión toma instantaneas o capturas a medida que

se ejecutan tus pruebas. Puedes “viajar en el tiempo” para ver cémo se veia tu

app en cualquier punto de la prueba.

Para instalar Cypress, puedes usar npm con el siguiente comando:

1 $ npm install --save-dev cypress

Una vez instalado, puedes abrir Cypress con el siguiente comando:

1 $ npx cypress open

Esto abrira el Cypress Test Runner, que es la interfaz grafica de usuario que viene con
Cypress.

Aqui tienes un ejemplo de cémo podria ser una prueba E2E con Cypress:

1 // cypress/integration/sample_spec. js
2 describe('My First Test’, () => {

3 it('Visits the Kitchen Sink', () => {

4 cy.visit('https://example.cypress.io')

5 // visita una pagina

? cy.contains('type').click()

8 // busca un elemento que contenga "type" y hace clic en él

10 // Verifica que la URL deberta incluir '/commands/actions'
11 cy.url().should('include', '/commands/actions')

13 // Obtiene un elemento de entrada con atributo name
14 // igual a ‘email’ y escribe en él

15 cy.get('[name=email]').type('fake@email.com')

as 3)

Playwright

Playwright es una biblioteca de Node.js para automatizar los navegadores
Chromium, Firefox y WebKit con una unica API. Playwright permite escribir
pruebas fiables y rapidas de extremo a extremo en un entorno real de navegador.
Para instalar Playwright, puedes usar npm con el siguiente comando:

1 $ npm init playwright@latest

Este es un ejemplo de pruebas de extremo a extremo utilizando Playwright. En este
caso, se estan realizando dos pruebas diferentes en el sitio web de Playwright.

1 import { test, expect } from '‘@playwright/test';
2

3 // Primera prueba: Verifica que el titulo de la
4 // pagina contenga la palabra "Playwright"

5 test('has title', asyne ({ page }) => {

6 // Navega a la pagina web de Playwright

7 await page.goto('https://playwright.dev/');

9 // Espera que el tttulo de la pdgina contenga

10 //la palabra "Playwright"

11 await expect (page).toHaveTitle(/Playwright/);

123)3

13

14 // Segunda prueba: Verifica que el enlace "Get started"
15 // redirige a la pdgina correcta

16 test('get started link’, asyne ({ page }) => {

17 // Navega a la pdgina web de Playwright

18 await page.goto('https://playwright.dev/');

20 // Hace clic en el enlace que tiene el texto "Get started"

24 await page.getByRole('link', { name: ‘Get

started’ }).click();

23 // Espera que la URL de la pdgina contenga la palabra "intro"

24 await expect(page).toHaveURL(/.*intro/);

25 3)5

En la primera prueba, toHaveTitle(/Playwright/) verifica que el titulo de
la pagina contenga la palabra “Playwright”. La barra inclinada / alrededor de
Playwright indica que es una expresión regular, lo que significa que estamos
buscando cualquier titulo que contenga la palabra “Playwright”, no solo los titulos
que son exactamente “Playwright”.

En la segunda prueba, getByRole('link', { name: 'Get started' })
selecciona un enlace con el texto “Get started”. Luego, .click() hace clic en ese
enlace. Finalmente, toHaveURL(/.*intro/) verifica que la URL de la pagina
contenga la palabra “intro”. Esto es util para comprobar que el enlace “Get started”
redirige a la pagina correcta.

Con esto concluimos nuestro recorrido por el mundo del testing y la calidad del
cédigo en React. Hemos aprendido sobre la importancia de las pruebas, como
implementar pruebas unitarias y de integración con Jest y Vitest, como probar
componentes de React con React Testing Library, y como mantener nuestro cédigo
limpio y de alta calidad con Eslint y Prettier. Tambión hemos explorado cé6mo
realizar un analisis de cobertura de pruebas para asegurarnos de que todas
las partes de nuestro cédigo estón adecuadamente probadas. Finalmente, hemos
introducido las pruebas de extremo a extremo con Cypress y Playwright, dos
herramientas que nos permiten asegurarnos de que nuestra app funciona
correctamente en su conjunto.
Espero que este capitulo te haya proporcionado las herramientas y el conocimiento
necesarios para escribir cédigo de buena calidad en React. Recuerda, un buen
cédigo no es solo cédigo que funciona, sino cédigo que es facil de entender,

mantener y probar.

En el préximo capitulo, nos adentraremos en el despliegue a producción.

Aprenderemos cémo llevar nuestras aplicaciones de React desde nuestro entorno
de dev local hasta un entorno de producción, donde los usuarios podran

interactuar con ellas.
Referencias

+ Da Costa, L. (2021). Testing JS Applications. Manning Publications.

+ Herman, D. (2012). Effective JS: 68 Specific Ways to Harness the Power of
JS. Addison-Wesley Professional.

+ Cypress.io. (2023). Cypress Documentation. https://docs.cypress.io

+Playwright. (2023). Playwright Documentation. Microsoft. https://
playwright.dev

«Jest. (2023). Jest Documentation. FB. https://jestjs.io

+ Vitest. (2023). Vitest Documentation. https://vitest.dev

+React Testing Library. (2023). React Testing Library Documentation. https://
testing-library.com/docs/react-testing-library/intro

+ ESLint. (2023). ESLint Documentation. https://eslint.org

+ Prettier. (2023). Prettier Documentation. https://prettier.io

Capitulo 10: Despliegue y Entornos de Produccion
Introducción

En este capitulo final, exploraremos cémo llevar nuestras aplicaciones React desde
nuestro entorno de dev local hasta un entorno de producción optimizado,

listo para ser consumido por los usuarios finales.

Abordaremos la creación de un entorno de producción, el despliegue en
plataformas populares como Netlify y Vercel, y finalmente, discutiremos sobre SEO

y rendimiento en aplicaciones de React.
Creación de un entorno de producción optimizado

Cuando desarrollamos una app, generalmente trabajamos en un entorno de
dev. Este entorno esta configurado para facilitar la depuración y las pruebas,
pero no esta optimizado para el rendimiento. Al estar listos para desplegar nuestra
app, es esencial crear un entorno de producción optimizado para la velocidad
yeficiencia.

En React (utilizando Vite), logramos esto con el comandonpm run build. Este
comando genera una version de producción de tu aplicacion en el directorio build.
Esta version ha sido minificada (el cédigo se comprime para reducir su tamajio) y
optimizada para el rendimiento.

Aqui tienes un ejemplo de cémo se ve este proceso:

1 # En tu directorio de proyecto
2 $ npm run build

Este comando crea un directorio build con un archivo index.html y todos
los archivos JS y CSS necesarios. Estos archivos estan listos para ser

desplegados en un servidor de producción.

Es crucial recordar que la version de producción de tu app puede
comportarse de manera ligeramente diferente a la version de dev.

Diferencias entre el entorno de producción y el de dev

En el entorno de dev, priorizamos la facilidad de depuración y la velocidad
de dev. Por ejemplo, en React, el entorno de dev incluye mensajes
de advertencia detallados para ayudarte a entender y corregir problemas en tu
cédigo. Tambión se incluyen herramientas como “hot reloading”, que actualiza
automaticamente tu app en el navegador a medida que modificas el cédigo,
acelerando el ciclo de dev.

En cambio, en el entorno de producción, la prioridad es la eficiencia y el
rendimiento. Los mensajes de advertencia detallados y el “hot reloading” son utiles
durante el dev, pero pueden ralentizar tu app en producción y exponer
detalles de implementación que preferirias mantener privados. Por lo tanto, estas

caracteristicas se eliminan en la versión de producción.
Minificación y su importancia

La minificación es el proceso de eliminar todos los datos innecesarios de tu cédigo
sin afectar su funcionalidad. Esto incluye espacios en blanco, comentarios, saltos
de linea, y a veces, incluso los nombres de las variables se acortan. La minificación
hace que tu cédigo sea mas dificil de leer para las personas, pero no afecta su
interpretacion por parte de la maquina.

La principal ventaja de la minificación es que reduce el tamajio de tus archivos
JS y CSS, lo que a su vez disminuye el tiempo de carga de tu pagina.
Esto puede tener un impacto significativo en el rendimiento de tu app,
especialmente para los usuarios con conexiones a internet mas lentas.

Ademis, la minificación puede ofrecer beneficios de seguridad, ya que hace que tu
cédigo sea mas dificil de entender para alguien que intenta leerlo.
Importancia de probar en el entorno de producción

Como mencioné anteriormente, debido a estas diferencias entre los entornos de
dev y producción, es posible que tu app se comporte de manera
diferente en producción que en dev. Por lo tanto, siempre es una buena
practica probar tu app en un entorno que se asemeje lo mAs posible al de

producción antes de desplegarla. Esto te ayudard a detectar y corregir cualquier
problema antes de que tus usuarios lo hagan.

En el siguiente apartado, hablaremos sobre cémo desplegar nuestra app en

plataformas populares de hosting.
Despliegue en plataformas populares
(Netlify, Vercel, Firebase...)

Las plataformas de despliegue de aplicaciones web, como Netlify, Vercel o Firebase,
son servicios que permiten publicar aplicaciones web en Internet. A diferencia
de los servicios de hosting tradicionales, que a menudo requieren que nosotros
gestionemos manualmente los servidores y subamos los archivos a través de FTP,
estas plataformas nos proporcionan herramientas y servicios integrados disefiados

para facilitar el proceso de despliegue.

Estas plataformas se encargan de la infraestructura y la gestión del servidor,
permitióndonos centrarnos en el dev de nuestras aplicaciones. Ademas,
ofrecen caracteristicas como la integración continua/despliegue continuo (CI/CD),
que permiten desplegar automaticamente las aplicaciones cada vez que hacemos
un push al repositorio de cédigo, y la posibilidad de revertir a versiones anteriores
de la aplicacin si algo sale mal.

Ahora, vamos a ver cémo desplegar una app React en cada una de estas

plataformas.

Despliegue en Vercel

Preview. Ship.

Pagina de producto de Vercel

Vercel es una plataforma de despliegue en la nube que proporciona funcionalidades
de despliegue continuo desde repositorios de Git. Es especialmente util para
aplicaciones de JS, incluyendo React.

Acontinuación, te guiaré a través de los pasos para desplegar una app React
en Vercel.

Paso 1: Preparar tu aplicacion React

Antes de desplegar tu app, debes asegurarte de que esta lista para la
producción. Esto significa que debes ejecutar elcomandonpm run buildentu
proyecto React, que creard una versión optimizada de tu app en el directorio
build.

# En tu directorio de proyecto
$ npm run build
Paso 2: Crear un repositorio Git

Vercel utiliza Git para obtener el cddigo de tu app. Por lo tanto, necesitas
tener tu app en un repositorio Git. Si atin no has hecho esto, aqui te muestro

cémo puedes hacerlo:

1 # Inicializa un nuevo repositorio Git
2 git init

4 # Afiade todos tus archivos al repositorio
5 git add .

7? # Realiza un commit con tus archivos
8 git commit -m "Mi primera app React"

Si tienes dudas con Git y GitHub, te recomiendo la lectura del libro: Git y
GitHub desde cero: Guia de estudio tedrico-prdctica de Brais Moure (@mouredev).

Una vez que hayas hecho esto, debes subir tu repositorio a un servicio de hosting de
Git como GitHub, GitLab o Bitbucket.

Paso 3: Crear una cuenta en Vercel

Si aun no tienes una cuenta en Vercel, puedes crear una de forma gratuita en su
sitio web. Puedes registrarte con tu cuenta de GitHub, GitLab o Bitbucket, lo que
facilitard el despliegue de tus repositorios en Vercel.

Paso 4: Desplegar tu aplicacion en Vercel

Una vez que hayas iniciado sesión en Vercel, puedes desplegar tu app
siguiendo estos pasos:

1. Haz clic en “New Project”.

2. Selecciona tu repositorio de Git. Si has iniciado sesión con tu cuenta de GitHub,
GitLab o Bitbucket, deberias ver tus repositorios en la lista. Si no, puedes
afiadirlos manualmente.

3.En la configuración de despliegue, asegurate de que el comando de
construcción seanpm run buildyel directorio de salida sea build/. Vercel
deberia detectar estos automaticamente si estas desplegando una app
React.

4. Haz clic en “Deploy”. Vercel construira y desplegara tu app.

Una vez que tu app esté desplegada, recibiras una URL unica donde
podras acceder a ella. Vercel tambión continuard desplegando automaticamente tu
app cada vez que hagas un push a tu repositorio de Git.

Ahora tienes tu app React desplegada en Vercel.
Despliegue en Netlify

Paton ¥ Sluions¥ tntegatons Start Bulg Does Pricing

2 cmt tose SEED

Netlify
Connect

Connect everything. Build anything.

Pagina de producto de Netlify

Netlify es una plataforma de despliegue en la nube que proporciona
funcionalidades de despliegue continuo desde repositorios de Git, al igual
que Vercel. Es una excelente opción para desplegar aplicaciones de JS,
incluyendo tambión React.

Acontinuación, te guiaré a través de los pasos para desplegar una app React
en Netlify.

Paso 1: Preparar tu app React

Al igual que con Vercel, antes de desplegar tu app, debes asegurarte de que
esta lista para produccion. Esto significa que debes ejecutar el comandonpm run
build en tu proyecto React, que creara una versión optimizada de tu app en
el directorio build.

Paso 2: Crear un repositorio Git

Netlify tambión utiliza Git para obtener el cédigo de tu app. Por lo tanto,
necesitas tener tu app en un repositorio Git. Los pasos serfan similares al
apartado con Vercel.

Paso 3: Crear una cuenta en Netlify

Si atin no tienes una cuenta en Netlify, puedes crear una de forma gratuita en su
sitio web. Puedes registrarte con tu cuenta de GitHub, GitLab o Bitbucket, lo que al
igual que en Vercel, facilitard el despliegue de tus repositorios en la plataforma.

Paso 4: Desplegar tu app en Netlify

Una vez que hayas iniciado sesión, puedes desplegar tu app siguiendo estos
pasos:

1. Haz clic en el botón “New site from Git”.

2. Selecciona tu proveedor de Git (GitHub, GitLab, Bitbucket) y autoriza a Netlify
para acceder a tus repositorios.

3. Selecciona el repositorio que contiene tu app React.

4.En la configuración de despliegue, asegurate de que el comando de
construcción seanpm run buildyel directorio de publicación sea build/.

5. Haz clic en “Deploy site”. Netlify construira y desplegara tu app.
Una vez que tu app esté desplegada, recibiras una URL tnica donde podras
acceder a ella. Netlify tambión continuard desplegando automaticamente tu

app cada vez que hagas un push a tu repositorio.

Y eso es todo. Ahora tienes tu app React desplegada en Netlify.

Despliegue en Firebase Hosting

We Feeboce rene oes ton tee @ x Otea-) cee ann

Acomplete foundation
for your web app

05 °
‘ae

Pagina de producto de Firebase Hosting

Firebase Hosting es un servicio de hosting de aplicaciones web de Google.
Proporciona una forma rapida y facil de desplegar aplicaciones web de un solo
archivo o de varias paginas. A continuacidn, te guiaré a través de los pasos para
desplegar una app React en Firebase Hosting.

Paso 1: Preparar tu app React

Antes de desplegar tu app, debes asegurarte de que esta lista para la
producción. Esto significa que debes ejecutar elcomandonpm run buildentu
proyecto React, que crear una versión optimizada de tu app en el directorio
build. Tal y como hicimos en los anteriores pasos.

Paso 2: Crear una cuenta en Firebase

Para usar Firebase Hosting, necesitards una cuenta de Google y un proyecto en
Firebase. Si atin no tienes una cuenta de Google, puedes crear una de forma gratuita
enel sitio web de Google. Una vez que la tengas, puedes crear un nuevo proyecto en
Ja consola de Firebase.

Paso 3: Instalar Firebase CLI

Firebase CLI (Command Line Interface) es una herramienta que te permite
interactuar con Firebase desde tu linea de comandos. Necesitaras Firebase CLI para
desplegar tu app en Firebase Hosting. Puedes instalar Firebase CLI con npm:

1 $ npm install -g firebase-tools

Paso 4: Iniciar sesion en Firebase

Una vez que hayas instalado Firebase CLI, puedes iniciar sesión en Firebase con el
siguiente comando:

1 $ firebase login
Esto abrird una nueva ventana en tu navegador web para que inicies sesión en tu
cuenta de Google.

Paso 5: Inicializar tu proyecto

Ahora puedes inicializar tu proyecto de Firebase con el siguiente comando:

1 $ firebase init

Esto iniciara un asistente interactivo. Cuando se te pregunte qué caracteristicas de
Firebase quieres usar, selecciona “Hosting”. Luego, elige el proyecto de Firebase que
creaste en la consola de Firebase.

Cuando se te pregunte por el directorio publico, introduce build/. Esto es porque
build/ es el directorio donde React crea la version de producción de tu app.

Tambión puedes ahorrarte el paso del asistente e indicar con un comando que solo
quieres hacer uso del servicio de hosting que provee Firebase:

1 $ firebase init hosting

Al final de la inicialización, Firebase crea automaticamente y afiade dos archivos a
la raiz del directorio de tu app local:

Un archivo de configuración f irebase . json que enumera la configuración de tu
proyecto. Y un archivo . firebaserc que almacena los alias de tu proyecto.

Paso 6: Desplegar tu app

Finalmente, puedes desplegar tu app en Firebase Hosting con el siguiente
comando:

1 $ firebase deploy

2 # tambión puedes especificar sélo el servicio de hosting al
despl\

3 egar

4 $ firebase deploy --only hosting

Este comando subira tu app al servicio de alojamiento. Una vez que tu
aplicacion esté desplegada, recibiras una URL tnica donde podras acceder a ella.
SEO y rendimiento en aplicaciones de React

Tanto el SEO (Search Engine Optimization) y el rendimiento son dos aspectos
cruciales para cualquier app web cuya propuesta de valor es el contenido, y
las aplicaciones React no son una excepción. En este apartado, vamos a explorar
cémo optimizar tu app React para los motores de busqueda y mejorar su
rendimiento.

SEO en React

Las aplicaciones de React son aplicaciones de una sola pagina (SPA), lo que significa
que toda la app se carga en una tinica pagina o documento HTML y luego se
actualiza dindmicamente a medida que los usuarios interacttian con ella. Aunque
esto puede proporcionar una experiencia de usuario fluida, puede presentar
desafios para el SEO, ya que los motores de busqueda pueden tener dificultades para
indexar el contenido dinamico.

Aqui hay algunas estrategias que puedes usar para mejorar el SEO de tu app
React:

Uso de la etiqueta de titulo y descripcion
El titulo y la descripción de tu pagina son dos de los factores mas importantes para

el SEO. Puedes establecer el titulo y la descripción de tu pagina en React utilizando
el componente He 1met de la biblioteca react -helmet.

1 import { Helmet } from "react-helmet";

3 function MyComponent() {

4  veturn (
<div>
6 <Helmet>
? <title>Mi app React</title>
8 <meta name="description" content="Esta es mi app

R\
9 eact." />
10 </Helmet>
{/* El resto de tu componente */}
</div>

Renderizado en el servidor

El renderizado en el servidor (SSR, por sus siglas en inglés) es otra técnica que
puedes usar para mejorar el SEO de tu app React. Con SSR, tu app se
renderiza en el servidor antes de ser enviada al navegador, lo que significa que
los motores de busqueda pueden ver e indexar todo tu contenido, incluso si es
dinamico.

React tiene soporte incorporado para SSR, pero implementarlo puede ser un poco
complicado y se escapa del ambito de este libro. Hoy en dia, soluciones como Next
facilitan mucho poder tener una app SSR y mucho mas.
Rendimiento en React

React es conocido por su alto rendimiento, pero hay varias técnicas que puedes usar

para hacer que tu app React sea atin mas rapida.

Uso de React.memo

Como vimos en capitulos anteriores, React.memo es una función de orden
superior que puedes usar para evitar el renderizado innecesario de tus
componentes. Si tienes un componente que recibe props pero que se renderiza
de la misma manera independientemente de esas props, puedes envolver
ese componente en React.memo para evitar que se vuelva a renderizar

innecesariamente.

Uso de React.lazy y Suspense

Tambión lo vimos en anteriores capitulos, React. lazy y Suspense son dos
caracteristicas de React que te permiten cargar tus componentes de manera
“perezosa” (lazy loading), lo que significa que los componentes no se cargaran hasta
que sean necesarios. Esto puede mejorar significativamente el tiempo de carga de tu

app.

Estas son solo algunas de las técnicas que puedes usar para mejorar el SEO y el
rendimiento de tu app React.

Hemos Ilegado al final de nuestro camino explorando el despliegue y el entorno de
producción en React.js. Hemos aprendido cémo preparar nuestra app para la
producción, cémo desplegarla en varias plataformas populares y cémo optimizarla
para el SEO y el rendimiento.

Espero que este capitulo te haya proporcionado una sdlida comprensión de cémo
llevar tu app React desde tu entorno de dev local hasta un entorno
de producción listo para ser consumido por los usuarios finales. Recuerda, el
despliegue es solo el comienzo. Una vez que tu app esté en producción,
deberds monitorizarla, mantenerla y actualizarla regularmente para asegurarte de
que sigue siendo segura, eficiente y relevante para tus usuarios.

Aunque hemos cubierto mucho en este capitulo, todavia hay mucho mas que
aprender sobre React y el dev web en general. Te animo a que sigas
explorando, experimentando y aprendiendo. Y recuerda, la mejor manera de
aprender es haciendo, asi que no tengas miedo de “ensuciarte las manos” y
construir cosas.
Referencias

-Bank, J., Porcello, T., & Lerner, E. (2017). Learning React: Functional Web
Development with React and Redux. O'Reilly Media.

« Rauschmayer, A. (2018). JS for impatient programmers. Independently
published.

+ FB Inc. (2023). React - A JS library for building user interfaces.
https://react.dev/

+ Netlify. (2023). Deploy React Apps in less than 30 Seconds. Netlify. https://
www.netlify.com/blog/2016/07/22/deploy-react-apps-in-less-than-30-
seconds/

+ Vercel Inc. (2023). Deploy | Documentation. https://vercel.com/docs

-Firebase. (2023). Firebase Hosting. Firebase. https://firebase.google.com/
products/hosting

«Moz. (2023). The Beginner's Guide to SEO. Moz. https://moz.com/beginners-
guide-to-seo
Epilogo

Hemos recorrido un largo camino desde el primer capitulo de este libro, en el que
comenzamos nuestro viaje explorando la historia y los fundamentos de React js. A
lo largo de este trayecto, hemos profundizado en conceptos esenciales como JSX, el
estado, las props de los componentes, el manejo de eventos y los complejos ciclos de
vida de los componentes de React.

Experimentamos la flexibilidad y potencia de la gestión del estado global con
la Context API y Redux, y aprendimos a navegar en nuestras aplicaciones con
React Router. Ademas, abordamos técnicas para estilizar nuestras aplicaciones y
adaptarlas a diferentes tamafios de ventana.

En los capitulos finales, nos adentramos en el consumo de APIs y la comunicación
con el servidor, aprendiendo cémo optimizar nuestras aplicaciones para obtener
el maximo rendimiento y como garantizar la calidad de nuestro cédigo mediante
pruebas y herramientas de mantenimiento.

Finalmente, exploramos cémo preparar nuestras aplicaciones para su despliegue y
discutimos estrategias para mejorar el SEO y el rendimiento en producción.

Aunque hemos abordado una amplia variedad de temas, el viaje con React.js no

termina aqui. Existen muchos otros aspectos de React y su ecosistema que puedes
descubrir. Por ejemplo, puedes aventurarte en el dev de aplicaciones méviles
con React Native o profundizar en técnicas de dev con Server-Side Rendering
(SSR) usando Next.js. Tambión puedes explorar bibliotecas y herramientas como
React Query, Redux Toolkit y otros elementos del ecosistema de React.

Recuerda que la practica constante es esencial para perfeccionar tus habilidades
en cualquier tecnologia. Desafiate a ti mismo creando proyectos que solucionen
problemas reales, colabora en proyectos de cédigo abierto y mantente informado
sobre las tltimas tendencias y novedades en React y la comunidad de dev
web.

Estoy convencido de que estas preparado para enfrentar los desafios del dev
front-end en el mundo actual. Espero que este libro te haya servido como guia e
inspiración para seguir explorando y aprendiendo.

Si es asi, me encantaria conocer tu opinión. Puedes compartir tus impresiones
sobre este libro en Twitter(X) o en cualquier red social de tu preferencia. Me puedes
encontrar en todas ellas como @carlosazaustre.

jHasta la proximal!
