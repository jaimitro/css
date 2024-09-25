1

        indispensable el metaviewport

        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        ancho del viewport adaptarse al aparato
        escala inicial normalizada a 1

2

        Controlar tamaño de las imagenes, se deben adaptar al contenedor

        img{
            width: 100%;
            heiht: auto
            display: block
        }

3

        No usar medidas fijas (100px), usar medidas porcentuales o max y min (max-width: 300px)

4

        Uso de mediaqueries: css dentro de css
        breakpoint o puntos de corte, que definen el ancho de nuestro dispositivo, es decir cuando queremos que el dispositivo cambie

- mobilefirst -> ancho min-width
- desktop -> ancho max-width

        0  -> 425px -> mobile
        426px -> 768pc -> mobile grande o tablet pequeña 7"
        769px -> 1004px -> tablet grande - taptop pequeño
        1005px -> 1200px -> portatil, pantalla
        1201 -> alto formato (2k, 4k, retina)