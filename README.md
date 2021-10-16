# Build-A-TodoList-with-Laravel-and-Vue

### instalar docker-desktop ver repositorio

`
https://github.com/jdvpl/Docker-Kubernates-Azure
`

### instalar kool

`
https://kool.dev/docs/getting-started/installation
`


### creando proyecto

`
kool create laravel todolist
`

#### seleccionado

`
php 8
postgreSql
redis para caches
npm
`


### configurar el archivo de .env.example

`
https://kool.dev/docs/presets/laravel
`


### correr comando bash de git

`
kool run setup
`


### error del puerto 80 con docker ejecutar


`
NET stop HTTP
`

---
### ejecutar  `kool run setup` hasta que diga wbpack compiles sucesfully


### crear modelos y migraciones 

`
kool run artisan make:model Todo --migration
`

### despues de haber creado el modelo se migra hacia la base de datos

`
kool run artisan migrate
`


### creando controllers

`
kool run artisan make:controller API/TodoController --api
`


### comprobar si podemos acceder a las rutas

`
kool run artisan route:list
`