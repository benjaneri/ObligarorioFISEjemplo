# Informe académico entrega 1
Fecha de entrega: 18-oct-2021

**Identificación:**

- Karen Hirschfeld (233805)
- Benjamín Neri (253128)
- Mateo Saravia (255917)

<br>

# Repositorio Git
**Creación y uso de repositorios locales y remotos**

El repositorio remoto, proporcionado por el docente, fue creado en la fecha del 02-sep-2021.

Asimismo, el repositorio remoto fue clonado en el dispositivo de cada integrante del grupo con el fin de hacer uso del mismo localmente. Mediante los comandos adecuados se logró la sincronización entre los repositorios y los integrantes del grupo.

A lo largo de esta primera entrega se trabajó con git y sus comandos, únicamente versionando el informe académico. Más adelante otros *Elementos de la Configuración de Software* se harán presentes, exigiendo también su correcto versionado. Entre ellos podemos nombrar: librerías, recursos, código fuente, entre otros.

<br>

**Comandos Git ejecutados desde terminal y desde el IDE**

Haciendo un resumen de los comandos Git ejecutados podemos resaltar el uso de los siguientes:

- *git clone* para hacer uso de los repositorios locales.
- *git pull* para mantener la conexión en el repositorio local.
- *git push* para mantener la conexión en el repositorio remoto.
- *git branch* para crear la rama donde trabajar sobre el informe.
- *git chekout* para moverse entre las distintas ramas.
- *git commit -a -m* para realizar el versionado del informe.
- *git add* para trabajar con el área de staging por separado del commit.
- *git merge* para combinar las ramas "main" e "Informe_academico".

En esta primera instancia el equipo opto por trabajar con Git desde la terminal.

<br>

# Versionado

**Buenas prácticas de versionado**
- Comenzar ejecutando *git pull* para mantener actualizado el repositorio local y prevenir posibles conflictos.
- Previo a realizar un *git push* efectuar *git pull*. Dicha práctica es de gran importancia en los casos donde el equipo no se encuentra en contacto.

<br>

**Uso de ramas separadas de 'main'**

Tal como se mencionó anteriormente, en esta primera entrega el equipo se inclinó por trabajar en el informe en una rama ("Informe_academico") separada de la rama main.

Además, a futuro trabajaremos con ramas en las siguientes situaciones:
- Para estructurar el trabajo interno del equipo.
- Realizar de forma independiente un grupo de cambios mientras se trabaja en ellos.
- Trabajar en nuevas funcionalidades y versiones del proyecto.

<br>

**Resumen de commits y evolución del proyecto**

Ejemplo de los commits realizados por el equipo durante la primer entrega. El historial completo se puede encontrar en GitHub.

<p align="left">
<img src="https://i.ibb.co/PN4Hykf/Microsoft-Teams-image-10.png">
</p>

*Aclaración:* para los mensajes de commit no se siguió ningún estándar. Simplemente de describió lo realizado por el equipo.

<br>

# Elicitación

**Evidencia de actividades de investigación**

Cuando una persona consigue su primer trabajo, siempre se habla de lo que va a ser con su primer sueldo, en qué lo va a gastar. Parece algo emocionante, pero en realidad lo único que hace es fomentar malas prácticas económicas, ya que ese dinero se podría ahorrar en vez de gastarse en cosas que pueden resultar ser innecesarias. Esto demuestra el poco conocimiento de gestión de ingresos que tienen las personas en general cuando comienzan a ganar dinero.

De continuar con estas prácticas, se puede llegar a perder control de los ingresos o egresos de capital de una persona, lo que podría llevar a problemas económicos más adelante. También existe la situación contraria, ya que cuando una persona empieza a tomar control de los gastos que tiene, hasta el último peso, va a ser capaz de analizarlos y optimizarlos para prosperar en su estado económico.

El equipo realizó un profundo análisis de cuál sería la manera ideal de gestionar gastos. Lo que notamos que es fundamental es que, para gestionar gastos, es necesario tener en cuenta las siguientes cosas:

- Siempre ahorrar un porcentaje de los ingresos. 
- Tener en cuenta en que se gasta la plata: comida, indumentaria, vivienda. Es decir, poder **categorizar** los gastos. 
- Generar un **presupuesto** en el cual basar lo que se gasta. 
- Llevar un **registro** de todos los gastos. 
- Hacer un balance por mes que muestre cómo va la economía de la persona, y dejar en claro si este es positivo o negativo.  
- Poder hacer una diferencia entre los gastos fijos y los gastos variables. 

<br>

**Referencias a fuentes de información**

Investigamos en artículos online: 
- [Articulo 1](https://www.mundodeportivo.com/uncomo/negocios/articulo/como-gestionar-la-economia-familiar-49421.html "Articulo 1")
- [Articulo 2](https://www.agenthia.com/es/blog/27/133 "Articulo 2")
- [Articulo 3](https://www.infolab.es/es/blog/gestionar-los-gastos-de-manera-eficaz/#:~:text=La%20opci%C3%B3n%20m%C3%A1s%20sencilla%20para%20llevar%20a%20cabo,en%20el%20departamento%20de%20administraci%C3%B3n%20para%20su%20gesti%C3%B3n. "Articulo 3")

<br>

**Ingeniería reversa**

Por otro lado, experimentamos distintas aplicaciones para conocer más acerca de los sistemas de gestión de gastos. 

Tomamos como referencia las aplicaciones Monefy, Wallet y 1Money, donde a raíz de su uso pudimos concluir que las siguientes funcionalidades son frecuentes y de gran utilidad en un sistema de gestión de gastos:

1.  *Manejo de usuarios.* Permite el uso, sincronizado, en distintos dispositivos.
2. *Movimiento de dinero.* Permite el ingreso y egreso de dinero. Además, se puede gestionar distintos medios donde se generan movimientos de dinero.
3. *Historial de movimientos*. Visualizar el registro de la actividad pasada con el fin de analizar los datos estadísticamente.
4. *Planificación de futuros gastos*. Hace posible el ingreso de gastos programados para poder tenerlos en cuenta con mayor facilidad.

Sin embargo, no todas fueron experiencias ejemplares. En algunas situaciones nos encontramos con aspectos mejorables, y consideramos sacar provecho de los mismos.  Por ejemplo algunos aspectos a considerar fueron:

1. En el caso de Monefy, notamos que hacía falta el *registro de la fecha y hora* al momento de agregar una transacción. Asimismo, notamos la falta de colores en casos donde era necesario resaltar la diferencia entre egreso e ingreso.
2. Adicionalmente, en Wallet, notamos una limitación en la sección *agregar categoría*. Su acceso fue dificultoso y como herramienta deja que desear.

Adjuntamos links de las aplicaciones investigadas:
- [Monefy](https://monefy.me/ "Monefy")
- [Wallet](https://play.google.com/store/apps/details?id=com.droid4you.application.wallet&hl=es_UY&gl=US "Wallet")
- [1Money](https://www.1moneyapp.com/ "1Money")

<br>

**Caracterización de usuarios: User Personas**

En la siguiente técnica de elicitación buscamos representar ciertos perfiles de usuarios que consideramos de suma importancia abarcar en nuestro sistema.

- **Martina Giménez** cambió su dinámica económica personal radicalmente, y es un usuario en busca de una herramienta que la ayude a manejar sus nuevas finanzas personales. 
<p align="left">
  <img src="https://i.ibb.co/Dp7s8M4/User-persona.png">
</p>

- **Juan Bergessio** es un estudiante que convive con sus padres, siendo un usuario dependiente. Sus ingresos son nulos y por ende su gastos están sumamente relacionados con sus superiores. 
<p align="left">
  <img src="https://i.ibb.co/5LL6kBy/Sin-t-tulo.png">
</p>

- **Martina Díaz** es una persona con una dinámica económica ya formada que ya conoce aplicaciones de gestión de gastos, considerándose un  usuario frecuente.
<p align="left">
  <img src="https://i.ibb.co/p3qRHgC/Sin-t-tulo.png">
</p>

- **Carlos Sosa** actualmente desempleado, encaja en el un perfil con poco ingresos y casi nulo conocimiento tecnológico. Busca mejorar su organización y obtener el mayor beneficio posible.
<p align="left">
  <img src="https://i.ibb.co/mN7z5w2/Microsoft-Teams-image.png">
</p>

<br>

**Entrevistas**

El equipo utilizó las entrevistas como método de elicitación más personalizado. Buscamos profundizar en los intereses y experiencias de los posibles usuarios.

Para ello optamos por las siguientes **preguntas**:


1. ¿Cómo organiza sus gastos? ¿Utiliza algún gestor de gastos?
2. ¿Está conforme con la manera que realiza su gestión?
3. ¿Qué características cree fundamentales en un gestor de gastos?
4. ¿Con que frecuencia utilizaría un gestor de gastos?
5. ¿Confiaría en un gestor de gastos online?

Obteniendo como respuestas y conclusiones: 
[archivo adjunto](elicitacion/entrevista.md)

<br>

**Cuestionario**

Con el fin de conocer las opiniones de potenciales usuarios, realizamos un cuestionario de Google donde buscamos conocer más acerca de sus intereses y experiencias propias.

A diferencia de las entrevistas, con este método, recabamos datos a gran escala, aportando una generalización más acertada.

- [Formulario Google difundido](https://forms.gle/s2osJZkE4ysBNebJ7)
- [Resultados obtenidos](elicitacion/cuestionario/cuestionario.md)

En vista de los resultados, de gran número, podemos concluir lo siguiente:

- [Conclusiones](elicitacion/cuestionario/conclusiones.md)


<br>

**Modelo conceptual del problema**

A través del diagrama buscamos reflejar una posible organización de clases, donde posteriormente nos podamos basar para desarrollar el sistema.

Realizamos un diagrama "tipo" MER donde profundizamos en los aspectos cruciales del sistema: entidades, atributos y relaciones.

<br>
<p align="left">
  <img src="https://i.ibb.co/zJF4XVG/Microsoft-Teams-image-9.png">
</p>

<br>

# Especificación

**Definición de requerimientos funcionales y no funcionales**

<br>

*Requerimientos no funcionales:*

**RNF 1:**
El sistema debe soportar múltiples plataformas, a partir de un diseño responsive, donde el usuario debe poder acceder al sistema tanto en una computadora como un dispositivo móvil.

*Prioridad:* media

**RNF 2:** El sistema debe desarrollarse, inicialmente, en español. Además, el sistema debe poder ser escalable con la posibilidad de traducir la aplicación a nuevos idiomas.

*Prioridad:* media

**RNF 3:** El usuario debe acceder a una interfaz sencilla e intuitiva. La misma será web utilizando la versión más actualizada de los lenguajes: html5, CSS3 y JavaScript (ES6).

*Prioridad:* alta

**RNF 4:** El sistema debe ser seguro. Solicitar contraseñas segura: incluyendo: mínimo 8 caracteres, una mayúscula, un número y un caracter especial.

*Prioridad:* alta

<br>

***

<br>

*Requerimientos funcionales:*

**RF 1:** Cada usuario debe poder agregar, eliminar y editar un gasto.

*Prioridad:* alta

**RF 2:** Los usuarios deben poder acceder a un historial de gastos, pudiendo manejar distintas visualizaciones (gráficas, totales, entre otras) y filtrados (por fechas, categorías, entre otras), para facilitar un análisis posterior.

*Prioridad:* alta

**RF 3:** Los usuarios deben poder manipular sus distintas cuentas bancarias, pudiendo acceder a cada una de ellas de forma independiente. Adicionalmente, debe ser posible seleccionar distintas divisas.

*Prioridad:* media

**RF 4:** El sistema debe manejar un usuario y contraseña personal para cada usuario (será trabajado de manera local).

*Prioridad:* alta

**RF 5:** El sistema debe generar un presupuesto mensual, el cual se realizará según los ingresos registrados y las preferencias personales de ahorro del usuario.

*Prioridad:* media


<br>


**User Stories / Use Cases detallados**

Consideramos distintas historias de usuarios describiendo funcionalidades del sistema y siguiendo ciertas características: independientes, negociables, valuables, estimables y testeables.

Las mismas son detalladas en el siguiente archivo:
[User Stories](especificacion/userStories.md)

***

Por otro lado, especificamos las posibles interacciones entre el sistema y los usuarios. Para ello, consideramos un estándar informal y diagramático.

Abarcamos los siguientes casos de uso:
[User Cases](especificacion/userCases.md)

<br>

**Bocetos de IU**

Realizamos bocetos de interfaz de usuario, tanto mobile como web. En el siguiente [archivo](bocetosiu/README.md) se detalla lo realizado y también se adjuntan las imágenes de los mismos.

Buscamos representar los requerimientos que consideramos de alta prioridad. Una vez comencemos a desarrollar el sistema, adaptaremos los bocetos para poder cumplir con la totalidad de los requerimientos.

<br>

# Validación y verificación

**Validación**

Entre todas las técnicas, de validación, el equipo opto por realizar una revisión del tipo *"Walktrough"*.

Para esta forma de validación, hablamos con Malena López, una estudiante de Administración de Empresas y encargada del área de administración de WeCode, una academia de programación para niños. Luego de comentarle del trabajo, ella nos dio su perspectiva tanto en lo personal como en lo profesional. 

Reconoció los siguientes **puntos a favor** de nuestra aplicación:

- Poder ver las estadísticas de los gastos. Está bueno poder tener un paneo mas general acerca de los gastos que se realizan por mes, lo que permitirá analizarlos de otra forma. 
- La información que se maneja en esta aplicación necesita ser segura, es información sensible. 
- La interfaz de usuario le pareció amigable, fácil de usar, simple e intuitiva. Va a permitir que un público diverso pueda usar el sistema. 
- También, reconoció la importancia de los presupuestos, y de poder categorizar los diferentes gastos. Es muy importante saber los gastos fijos, algo que mucha gente suele dejar de lado. 

Por otra parte, comentó que un **punto negativo** es que, por la forma que diseñamos el sistema, no es muy compatible con la gestión de gastos de una empresa.

Por último, nos comentó una **lista de sugerencias** que no nos es posible implementar en el sistema: 

- Poder conectar la información de las cuentas bancarias. Esto permitirá registrar los gastos de manera automática, en el instante que se descuenta la plata del banco. 
- También, nos comentó acerca de la diferencia entre contabilidad y finanzas, ya que una analiza los gastos pasados y otra trata de ver los gastos del futuro, incluyendo como ahorrar e invertir. Para esto, sugiere incluir conexión directa con fondos de inversión o con lugares que permitan ahorrar en dólares, para poder facilitar ese proceso. 
- A su vez, reconoce que a ella se le olvidaría seguro ingresar los gastos, por lo que recomienda tener notificaciones o poder prefijar recordatorios para poder ingresar los gastos. 

Por último, luego de que le contamos el trabajo quedó fascinada, tanto que nos pidió que le mostremos el sistema terminado y nos preguntó si iba a estar disponible en la tienda de aplicaciones para bajársela en el celular y comenzar a usarla.

<br>

**Verificación**

Para la verificación de requerimientos nos centramos en las siguientes características, obtenidas del material utilizado en clase: 
- Completitud
- Verificabilidad y no ambiguedad
- Correctitud y consistencia
- Trazabilidad

Para mayor claridad realizamos la siguiente tabla con los puntos a verificar de cada característica:

*Completitud*

|Requerimiento|RF1|RF2|RF3|RF4|RF5|
|-------------|--|--|--|--|--|
|¿Está correctamente priorizado?|Sí|Sí|Sí|Sí|Sí|
|¿Respeta el estándar? |Sí|Sí|Sí|Sí|Sí|
|¿Características de calidad tenidas en cuenta? |Sí|Sí|Sí|Sí|Sí|

<br>

*Verificabilidad y no ambigüedad*

|Requerimiento|RF1|RF2|RF3|RF4|RF5|
|-------------|--|--|--|--|--|
|¿Tiene una única interpretación?|Sí|Sí|Sí|Sí|Sí|
|¿Puede ser verificado?|Sí|Sí|Sí|Sí|Sí|

<br>

*Correctitud y consistencia*

|Requerimiento|RF1|RF2|RF3|RF4|RF5|
|-------------|--|--|--|--|--|
|¿Consistentes y detallados?|Sí|Sí|Sí|Sí|Sí|
|¿Conflicto entre los requerimientos?|No|No|No|No|No|
|¿Dentro del alcance? |Sí|Sí|Sí|Sí|Sí|
|¿Evitan incluir aspectos de diseño o implementación de la solución?|Sí|Sí|Sí|Sí|Sí|

<br>

*Trazabilidad*

|Requerimiento|RF1|RF2|RF3|RF4|RF5|
|-------------|--|--|--|--|--|
|¿Identificado correctamente y forma única?|Sí|Sí|Sí|Sí|Sí|
|¿Referenciados correctamente entre sí?|Sí|Sí|Sí|Sí|Sí|

<br>

***
<br>

Por otro lado, para la verificación de casos de uso realizamos, nuevamente, un checklist que abarcara todos los puntos analizados en clase:

|Caso de Uso|CU1|CU2|CU3|CU4|CU5|CU6|
|-----------|---|---|---|---|---|---|
|¿Tiene un objetivo único?|Sí|Sí|Sí|Sí|Sí|Sí|
|¿Tiene un objetivo medible?|Sí|Sí|Sí|Sí|Sí|Sí|
|¿Existe una secuencia lógica en los pasos?|Sí|Sí|Sí|Sí|Sí|Sí|
|Nivel de abstracción adecuado|Sí|Sí|Sí|Sí|Sí|Sí|
|¿Está libre de diseño e implementación?|Sí|Sí|Sí|Sí|Sí|Sí|
|¿Cursos alternativos?|Sí|Sí|Sí|Sí|Sí|Sí|

<br>

# Reflexión

**Técnicas aplicadas**

Antes de comenzar a trabajar en grupo repasamos cada uno de los temas que iban a ser aplicados en el obligatorio para así poder empezar a realizar el trabajo con los conceptos claros.

En esta instancia el trabajo lo realizamos en llamadas grupales, mientras que algunas tareas nos las dividimos para así poder avanzar más eficientemente en el trabajo. Entre ellas, trabajamos por separado en las entrevistas, análisis individual de una aplicación de gastos y en la creación de los User Personas.

Además, buscamos información sobre el tema y la compilamos, para luego realizar una puesta en común en el grupo para que el informe académico quedara lo más completo posible.

**Aprendizajes**

Esta instancia sirvió para aplicar los conocimientos vistos en clase y reafirmarlos. Al realizarlos de manera práctica hizo que tuviéramos que entender bien los conceptos para poder aplicarlos de manera correcta.

Asimismo, el trabajo fue de suma importancia ya que fue la primera vez que nos enfrentamos, por completo, al proceso de creación de software. Nos proporcionó una visión completa, donde pudimos ejercer los distintos roles que nos podremos encontrar en el mundo laboral.

Por último, consideramos que nos encontramos preparados para continuar con la etapa de desarrollo.
