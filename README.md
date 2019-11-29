# Angular Material

Se debe trabajar sobre un proyecto con angular-cli

~~~
ng new nombre-curso --routing --prefix ed --style css
~~~

## Instalación via Angular CLI

Instala y configura

~~~
ng add @angular/material
~~~

Se recomienda eliminar el contenido del archivo *app.component.html* y solo dejar `<router-outlet></router-outlet>` e ir agregando componentes

## Generando Componentes

Angular CLI schematics, generados de código que se basan en un template.

~~~
ng generate @angular/material:componente nombre-componente
~~~
Ej: 
- ng generate @angular/material:dashboard tablero

- ng generate @angular/material:table tabla

- ng generate @angular/material:tree arbol

~~~
ng generate component archivo --no-spec --dry-run

ng generate component carpeta/archivo --no-spec --dry-run
~~~

## Importación de Módulos

~~~
ng generate module nombre-modulo --dry-run
~~~

--dry-run, es para simular resultado

~~~
ng generate module demo --routing --dry-run
~~~

