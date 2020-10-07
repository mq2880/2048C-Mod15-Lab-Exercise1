# Module 15: Packaging JavaScript for Production Deployment

**Lab: Setting Up Webpack Bundle for Production**

**Nombre:** Francisco Javier Moreno Quevedo

**Fecha:** 2/10/2020

**Resumen del Ejercicio:** El laboratorio se compone de un ejercicio. En el ejercicio uno se crea prepara nuestros scripts para el despliegue a producción usando webpack

**Dificultad o problemas presentados y como se resolvieron:** Muchos, tuve que instalar la libreria babel-loader@7 tras muchos intentos y cambios el problema radicaba en que el path de donde estaba los ficheros tenia un espacio en blanco. Tuve que repetir el proceso desde una carpeta situada en la raiz del disco y entonces el proceso funcionó

- Ejercicio 1
  - Se crea el fichero package.json
  - Se  instalan las librerias del transpilador
  - Se crea el fichero Webpack.config.js
  - Se crean los ficheros bundles