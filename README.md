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


## fonrzar la instakacion de un paquete
> npm install [**nombre paquete**] -f


## instalar un paquete con una version especifica
> npm install [**nombre paquete**]@[**version**]