# APUNTES DEL CURSO

## iniciar un proyecto
> npm init: 

## iniciar un proyecto con una configuracion predeterminada
> npm init -y

## define valores por defecto para ciertps atributos de la configuracion
> npm set init.author.email "fau.obregon@gmail.com"

> npm set init.author.name "Fausto Obregón"

> npm set init.license "MIT"


## instalar un paquete necesario para produccion
> npm install [**nombre del paquete**]

> npm install [**nombre del paquete**] --save

> npm i [**nombre del paquete**]  -S


## instalar paquete solo para un entorno de desarrollo
> npm install [**nombre del paquete**] --save-dev

> npm i [**nombre del paquete**]  -D


## instalar paquete de manera global
> npm install -g [**nombre de paquete**]


## lista dependencia globales
> npm list -g --depth 0


## instalar paquete opcional
> npm i [**nombre paquete**] -O


## simula la instalacion de paquete para tener detalle de lo que se podraa instalar
> npm i [**nombre paquete**] --dry-run


## forzar la instakacion de un paquete
> npm install [**nombre paquete**] -f

## Intallar todo lo que este parametrizado en el archivo *package.json*
> npm install

## instalar un paquete con una version especifica
> npm install [**nombre paquete**]@[**version**]
-  si colocas *latest* en o que respecta a la version te descargara la ultima versiona estable

## Listar paquetes instalados 
> npm lits

## muestra la lista de paquetes que esta desactualizdos y su version actual
> npm outdate

-  Podemos agregar el flag  [--dd] para ver detalles de lo que ocurre en la ejecucion del comando
    > npm outdate --dd

## Actualizar los paquetes
> npm update

## eliminar paquetes 
> npm uninstall [*nombre paquete*]

## eliminar paquete sin borrarlo del package.json
> npm uninstall [*nombre paquete*] --no-save


## para que sirve el simbolo **^** adjunto a las versines de los paquetes
    Indica que se realice actualizaciones a partir de cambios menores o parches.
    Si se remplaza por **-** indicaras que solo se realice actualizaciones de parches y/o bugfixes.
    Para que no se realicen actualizaciones debemos quitar estos simbolos de la version
