# Table-Forms
## Proyecto de Tablas HTML y CSS

## Minutos clave

- 4.28 --> Fue importante para mi conocer a fondo la definicion de las etiquetas, por que asi pude apropiarlas a la actividad y a usarlas correctamente,siguiento el orden y la estructura para hacer una tabla.

- 12.15 --> La aclaracion que tuve fue de no usar "Solid",por que no se veia bien,en mi tecnico yo dejaba de esa forma mis tablas,tenia 0 conocimiento de que era el peor diseño para las mismas. (Me ayudo a conocer mas estilos)

- 36.15 --> En esta corta fraccion de video pude aprender que se pueden unir 2 columnas,desconocia esa forma de unir columnas porque nunca lo e echo, asi es un buen avance para mi.

- 43.37 --> Siento que la forma de interpretar el padding me fue util y ademas me ayudo a poder interpretar lo qque hace una etiqueta, cosa que no hago, es no entender las etiquetas,las pongo por poner asi que me ayuda bastante estas explicaciones de etiquetas.

## APUNTES
## Etiquetas basicas de CSS utiles (Que no conocia)

- table, th , td {
        border: 1px solid black; --> No solo (Solid), por ejemplo: dotted,dashed,solid,double,groove,rigde.
        border-radius: 10px;
       } --> Bordes a toda la tabla y sus celdas.

- th , td {
        background-color: rgb(163, 209, 209);
       } --> Redondear esquinas 

- th , td {
        border: 1px solid rgb(119, 170, 168);
         border-radius: 10px;
        } --> Pintar el fondo de las celdas 

- tr {
            background-color: rgb(172, 108, 25);
        } --> Color de fondo a toda una fila

- <tr style="height: 200px;">
                        <td>Pedro</td>
                        <td>45</td>
                        <td>Valencia</td>
                    </tr> --> Hacer filas mas altas         

- <th colspan="2">Nombre</th> --> Unir 2 columnas en una sola celda 

- <caption>Tabla de ejemplo</caption> --> Agregar un titulo encima de la tabla

- table, th ,td {
        border: 1px solid black;
        border-collapse: collapse;
    } --> Bordes a las celdas 

    th, td {
        padding: 15px 10px;
        padding-bottom: 20px;
        padding-left: 30px;
        padding-right: 40px;

    } --> Espacio interno del texto y las celdas 

- tr:nth-child(odd) {
            background-color: #992d2d;
        } --> Colorea las filas impares

- tr:hover {
            background-color: #a05d5d;} --> Pasar con mouse y aparece el color


## Lo que investigue como recordatorio 

🔧 Estructura General Utilizada
A lo largo de el trabajo se aplicaron las siguientes etiquetas y propiedades CSS para dar formato a las tablas:

🟨 table, th, td
Selecciona toda la tabla, celdas de encabezado (th) y celdas normales (td) para aplicar reglas generales, como:

border: Borde que rodea cada celda. Tipos usados:

- solid: Línea continua

- dashed: Línea discontinua

- dotted: Línea punteada

- double: Doble línea

- groove, ridge: Efecto 3D

- border-radius: Esquinas redondeadas (ej. 10px).

- border-collapse: Junta los bordes de celdas adyacentes (collapse).

🟧 th, td
Aplica formato al contenido de las celdas:

background-color: Color de fondo (azules, verdes, pasteles, etc.).

padding: Espaciado interno, da aire al texto dentro de las celdas.



