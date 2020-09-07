
# Avatar-Jenkins-Asset

  

Para poder obtener el nuevo diseño de jenkins se debe reemplazar archivos y carpetas de jenkins.

Dentro de la carpeta assets del repositorio estan las carpetas y archivos con los mismos nombres para reemplazarlo en sus ambientes.

  

------------

#### CAMBIAR FUENTES Y ASSETS DE JENKINS

>  1. Ubicarse en la siguiente direccion de jenkins y reemplazar la carpeta **images** con la que se encuentra en el repositorio
**/var/cache/jenkins/war/** 
> 2. Ubicarse en la siguiente direccion de jenkins y pegar la carpeta de la fuente OpenSans
> **/var/cache/jenkins/war/css/google-fonts**
>  3. Ubicarse en la siguiente direccion y reemplazar la carpeta **images** con la que se encuentra en el repositorio (ojo! que son direcciones distintas e imagenes distintas)
**/var/lib/jenkins/plugins/cloudbees-folder/**

  
  

------------

  
  

#### NUEVO DISEÑO DE FORMULARIO

  

> Reemplazar los archivos CSS para cambiar el diseño del formulario de login:
> 1. Ubicarse en la siguiente direccion de jenkins:
***/var/cache/jenkins/war/css***
> 2. Reemplazar los archivos mencionados por los que se ubican en el repositorio:
>  ***simple-page.css***
>  ***simple-page-forms.css***
>  ***simple-page.theme.css***

  
  

>  ***NOTA: Una vez hecho ese cambio debera reiniciar jenkins y ver el cambio de estilos en el formulario***

  

------------

#### NUEVO DISEÑO DE JENKINS

> Reemplazar los archivos CSS para cambiar el diseño total de jenkins:
> 1. Ubicarse en la siguiente direccion de jenkins:
**/var/cache/jenkins/war/jsbundles**
>  2. Reemplazar el archivo css llamado:
**base-styles-v2.css**

>  ***NOTA: Una vez hecho ese cambio debera reiniciar jenkins y ver el cambio de estilos total de jenkins***
