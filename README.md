<h1 align="center">💿 Born2beroot / Debian 💿</h1>

<h2 align="center">1. ¿Cómo funciona una máquina virtual? ¿Y cuál es su propósito? 💻</h2>

<p align="center">Es un software que simula un sistema operativo, permitiendole ejecutar programas en un mismo equipo fisico, lo cual es posible gracias a que se le comparten recursos de la maquina fisica, esto se conoce como host o sistema anfitrión.</p>

<p align="center">Su proposito es ampliar la capacidad de procesamiento y almacenamiento de un sistema, permitiendo ejecutar distintos sistemas operativos en un mismo equipo. Facilitan las pruebas de nuevas versiones de un sistema operativo y aplicaciones sin afectar al sistema principal, tambien ejecutan software antiguo los cuales ya no son compatibles con el hardware o software moderno.</p>

<h3 align="center">Existen dos tipos de maquinas virtuales</h3>

<p align="center"><b><i>.De sistemas:</i></b> Simulan un ordenador completo, permitiendo ejecutar otro sistema operativo en su interior, con sus propios conjuntos de componentes de hardware virtualizados.</p>
<p align="center"><b><i>.De proceso:</i></b> Son más ligeros y se centran en emular un entorno especifico para ejecutar un programa o una aplicacion.</p>

<h2 align="center">2. ¿Qué es una ISO? 💾</h2>

<p align="center">Es un archivo que contiene una copia exacta de un programa o un sistema operativo, estos pueden pueden tomar gran cantidad de datos.</p>

<h2 align="center">3. ¿Por qué eligió Debian? 📌</h2>

<p align="center">Debian es una distribución sencilla de configurar, lo cual es perfecto para desarrolladores novatos.  Este permite admision de bibliotecas, sistemas de archivos y arquitectura, por mencionar algunas caracteristicas... cuenta con más opciones de personalización.</p>

<p align="center">CentOS por otro lado es una distribución más compleja de personalizar, es muy usuda y recomendada en entornos empresariales por la seguridad que ofrece. Como dato no irrelevante CentOS nace en el 2.004, mientras que Debian en 1.993 como una de las primeras distribuciones de linux.</p>

<h2 align="center">4. ¿Cuál es la diferencia entre Debian y CentOS? 🔎</h2>

<p align="center">CentOS es una distribución que ofrece soporte comercial y una estabilidad probada para aplicaciones empresariales, lo que lo vuelve una opcion recomendable en este aspecto. Debian ofrece una amplia variedad de paquetes, un soporte directo por ZFS y una comunidad activa. Elegir entre uno u otro depende de las necesidades.</p>

<h2 align="center">5. ¿Cuál es la diferencia entre aptitude, apt y qué es APPArmor? 📎</h2>

<p align="center"><b><i>.Aptitude:</i></b> es un administrador de paquetes de alto nivel que ofrece una interfaz grafica y una interfaz de linea de comandos interactiva. Es capaz de manejar situaciones complejas de dependencias y conflictos de paquetes, proporcionando sugerencias de resolución y mostrando registros detallados de cambios. Es muy util para usuarios novatos por su facil uso y capacidad de resolver automaticamente problemas de dependencias.</p>

<p align="center"><b><i>.Apt:</i></b> es un administrador de paquetes de bajo nivel que opera exclusivamente en el terminal, requiere conocimientos solidos en linux ya que el usuario debe especificar manualmente muchas opciones. Sus siglas son: <i>Advanced packaging tool</i></p>

<p align="center"><b><i>.APPArmor:</i></b> es un sistema de seguridad con control de acceso obligatorio, diseñado para restringir las capacidades de las aplicaciones y proteger el sistema contra vulnerabilidad de seguridad. Funciona mediante la definición de perfiles de seguridad para cada aplicación, especificando a que recursos del sistema puede acceder y que operaciones puede realizar. Si una aplicación intenta realizar una acción que está restringida, APPArmor lo bloqueará brindando seguridad para evitar daños al sistema.</p>

<h2 align="center">6. ¿Cuáles son las ventajas y desventajas de una política de contraseñas segura? ¿Qué puede decir sobre su implementación? 🔐</h2>

<p align="center"><b><i>.Ventajas:</i></b> eliminar la tentación de usar una multi-contraseña disminuyendo el riesgo de perdida si una cuenta es afectada. Ofrecer comodidad al usuario, permitiendole frecuentemente cambiar de contraseñas sin perderse en el proceso, esto atribuye altos niveles de seguridad sin sacrificar la facilidad de uso. Utilizar frases de contraseñas en lugar de contraseñas tradicionales reduce el riesgo de violación de cuentas.</p>

<p align="center"><b><i>.Desventajas:</i></b> el gestor de contraseñas representa un unico fallo y es que si alguien obtiene la contraseña maestra, podria potencialmente acceder a todas las contraseñas almacenadas.</p>

<p align="center"><b><i>.Implementación:</i></b> revisar regularmente las politicas de seguridad para adaptarse a nuevas amenazas y tecnologias emergentes. Fomentar el uso de gestiones de contraseñas para mejorar la seguridad y gestión de seguridad sin sacrificar comodidad. Educar y concientizar la implementación de contraseñas seguras, llevandolos incluso de como generarlas de manera efectiva.</p>

<h2 align="center">7. ¿Qué es una partición? Y más en general, ¿cómo funciona LVM (Logical Volume Management)? 📐</h2>

<p align="center">Una partición es una división de disco duro o dispositivo de almacenamiento en varios segmentos separados, cada una de estas puede ser utilizada para almacenar datos de manera independiente. Cada partición tiene su propia tabla de archivos lo que significa que pude tener un sistema de archivos diferente al resto del disco. Son utiles para organizar el almacenamiento.</p>

<p align="center"><b><i>.LVM:</i></b> es un metodo alternativo para administrar el almacenamiento a sistemas linux, ofreciendo mayor flexibilidad y escalabilidad en comparación con el enfoque tradicional basado en particiones. En lugar de dividir fisicamente el disco en particiones, LVM divide el espacio de almacenamiento en bloques llamados "volumenes fisicos" de los cuales se pueden crear volumenes logicos. Los volumenes logicos son especies de almacenamientos que procesan discos duros completos para el sistema y aplicaciones, pero en realidad son creados a partir de los bloques de almacenamiento en los grupos de volumenes.</p>

<h2 align="center">8. ¿Qué es sudo? 👥</h2>

<p align="center">Es una herramienta que le permite a los usuarios poder ejecutar comandos con privilegios, sin la ncesidad de intercambiar al usuario root directamente. Esto siempre y cuando el usuario tenga los permisos necesarios. Esta herramienta es muy potente porque nos da una capa de seguridad a la hora de ejecutar comandos, ya que al entrar como usuario root, hay un riesgo de seguridad. Entonces con el hecho de que el usuario esté registrado con el grupo sudo y con sus espectivos permisos, reduce significativamente el compromiso de seguridad.</p>

<h2 align="center">9. ¿Qué es un UFW y para qué sirve? 🔥</h2>

<p align="center">Es una herramienta diseña para simplificar la gestión de firewalls, esto permite controlar el trafico de red entrante y saliente de memoria facilmente. Podemos configurarlo para impedir ciertos puertos y asi tener una seguridad en nuestro sistema.</p>

<h2 align="center">10. ¿Qué es SSH (Secure Shell) y para qué sirve? 🔑</h2>

<p align="center">Es un protocolo de red el cual permite a los administradores de sistemas acceder de manera segura a una computadora de red no segura. Este proporciona autenticación fuerte a traves de llaves publicas y privadas, asi como comunicación de datos entre dos computadoras, que se conectan a una red abierta, como internet.</p>

<h2 align="center">11. ¿Qué es crontab? ⏰</h2>

<p align="center">Es una herramienta que permite programar trabajos para que se ejecuten automaticamente en momentos especificos. Estos trabajos pueden ser scripts simples o más complejos. Su finalidad es automatizar tareas repetitivas. Un ejemlo podria ser; copias de seguridad. Como dato irrelevante, un usuario root puede modificar estas tareas que afecten a todos los usuarios.</p>
