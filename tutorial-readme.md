# Tutorial angular
## Instalaciones
    1. Tener instalado nodeJS
    2. npm i -g @angular/cli
    3. ng version
    4. Descargar en el navegador la extension **Angular DevTools**

## Iniciar un proyecto
    1. ng new "Nombre-app"
    2. ng serve (o ng run start)
    3. http://localhost:4200/
    4. Editaremos el HTML, CSS y cosas basicas en "src/app/..."

## Si hay problemas con restricciones de windows
    1. Abre como administrador powerShell
    2. Get-ExecutionPolicy (Estará en Restricted)
    3. Set-ExecutionPolicy Unrestricted
    4. Ya podrás usar el comando "ng serve" en la terminal

## Generamos la carpeta para usar APIs
* Comando: ng g c components/product
<br> *La 'g' es de generate y la 'c' es de components, seguido del nombre de la carpeta*
<br>
* Se usara **RxJS**
