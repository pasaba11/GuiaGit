# Guía básica del uso de Git.
> [!TIP]
> Aquí encontrarás una pequeña guía para iniciarte en los repositorios de Git.

## ¿Qué es Git?
Git es un *software* de control de versiones diseñado por **Linus Torvalds**, pensando en la <ins>**eficiencia, la confiabilidad y compatibilidad**</ins> del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. Su propósito es llevar registro de los cambios en archivos de computadora incluyendo coordinar el trabajo que varias personas realizan sobre archivos compartidos en un repositorio de código.

> [!NOTE]
> Git [Ir a página oficial git](https://git-scm.com/about/branching-and-merging) 

Al principio, Git se pensó como un motor de bajo nivel sobre el cual otros pudieran escribir la interfaz de usuario o front end como Cogito o StGIT. Sin embargo, Git se ha convertido desde entonces en un sistema de control de versiones con funcionalidad plena. Hay algunos proyectos de mucha relevancia que ya usan Git, en particular, el grupo de programación del núcleo Linux.

El mantenimiento del software Git está actualmente (2009) supervisado por Junio Hamano, quien recibe contribuciones al código de alrededor de 280 programadores. En cuanto a derechos de autor Git es un software libre distribuible bajo los términos de la versión 2 de la Licencia Pública General de GNU.

## ¿Qué es Github? ![Imagen carpetas](Github.png)
GitHub es una forja (plataforma de desarrollo colaborativo) para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de ordenador. El software que opera GitHub fue escrito en Ruby on Rails. Desde enero de 2010, GitHub opera bajo el nombre de GitHub, Inc. Anteriormente era conocida como Logical Awesome LLC. El código de los proyectos alojados en GitHub se almacena generalmente de forma pública.

El 4 de junio de 2018 Microsoft compró GitHub por la cantidad de 7500 millones de dólares. Al inicio, el cambio de propietario generó preocupaciones y la salida de algunos proyectos de este sitio; sin embargo, no fueron representativos. GitHub continúa siendo la plataforma más importante de colaboración para proyectos de código abierto.

## ¿Qué necesitamos para usar ***Github*** en nuestros proyectos?
1. Alta Github: registrarse con una cuenta personal gratuita y comprobar la dirección de correo electrónico.
  > [!WARNING]
  > Registrarse [Ir a página oficial git](https://github.com/.)
2. Git Bash (terminal): es una aplicación para entornos de Microsoft Windows que ofrece una capa de emulación para una experiencia de líneas de comandos de Git. > Bash es el acrónimo en inglés de Bourne Again Shell. Una *shell* es una aplicación de terminal que se utiliza como interfaz con un sistema operativo mediante comandos escritos. Bash es una shell predeterminada popular en <ins>**Linux y macOS.**</ins> Git Bash es un paquete que instala Bash, algunas utilidades comunes de bash y Git en un sistema operativo Windows.
3. Carpeta en disco local: C:\Users\Grupo1\repo6

### <ins>**Comandos habituales para trabajar con repositorios remotos:**</ins>
- [ ] git init: Esto crea un subdirectorio nuevo llamado .git, el cual contiene todos los archivos necesarios del repositorio – un esqueleto de un repositorio de Git. Todavía no hay nada en tu proyecto que esté bajo seguimiento.
- [ ] git status: Muestra el estado actual de la rama, como los cambios que hay sin commitear.
- [ ] git remote: Actualiza tu repositorio remoto en caso de que algún otro desarrollador haya eliminado alguna rama remota. 
- [ ] git add .: Comienza a trackear los archivos.
- [ ] git commit -m "mensaje": Confirma los cambios realizados. El “mensaje” generalmente se usa para asociar al commit una breve descripción de los cambios realizados.
- [ ] git push: Commitea los cambios desde el branch local origin al branch “nombre_rama”.

#### Clonar un repositorio.

#### Hacer Fork de un repositorio existente.
    **1.** Se busca el usuario del que se quiere copiar un proyecto a nuestro Git Hub.
    
