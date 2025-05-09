## Videojuego
## Historia de usuario #1: Expandir barra de maldición

**Como** jugador  
**quiero** extender mi barra de maldición al matar a un jefe  
**para** poder aumentar mi tiempo de juego

### Validación:
- Establecer un número de puntaje, donde a partir de este se alargue la barra de la maldición.
- Verificar que cuando se alcance ese puntaje automáticamente se alargue la línea de la maldición.
- Verificar que el tiempo de vida del jugador aumente.
- Validar que la línea se mantenga extendida en las siguientes partidas.

**Prioridad:** 4  
**Estimación:** 15 hrs

---

## Historia de usuario #2: Niveles y ecosistemas

**Como** jugador  
**quiero** tener varios niveles  
**para** poder jugar en ecosistemas diferentes y aleatorios.

### Validación:
- Niveles: 3 niveles en el juego
- Ecosistemas: Desierto, bosque y nieve
- Aleatoriedad: Los salas se eligen aleatoriamente entre los 3 niveles, habiendo 4 salas por nivel

**Prioridad:** 4  
**Estimación:** 20 hrs

---

## Historia de usuario #3: Elegir de clases

**Como** jugador  
**quiero** elegir mi clase al inicio del juego  
**para** poder jugar partidas con 3 formas/estrategias diferentes.

### Validación:
- Verificar que el jugador pueda elegir clases al principio de la partida
- Verificar que el jugador tenga el arma y el daño de la clase elegida
- Verificar que la interfaz muestra la clase actual

**Prioridad:** 3  
**Estimación:** 5 hrs

---

## Historia de usuario #4: Eventos aleatorios

**Como** jugador  
**quiero** enfrentarme a eventos aleatorios  
**para** poder mantener el juego impredecible y diferente.

### Validación:
- Comprobar que los eventos de cada partida cambien de manera aleatoria.
- Asegurarse de que los eventos tengan un impacto positivo y/o negativo en el jugador
- Asegurar que los eventos representen un desafío y añadan variedad al gameplay.
- Entre los eventos deben de haber cofres, una curandera, un armero y armas secundarias.

**Prioridad:** 5  
**Estimación:** 15 hrs

---

## Historia de usuario #5: Recoger y usar armas secundarias

**Como** jugador  
**quiero** armas secundarias  
**para** poder enfrentar enemigos con ellas y tener habilidades diferentes.

### Validación:
- Armas: Mínimo 3 diferentes
- Las armas aparecen se obtienen al abrir un cofre o al interactuar con el armero.
- Verificar que con la tecla “F” el jugador puede interactuar con los objetos y con la tecla “K” se pueda hacer daño.
- Daño: Estas armas hacen diferente daño, tienen movimientos únicos.

**Prioridad:** 6  
**Estimación:** 10 hrs

---

## Historia de usuario #6: Matar enemigos y aumento de maldición

**Como** jugador  
**quiero** matar a enemigos  
**para** poder aumentar mi puntaje y obtener ventajas

### Validación:
- Validar que se puede atacar a un enemigos y este recibe daño.
- Verificar que al recibir cierta cantidad de daño el enemigo muere.
- Aumentar el puntaje cuando el enemigo muere (estadísticas) y mostrarlo en la pantalla.

**Prioridad:** 4  
**Estimación:** 10 hrs

---

## Historia de usuario #7: Game over

**Como** jugador  
**quiero** que al morir, se reinicie el juego con el progreso que ya tenía de la barra de maldición  
**para** poder volver a intentar pasar el juego.

### Validación:
- Al morir antes de completar el último nivel, el usuario regresa al nivel 1.
- Validar que mantenga el tamaño de la barra de maldición.
- Verificar que no mantiene armas secundarias.

**Prioridad:** 2  
**Estimación:** 10 hrs

---

## Historia de usuario #8: Moverse

**Como** jugador  
**quiero** moverme en varias direcciones  
**para** poder mejorar mi experiencia de juego y poder matar enemigos fácilmente

### Validación:
- Validar que el jugador puede moverse.
- Verificar que se puede avanzar en el eje x y eje y.
- Verificar que se mueve con las teclas w, a, s y d.

**Prioridad:** 1  
**Estimación:** 10 hrs

---

## Historia de usuario #9: Atacar enemigos

**Como** jugador  
**quiero** atacar a enemigos  
**para** poder aumentar mi puntaje y obtener ventajas

### Validación:
- Validar que al presionar la tecla K se hace el movimiento para atacar a un jugador.
- Validar que al hacer el movimiento el enemigo recibe daño.
- Obtener y mantener puntaje cuando se ataque.

**Prioridad:** 2  
**Estimación:** 10 hrs

---

## Historia de usuario #10: Generación aleatoria de enemigos

**Como** jugador  
**quiero** que la posición y cantidad de enemigos sea aleatoria  
**para** poder agregar el elemento de aleatoriedad en el juego

### Validación:
- Validar que en cada partida la posición de los enemigos sea distinta.
- Enemigos:
  - Los esqueletos solo aparecerán en el desierto.
  - Los duendes y lagartos sólo aparecerán en el bosque.
  - Los minotauros y lobos sólo aparecerán en la nieve.
- Verificar que la cantidad de enemigos cambie cada partida.
- Validar que en cada partida, la dificultad de los enemigos y su número se mantenga en equilibrio con la dificultad.

**Prioridad:** 4  
**Estimación:** 15 hrs

---

## Historia de usuario #11: Sonidos

**Como** jugador  
**quiero** que el juego tenga música de fondo y sonidos de batalla  
**para** poder tener una mejor interacción con la historia

### Validación:
- Música de fondo: 
  - Estilo medieval
- Sonidos mínimos:
  - Golpe de espada
  - Tiro con arco
  - Disparo con la bola de fuego
  - Sonidos de golpes arma secundaria
  - Dash
  - Sonido interaccion armero
  - Abrir cofre
  - Sonido interacción curandera

**Prioridad:** 7  
**Estimación:** 5 hrs

---

## Historia de usuario #12: Dash

**Como** jugador  
**quiero** tener un dash  
**para** moverme más rápido

### Validación:
- Uso con tecla “espacio”
- Tiempo de recarga: 1 segundo
- Movimiento hacia la última dirección del personaje
- Animación del movimiento

**Prioridad:** 4  
**Estimación:** 5 hrs




## Desarrollador
## Historia de usuario #1: Crear sprites
**Como** desarrollador  
**quiero** tener los sprites del videojuego  
**para** poder visualizar a los personajes del juego  

### Validación:
- Buscar sprites que se acoplen a la idea del juego.
- Validar que cumplan con el diseño del juego (animación, perspectiva, etc.).
- Guardar las imágenes para más adelante en el desarrollo del videojuego.

**Prioridad:** 1  
**Estimación:** 5 hrs

---

## Historia de usuario #2: Implementar un sistema de colisión
**Como** desarrollador  
**quiero** programar sistemas de colisión  
**para** poder tener una experiencia precisa en el juego  

### Validación:
- Establecer hitboxes en los personajes.
- Implementar colisiones con objetos y paredes.
- Asegurar que los ataques impacten precisamente a los enemigos y personajes.

**Prioridad:** 3  
**Estimación:** 10 hrs

---

## Historia de usuario #3: Pantalla de inicio
**Como** desarrollador  
**quiero** una pantalla de inicio  
**para** poder cargar una partida nueva o ya existente  

### Validación:
- Pantalla con logo del juego, menú y logo del estudio.
- Opción "start" para elegir partida.
- Verificar que se puede inciciar sesión con varios correos y usuarios con progresos y estadísticas propias.
- Se puede ir a la página de créditos.
- Se puede ir a la página de estadísticas.

**Prioridad:** 2  
**Estimación:** 10 hrs

---

## Historia de usuario #4: Interfaz del juego
**Como** desarrollador  
**quiero** que se vea mi la barra de maldición y puntaje (enemigos eliminados)  
**para** poder llevar un seguimiento claro del progreso y tiempo restante.  

### Validación:
- **Barra de maldición:**
  - Cambio de color conforme disminuye el tiempo (25% cada color):
    - 75% - 100%: Verde
    - 50% - 75%: Amarillo
    - 25% - 50%: Naranja
    - 0% - 25%: Rojo
- **Puntaje:**
  - Puntaje total dependiendo de los enemigos que se han eliminado.
- **Iconos de estado:** Elementos visuales que informan sobre las armas secundarias.
- El jugador no puede avanzar a la siguiente sala hasta haber eliminado a todos los enemigos.

**Prioridad:** 1  
**Estimación:** 20 hrs

---

## Historia de usuario #5: Tener pantalla de ajustes y pausa
**Como** desarrollador  
**quiero** una pantalla de ajustes  
**para** poder ajustar el volumen, ir al menú, etc.  

### Validación:
- Poder acceder a esta pantalla presionando “esc”.
- Verificar que se puede cambiar el volumen del juego.
- Se puede activar/desactivar el sonido (golpes, recoger objetos, etc.).
- Se puede activar/desactivar la música de fondo.
- Se pueden ver estadísticas especificas de la partida
- Se puede ir al menú principal o de regreso a la partida

**Prioridad:** 2  
**Estimación:** 15 hrs

---

## Historia de usuario #6: Pantalla de créditos
**Como** desarrollador  
**quiero** una pantalla de créditos  
**para** poder dar agradecimientos y mencionar a los desarrolladores  

### Validación:
- Verificar que la pantalla de créditos aparece al terminar el juego.
- Incluye:
  - Nombre del estudio
  - Nombre del videojuego
  - Desarrolladores
  - Profesores
  - Referencias (si es el caso)
  - Copyright notice

**Prioridad:** 6  
**Estimación:** 10 hrs

---

## Historia de usuario #7: Transiciones
**Como** desarrollador  
**quiero** transiciones fluidas entre niveles y salas  
**para** brindarle al usuario una experiencia agradable de juego.  

### Validación:
- Verificar que al cambiar de salas, haya una transición fluida (puede ser una pantalla oscura o una transición).
- Verificar que al subir de nivel, muestre que cambió el nivel y se use una transición.

**Prioridad:** 5  
**Estimación:** 5 hrs

---

## Historia de usuario #8: Daño y alcance por clase
**Como** desarrollador  
**quiero** que las clases tengan diferente daño y alcance  
**para** poder influir en la decisión y jugabilidad del usuario.  

### Validación:
- **Daño por clase (sujeto a cambios):**
  - **Guerrero:**
    - Daño básico: 35
    - Daño cargado: 60
    - Distancia: Cuerpo a cuerpo
  - **Arquero:**
    - Daño básico: 15
    - Daño cargado: 40
    - Distancia: 40
  - **Hechicero:**
    - Daño básico: 20
    - Daño cargado: 50
    - Distancia: 20

**Prioridad:** 3  
**Estimación:** 15 hrs

---

## Historia de usuario #9: Dificultad
**Como** desarrollador  
**quiero** ajustar la dificultad de los enemigos por nivel  
**para** que el usuario tenga un reto cada vez mayor.  

### Validación:
- **Salud por tipo y nivel (puede variar, pero se busca una proporción similar):**
  - **Enemigo común:**
    - Nivel 1: 70
    - Nivel 2: 100
    - Nivel 3: 150
  - **Enemigo fuerte:**
    - Nivel 1: 200
    - Nivel 2: 350
    - Nivel 3: 500
  - **Jefe:**
    - Nivel 1: 1000
    - Nivel 2: 1500
    - Nivel 3: 2000

**Prioridad:** 4  
**Estimación:** 15 hrs



## Administrador de la Base de Datos
## Historia de usuario #1: Implementar base de datos
**Como** administrador de base de datos  
**quiero** establecer una base de datos  
**para** poder guardar datos importantes del juego  

### Validación:
- Crear una base de datos con MySQL Workbench.
- Establecer tablas principales: Jugador, Partida y Log_Partida.
- Crear las relaciones entre tablas mediante claves foráneas.
- Implementar restricciones adecuadas mediante CHECK constraints.

**Prioridad:** 1  
**Estimación:** 5 hrs

---

## Historia de usuario #2: Guardar el progreso del jugador
**Como** administrador de base de datos  
**quiero** que el sistema registre cada evento relevante del juego  
**para** mantener un historial del progreso y acciones del jugador  

### Validación:
- Crear una tabla Log_Partida que registre eventos como: inicio, pausas, checkpoints, muertes, salidas y victorias.
- Verificar que cada evento incluya datos como: tiempo de partida, puntuación, nivel actual y sala actual.
- Implementar el campo biomaActual para saber en qué área del juego ocurrió el evento.
- Asegurar que se registran correctamente valores de rankM (maldición) y vida en cada evento.

**Prioridad:** 1  
**Estimación:** 15 hrs

---

## Historia de usuario #3: Registrar la elección de clase al inicio de cada partida
**Como** administrador de base de datos  
**quiero** que el sistema registre la clase elegida por el jugador al inicio de la partida  
**para** que las habilidades y progresión se ajusten correctamente durante el juego.  

### Validación:
- Verificar que la clase elegida (guerrero, arquero, hechicero) se guarde correctamente en la tabla Log_Partida, al inicio de la partida. 
- Asegurar que el campo claseElegida tenga restricciones de tipo ENUM para validar los valores permitidos.
- Confirmar que la clase elegida se registra correctamente al iniciar una nueva partida.
- Confirmar que el jugador no pueda cambiar de clase durante la partida.

**Prioridad:** 1  
**Estimación:** 5 hrs

---

## Historia de usuario #4: Gestionar la cuenta del jugador
**Como** administrador de base de datos  
**quiero** almacenar los datos de los jugadores de forma segura  
**para** que puedan acceder a sus partidas y estadísticas  

### Validación:
- Crear una tabla Jugador con campos para nombre de usuario, correo y contraseña.
- Implementar validaciones para el formato de correo electrónico y nombre de usuario.
- Asegurar que los nombres de usuario y correos sean únicos en la base de datos.
- Implementar restricciones para la contraseña (mínimo 8 caracteres, mayúsculas, minúsculas, números y caracteres especiales).

**Prioridad:** 2  
**Estimación:** 8 hrs

---

## Historia de usuario #5: Registro de enemigos derrotados
**Como** administrador de base de datos  
**quiero** que el sistema registre los diferentes tipos de enemigos derrotados  
**para** ofrecer estadísticas detalladas al jugador  

### Validación:
- Añadir en Log_Partida campos para registrar enemigos comunes, fuertes y jefes derrotados.
- Verificar que estos contadores se actualicen correctamente a lo largo de la partida.
- Asegurar que los valores no puedan ser negativos mediante restricciones.

**Prioridad:** 3  
**Estimación:** 8 hrs

---

## Historia de usuario #6: Recopilar estadísticas de la partida
**Como** administrador de base de datos  
**quiero** que el sistema recopile estadísticas de las partidas (enemigos derrotados, tiempo jugado, muertes, etc.)  
**para** analizar que el jugador pueda ver su rendimiento

### Validación:
- Crear una vista Estadisticas que compile los datos más relevantes de cada partida.
- Incluir métricas como: puntuación final, nivel alcanzado, sala alcanzada, enemigos derrotados y causa de muerte.
- Calcular totales como "TotalEnemigosEliminados" para simplificar las consultas.
- Verificar que la vista se actualice correctamente al finalizar cada partida.

**Prioridad:** 4  
**Estimación:** 15 hrs

---

## Historia de usuario #7: Registro de objetos encontrados
**Como** administrador de base de datos  
**quiero** registrar los objetos que el jugador encuentra durante la partida  
**para** rastrear su progresión e interacción con elementos del juego  

### Validación:
- Añadir en Log_Partida un campo de objetosEncontrados que registre elementos como curandero, armero o cofre.
- Implementar restricciones de tipo ENUM para validar los tipos de objetos permitidos.
- Asegurar que la información del último objeto encontrado esté disponible en la vista de Estadisticas.

**Prioridad:** 3  
**Estimación:** 6 hrs

---

## Historia de usuario #8: Visualización de estadísticas globales
**Como** administrador de base de datos  
**quiero** que el sistema muestre estadísticas globales de todos los jugadores  
**para** identificar tendencias y preferencias de juego  

### Validación:
- Crear consultas para obtener datos como la clase más popular, porcentaje de jugadores por nivel alcanzado, y tipo de muerte más común.
- Verificar que las consultas funcionen correctamente con un volumen significativo de datos.
- Asegurar que los resultados puedan ser representados gráficamente en la interfaz de usuario.

**Prioridad:** 4  
**Estimación:** 6 hrs





## Desarrollo Web
## Historia de usuario #1: Crear la estructura básica de la Web
**Como** desarrollador web  
**quiero** crear la estructura básica de la página Web  
**para** que el juego tenga un espacio en donde ejecutarse  

### Validación:
- Crear una carpeta en GitHub Pages.
- Definir las subcarpetas.
- Implementar el HTML básico.
- Crear y adjuntar la hoja CSS.
- Implementar el script JS.

**Prioridad:** 1  
**Estimación:** 5 hrs

---

## Historia de usuario #2: Optimización de carga
**Como** desarrollador web  
**quiero** que la página cargue rápidamente  
**para** ofrecer una experiencia fluida para el jugador  

### Validación:
- Optimizar el peso de los archivos.
- Comprimir los sprites.
- Medir el rendimiento.

**Prioridad:** 5  
**Estimación:** 2 hrs

---

## Historia de usuario #3: Responsividad del juego
**Como** desarrollador web  
**quiero** que el juego se adapte a diferentes pantallas  
**para** garantizar que se vea bien en cualquier computadora  

### Validación:
- Aplicar un CSS flexible para que el canvas se escale sin distorsionarse.
- Ajustar los controles y HUD para que sean visibles y accesibles en diferentes resoluciones.
- Probar el juego en distintos tamaños de ventana y dispositivos.

**Prioridad:** 3  
**Estimación:** 3 hrs

---

## Historia de usuario #4: Diseño de la Web
**Como** desarrollador web  
**quiero** que la página tenga un diseño atractivo y accesible  
**para** poder mejorar la experiencia del usuario  

### Validación:
- Implementar un diseño visual coherente con la temática del juego.
- Usar etiquetas semánticas para mejorar la accesibilidad.
- Asegurar que los elementos sean intuitivos y fáciles de usar.
- Realizar pruebas con usuarios para verificar la experiencia.

**Prioridad:** 3  
**Estimación:** 3 hrs

---

## Historia de usuario #5: Juego en la Web
**Como** desarrollador web  
**quiero** mostrar el juego  
**para** que el usuario pueda jugar  

### Validación:
- Incluir el canvas en la página y asegurarse de que el juego se vea correctamente.
- Cargar los assets de manera eficiente sin afectar el rendimiento.
- Verificar el desempeño entre el juego y la interfaz web.

**Prioridad:** 1  
**Estimación:** 4 hrs

---

## Historia de usuario #6: Página intuitiva
**Como** desarrollador web  
**quiero** una página web fácil de entender y navegar  
**para** poder mejorar la experiencia del usuario  

### Validación:
- Implementar un menú de navegación simple.
- Usar etiquetas semánticas para mejorar la comprensión.
- Colocar textos claros y concisos.
- Utilizar elementos visuales que guíen al usuario.
- Validar su funcionamiento.

**Prioridad:** 4  
**Estimación:** 4 hrs

---

## Historia de usuario #7: Configurar el entorno de desarrollo
**Como** desarrollador web  
**quiero** configurar mi entorno de desarrollo correctamente  
**para** poder desarrollar de manera eficiente y organizada  

### Validación:
- Configurar Git y GitHub Pages para la versión inicial.
- Crear un repo con una estructura de carpetas clara.
- Implementar un sistema de versiones con commits bien hechos.

**Prioridad:** 1  
**Estimación:** -1 hrs

---

## Historia de usuario #8: Implementar fetch para la interacción con la base de datos

**Como** desarrollador web
**quiero** implementar diferentes funciones fetch en la API
**para** poder consultar, insertar, actualizar y eliminar datos desde el frontend

### Validación:
- Crear funciones fetch para operaciones GET, POST, PUT y DELETE.
- Verificar que cada fetch se conecta correctamente con los endpoints definidos.
- Probar cada operación con datos reales y validar las respuestas del servidor.
**Prioridad:** 2
**Estimación:** 2 hrs

---

## Historia de usuario #9: Crear endpoints para la API

**Como** desarrollador web
**quiero** definir y crear los endpoints necesarios en la API
**para** permitir que el frontend interactúe con la base de datos de forma organizada y segura

### Validación:
- Crear endpoints para las operaciones CRUD principales.
- Asegurar que los endpoints manejen correctamente los parámetros y respuestas.
- Validar que los endpoints respondan y se conecten con la Base de datos.
**Prioridad:** 2
**Estimación:** 2 hrs

---

## Total
- 12 historias de jugador
- 9 historias de desarrollador
- 8 historias de base de datos
- 9 de desarrollo web
- Total de historias: 38 historias de usuario


