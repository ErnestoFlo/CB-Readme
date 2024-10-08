# Título principal del proyecto ( # )

<a id="Titulo"></a>

_Párrafo para la descripción de secciones o del proyecto en general (Se hace con guión bajo al inicio y fin). Este apartado nos sirve para dar una descripción general del proyecto_

## Este es un subtítulo ( ## )

_Esta es la descripción del subtitulo, esta propiedad nos permite extendernos de la manera mas prolongada o breve de lo que queremos explicar, y no tiene un limite. Esta sección nos sirve para especificar los detalles del proyecto y darle realce a los mismos._

Para marcar con **Negrita** debemos usar los asteriscos (** **)

## Resaltar en enmarcado

_Si necesitamos resaltar el código en una caja de texto donde este permanesca aislado, podemos utilizar el **asento grave** (```)_

Ejemplo:
```
git init
```

### Agregar imagenes

Se pueden agregar imagenes de la misma manera y propiedades como las que utilizamos en `HTML`. Ejemplo:

<p align="center" width="100%"><img src="https://raw.githubusercontent.com/ErnestoFlo/CB-SistemaDisk_VB.Net/refs/heads/master/Documentacion/Menu%20pricipal.png" /></p>

Nota: Con acento grabe (**`**) podemos darle un resalte diferente a las palabras de un párrafo

### Tercer subtitulo ( ### )

_Para esta sección, se suelde dar a los detalles técnicos y códigos para procedimientos y iniciación del proyecto. Este proceso se llama **Instalación**_

Ejemplo
```
pip install python
python -m pip install Django
```

### Tablas de contenido

Podemos agregar tablas de contenido como la siguiente:

<details>
<summary><b>Expandir</b></summary>

1. [Titulo:](#Titulo)
    1. [1.1 Objeto 1](#obj1)
    1. [1.2 Objeto 2](#obj2)
    1. [1.2 Objeto 3](#obj2)
    1. [1.2 Objeto 4](#obj2)
2. [Agradecimientos](#thanks)
</details>

## Otras secciones para el README

_Estas son otras secciones que se pueden incluir par adetallar el desarrollo y aplicativo del sistema en el documento_

### Ejecución de pruebas

_Explica como aplicar y el por que de las pruebas del sistema_

### Pruebas end-to-end (E2E)

_Esta es la esquematización del flujo que lleva el proyecto, dinde se explica el por qué de su funcionamiento. Además de brindar un simulacro del comportamiento completo del sistema, de inicio a fin_

### Estilo de codificación

_Es una explicación	de la nomenclatura y tipo de orden que se llevo durante el desarrollo del proyecto_

Ejemplo de nomenclatura de modelos:
```
class ejemplo_model (models.Model):
    id_ejemplo	= models.AutoField(PrimaryKey = True)
    nombre = models.CharField(max_length=30)
    apellido = models.CharField(max_length=30)
```

## Despliegue

_Son las configuraciones necesarias para poner en producción el proyecto_

## Construido con:

_Se mencionan las herramientas con las que se desarrollo la app. Nota: Para poner una lista en el rreadme debemos usar un **asterisco** y para agregar un link usamos **Corchetes y Paréntesis**_

* [Django](https://www.djangoproject.com/) - Framework utilizado
* [Python](https://www.python.org/) - Manejador de dependencias

## Otras campos a mencionar

* Contribuyendo: Algunas directrices para leer detalles del codigo
* Wiki: Más informacion de como utilizar nuestro proyecto
* Versionado: Metodologia que se emplea para dar los tags de actualizacion de versiones del proyecto

## Autores

_Aqui se mencionan a todas las personas que ayudaron y contribuyeron en el desarrollo del sistema_

* **Ernesto Flores** - *Desarrollador Frontend* - [ErnestoFlo](https://github.com/ErnestoFlo)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](#fulanito-de-tal)

## Licencia 

Este proyecto está bajo la licencia (Mi licencia) - Mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 

<a id="thanks"></a>

* Comentarios sobre este proyecto 
* Menciones y agradecimeintos a miembros del equipo. 
* Dar las gracias públicamente.
* etc.