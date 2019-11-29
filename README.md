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

Se recomienda eliminar el contenido del archivo *app.component* y solo dejar `<router-outlet></router-outlet>` e ir agregando 

## Generando Componentes

Angular CLI schematics, generados de código que se basan en un template.

~~~
ng generate @angular/material:componente nombre-componente
~~~
Ej: 
ng generate @angular/material:dashboard tablero

ng generate @angular/material:table tabla