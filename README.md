# Angular

## Angular CLI
Abarca:
- Scaffold: Generar una estructura inicial de archivos para proyecto, configuraciones.
- Preview: Vista previa
- Local Build: Proceso para construir el JS, los scripts necesarios.
- Local Testing, Unit Test, E2E test: Pruebas para verificar código, clases, servicios
- Best Practices: Reglas, combinar las mejores practicas
~~~
npm install -g @angular/cli
~~~

## Crear aplicación / proyecto forma básica
~~~
ng new nombre-proyecto
~~~

### Crear proyecto/aplicacion desde cero
~~~
ng new nombre-proyecto --routing
                       --prefix letras-prefix
                       --style css
                       --skip-install
~~~ 
Opciones de personalización:
- --routing: Módulo de manejo de rutas
- --prefix: Prefijo para componentes, directivas, servicios
- --skip: Permite generar la estructura sin dependencias
- --style: Para definir con que vamos a trabajar css, preprocesadores ej. Sass

## Para levantar proyecto
~~~
ng serve
ng serve -p numeroPuerto
ng serve -o
~~~

## Para ejecutar los test
ng test
