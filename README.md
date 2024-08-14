<!DOCTYPE html>
<html lang="es">
<head><!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basura Tecnológica</title>
    <!-- Agrega el ícono de la pestaña del navegador -->
    <link rel="icon" type="image/png" href="https://ideogram.ai/assets/image/list/response/pEfXHfeZQzKx_UU6RyDqRg">

    <style>
        /* Estilos CSS */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000000;
            background-image: url('https://ideogram.ai/api/images/direct/SUVgreK-TY6TWb7f9datWw.png');
            background-size: cover;
            background-position: top;
            color: #FFFFFF;
        }
        header {
            background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente */
            padding: 30px 0;
            text-align: center;
            margin-bottom: 20px; /* Margen inferior agregado */
        }
        .logo img {
            width: 200px; /* Tamaño del logo 1 */
            display: block;
            margin: 0 auto; /* Centrar horizontalmente */
        }
        nav {
            background-color: transparent; /* Color transparente */
            padding: 10px 0;
            text-align: center;
            padding-bottom: 10px; /* Aumento del padding inferior */
        }
        nav a {
            display: inline-block; /* Modificado para mostrar en línea */
            color: #FFFFFF; /* Cambiado a color blanco */
            text-decoration: none;
            margin: 10px; /* Se cambió margin-top y margin-bottom a margin */
            padding: 10px;
            border-radius: 5px;
            background-color: transparent; /* Color transparente */
            border: 2px solid #FFFFFF; /* Agregar borde blanco */
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #93C0EE;
        }
        section {
            padding: 30px;
            margin: 20px;
            background-color: rgba(255, 255, 255, 0.9); /* Fondo blanco semitransparente */
            border-radius: 10px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
        }
        section h2,
        section p {
            color: #000000; /* Cambiar color del texto a negro */
        }
        footer {
            background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente */
            color: #FFFFFF; /* Cambiado a color blanco */
            padding: 20px 0;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        /* Estilos para el menú */
        .Menu {
            padding-bottom: 22px;
            width: 100%;
            margin: 0 auto;
            text-align: center;
        }
        .Menu ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex; /* Cambiado a flex para hacer el menú horizontal */
            justify-content: center; /* Centrar los elementos */
        }
        /* Estilos para la galería de imágenes */
        .galery {
            display: flex;
            height: 20rem;
            gap: 1rem;
        }
        .galery > div {
            flex: 1;
            border-radius: 1rem;
            background-position: center;
            background-repeat: no-repeat;
            background-size: auto 100%;
            transition: all .8s cubic-bezier(.25, .04, .45, 1.4);
        }
        .galery > div:hover {
            flex: 5;
        }
        /* Estilos para el contenedor de video */
        .video-container {
            display: flex;
            justify-content: center; /* Centra el video horizontalmente */
            align-items: center;     /* Centra el video verticalmente (opcional) */
            padding: 20px 0;
        }
        .video-container iframe {
            border: none;
            width: 80%;   /* Ajusta el ancho del iframe a un porcentaje del contenedor */
            height: 450px; /* Ajusta la altura del iframe a un valor fijo */
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://colegiodivinosalvadorcali.edu.co/images/fixed/ESCUDO%20OFICIAl.png" alt="Logo 1">
        </div>
        <h1>Proyecto Matriz LED controlada con joystick</h1>
    </header>

    <nav>
        <div class="Menu">
           <ul>
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/PROYECTOS%20DE%20MATRIZ%20LED%20PAGINA%20PRINCIPAL.html">Página Principal</a></li>
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/PANTALLA%20DE%20LETRAS.html">Pantalla de Letras</a></li>
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/JUEGO%20DE%20JOYSTICK.html">Juego con Joystick</a></li>
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/JOYSTICK%20GAME.html">joystick game</a></li>
            </ul>    
        </div>
    </nav>

    <section id="introducción">
        <h2>INTRODUCCIÓN</h2>
        <p>En este trabajo se busca mejorar nuestras capacidades en la robótica y la programación para ello se busca hacer funcionar una matriz led 8x8 la cual trasnmita una secuencia de letras que envíen un mensaje el cual diga "TE AMO",para esto se hizo uso de ciertos materiales, de los cuales los principales son un arduíno, una matriz led 8x8 y cables macho/hembra, los cuales fueron conectados consecutivamente para el funcionamiento del circuito, los aprendizajes adquiridos en este proyecto fueron los conceptos manejados por la martriz led, las cuales fueron, (CLK) que viene de las palabras en inglés "clock" o reloj que tiene por objetivo sincronizar las acciones de un dispositivo con otro que tenga el mismo hardware. En este proyecto se tuyo el contratiempo de que se presentó un error el cual no permitía que el mensaje se exprese con normalidad, por lo que aparece una z que estaba destinada a aparecer, pero igualmente se levó a cabo la actividad.</p>
    </section>

    <section id="funcionamiento">
        <h2>FUNCIONAMIENTO</h2>
        <p>Primeramente, se realizaron las conecciones entre la matriz led y el arduino tanto para alimentarlo de energía electrica, como para transmitir la información del ordenador al arduíno y que así este le de las ordenes a la matruiz, luego se conectó el GND (polo a tierra) de la matriz al GND del arduino, esto se hace con el fin de evitar dañar alguna piesa adicional que se esté usando,ya que el papel del polo a tierra es es recibir la energía evitando que esta dañe otras partes del circuito,se conectó el DIN de la matriz al pin 12 del arduino para que este le pase la información de lo que tiene que hacer la matriz led, se conectó el CS de la matriz al pin 10 con un objetivo similar al anterior y finalmente el CLK de la matriz al pin 11 del arduino para que así se sincronicen los dos dispositivos.</p>
    </section>

    <section id="materiales">
        <h2>MATERIALES</h2>
        <p><br>Para este proyecto se utilizaron muy pocos materiales:</br><br>- 5 cables macho/hembra</br> <br>- Un arduino con su respectivo cable para conectarlo al ordenador</br><br>-la matriz led.</br></p>
    </section>

    <section id="paso a paso">
        <h2>PASO A PASO</h2>
        <p>Primeramente, se realizaron las conecciones entre la matriz led y el arduino, luego se conectó el GND (polo a tierra) de la matriz al GND del arduino,se conectó el DIN de la matriz al pin 12 del arduino, se conectó el CS de la matriz al pin 10 y finalmente el CLK de la matriz al pin 11 del arduino.</p>
        <p>Posteriormente se integró el código que le diera la orden a la matriz led de escribir un "TE AMO", de forma que cada letra aparezca de forma consecutiva a la anterior..</p>
    </section>

    <section id="que se aprendimos">
        <h2>QUE SE APRENDIO</h2>
        <p>Al culminar este proceso descubrimos un par de conceptos nuesvos al momento de usar la matriz 8x8, entre ellos se encuentra "VCC" que quiere decir (voltaje de corriente continua)el cual le brinda energía eléctrica sin ningún tipo de alteración, seguido a este se encuentra el "DIN" establece una conexió con la interfáz, la conexión "CS" que envía la información a la matriz y por último el "CLK" que sincriniza los dos dispositivos.</p>
    </section>

 <section id="Referencias">
        <h2>REFERENCIAS</h2>
        <p> 
<br>Carmenate, J. G. (2020, November 3). Matriz de LED 8x8 con Arduino y driver MAX7219. Programarfacil Arduino y Home Assistant. https://programarfacil.com/blog/arduino-blog/matriz-led-arduino-max7219/</br>

<br>Cómo funciona la toma de tierra GND: cómo conectarla correctamente. (2021, June 8). Descubrearduino.com. https://descubrearduino.com/gnd/</br>

<br>Profesor, L. E. D. (2021, December 14). Diferencia entre voltaje constante (VC) y corriente constante (CC). Ledbox News; Profesor LED. https://blog.ledbox.es/diferencia-entre-voltaje-constante-vc-y-corriente-constante-cc/</br>

<br>Secuenciales, S. (n.d.). Ingeniería de sistemas industriales Curso 2019-2020. Cartagena99.com. Retrieved August 5, 2024, from https://www.cartagena99.com/recursos/alumnos/apuntes/Apuntes%20secuenciales.pdf</br></p>
    </section>

    <section id="video de solución">
        <h2>VIDEO DE SOLUCIÓN</h2>
     
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video de TikTok</title>
</head>
<body>
    <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@santiagovibes17/video/7399336734716103941" data-video-id="7399336734716103941" style="max-width: 605px;min-width: 325px;" >
        <section> </section>
    </blockquote> 
    <script async src="https://www.tiktok.com/embed.js"></script>
</body>
<script async src="https://www.tiktok.com/embed.js"></script>

        </div>
    </section>

    <!-- Nueva sección de galería de imágenes -->
    <section class="galery">
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
    </section>

    <footer>
        <p>&copy; 2024 - Combita y Laiseca - Matriz LED - C.D.S</p>
    </footer>
</body>
</html>
