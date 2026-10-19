<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-oscuro.svg">
  <img src="assets/banner-claro.svg" alt="Santiago Angarita. Estudiante de Ingeniería de Sistemas y Técnico en Sistemas del SENA." width="100%">
</picture>

Estudio Ingeniería de Sistemas en la Universidad Santo Tomás, en Tunja, y soy Técnico en Sistemas del SENA. Me gusta construir software que se pueda usar de verdad: aplicaciones de escritorio en Java con su base de datos y sus pruebas, y sitios web rápidos, accesibles y publicados. También trabajo con agentes de IA, incluso varios en paralelo, y reviso todo lo que producen antes de aceptarlo.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/cifras-oscuro.svg">
  <img src="assets/cifras-claro.svg" alt="6 proyectos publicados. 94 pruebas automáticas. 95 % menos peso en imágenes en landing-cs, de 2,1 MB a 112 KB. 4 sitios con CSP y HTTPS." width="100%">
</picture>

## Sitios web

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://templvm-kyotto44.netlify.app"><img src="https://github.com/kyotto44/templvm/raw/main/docs/captura-escritorio.webp" alt="Portada de Templvm: caballeros templarios de fondo y el título TEMPLVM" width="100%"></a>
      <h3>Templvm</h3>
      Historia de la Orden del Temple, seis castillos con su foto y una tienda con carrito de compras.
      <br><br>
      <code>Bootstrap 5</code> <code>JavaScript</code>
      <br><br>
      <a href="https://templvm-kyotto44.netlify.app"><b>Ver sitio</b></a> &nbsp;&nbsp; <a href="https://github.com/kyotto44/templvm">Código</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://pitlane-kyotto44.netlify.app"><img src="https://github.com/kyotto44/pitlane/raw/main/docs/captura-escritorio.webp" alt="Portada de PitLane: barra lateral con las secciones y una foto del paddock de Fórmula 1" width="100%"></a>
      <h3>PitLane</h3>
      Portal de Fórmula 1 con pilotos, clasificación, circuitos, club de fans y preferencias que se guardan.
      <br><br>
      <code>HTML</code> <code>CSS</code> <code>JavaScript</code>
      <br><br>
      <a href="https://pitlane-kyotto44.netlify.app"><b>Ver sitio</b></a> &nbsp;&nbsp; <a href="https://github.com/kyotto44/pitlane">Código</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://matchpoint-kyotto44.netlify.app"><img src="https://github.com/kyotto44/matchpoint/raw/main/docs/captura-escritorio.webp" alt="Portada de MatchPoint: foto de un estadio con el partido destacado a la derecha" width="100%"></a>
      <h3>MatchPoint</h3>
      Resultados, calendario, equipos y tabla de posiciones de cuatro ligas europeas, con filtros por liga.
      <br><br>
      <code>Tailwind CSS</code> <code>JavaScript</code>
      <br><br>
      <a href="https://matchpoint-kyotto44.netlify.app"><b>Ver sitio</b></a> &nbsp;&nbsp; <a href="https://github.com/kyotto44/matchpoint">Código</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://landing-cs-kyotto44.netlify.app"><img src="https://github.com/kyotto44/landing-cs/raw/main/docs/captura-escritorio.webp" alt="Primera pantalla de la landing: silueta de un jugador sobre fondo amarillo y azul" width="100%"></a>
      <h3>Táctica y ejecución</h3>
      Landing que explica cómo se construye software con la metáfora de una ronda de Counter-Strike.
      <br><br>
      <code>HTML</code> <code>CSS</code> <code>JavaScript</code>
      <br><br>
      <a href="https://landing-cs-kyotto44.netlify.app"><b>Ver sitio</b></a> &nbsp;&nbsp; <a href="https://github.com/kyotto44/landing-cs">Código</a>
    </td>
  </tr>
</table>

## Aplicaciones de escritorio

<a href="https://github.com/kyotto44/sanrafa-app"><img src="https://github.com/kyotto44/sanrafa-app/raw/main/docs/captura-dashboard.png" alt="SanRafa: indicadores de citas, agenda del día y gráfico de atenciones por especialidad" width="100%"></a>

### SanRafa

Registro de pacientes, agenda de citas por médico e historias clínicas para un hospital, con validaciones según la edad del paciente. La base de datos se crea sola la primera vez que se abre. Proyecto académico.

<code>Java</code> <code>JavaFX</code> <code>SQLite</code> <code>JUnit</code> &nbsp; 46 pruebas automáticas &nbsp;&nbsp; <a href="https://github.com/kyotto44/sanrafa-app"><b>Ver código</b></a>

<table>
  <tr>
    <td width="58%" valign="top">
      <a href="https://github.com/kyotto44/dashboard-gobernacion"><img src="https://github.com/kyotto44/dashboard-gobernacion/raw/main/docs/captura-principal.png" alt="Dashboard de gobernación: indicadores de vacaciones y permisos, gráfico de retiros y formulario de empleados" width="100%"></a>
    </td>
    <td width="42%" valign="top">
      <h3>Dashboard de talento humano</h3>
      Muestra en una sola pantalla quién está de vacaciones o en permiso hoy, quién lleva más de un año sin tomarlas y cuántas personas se retiran cada mes.
      <br><br>
      Tiene modo demostración para probarlo sin instalar MySQL.
      <br><br>
      <code>Java</code> <code>JavaFX</code> <code>MySQL</code> <code>JDBI</code> <code>JUnit</code>
      <br><br>
      48 pruebas automáticas
      <br><br>
      <a href="https://github.com/kyotto44/dashboard-gobernacion"><b>Ver código</b></a>
    </td>
  </tr>
</table>

## Lo que sé hacer

Todo esto se puede ver en el código y en los archivos `CAMBIOS.md` de cada proyecto.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Java y escritorio</h3>
      <ul>
        <li>Interfaces con JavaFX, FXML y hojas de estilo propias que se adaptan al tamaño de la ventana.</li>
        <li>Diseño en capas: la interfaz <code>DataSource</code> tiene una versión MySQL y otra en memoria, y las dos pasan la misma batería de pruebas.</li>
        <li>Modelos inmutables con <code>record</code>, fechas con <code>LocalDate</code> y validaciones separadas de las pantallas.</li>
        <li>94 pruebas con JUnit 5 y proyectos Gradle que descargan sus dependencias solos.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Bases de datos</h3>
      <ul>
        <li>MySQL con JDBI y SQLite con JDBC, siempre con <code>PreparedStatement</code>.</li>
        <li>Reglas en la propia base: llaves foráneas, borrado en cascada, valores únicos y restricciones de estados y fechas.</li>
        <li>Transacciones para que un borrado no deje datos a medias, y una consulta agrupada en lugar de doce.</li>
        <li>Scripts de esquema, datos de ejemplo y migración.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Desarrollo web</h3>
      <ul>
        <li>HTML semántico, CSS con variables, Grid y diseño responsive, y JavaScript sin frameworks.</li>
        <li>Tailwind CSS compilado para producción y Bootstrap personalizado con sus propias variables.</li>
        <li>Interacciones con <code>IntersectionObserver</code>, Web Animations API y <code>localStorage</code> protegido.</li>
        <li>Mejora progresiva: sin JavaScript el contenido se sigue viendo.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Accesibilidad</h3>
      <ul>
        <li>Contraste WCAG AA revisado color por color.</li>
        <li>Navegación con teclado: foco visible, menús que se cierran con Escape y ventanas que no dejan escapar el foco.</li>
        <li>Errores de formulario debajo de cada campo, atributos ARIA y respeto por la opción de reducir movimiento.</li>
        <li>Botones y enlaces de al menos 44 px en celular.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Rendimiento y recursos</h3>
      <ul>
        <li>Imágenes en WebP con <code>srcset</code> y carga diferida. En PitLane pasaron de 7,1 MB a 0,8 MB.</li>
        <li><code>width</code> y <code>height</code> en cada imagen para que la página no salte al cargar.</li>
        <li>Dependencias sin uso retiradas y un SDK de 112 MB sacado del repositorio.</li>
        <li>Tailwind compilado en lugar del CDN que generaba el CSS en cada visita.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>Seguridad y publicación</h3>
      <ul>
        <li>Cabeceras de seguridad en Netlify: CSP, HTTPS obligatorio, <code>X-Frame-Options</code> y <code>nosniff</code>.</li>
        <li>Integridad (SRI) en los archivos que llegan desde un CDN.</li>
        <li>Contraseñas fuera del código, con variables de entorno y <code>.gitignore</code>, y sin datos personales reales en los repositorios.</li>
        <li>Git y GitHub para el control de versiones, y Netlify para publicar.</li>
      </ul>
    </td>
  </tr>
</table>

## Cómo trabajo con IA

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/ia-oscuro.svg">
  <img src="assets/ia-claro.svg" alt="Planifico y divido el trabajo. Varios agentes avanzan en paralelo: código, pruebas y revisión. Al final verifico, pruebo y decido qué cambio se queda." width="100%">
</picture>

Sé coordinar varios agentes de IA al mismo tiempo, cada uno en una tarea separada y sin que se pisen entre sí. Para mí, usar bien la IA significa:

- **Dar buen contexto.** Explico qué se busca, qué se puede tocar y cómo se va a comprobar el resultado.
- **Dividir el trabajo.** Reparto tareas independientes para que los agentes avancen en paralelo.
- **Verificar todo.** Pruebo, leo y entiendo cada cambio antes de aceptarlo. Si no lo entiendo, no entra.
- **Cuidar lo que se publica.** Ni credenciales, ni datos personales, ni código sin revisar en un repositorio público.

## Formación

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/formacion-oscuro.svg">
  <img src="assets/formacion-claro.svg" alt="Técnico en Sistemas del SENA, completado. Ingeniería de Sistemas en la Universidad Santo Tomás, Tunja, en curso." width="100%">
</picture>

## Tecnologías

<p>
  <img src="https://cdn.simpleicons.org/openjdk/1f2328/e6edf3" alt="Java" title="Java" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/mysql/1f2328/e6edf3" alt="MySQL" title="MySQL" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/sqlite/1f2328/e6edf3" alt="SQLite" title="SQLite" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/junit5/1f2328/e6edf3" alt="JUnit 5" title="JUnit 5" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/gradle/1f2328/e6edf3" alt="Gradle" title="Gradle" height="36"> &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/html5/1f2328/e6edf3" alt="HTML" title="HTML" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/css/1f2328/e6edf3" alt="CSS" title="CSS" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/javascript/1f2328/e6edf3" alt="JavaScript" title="JavaScript" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/tailwindcss/1f2328/e6edf3" alt="Tailwind CSS" title="Tailwind CSS" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/bootstrap/1f2328/e6edf3" alt="Bootstrap" title="Bootstrap" height="36"> &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/git/1f2328/e6edf3" alt="Git" title="Git" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/github/1f2328/e6edf3" alt="GitHub" title="GitHub" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/netlify/1f2328/e6edf3" alt="Netlify" title="Netlify" height="36"> &nbsp;
  <img src="https://cdn.simpleicons.org/intellijidea/1f2328/e6edf3" alt="IntelliJ IDEA" title="IntelliJ IDEA" height="36">
</p>

Cada proyecto tiene su README con capturas, cómo ejecutarlo y qué cambió desde la entrega original.
