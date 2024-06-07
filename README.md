# Integradora-pr-ctica-02
En esta práctica aprenderemos a utilizar las herramientas Git y GitHub para el control de Versiones, Documentación, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la asgnatura de Integradora 1
##
Comandos Básicos para la Documentación, utilizando el estándar de Markdown (ad)
Mariban es el estándar utilizado por Git y Github, para maquetar la docurentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.

### 1. Encabezados o Titulos (HEADERS)
Para poder realizar una buena documentación del proyecto deberos, distribuir correctamente los contenido, para poder delimitar o hacer énfasis (enfatizar), es decir resaltar las secciones importantes, podemos utilizar los siguiente:
# Encabezado de Nivel 1 • Similar a H1 en HTML
## Encabezado de Nivel 1 • Similar a H1 en HTMl
### Encabezado de Nivel 1 • Similar a Mi en HTML
#### Encabezado de Nivel 1 • Similar a H1 en HTML
###### Encabezado de Nivel 1 • Similar a M1 en HTMl
###### Encabezado de Nivel 1 • Similar a M1 en HTML
###### Encabezado de Nivel 1 • Similar a H1 en HTML
###### Encabezado de nivel 7 - Solo 6 son los niveles permitidos, a partir de este el maquetado sera
ignorado, s

### 2. Separadores (SEPARATORS)
Si desea carcar una separación eás visual de contenidos pordemos utilizarlos indicando tres caractres "-" en el maquetado

EJEMPLO:
'Esto es similar a un tag de < HR >en HTML.

### 3. Párrafos (PARAGRAHS)
Son utilizados para por presentar grandes secciones de texto que describen detalladamente las secciones de la documentación del proyecto.
EJEMPLO: Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este
texto pertenece al párrafo 1.
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo Este texto pertenece al párrafo
2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al parrafo
2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo
LEste texto pertenece al parrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo Este texto pertenece al párrafo 2Este texto pertenece al parrafo
2Este texto pertenece al párrafo 2

Lo que en una página utilizaríamos usando la etiqueta ‹ P ›.
Tarbién podenos aplicar estilos básicos de alineación :

Este párrafo está alineado a la izquierda por defecto Este parrafo esta alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto Este párrafo esta alineado a la izquierda por defecto
<p align ="right">
Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo esta al resto a la derecha utilizando la propiedad de alineación Este párrafo está alíneado a la derecha
Etilizando la propledad de alineación Este parrafo esta alineado a la derecha utilizando la propiedad de alinación este párrafo esta alinado a la derecha utilizando la propiedad de alineación </p>

<p align="center">
Este párrafo esta centrado urando la propledad de alineación Este párrafo esta centrado usando la
propledad de alleeacdon Este pirrafo esta centrado usando la propledad de alineacien Este parrafo
esta centrado usando la propiedas de alineación Este párrafo esta centrado usando la propiedad de alfreación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedas de alineación Este párrafo esta centrado usando la propiedad de alineación Este
párrafo esta centrado usando la propledas de alineación Este párrafo esta centrado usando la
propiedad de alineación</p>


<p align= "justify">
Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado vtllizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alíneacón Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará
Justificado utilizando la propledad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este
párrafo estará justificado utilizando la propiedad de alineación</p>

#### 4, Testo Enfatizado (BOLD, ITALIC, BOLD/ITALIC)
Si el texto que deseaños enfatizar se encuentra de un parrafo, podenos utilizar algunos trucos para ubicarlos en la documentacion
### Texto en Negrita (BOLD)
Para poder porer el texto en negrita, este deberá ser encerrado entre ** **


texto Texto Texto Texto Texto Texto ** Texto ** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Terto Texto Texto Terto Texto Texto Texto Texto Texto Texto Texto Texto.

### ITALIC


Para poner en cursiva 



**EJEMPLO**


texto texto *texto* texto texto 

#### Subrayado (UNDERLINE)
algunas veces necesitaremos subrayar texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que use el estándar de HTML usando el tag /<ins> y cerrando con /</ins>.

**EJEMPLO**

TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO 
TEXTO TEXTO TEXTO TEXTO "TEXTO Cursivo" TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO 
TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO 
TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO <ins> TEXTO Subrayado < ins> TEXTO 

#Integradora practica 03


Continuamos con los comandos básicos de Git y GitHub para el maquetado de la documentación 

###5. Cuadros de código o reseñas (BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones especificas para la instalación, configuración y/o inicializar mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (>). 

**EJEMPLO**
Para listar las carpetas y archivos es desde una terminal de sistema operativo Windows debemos ingresar el comando:

C:/dir

Después oprimimos la tecla "enter"

También podemos ingresas textos multilínea 

**EJEMPLO**

>Aquí se ingresa un conjunto de instrucciones 
>para explicar al usuario, como instalar el
>que hemos diseñado.

Y si deseamos incluir viñetas para enlistar los pasos  podemos utilizar el carácter dentro del texto a documentar

 **EJEMPLO**

**PASOS PARA INSTALAR LA BASE DE DATOS**
>- Decargar MySQL Server del Sitio Oficial 
>- instalar el Sistema Gestor de Base de Datos definiendo el puesto y la contraseña para el usuario ***root***
>-Descargamos el archivo de respaldo de la base de datos (.sql)
>-restauramos la Base de Datos usando el comando *mysql*
C:/ProgramFiles/MySQL/MYSQLServer8.0/bin/mysql-u root -p
password < respaldo sql

**6. Listas ordenadas y Desordenadas 

síes en nuestra documentación necesitamos incluir información de texto en modo de lista, un elemento tras otro podemos hacerlo utilizando los números con un punto decimal si las deseamos ordenadas o un guion en medio - si solo queremos una viñeta 


**EJEMPLO**
  Para poder crear tu primero repositorio en GitHub deveras;
1. Contar con una cuenta GitHub 
2.Dar clic en el botón **Nuevo Repositorio*
3.Asignarle un nombre a tu repositorio, por ejemplo: 'ptactica03-3b'
4.Asignarle un nivel de privacidad entre 

-**PUBLICO** Si quieres que este disponible para todos los usuarios.
-**PRIVADO** Si deseas que solo a quien decidas puedan colaborar con tu proyecto.

10.Definir si incluye un archivo de descripción llamado: *README.md*
11.Definir si habrá exclusiones de archivo a través del archivo a través del archivo : *gitignore*
7. Guardar los cambios 


####7. Ligas (Hipervínculos)
las ligas utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizando lo corchetes \[ \], inmediatamente después pondremos la liga de referencia entre paréntesis /()

**EJEMPLO**

Mi buscador favorito es: [www.google.com]/(https://www.google.com)

Pero si deseasa poner solo las ligas directas a un correo electrónico podemos utilizar los símbolos \<\>

**EJEMPLO**

Documentación creada por: ***Abril Guzman Barrera*** (<aguzm347@gmail.om>)

(<http://www.utxicotepec.edu.mx>)

