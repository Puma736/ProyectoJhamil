Quiero que desarrolles una experiencia web interactiva de una sola página inspirada en un jardín mágico de flores amarillas, similar visualmente a una escena 3D romántica/floral.

IMPORTANTE:
No quiero una página web convencional con tarjetas o una cuadrícula de flores.
Quiero que toda la pantalla sea una escena inmersiva donde las flores estén distribuidas en profundidad y parezca que están flotando alrededor del usuario.

OBJETIVO PRINCIPAL
Crear una página HTML interactiva que pueda abrirse directamente en un navegador y que muestre un jardín mágico de flores amarillas en un entorno oscuro, con profundidad 3D, partículas luminosas y animaciones suaves.

TECNOLOGÍAS

Utiliza:

- HTML5
- CSS3
- JavaScript
- Three.js para el efecto 3D
- JavaScript ES6+
- WebGL mediante Three.js

No utilizar React.
No utilizar Vue.
No utilizar Angular.
No utilizar backend.
No utilizar base de datos.

La aplicación debe poder ejecutarse como una página web estática.

ESTRUCTURA DEL PROYECTO

Crear:

/index.html
/style.css
/script.js
/assets/

Si es necesario utilizar imágenes:

/assets/flowers/
/assets/music/
/assets/images/

La estructura debe ser sencilla y fácil de modificar.

--------------------------------------------------
1. ESCENA PRINCIPAL
--------------------------------------------------

La pantalla completa debe convertirse en una escena 3D.

Fondo:

- Negro muy oscuro.
- Tonos verdes oscuros.
- Iluminación amarilla muy tenue.
- Aspecto de jardín mágico nocturno.
- Sin bordes blancos.
- Sin apariencia de dashboard.
- Sin tarjetas visibles inicialmente.
- La escena debe ocupar prácticamente toda la pantalla.

Agregar un ligero efecto de iluminación ambiental amarilla alrededor del centro.

Debe existir una sensación de profundidad.

Las flores que estén cerca de la cámara deben verse más grandes.

Las flores que estén lejos deben verse más pequeñas y ligeramente desenfocadas.

--------------------------------------------------
2. FLORES AMARILLAS
--------------------------------------------------

Crear aproximadamente entre 20 y 30 flores amarillas.

Las flores deben parecer flores amarillas reales, similares a girasoles, margaritas amarillas o flores pequeñas de campo.

No quiero que todas sean exactamente iguales.

Variar:

- tamaño
- rotación
- posición
- profundidad
- inclinación
- velocidad de movimiento

Distribuirlas en todo el espacio 3D.

Ejemplo conceptual:

                🌼

        🌻                 🌼

              🌼

   🌼                     🌻

             🌻

       🌼             🌼

Las flores NO deben formar una cuadrícula.

Deben estar distribuidas orgánicamente.

Algunas flores deben estar muy cerca de la cámara.

Otras deben estar al fondo.

--------------------------------------------------
3. MOVIMIENTO 3D
--------------------------------------------------

Este punto es MUY IMPORTANTE.

Las flores deben moverse suavemente como si estuvieran flotando en el aire.

Cada flor debe tener un movimiento ligeramente diferente.

Utilizar:

- movimiento vertical suave
- movimiento horizontal suave
- rotación lenta
- oscilación
- movimiento sinusoidal
- pequeñas variaciones aleatorias

El movimiento debe ser lento y elegante.

NO hacer movimientos rápidos.

NO hacer que las flores giren violentamente.

La animación debe sentirse romántica y relajante.

--------------------------------------------------
4. EFECTO PARALLAX / PROFUNDIDAD
--------------------------------------------------

Implementar un efecto 3D/parallax.

Cuando el usuario mueve el mouse:

- las flores cercanas deben desplazarse más
- las flores lejanas deben desplazarse menos
- el fondo debe moverse ligeramente
- la cámara debe reaccionar suavemente

El movimiento del mouse no debe mover bruscamente la escena.

Utilizar interpolación/suavizado.

Por ejemplo:

mouse → derecha

las flores cercanas se desplazan ligeramente en sentido contrario.

Las flores lejanas casi no se mueven.

Esto debe crear la sensación de estar dentro del jardín.

--------------------------------------------------
5. SOPORTE PARA CELULAR
--------------------------------------------------

En dispositivos móviles no existe mouse.

Por eso:

utilizar touch/pointer events para producir un efecto de movimiento similar.

Cuando el usuario deslice el dedo:

la cámara debe reaccionar suavemente.

También se puede utilizar el movimiento del dispositivo si el navegador lo permite, pero debe existir un fallback mediante touch.

La página debe ser totalmente responsive.

Debe funcionar correctamente en:

- computadora
- laptop
- tablet
- celular

No debe existir scroll horizontal.

--------------------------------------------------
6. PARTÍCULAS
--------------------------------------------------

Agregar cientos de pequeñas partículas luminosas.

Las partículas deben parecer:

- polvo mágico
- polen
- pequeñas partículas de luz
- estrellas diminutas

Usar tonos:

- amarillo
- dorado
- verde amarillento
- blanco cálido

Las partículas deben moverse lentamente.

Algunas deben acercarse a la cámara.

Otras deben estar en el fondo.

Crear profundidad mediante diferentes tamaños y velocidades.

También agregar algunas partículas ligeramente desenfocadas.

--------------------------------------------------
7. EFECTO DE LUZ
--------------------------------------------------

Crear una iluminación central suave de color amarillo/dorado.

La iluminación debe dar la impresión de que existe una fuente de luz en el centro del jardín.

Agregar pequeños puntos de luz alrededor de algunas flores.

No exagerar el brillo.

Debe verse elegante.

--------------------------------------------------
8. TEXTO FLOTANTE
--------------------------------------------------

Algunas flores deben tener pequeños textos flotando cerca.

Ejemplos:

"Mi Amor"

"Eres preciosa"

"Me encantas"

"Para ti"

"Gracias por existir"

"Mi vida"

"Te quiero"

"Siempre contigo"

Los textos deben ser pequeños y elegantes.

No colocar texto sobre todas las flores.

Solo algunas flores tendrán mensajes.

El texto debe moverse ligeramente junto con la flor.

Utilizar una tipografía elegante.

Puede utilizarse:

- Playfair Display
- Cormorant Garamond
- Georgia

Los textos deben tener color blanco cálido o amarillo claro.

--------------------------------------------------
9. INTERACCIÓN CON LAS FLORES
--------------------------------------------------

ESTE ES UNO DE LOS REQUISITOS PRINCIPALES.

Cada flor debe ser interactiva.

Cuando el usuario coloque el mouse encima de una flor:

- aumentar ligeramente su tamaño
- aumentar ligeramente su brillo
- mostrar un pequeño efecto luminoso
- cambiar ligeramente la escala

En celular:

debe funcionar mediante tap.

Cuando el usuario haga clic/tap sobre una flor:

debe abrirse una carta.

--------------------------------------------------
10. CARTA / MENSAJE
--------------------------------------------------

Cada flor debe tener asociado un mensaje diferente.

Ejemplo:

Flor 1:

Título:
"Para ti ❤️"

Mensaje:
"Quería dejarte estas palabras para recordarte lo especial que eres."

Flor 2:

Título:
"Eres preciosa"

Mensaje:
"Tu forma de ser hace que todo sea un poquito más bonito."

Flor 3:

Título:
"Gracias"

Mensaje:
"Gracias por todos esos momentos que se quedan guardados en el corazón."

Flor 4:

Título:
"Mi persona especial"

Mensaje:
"Hay personas que llegan a nuestra vida y hacen que todo tenga otro significado."

Flor 5:

Título:
"Siempre"

Mensaje:
"Espero que siempre podamos compartir momentos que nos hagan sonreír."

Los mensajes deben estar almacenados en un arreglo JavaScript para poder modificarlos fácilmente.

Ejemplo:

const messages = [
    {
        title: "Para ti ❤️",
        text: "Quería dejarte estas palabras..."
    },
    {
        title: "Eres preciosa",
        text: "Tu forma de ser..."
    }
];

--------------------------------------------------
11. ANIMACIÓN DE LA CARTA
--------------------------------------------------

NO mostrar simplemente un alert().

Crear una carta visual.

Cuando el usuario seleccione una flor:

1. La escena debe oscurecerse ligeramente.
2. La cámara puede acercarse suavemente a la flor.
3. Aparece una carta en el centro.
4. La carta entra mediante una animación.
5. La carta puede tener apariencia de papel.
6. Mostrar título.
7. Mostrar mensaje.
8. Mostrar un pequeño corazón o decoración floral.

La carta debe tener:

- fondo color crema
- bordes suaves
- sombra
- detalles amarillos/dorados
- tipografía elegante

Ejemplo visual:

        ┌─────────────────────────┐
        │          🌼             │
        │                         │
        │       Para ti ❤️        │
        │                         │
        │  Quería dejarte estas   │
        │  palabras para decirte │
        │  lo especial que eres. │
        │                         │
        │          🌻             │
        │                         │
        │       [Cerrar]          │
        └─────────────────────────┘

--------------------------------------------------
12. CIERRE DE LA CARTA
--------------------------------------------------

Agregar un botón:

"Cerrar"

Cuando se presione:

- cerrar la carta mediante animación
- desaparecer el overlay
- regresar a la escena 3D
- continuar las animaciones de las flores

NO recargar la página.

--------------------------------------------------
13. INTRODUCCIÓN
--------------------------------------------------

Al entrar a la página mostrar inicialmente una pequeña introducción.

Por ejemplo:

"Para alguien especial..."

debajo:

"Hay un pequeño mensaje escondido en cada flor."

Y un botón:

"Entrar al jardín 🌻"

Al presionar el botón:

- desaparecer la introducción
- comenzar la experiencia 3D
- iniciar las animaciones
- mostrar las flores

La introducción debe ser elegante y minimalista.

--------------------------------------------------
14. MÚSICA
--------------------------------------------------

Preparar soporte para música ambiental.

Crear:

/assets/music/background.mp3

La música debe comenzar solamente después de una interacción del usuario, por las restricciones de autoplay de los navegadores.

Agregar un pequeño botón para:

🔊 Música

y permitir:

- reproducir
- pausar
- activar/desactivar sonido

Si no existe el archivo MP3, la página debe continuar funcionando normalmente.

No debe aparecer ningún error.

--------------------------------------------------
15. EFECTOS VISUALES
--------------------------------------------------

Agregar sutilmente:

- partículas
- polvo luminoso
- pequeñas estrellas
- glow amarillo
- desenfoque de profundidad
- iluminación ambiental
- movimiento de cámara
- parallax
- flores flotantes
- pequeños destellos

NO sobrecargar la pantalla.

El resultado debe sentirse elegante y mágico.

--------------------------------------------------
16. CÁMARA 3D
--------------------------------------------------

Crear una cámara PerspectiveCamera.

Utilizar una profundidad suficiente para colocar flores delante y detrás.

Por ejemplo:

z = -20 hasta z = 10

La cámara debe moverse suavemente.

No utilizar movimientos bruscos.

Implementar interpolación:

camera.position.x += (targetX - camera.position.x) * 0.03;

o una técnica equivalente.

--------------------------------------------------
17. RENDERIZADO
--------------------------------------------------

Utilizar Three.js.

Crear:

Scene
PerspectiveCamera
WebGLRenderer

Implementar:

requestAnimationFrame()

para mantener una animación fluida.

Optimizar el número de objetos para dispositivos móviles.

Intentar mantener aproximadamente:

60 FPS en computadora

y una experiencia fluida en celular.

--------------------------------------------------
18. PROFUNDIDAD DE CAMPO
--------------------------------------------------

Si es posible utilizar post-processing de Three.js:

- EffectComposer
- UnrealBloomPass
- BokehPass

para crear:

- glow
- profundidad
- desenfoque de objetos lejanos

Pero si esto complica demasiado el proyecto, crear un fallback utilizando CSS/Three.js básico.

La página debe funcionar aunque el post-processing no esté disponible.

--------------------------------------------------
19. DISEÑO RESPONSIVE
--------------------------------------------------

Desktop:

La escena ocupa toda la ventana.

Mobile:

Reducir:

- cantidad de partículas
- cantidad de flores
- efectos pesados

para mejorar rendimiento.

Las cartas deben adaptarse al tamaño de pantalla.

Nunca permitir que la carta salga de la pantalla.

--------------------------------------------------
20. ACCESIBILIDAD
--------------------------------------------------

Agregar:

- botones accesibles
- aria-label cuando sea necesario
- posibilidad de cerrar la carta con ESC
- buen contraste del texto
- soporte para prefers-reduced-motion

Si el usuario tiene activada la reducción de movimiento:

reducir considerablemente las animaciones.

--------------------------------------------------
21. RENDIMIENTO
--------------------------------------------------

Optimizar la aplicación.

No crear cientos de objetos Three.js independientes si no es necesario.

Para partículas utilizar:

THREE.Points

y

THREE.BufferGeometry

para mejorar rendimiento.

Evitar cálculos innecesarios dentro del animation loop.

Detectar dispositivos móviles y reducir efectos.

--------------------------------------------------
22. PERSONALIZACIÓN
--------------------------------------------------

Crear una sección claramente identificada dentro de script.js donde pueda modificar fácilmente:

- cantidad de flores
- mensajes
- títulos
- colores
- velocidad
- tamaño de partículas
- música
- textos de bienvenida

Por ejemplo:

const CONFIG = {
    flowerCount: 25,
    particleCount: 500,
    flowerSpeed: 0.5,
    particleSpeed: 0.2
};

Y:

const messages = [
    {
        title: "Mi Amor ❤️",
        text: "..."
    },
    {
        title: "Eres preciosa 🌼",
        text: "..."
    }
];

--------------------------------------------------
23. EXPERIENCIA FINAL
--------------------------------------------------

La experiencia completa debe sentirse así:

1. El usuario abre index.html.

2. Aparece:

"Para alguien especial..."

"Hay un pequeño mensaje escondido en cada flor."

[ Entrar al jardín 🌻 ]

3. El usuario presiona el botón.

4. Aparece el jardín 3D.

5. Las flores amarillas flotan alrededor.

6. Las partículas se mueven.

7. El usuario mueve el mouse y la escena responde.

8. El usuario observa diferentes textos:

"Mi Amor"

"Eres preciosa"

"Me encantas"

"Para ti"

9. El usuario hace clic en una flor.

10. La flor responde con una animación.

11. Se abre una carta.

12. Aparece el mensaje correspondiente a esa flor.

13. El usuario pulsa "Cerrar".

14. Regresa al jardín.

15. Puede seleccionar otra flor y descubrir otro mensaje.

--------------------------------------------------
24. ESTILO VISUAL
--------------------------------------------------

La referencia visual debe ser:

- romántica
- elegante
- mágica
- nocturna
- floral
- cálida
- inmersiva
- delicada

Paleta aproximada:

Fondo:
#020402

Verde oscuro:
#071507

Amarillo:
#F5C518

Dorado:
#D9A441

Blanco cálido:
#FFF8DC

Crema:
#FFF4D6

Evitar colores extremadamente saturados.

--------------------------------------------------
25. IMPORTANTE SOBRE LAS FLORES
--------------------------------------------------

No utilizar simplemente emojis 🌻 como flores principales.

Las flores deben ser elementos visuales reales creados mediante:

- sprites
- texturas PNG con transparencia
- SVG
- geometría de Three.js

Preferentemente utilizar imágenes PNG transparentes de flores amarillas para obtener un resultado visual más bonito.

Si no existen imágenes disponibles, crear un fallback mediante formas/partículas.

--------------------------------------------------
26. RESULTADO FINAL
--------------------------------------------------

Quiero que entregues el proyecto COMPLETO.

No solamente fragmentos de código.

Entregar:

1. index.html completo
2. style.css completo
3. script.js completo
4. estructura de carpetas
5. explicación de dónde colocar las imágenes
6. explicación de dónde colocar la música
7. instrucciones para ejecutar el proyecto

El código debe estar listo para copiar y pegar.

IMPORTANTE:

No simplifiques la experiencia convirtiéndola en una página estática.

El objetivo es conseguir una experiencia visual 3D inmersiva de flores amarillas flotando en un espacio oscuro, con partículas, profundidad, movimiento de cámara, parallax y cartas interactivas.

La prioridad visual es:

1. profundidad 3D
2. flores amarillas flotantes
3. partículas
4. movimiento/parallax
5. interacción con las flores
6. cartas animadas
7. estética romántica y elegante
8. rendimiento en celular

Antes de entregar el código, verifica que no existan errores de JavaScript, referencias a elementos inexistentes o variables sin definir.