# <center>***INTRODUCCION AL GIT***<center>

 ## **Índice**

 ### 1. Definición
 ### 2. Características
 ### 3. Estructura
 ### 4. Comandos de Git básicos
 ### 5 ¿Qué es GitHub?
 ### 6. ¿Para qué sirve?
 ### 7. Características de GitHub
 ### 8.Uso básico para trabajar con Git y GitHub

<hr> 
<br>

 ### **Definición**

<div style="text-align:justify">
Git es un sistema de control de versiones distribuido, diseñado por Linus Torvalds. Está pensado en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.

<br>

 ### **Características**

<br>

 - Git está optimizado para guardar cambios de forma incremental.
<br>

- Permite contar con un historial, regresar a una versión anterior y agregar funcionalidades.
<br>

- Lleva un registro de los cambios que otras personas realicen en los archivos.
<br>

- Es muy rápida. 
<br>

- Tiene un sistema de trabajo con ramas que lo hace especialmente potente.

<br>

 ### **Estructura**

 **Un proyecto GIT consta de tres secciones principales:** el directorio de trabajo, el área de preparación y el directorio git.
 El directorio de trabajo es donde se agregan, borran y editan los archivos. Luego, los cambios son preparados (indexados) en el área de preparación. Después de que confirmes tus cambios, la instantánea de los cambios se guardará en el directorio git.
 

<br>

 #### **Un directorio .git tiene una estructura similar a la siguiente:**
 <br>

**Carpeta objects/:** En este directorio, se almacenan los datos de los objetos Git – todo el contenido de los archivos que hayas insertado, tus commits, árboles (trees) y etiquetas de objeto.

**Carpeta refs:** En los subdirectorios de este directorio se almacenan referencias. El comando git prune sabe preservar los objetos accesibles desde las referencias que se encuentran en este directorio y sus subdirectorios.

**Carpeta objects/pack:** En este directorio se encuentran archivos que almacenan muchos objetos en forma comprimida, junto con archivos index para permitir el acceso aleatorio a ellos.

<br>

 ### **Comandos de Git básicos:**
 
 <br>

***git init*** creará un nuevo repositorio local GIT. El siguiente comando de Git creará un repositorio en el directorio actual: git init. 

***git clone*** se usa para copiar un repositorio. Si el repositorio está en un servidor remoto, usa: git clone nombredeusuario@host:/path/to/repository.

***git add*** se usa para agregar archivos al área de preparación. Por ejemplo, el siguiente comando de Git básico indexará el archivo temp.txt: git add <temp.txt>.

***git commit*** creará una instantánea de los cambios y la guardará en el directorio git: git commit –m “El mensaje que acompaña al commit va aquí”.

***git config*** puede ser usado para establecer una configuración específica de usuario, como el email, nombre de usuario y tipo de formato, etc. Por ejemplo, el siguiente comando se usa para establecer un email: git config --global user.email tuemail @ejemplo.com

***git status*** muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.

***git remote*** te permite ver todos los repositorios remotos. El siguiente comando listará todas las conexiones junto con sus URLs:
git remote -v.

<br>

### **¿Qué es GitHub?**

Github es una plataforma de desarrollo colaborativo para alojar proyectos utilizando el sistema de control de versiones Git. Se emplea principalmente para la creación de código fuente de programas de computadora.

Puede considerarse a Github como la red social de código para los programadores y en muchos casos es visto como un curriculum vitae, pues aquí se guarda el portafolio de proyectos de programación.

<br>

### **¿Para qué sirve?**

Github permite que los desarrolladores alojen proyectos creando repositorios de forma gratuita. 

En Github también puedes entrar a los proyectos de los demás y colaborar para mejorarlos. Esto quiere decir que los usuarios pueden opinar, dejar sus comentarios sobre el código, colaborar y contribuir mejorando el código. También pueden reportar errores para que los desarrolladores lo mejoren.

<br>

### **Características de GitHub**

<br>

- GitHub permite alojar proyectos en repositorios de forma gratuita y pública, pero tiene una forma de pago para privados.

- Puedes compartir fácilmente tus proyectos.

- Permite colaborar para mejorar los proyectos de otros y a otros mejorar o aportar a los tuyos.

- Ayuda a reducir significativamente los errores humanos, a tener un mejor mantenimiento de distintos entornos y a detectar fallos de una forma más rápida y eficiente.

- Es la opción perfecta para poder trabajar en equipo en un mismo proyecto.

- Ofrece todas las ventajas del sistema de control de versiones Git, pero también tiene otras herramientas que ayudan a tener un mejor control de proyectos.

<br>

### **Uso básico para trabajar con Git y GitHub**

<br>

Lo primero que debemos hacer es realizar la instalación de Git en nuestro equipo; dependiendo del tipo de sistema operativo que utilicemos, descargaremos una versión u otra. 

Una vez instalado, será necesario realizar una configuración básica en la que indicaremos nuestro nombre y correo electrónico. Para ello ejecutamos la aplicación Git, con lo que abriremos el terminal desde donde ejecutaremos todas las instrucciones necesarias:

#### 1. Lo primero será indicar nuestro nombre y para ello ejecutaremos la siguiente instrucción en el terminal: git config –global user.name “xxxxxxxx”

<br>

 #### 2. Lo siguiente será configurar nuestro correo electrónico, y la instrucción para esto será: git config –global user.email loquesea @tudominio.com

<br>

 #### 3. Si queremos ver la configuración, bastará con ejecutar lo siguiente: git config –list

</div>