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


### request tipo post -- insonmia para las peticiones crear `POST`

`
http://localhost/api/todos

{   "title":"instalar wsl",
    "completed":false
}
`

### obtener todos tipo `GET`

`
http://localhost/api/todos

solo uno

http://localhost/api/todos/1
`


### actualizar tipo `PUT`

`
http://localhost/api/todos/1
{
  "id": 1,
  "title": "descargar y configurar docker desktop",
  "completed": true
}
`

### borrar tipo `DELETE`

`
http://localhost/api/todos/5
`

### instalar vue globalmente

`
npm i -g @vue/cli
`

### se separon el frontend en la carpeta frontend-vue para crear el frontend con vue

`
vue create vue-todos

`

---

#### seleccion de versiones 

--

manually select features

---
con espaciadora se seleccionan y enter para confirmar

babel,typeScript


---

version 3x

---
y

---

y

---

in dedicated config files

---

N

---

npm


### para correr el proyecto

`
npm run serve
`