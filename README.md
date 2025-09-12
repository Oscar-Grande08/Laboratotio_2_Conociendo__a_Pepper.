<h1 align="center">Laboratorio 2</h1>
<h2>Coreografía de Pepper</h2>

<p><strong>Pepper</strong> es un robot humanoide capaz de interactuar con personas, mantener conversaciones, reconocer emociones, mostrar información relevante e incluso realizar bailes. 
Su funcionamiento se apoya en distintas librerías de programación (Python, C++, Java) integradas con el framework <strong>NAOqi</strong>.</p>

<h2>Librerías principales</h2>
<ul>
  <li><strong>qi</strong>: Middleware oficial de NAOqi. Conecta programas con los servicios internos de Pepper (voz, movimiento, sensores, memoria, tablet).</li>
  <li><strong>argparse</strong>: Manejo de argumentos en la terminal. Permite definir IP, puerto, modo de ejecución y servicios.</li>
  <li><strong>sys</strong>: Interacción con el intérprete de Python. Administra argumentos (<code>argv</code>), rutas, salidas y errores.</li>
  <li><strong>os</strong>: Comunicación con el sistema operativo Linux NAOqi. Manejo de archivos, directorios, variables de entorno y procesos.</li>
  <li><strong>almath</strong>: Librería matemática para robótica. Calcula cinemática, trayectorias 2D/3D, matrices de rotación/traslación y estabilidad.</li>
  <li><strong>math</strong>: Funciones matemáticas estándar (trigonometría, logaritmos, constantes). Se combina con <code>almath</code> para ángulos y movimientos.</li>
  <li><strong>motion</strong>: Control de articulaciones, posturas, locomoción, manipulación de manos y equilibrio.</li>
  <li><strong>httplib</strong>: Cliente HTTP/HTTPS (Python 2.7). Permite comunicación con APIs, servidores y sistemas IoT.</li>
  <li><strong>json</strong>: Manejo de datos JSON. Serialización y deserialización de configuraciones, logs e interacciones.</li>
</ul>

<h2>Conclusión</h2>
<p>El ecosistema de librerías de Pepper permite combinar interacción social (voz, gestos, tablet), movimiento avanzado y conectividad con servicios externos, 
facilitando el desarrollo de aplicaciones de interacción humano-robot flexibles y potentes.</p>

<p align="center">
  <a href="https://www.dailymotion.com/video/x9q3sjq">
    <img src="https://static.vecteezy.com/system/resources/previews/036/280/846/non_2x/modern-robot-with-video-play-icon-artificial-intelligence-multimedia-concept-illustration-for-technology-and-streaming-vector.jpg" width="250">
  </a>
</p>
