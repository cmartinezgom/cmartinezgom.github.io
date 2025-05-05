---
layout: archive
title: "🐟 The Abyss"
excerpt: "Developed in a couple of weeks for the Confounding Calendar 2024"
permalink: /portfolio/theabyss/
header:
  image: /images/FlashYourFears.jpg
  teaser: /images/FlashYourFears.jpg
gallery:
  - url: /images/flashyourfears/flashyourfearsmenu.png
    image_path: /images/flashyourfears/flashyourfearsmenu.png
    alt: "placeholder image 1"
  - url: /images/flashyourfears/flashyourfears25.png
    image_path: /images/flashyourfears/flashyourfears25.png
    alt: "placeholder image 2"
  - url: /images/flashyourfears/flashyourfears1.png
    image_path: /images/flashyourfears/flashyourfears1.png
    alt: "placeholder image 2"
  - url: /images/flashyourfears/flashyourfears3.png
    image_path: /images/flashyourfears/flashyourfears3.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears4.png
    image_path: /images/flashyourfears/flashyourfears4.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears6.png
    image_path: /images/flashyourfears/flashyourfears6.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears7.png
    image_path: /images/flashyourfears/flashyourfears7.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears10.png
    image_path: /images/flashyourfears/flashyourfears10.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears12.png
    image_path: /images/flashyourfears/flashyourfears12.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears13.png
    image_path: /images/flashyourfears/flashyourfears13.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears14.png
    image_path: /images/flashyourfears/flashyourfears14.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears15.png
    image_path: /images/flashyourfears/flashyourfears15.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears17.png
    image_path: /images/flashyourfears/flashyourfears17.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears18.png
    image_path: /images/flashyourfears/flashyourfears18.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears20.png
    image_path: /images/flashyourfears/flashyourfears20.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears21.png
    image_path: /images/flashyourfears/flashyourfears21.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears22.png
    image_path: /images/flashyourfears/flashyourfears22.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears23.png
    image_path: /images/flashyourfears/flashyourfears23.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/flashyourfears24.png
    image_path: /images/flashyourfears/flashyourfears24.png
    alt: "placeholder image 3"
  - url: /images/flashyourfears/particlepixelartfire.png
    image_path: /images/flashyourfears/particlepixelartfire.png
    alt: "placeholder image 3"
---
[**Itch.io** <i class="fa-brands fa-itch-io"></i>](https://patatinpatatan.itch.io/the-abyss) ||| [**GitHub** <i class="fa-brands fa-github"></i>](https://github.com/Mavalco/proyecto-patatin-patatan) ||| [**Game Jam** <i class="fa-solid fa-jar"></i>](https://confoundingcalendar.itch.io/)

<div style="width: 70%; margin: auto;">
  <img src="/images/FlashYourFears.jpg" alt="full" style="display: block; margin: auto; width: 100%;">
</div>

The Abyss is a short 2D puzzle game made with Unity set in an underwater masion, through which the player must explore to uncover all its secrets and be able to brake free.

It was developed by me and five other friends in **a couple weeks** for [the Confounding Calendar 2024](https://confoundingcalendar.itch.io/).

I was the **lead programmer, solo designer and overall producer/director**.

The Abyss buscó crear un juego de puzles corto de un solo nivel usando una paleta de colores limitada. Por ello el equipo se decidió a aprovechar los colores y el diseño del puzle para una mecánica principal: El uso de la luz y lo que puedes ver dependiendo de su color.

Una vez se planteó la idea de juego y mis compañeros de arte plantearon la estética del juego, boceté un primer borrador de lo que podría ser el puzle y propuse una mecánica extra para darle un toque de puzle de verdad: Las habitaciones de la casa pueden reubicarse y el jugador deberá avanzar dependiendo de los colores de luz que tenga y del orden de las habitaciones.

*boceto que hice del puzle en Paint*
![full](/images/KatergarisLabyrinthUI.jpg){: full}

Esta mecánica adicional me parecía que le daba al juego algo más que no fuese simplemente avanzar por la casa encontrándose cristales de colores, y obligaba al jugador a plantearse qué usos había visto para cada tipo de luz en cada una de las habitaciones, y qué uso le podría dar a ese elemento en otras configuraciones de la casa. Por ejemplo: En una habitación podría encontrarse un agujero que solamente se puede ver con la luz naranja, y reordenando la casa, ese mismo agujero le podría permitir caer en una habitación a la que no puede acceder desde el rellano.

El diseño el puzle lo pensé introduciendo las mecánicas poco a poco para que se llegasen a entender bien, por lo que el jugador, idealmente, pasaría por los siguientes estados:
1- **Desconocimiento**: El jugador solamente ve al pequeño pez, rodeado de total oscuridad mostrando los controles del juego. Aquí descubrirá cómo moverse hacia los lados con su personaje. Aparecerá en el extremo izquierdo del ático, para moverse instintivamente hacia la derecha.
2- **Luz**: En la oscuridad, lo único que podrá distinguir será el primer cristal en el extremo derecho del ático, destacando además por su color llamativo y un efecto de partículas de brillos. Al tenerlo cerca le aparecerá la "E" para interaccionar con él. Al hacerlo, el jugador adquirirá el cristal y, al ser la primera luz, la oscuridad total que envolvía al personaje se irá retirando para, ahora sí, descubrirle toda una casa que explorar.
3- **Escaleras**: Ahora que puede ver los diferentes pisos de la casa y tiene su primera luz alrededor del personaje, al volver hacia atrás descubrirá que gracias a esta luz, ahora puede ver una escalera de su mismo color en el medio del ático, justo encima de los rellanos. El jugador instintivamente bajará por ella, descubriendo la mecánica de subir y bajar por escaleras.
4- **Puerta cerrada**: Unos pisos más abajo, con la luz se le mostrará una puerta del mismo color del cristal con una gran "E" de interacción, pero no podrá abrirla y escuchará un sonido de que está cerrada. El jugador entenderá instintivamente que debe buscar una llave.
5- **Primera llave**: El jugador seguirá bajando hasta el salón, desde donde podrá ver un esqueleto moviéndose por la habitación cerrada, reforzando su curiosidad. Tras seguir explorando el salón, encontrará una criatura con la que podrá interactuar, y recibirá su primera llave, del mismo color del cristal y la puerta, con la que podrá abrir la puerta.
6- **Segundo cristal**: Tras abrir la puerta cerrada e interaccionar con el esqueleto, este le dará el segundo cristal. Al interaccionar con él se equipa automáticamente, cambiando el color de la luz y revelando una escalera de mano que no podía ver con la luz inicial, y que le permite subir a la habitación que tiene justo encima.
7- **Uso de cristales**: En la habitación superior encontrará la llave del mismo color que el nuevo cristal y la llave para abrirla. Al bajar por el rellano (o por la escalera que le llevó a esta habitación), descubrirá que con la nueva luz no puede ver la primera puerta cerrada del juego, aprendiendo así la importancia del cambio de cristales.
Nota: Originalmente diseñé todo para que este cristal fuese el rosa, y así diferenciarse más del color del primer cristal. Sin embargo, mis compañeros de arte intercambiaron los colores y se quedó así. Creo que con el color rosa hubiese quedado mucho más claro el cambio de luz, de cristal, y por ende, que el jugador puede usarlos indistintamente.
8- **Mover habitaciones**: Con el nuevo cristal, el jugador podrá bajar de nuevo al salón, donde en el extremo derecho, se le mostrará una trampilla que le permite bajar al sótano, donde le aguardará una misteriosa criatura con la que podrá hablar. Este ser se utiliza para marcar el ambiente del juego, pero también es el desbloqueo de la mecánica de movimiento de habitaciones. Tras un breve diálogo, le preguntará al jugador si quiere modificar la casa, y el jugador podrá decir que sí o no. Al decir que sí, se sale automáticamente del diálogo y se reproduce la animación en la que las habitaciones rotan en sentido antihorario. Al haber salido de la conversación, la primera reacción del jugador seguramente será investigar la nueva disposición de la casa.
9- **Momento Eureka**: Al explorar la casa de nuevo, el jugador descubrirá que se han movido tanto las habitaciones, como sus puertas correspondientes y... Los elementos dentro de cada una de ellas. En este momento, idealmente, se dará cuenta de que la escalera que le permitió subir a la habitación del segundo cristal, ahora le permite subir al ático, dado que es lo que se encuentra justo encima de la habitación del esqueleto.
10- **Conocimiento del juego**: Ahora que se le han presentado todas las mecánicas y ha entendido cómo usarlas, el jugador podrá explorar todas las habitaciones de la casa moviéndolas de posición y usando los distintos cristales, hasta que finalmente pueda completar este puzle/scape room y salir de la mansión sumergida. En caso de no haberlas entendido también se puede completar el juego con fuerza bruta, pero llevará más intentos que entendiendo la situación.


Mi contribución:
- **Diseño del puzle**: Diseño e iteración del puzle principal del juego.
- **Mecánica principal**: Diseño e implementación de la mecánica principal del puzle, el poder mover las habitaciones de lugar.
- **Sistema de luces y elementos**: Implementación del sistema de luces y capas para mostrar diferentes elementos o habitaciones dependiendo del color de la luz actual. Probé tanto hacerlo con máscaras como hacer spawn de objetos al detectar el overlap con la luz correspondiente. Lo óptimo hubiese sido usar solamente las máscaras, pero dado que Unity no permite tener varias máscaras a la vez (o al menos no en la versión utilizada para la Jam), me decanté por el uso de ambas a la vez: Habría una única máscara para mostrar solamente los elementos del color de la luz actual en su radio de alcance, pero a su vez el cambio de luces se haría activando y desactivando las distintas "capas" de colores de la casa.
- **Movimiento del jugador**: Implementación de un player controller sencillo que permitiese moverse lateralmente, interaccionar, cambiar de luz y subir/bajar escaleras.
- **Game Manager**: Definición e implementación de la lógica general del juego, así como el Game Manager que trackea el progreso actual, las luces y llaves obtenidas, el cambio de escenas, etc...
- **Support**: También di soporte y ayudé a mis compañeros tanto de programación como de arte a la hora de importar assets, implementar una mecánica, resolver bugs, etc...
- **UI Logic**: Implementación de la lógica de la UI, principalmente del menú principal y los créditos.

And more!

It's a pretty short game and it was built using Unity WebGL, so **play it now right here!*^*

<div style="position: relative; padding-bottom: 57.29%; /* Aspect ratio (1100 / 1920 * 100) */ height: 0; overflow: hidden; max-width: 100%; margin: 1.5em auto;">
  <iframe
    frameborder="0"
    src="https://itch.io/embed-upload/12137062?color=a7a79e"
    allowfullscreen=""
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;"
  >
    <a href="https://patatinpatatan.itch.io/the-abyss">Play The Abyss on itch.io</a>
  </iframe>
</div>

<iframe frameborder="0" src="https://itch.io/embed/3144622" width="552" height="167"><a href="https://patatinpatatan.itch.io/the-abyss">The Abyss by PatatinPatatan, JAMZILA, cmartinezgom</a></iframe>

Too scared to play? Check out these screenshots:

{% include gallery.html caption="The Abyss screenshots." %}
