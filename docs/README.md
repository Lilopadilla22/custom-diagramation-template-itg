## Special-diagramation

Este componente tiene como objetivo mostrarle al cliente una grilla dinamica para mostrar sus productos 
 ## vista del componente

![grig__custom](https://user-images.githubusercontent.com/97923792/209364210-8e57bb6a-e863-4da9-a274-49caa777496c.jpg)

## CONFUGURACION 

### Primero - Configuración Básica 

Ingresar al siguiente repositorio en GitHub react-app-template (https://github.com/vtex-apps/react-app-template) y crear un nuevo repositorio usando este template

### Segundo - Clonación del repositorio 

Abrir la terminal e ingresar el comando git clone mas la URL del repositorio en gitHub así:
git clone [url](), posteriormente acceda a la carpeta del proyecto en su repositorio local.

### Tercero - Editar el Manifest.json

Modificar en el archivo manifest.json:
1ro. El valor del vendor con el nombre correspondiente a su vendor
2do. El valor del name con el nombre con el que va a usar su componente. 
3ro. Opcionalmente puede modificar la versión, el título y agregar una descripción, para darle un mejor esquema y explicación de lo que hace nuestro componente. 
4to. Agregar las dependencias necesarias, que vaya a utilizar para su desarrollo.

Ejemplo:  
{  
  "vendor": "itgloberspartnercl",  
  "name": "special-diagramation",  
  "version": "0.0.1",  
  "title": "special-diagramation",    
  "description": "Este componente tiene como objetivo mostrarle al cliente una grilla dinamica para mostrar sus productos"  
}

Adicionalmente debe asegurarse de tener en los builders el store en su version 0.x así:

"builders":{   
"store": "0.x"   
}

## depedencias

1.  "vtex.css-handles": "0.x"

### Cuarto - Editar el Package.json 

Modificar en los archivos package.json ubicado de manera global asi como el que esta ubicado en la carpeta de react, el nombre y la versión de igual forma como fueron modificados en el archivo manifest.json

Ejemplo:  

{  
  "version": "0.0.1",  
  "name": "special-diagramation"
}

### Quinto - Instalar apps

En la terminar dar ubicarse en la carpeta de react que nos proporciona el temple, cd react, luego escribir "yarn" para darle inicio a la instalacion de todos los nodulos que haran funcionar la aplicacion. 

## Sexto - Ejecutar el preview de la tienda.

En su terminal digite el comando vtex link, si su aplicacion es lanzada sin ningún error, en su ternimal aparecerá la siguiente información:   
(info: App linked successfully). 

Para usar la aplicación en su tienda debe adicionar en el archivo manifest.json la dependencia correspondiente al componente.

Ejemplo:  
"dependencies": {  
 "itgloberspartnercl.special-diagramation": "0.x",  
}

## Firma
1. Lilia padilla Arends
