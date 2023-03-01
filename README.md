# Microfrontend Styles

<p style='text-align: justify;'> Este proyecto es un microfrontend desarrollado en angular versión 15.1.2 y con single-spa en su version 4.0.0. Su principal función es proveer los estilos genéricos de la aplicación. </p>


## Servidor de desarrollo

<p style='text-align: justify;'> Primero debemos clonar el código del <a href="https://github.com/lamatcalderon/mf-styles">repositorio</a> y con una terminal instalar las dependencias</p> 

```sh
npm i
```

<p style='text-align: justify;'> Luego debemos ejecutar</p> 

```sh
npm start
```

<p style='text-align: justify;'> Esto levantará un servidor de desarrollo localhost en el puerto 4202 </p> 


## Construcción

<p style='text-align: justify;'> Los archivos generados a través del proceso de contrucción se almacenan en la carpeta <strong>dist/mf-styles</strong>, para construir el proyecto debemos ejecutar el siguiente comando en una terminal</p> 


```sh
npm run build:single-spa:portafolio
```
