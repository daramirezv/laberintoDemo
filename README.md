## laberintoDemo

**Objetivo**

El objetivo del proyecto fue crear un laberinto de tamaño mediano. Dentro del laberinto hay unas imágenes en las paredes que contienen acertijos. Con la respuesta de los acertijos, se le va a indicar al jugador por dónde debe ir. Si escogió mal alguna respuesta, se va a encontrar con una pared que dice "incorrecto" y deberá devolverse para ir por el camino correcto. Los acertijos son solo guías, ya que la persona puede ignorarlos si quiere.

**Movimiento**

Para moverse dentro del laberinto, la persona debe utilizar los controles del vive. Al oprimir el trackpad, va a aparecer una zona verde con la que puede apuntar a dónde quiere ir.

**Instalación**

Todo el juego fue hecho en la versión de Unity que se encuentra en Colivrí (2018.3.5). Debido a esto, se necesita por lo menos esta versión para ejecutar el juego.

* Se debe descargar el repositorio a una carpeta en el computador.
* Al abrir Unity, hay que seleccionar la opción de "open".
* Ahora hay que seleccionar la carpeta que se llama "laberinto" dentro del repositorio que acabamos de descargar y poner "select folder" (laberintoDemo\laberinto).
* Se debe abrir SteamVR que es la aplicación que lee y deja listo el Vive con sus controles.
* Ya se puede poner "play" en Unity para empezar a jugar.

**Extensión/Demo Base**

La aplicación fue hecha desde cero, por lo que no utilicé ninguna base de un proyecto ya existente.

**Cómo se realizó**

Armé el mapa con figuras geométricas ofrecidas por Unity. Los assets de las paredes, el piso y el cielo los descargué de la tienda y se los aplique a los objetos respectivos. Una vez tuve listo el mapa, descargué el plugin de SteamVR para Unity que viene con unos pre-fabs ya hechos. Utilicé los prefabs para que aparecieran las manos del jugador y se pudiera teletransportar en el mapa. Hubo que agregar un script que se encontraba dentro del asset de Steam VR a todo el piso. Para las imágenes de los acertijos, utilicé capturas de pantalla de un juego que se llama "Professor Layton" que trata de acertijos. Estos .jpg los agregué como assets a las paredes respectivas.
