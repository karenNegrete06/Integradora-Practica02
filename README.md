# Integradora-Practica02-3B

En esta práctica aprenderemos a utilizar las herramientas Git y Github para el control de versiones, documentación, desarrollo colaborativo y respaldo del proyecto integrador para la asignatura de integradora 1

## comandos básicos para la documentación,  utilizando el estándar de markdown (nd)
Markdown es el estándar utilizando por GIT y GitHub, para maquetar la documentación de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operación del mismo.

### 1. Encabezado o Titulos (HEADERS)
para poder realizar una buena documentación del proyecto debemos como distribuir correctamente los contenido, para poder delimitar o hacer énfasis (enfatizar),es decir resaltar las sesiones importantes, podemos utilizar los siguiente:

# Encabezado de Nivel 1 - similar a H1 en HTML
## Encabezado de Nivel 2 - similar a H2 en HTML
### Encabezado de Nivel 3 -similar a H3 en HTML
#### Encabezado de Nivel 4 -similar a H4 en HTML
##### Encabezado de Nivel 5 -similar a H5 en HTML
###### Encabezado de Nivel 6 -similar a H6 en HTML
####### Encabezado de Nivel 7 -Solo 6 son los niveles permitidos, a partir de este el maquetado será ignorado.

### 2. Separadores (SEPARATORS)
sí desea marcar una separación más visual de contenido podemos utilizarlos indicando tres caracteres de "-" continuos, en el maquetado 

EJEMPLO:
---

*Esto es similar a un tang de < HR > en HTML.

### 3. Párrafos (PARAGRPANS)
Son utilizados para por presentar grandes sesiones de texto que describen detalladamente las sesiones de la documentación del proyecto. 

EJEMPLO:

Este texto permanece al párrafo 1  Este texto permanece al párrafo 1 Este texto permanece al párrafo 1 Este texto permanece al párrafo 1 Este texto permanece al párrafo 1 Este texto permanece al párrafo 1  Este texto permanece al párrafo 1  Este texto permanece al párrafo 1.

Este texto permanece al párrafo 2  Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2 Este texto permanece al párrafo 2.

Lo que es una página utilizaríamos etiqueta < P >

También podemos aplicar estilos básicos de alineación:

Este párrafo está alineado a la izquierda utilizando la propiedad de alineación Este párrafo está alineado a la izquierda utilizando la propiedad de alineación Este párrafo está alineado a la izquierda utilizando la propiedad de alineación Este párrafo está alineado a la izquierda utilizando la propiedad de alineación Este párrafo está alineado a la izquierda utilizando la propiedad de alineación Este párrafo está alineado a la izquierda utilizando la propiedad de alineación 

<p align="right">
Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación
<\p>

<p align="center">
Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación Este párrafo está centrado usando la propiedad de alineación 
<\p>

<p align="justify">
Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineaciónEste párrafo estará justificado utilizando la propiedad de alineaciónEste párrafo estará justificado utilizando la propiedad de alineaciónEste párrafo estará justificado utilizando la propiedad de alineaciónEste párrafo estará justificado utilizando la propiedad de alineación
</p>

### 4. Texto Enfatizado (BOLD,ITALIC,BOLD/INTALIC)
Si el texto qué deseamos enfatizar se encuentra en un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación

##### Texto en Negrita (BOLD)
Para poder poner el texto en negrita, este deberá ser encerrado entre dobles ** 

EJEMPLO:
Texto Texto Texto Texto **Texto Importante** Texto Texto Texto Texto Texto Texto 

##### Texto en cursiva (ITALIC)
Para poder poner el texto en cursiva, este deberá ser encerrado con la i

EJEMPLO:
Texto Texto Texto Texto <i>Texto Importante</i> Texto Texto Texto Texto Texto Texto

##### Texto en cursiva y negrita(BOLD/ITALIC)
Para poder poner el texto en cursiva y negrita, este deberá ser encerrado con **

Texto Texto Texto Texto Texto Texto ***Texto importante*** Texto Texto Texto Texto


# Integradora-Practica03
Continuaremos con los comandos básicos de Git y Github para el enmaquetado de la documentación

### 5. Cuadros para código o Reseñas (BLOCKQUOTES)

Estos elementos son utilizados para resaltar intrucciones especificas para la instalación, configuracion y/o inicializacion o mostrar secciones de código fuente. Se maqueta iniciando el texto con un Símbolo de mayor que (>)

**EJEMPLO**

Para instalar las carpetas y archivos en desde una terminal de sistemas operativos Windows debemos ingresar el comando:

C:/dir

Despues oprimimos la tecla "Enter".

rambien podemos ingresar textos multilineas

**EJEMPLO**

>Aqui se ingresa un conjunto de instrucciones
>Para explicar al usuario, como instalar el
>Software que hemos diseñado.

Y si debemos incluir viñetas para enlistar pasos podemos utilizar el caracter - dentro del texto a documentar.

**EJEMPLO: Pasos para instalar la Base de Datos:**

> - Descargar MYSQL Serverdel Sitio Oficial
> - Instalar el Sistema Gestor de Bases de Datos, definiendo el puerto y contraseña para el usuario ***root***
> - Descargamos el archivo de respaldo de la base de datos (.sql)
> - Restauramos la Base de Datos usuando el comando "MYSQL"

C:/Program Files/MYSQL Server 8.0/bin/mysql-u root-p password < respaldo.sql

### 6. Listas Ordenadas y Listas Desordenadas

Si en nuestra documentacion necesitamos incluir informacion en modo de klista, un elemento tras otro podemos hacerlo utilizando los numeros con un punto decimal si las deseamos ordenadas o un guion medio - si solo queremos una viñeta.

***EJEMPLO:***

Para crear tu primer repositorio en GitHub deberas:
1. Contar con tu cuenta GitHub.
2. Dar clik en el boton: **Nuevo Repositirio*
3. Asignarle un Nombre a tu repositorio:
- **Público:** Si quieres que este disponible para todos los usuarios.
- **Privado:** Si deseas que solo a quien tu decidas puedan y colaborar con tu proyecto.
5. Definir si incluye un archivo de descripcion llamado: *README.md*
50. Definir si habra exclusiones de archivos atravéz del archivo: *.gitignore*
3. Guardar los cambios. 

### 7. Ligas (Hipervinculos)
Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetean utilizando los corchetes \[\]

**EJEMPLO**
Mi buscador favorito es: [Google](http://www.google.com).

Pero si deseamos poner solo las ligas directas o un correo electronico podemos utilizar los simbolos \<\>

**EJEMPLO:**

Documentacion creada por:***Karen Lizbeth Negrete Hernandez***

<230570@utxicotepec.edu.mx>

<http://utxicotepec.edu.mx>


### 8. Imágenes
Puede mostrar una imágen agregando ! y ajustar el texto alternativo en [ ]. El texto alternativo es un texto corto equivalente a la información de la imágen. Luego escribe el vinculo de la imágen entre paréntesis ().

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)






GitHub admite la inserción de imágenes en incidencias, solicitudes de incorporación de cambios, debates, comentarios y archivos .md. Puedes mostrar una imagen desde tu repositorio, agregar un enlace a una imagen en línea o cargar una imagen. Para obtener más información, consulte "Carga de recursos".


### 9. Tabla(Tables)
La habitación lo requiere podemos presentar información en formato de jaulas con filas y columnas, para maquetarlas podemos utilizar el carácter \| para deliminar las columnas y \- para delimitar filas.

**Ejemplo:**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 |
|--------------|--------------|--------------|--------------|
|Fila 1 celda 1|Fila 1 celda 2|Fila 1 celda 3|Fila 1 celda 4|
|Fila 2 celda 1|Fila 2 celda 2|Fila 2 celda 3|Fila 2 celda 4|
|Fila 3 celda 1|Fila 3 celda 2|Fila 3 celda 3|Fila 3 celda 4|

En el caso de la función de celda en columnas usaremos la propiedad "colspan" del tag \<td> y el caso de necesitar la funcion de las filas utilizaremos la propiedad "rowspan".

**Ejemplo**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 |
|--------------|--------------|--------------|--------------|
|Fila 1 celda 1|Fila 1 celda 2|Fila 1 celda 3|Fila 1 celda 4|
|Fila 2 celda 1 <tb colspan=2>|Fila 2 celda 2|Fila 2 celda 3|Fila 2 celda 4|
|Fila 3 celda 1|Fila 3 celda 2|Fila 3 celda 3|Fila 3 celda 4|
|              |Fila 4 celda 2|Fila 4 celda 3|Fila 4 celda 4|
|              |Fila 5 celda 2|Fila 5 celda 3|Fila 5 celda 4|
|Fila 6 celda 1|Fila 6 celda 2|Fila 6 celda 3|Fila 6 celda 4|

