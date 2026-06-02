## Bitácora
<ul>
    <i>
        Aviso: por lo menos en esta parte puede haber inconsistencias, ya que me olvidé de documentar desde el principio.
    </i>
</ul>

## <b><i>Índice / Días</i></b>
<ol>
<li><a href="#20-04-2026">20-04-2026</a></li>
<li><a href="#21-04-2026">21-04-2026</a></li>
<li><a href="#25-04-2026">25-04-2026</a></li>
<li><a href="#07-05-2026">07-05-2026</a></li>
<li><a href="#10-05-2026">10-05-2026</a></li>
<li><a href="#18-05-2026">18-05-2026</a></li>
<li><a href="#20-05-2026">20-05-2026</a></li>
<li><a href="#02-06-2026">02-06-2026</a></li>
</ol>
<hr>
<hr>

## 20-04-2026
Me dieron mes y medio para hacerlo; los requerimientos, a grandes rasgos, son una instalación de red para una cafetería con dos redes separadas: una para empleados y otra para clientes, que no se pueda hacer ping de una a otra y que tenga configurado el DHCP para ambas redes. Primero empezaré con Cisco, ya que en sí es lo más fácil de hacer, e iré desarrollando todo conforme avance.
<hr>
<hr>

## 21-04-2026
Después de pensarlo mucho, al final decidí hacer primero el diseño de la cafetería. Me lo aventaré en [diagram.io](https://diagram.io) para solo importarlo al formato que acepta Cisco. Además se me ocurrió configurar una TV para la cafetería :3
<hr>
<hr>

## 25-04-2026
Ok, ya me aventé la estructura; se me pasó hacer el "modelo o plano" de la red, así que me lo aventaré otra vez para agregarlo. Por mientras veré cómo le hago con lo de la tele; la verdad lo demás fue "fácil", pero la tele me está matando.
<hr>
<hr>
<i>Sabático de vacaciones del <b>16/17 de abril</b> al <b>6 de mayo</b>.</i>
<hr>
<hr>

## 07-05-2026
Ok, la neta me hice wey, pero ya vi cómo configurar la TV: solo es ponerle imágenes en formato PNG a una nube y luego conectarla a la TV. Lo voy a elaborar; intentaré poner una animación sencilla para esto. Además ya está configurada la red; solo haré algunas pruebas para ver si funciona. Por mientras, configuraré DHCP en el switch.
<hr>
<hr>

## 10-05-2026
Ya quedó la TV; usé [Kirta](https://krita.org) para convertir la animación .gif a secuencia de imágenes y las subí. Además de esto, después de revisar la red de la cafetería me dio un error: la configuración de la red de empleados está mal configurada; tendré que resolverlo. Por el momento lo dejaré así.
<hr>
<hr>

## 18-05-2026
Después de revisar, lo último que falta es configurar bien el DHCP para que dé la dirección IP correcta y se pueda hacer ping. Voy a preguntar qué más falta o algo así para acabarlo ya.
<hr>
<hr>

## 20-05-2026
Ok, intente cambiar el como configuraba, pero todo fallo, los DHCP no están nada bien y me hice bolas, por el momento me asesorare y vere como lo arreglo para que quede mejor, por el momento hare el primer commit a github
<hr>
<hr>

## 02-06-2026
Después de dejar el proyecto por temas de otros proyectos, lo retoma por recomendación del profesor; al final solo era no cagarla con la configuración del DHCP para que todo saliera bien. Lo único que hice fue bloquear las IP correctas con el comando 
    ip dhcp excluded-address [la ip con máscara]
para que todo funcionara correctamente. Ya haré el último commit y le mandaré el enlace al maestro. La verdad no tengo material didáctico extra más que el final en las carpetas [videos](https://github.com/Had3rm3sGit/Red_Cafeteria_Unicornio/tree/main/Material/videos) y en la carpeta [img](https://github.com/Had3rm3sGit/Red_Cafeteria_Unicornio/tree/main/Material/img), pero fuera de esto la verdad estoy feliz de haberlo acabado para exentar; solo sería cumplir con mi otro proyecto.
En general, hoy solo fue arreglar todo y tenerlo listo. Cualquier solicitud posterior será añadida.

### Ideas descartadas por falta de tiempo y de conocimiento
<ol>
    <li>
        <i>
            Implementación de teléfono analógico y simulación de llamada para un pedido por el mismo medio.
        </i>
    </li>
    <li>
        <a href="https://www.youtube.com/watch?v=MuUrfz5nxys">curiosidad</a>
    </li>
</ol>