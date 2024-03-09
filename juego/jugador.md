---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# ☠️ Jugador

## Contenedor

El jugador se personifica como un ente no-muerto llamado Contenedor. Este ente debe acumular sangre para mantener su vida. Cuando el Contenedor no tiene sangre, su cuerpo está completamente blanco y sin vida, pero a medida que acumula sangre, su cuerpo se va tornando progresivamente más rojo y lleno de vitalidad. Esta representación visual no solo proporciona una forma intuitiva de comprender el estado de salud del jugador, sino que también añade una capa de inmersión al juego, permitiendo a los jugadores sentirse más conectados con su personaje y su lucha por sobrevivir.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p><em>Imagen generada por IA. Representa la visión del proyecto, pero no determina el arte final.</em></p></figcaption></figure>

## Vida

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p><em>Boceto que representa el sistema de vida.</em></p></figcaption></figure>

El sistema de vida en el juego se compone de tres elementos principales: plaquetas, sangre y energía.

* **Plaquetas:** Esta barra representa el escudo general del personaje. Cada vez que el personaje recibe daño, las plaquetas se activan para formar un escudo temporal que reduce el daño recibido. Si la barra llega a cero, el siguiente daño recibido restará sangre al jugador.
* **Sangre:** Esta barra representa la salud general del personaje y se reduce cada vez que recibe daño. Si la barra de vida llega a cero, el personaje muere.
* **Plasma:** Esta barra representa la capacidad del personaje para realizar esquivas. Cada vez que se esquiva, la barra de plasma se reduce.

## Pesadilla

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p><em>Boceto que representa cómo las pesadillas afectan al sistema de vida.</em></p></figcaption></figure>

La **pesadilla** afecta a aquellos jugadores que pasan mucho tiempo en el abismo. A partir de las 6h de juego continuo, comienza a aplicarse un decremento gradual en la salud del jugador, disminuyendo un porcentaje determinado con cada hora adicional de juego. Este efecto persiste hasta que el jugador sólo dispone de un 20% de salud. Normalmente, la mayoría de los jugadores no se verán afectados.

Es posible contrarrestar los efectos dejando permaneciendo desconectado del juego el mismo tiempo que acumuló de pesadilla. O adquiriendo una poción especial que limita los impactos negativos en la salud del jugador, permitiéndole prolongar su sesión de juego.

#### **Objetivo**

Otros proyectos de Gamefi limitan las sesiones de juegos mediante un sistema de energía. Este sistema es heredado de malas prácticas de monetización de juegos móviles. Su objetivo es limitar el número de tokens o NFT que un jugador puede obtener para no romper la economía del juego.

En lugar de imponer límites de tiempo restrictivos para monetizar el juego, hemos desarrollado un sistema de energía menos intrusivo que permite a los jugadores tener más control sobre su tiempo de juego.

Este enfoque evita que algunos jugadores con más tiempo libre se beneficien injustamente sobre otros con menos disponibilidad, al tiempo que mitiga los riesgos económicos a largo plazo. Nuestro objetivo es promover una experiencia de juego más equitativa y sostenible, donde los jugadores disfruten de mayor libertad para jugar según sus preferencias.

## Propiedades NFT

Es importante destacar que los contenedores no poseen características NFT y, por lo tanto, no pueden ser objeto de comercio. El contenedor es simplemente un representante virtual del jugador en el Abismo Infernal, esencial para su experiencia de juego, pero no diseñado para ser intercambiado o transferido entre jugadores.
