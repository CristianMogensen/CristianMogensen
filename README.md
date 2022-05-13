# Trabajo Práctico - Markdown

Ingeniería en Computación
UNRN

Cristian Gustavo Mogensen (@CristianMogensen)

Comisión 1


## Historia de Git

Git es un software de control de versiones diseñado por Linus Torvalds, desarrollador de Linux.

[2] _El kernel de Linux es un proyecto de software de código abierto con un alcance bastante amplio. Durante la mayor parte del mantenimiento del kernel de Linux (1991-2002), los cambios en el software se realizaban a través de parches y archivos. En el 2002, el proyecto del kernel de Linux empezó a usar un DVCS propietario llamado BitKeeper._

_En el 2005, la relación entre la comunidad que desarrollaba el kernel de Linux y la compañía que desarrollaba BitKeeper se vino abajo y la herramienta dejó de ser ofrecida de manera gratuita. Esto impulsó a la comunidad de desarrollo de Linux (y en particular a Linus Torvalds, el creador de Linux) a desarrollar su propia herramienta basada en algunas de las lecciones que aprendieron mientras usaban BitKeeper. Algunos de los objetivos del nuevo sistema fueron los siguientes:_

* _Velocidad_
* _Diseño sencillo_
* _Gran soporte para desarrollo no lineal (miles de ramas paralelas)_
* _Completamente distribuido_

_Capaz de manejar grandes proyectos (como el kernel de Linux) eficientemente (velocidad y tamaño de los datos)_

_Desde su nacimiento en el 2005, Git ha evolucionado y madurado para ser fácil de usar y conservar sus características iniciales. Es tremendamente rápido, muy eficiente con grandes proyectos y tiene un increíble sistema de ramificación (branching) para desarrollo no lineal._

## Sistemas de control de versiones

Además de Git existen distintas alternativas de software para el control de versiones. Dos de ellas son _Perforce_ y _Subversion_.

[4] Perforce Software fue fundado en 1995 en Alameda, California, por Christopher Seiwald, un desarrollador de software y graduado en ciencias de la computación de UC  Berkeley. Su primer producto fue llamado Perforce, y era un sistema de control de versiones que permitía la colaboración entre empresas para el desarrollo de proyectos grandes de software al hacer un seguimiento de los cambios del código y los archivos binarios.

[5] _Apache Subversion (abreviado frecuentemente como SVN, por el comando svn) es una herramienta de control de versiones open source basada en un repositorio cuyo funcionamiento se asemeja enormemente al de un sistema de ficheros. Es software libre bajo una licencia de tipo Apache/BSD. Utiliza el concepto de revisión para guardar los cambios producidos en el repositorio. Entre dos revisiones solo guarda el conjunto de modificaciones (delta), optimizando así al máximo el uso de espacio en disco. SVN permite al usuario crear, copiar y borrar carpetas con la misma flexibilidad con la que lo haría si estuviese en su disco duro local._

## Herramientas ```grep``` y ```sed```

Para conocer el uso de los comandos ```grep``` y ```sed``` se ejecutó el comando help (y se accedió a sus respectivas páginas web de ayuda):
```sh
grep --help
sed --help
```
[7] ```sed``` (stream editor) es un editor de texto de líneas de comando no interactivo. Es mayormente utilizado para filtrar un texto, por lo tanto, recibe un texto de input, realiza alguna operacion (u operaciones) en el mismo, y devuelve un texto modificado en el output. ```sed``` es típicamente usado para extraer partes de un archivo, usando un patrón que coincida o sustituyendo múltiples ocurrencias de un string dentro de un archivo.

[8] ```grep``` busca en el input, uno o más archivos que contengan una coincidencia a un patrón especificado. Por defecto, ```grep``` devuelve en el output las líneas coincidentes.

### Referencias

* [1] _Git_. Wikipedia. (https://es.wikipedia.org/wiki/Git)
* [2] _Una breve historia de Git_. Git. (https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Una-breve-historia-de-Git)
* [3] _Fundamentos de Git_. Git. (https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Fundamentos-de-Git)
* [4] _Perforce_. Wikipedia. (https://en.wikipedia.org/wiki/Perforce)
* [5] _Subversion (software)_. Wikipedia. (https://es.wikipedia.org/wiki/Subversion_(software))
* [6] _GNU sed_. GNU. Free Software Foundation. (https://www.gnu.org/software/sed/)
* [7] _Grep_. GNU. Free Software Foundation. (https://www.gnu.org/software/sed/)
![Badge](https://bit.ly/icom-badge)
