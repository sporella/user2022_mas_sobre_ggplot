# Preparación para el tutorial

A continuación encontrarás las indicaciones necesarias para preparar tanto tu computador como tu espacio de trabajo.

## Preparar tu computador

En este taller utilizaremos R a través de RStudio. En el caso de R, es importante que tengas instalada la versión 4.0 o superior. Para chequear qué versión tienes, puedes ejecutar el siguiente comando:

```
R.Version()$version.string
```

También puedes trabajar en RStudio Cloud, si así lo prefieres, que por defecto traer la versión 4.2 de R. 

## Paquetes necesarios

A continuación encontrarás los paquetes que es necesario instalar para poder ejecutar sin problemas el código que escribiremos durante la sesión. 

**Disponibles en CRAN**
* tidyverse (esto instalará ggplot2 y algunos otros paquetes que utilizaremos para el procesamiento de los datos que se utilizarán como ejemplo)
* gghighlight
* ggtext
* ggthemes
* showtext
* ggimage

El código para instalarlos todos: `install.packages(c("tidyverse", "gghighlight", "ggtext", "ggthemes", "showtext", "ggimage"))`

**Disponibles en GitHub**
* `remotes::install_github("wilkelab/gridtext")` (es importante instalar la versión de desarrollo, ya que contiene una actualización imṕortante que no está en la versión de CRAN aún)

Al inicio del tutorial se compartirá un enlace a un proyecto de RStudio Cloud que tiene todo instalado, en caso de que prefieras utilizar esta plataforma o que no te resulte instalar algún paquete. 

Adicionalmente, hablaremos acerca de algunos paquetes que permiten extender las funcionalidades de {ggplot2}, pero no los utilizaremos en los ejercicios del taller. La lista quedará en la presentación que se mostrará durante el tutorial. 

## Preparar tu espacio de trabajo

Este es un tutorial práctico. A lo largo de las 3.5 horas que dura, escribiremos código en vivo, es decir, no traeremos un script pre-hecho que solo tendrás que ejecutar, sino que iremos escribiendo el código en el momento y discutiendo qué es lo que hace cada línea de código. Esto permite que repliques en tu computador todo lo vayamos mostrando. Para ello, es necesario que pienses en alguna configuración de pantalla que te permita ir mirando lo que hacemos en Zoom y replicándolo en tu sesión de RStudio.  

A continuación hay algunas opciones:

### Una mitad de la pantalla para cada cosa

Es la opción más simple y no requieres nada más que tu computador.

<p align="center">
<img src="imagenes/pantalla-dividida.JPG" width="500"/>
</p>

### Una segunda pantalla

Esta es la opción más cómoda, pero no siempre es posible porque requieres más cosas que solo tu computador. Aquí van algunas ideas, en caso de que no tengas un segundo monitor.


#### Conectar tu computador a un televisor

Luego de conectarlo, configura tu computador para que las pantallas no se dupliquen, sino que veas dos cosas distintas en cada una. Así podrás trabajar en tu computador e ir mirando el taller en el televisor:

<p align="center">
<img src="imagenes/compu-tele.JPG" width="400"/>
</p>

#### Usar otro dispositivo

Si tienes una tablet, puedes conectarte a Zoom desde ella para participar en el taller y en paralelo trabajar en tu computador. También puedes hacerlo con un teléfono móvil si es que te acomoda ese tamaño.

<p align="center">
<img src="imagenes/compu-telefono.jpeg" width="400"/>
</p>
