CONTADOR DE BILLETES - PROYECTO ANDROID

Este ZIP contiene el proyecto Android y un flujo de GitHub Actions para compilar el APK en la nube, sin ordenador propio.

Cómo hacerlo desde el teléfono:
1. Descarga y descomprime este ZIP usando una aplicación de archivos.
2. Entra en https://github.com/ y crea una cuenta o inicia sesión.
3. Crea un repositorio nuevo (puede ser privado).
4. Sube todos los archivos y carpetas de este proyecto, incluida la carpeta oculta .github/workflows/compilar-apk.yml.
5. Abre la pestaña Actions del repositorio y selecciona “Compilar APK del Contador de Billetes”. Pulsa Run workflow si aparece.
6. Cuando termine correctamente, abre la ejecución y descarga el artefacto “Contador-de-Billetes-APK”. Descomprime el ZIP descargado para obtener app-debug.apk.
7. Abre app-debug.apk en el teléfono. Android puede pedir permiso para instalar aplicaciones desde el navegador o gestor de archivos; actívalo solo para la aplicación que estás usando y continúa si confías en el archivo.

IMPORTANTE: Este archivo es el código fuente preparado para compilar en la nube, no es todavía el APK. La compilación necesita ejecutarse en GitHub Actions.
