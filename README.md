# Laboratorio Calificado 03

Este proyecto es una aplicación Android que consume una API para mostrar una lista de profesores. La aplicación muestra la foto, nombre y apellido de cada profesor en tarjetas (CardView). Además, proporciona funcionalidades para interactuar con los datos de los profesores, como hacer una llamada telefónica o enviar un correo electrónico a un profesor.

## Características

- **Consumo de API**: Se utiliza Retrofit para obtener los datos de los profesores desde un servicio remoto.
- **Diseño atractivo**: La aplicación utiliza **CardViews** con imágenes redondeadas y un diseño limpio y funcional.
- **Interactividad**: Al hacer clic en un profesor, se pueden realizar acciones como llamar o enviar un correo electrónico.
- **Optimización**: Se emplean buenas prácticas de diseño y optimización de la interfaz para ofrecer una experiencia de usuario fluida.

## Requisitos

- Android Studio con soporte para Kotlin.
- SDK de Android 24 o superior.
- Conexión a Internet para obtener los datos de la API.

## Instalación

1. Clona este repositorio en tu máquina local:
    ```bash
    https://github.com/EduardoBullon/LaboratorioCalificado03_EduardoBullon.git
    ```

2. Abre el proyecto en Android Studio.

3. Asegúrate de que tu proyecto esté configurado con los permisos necesarios en el archivo `AndroidManifest.xml`, incluyendo el acceso a **Internet**.

4. Ejecuta el proyecto en tu dispositivo o emulador Android.

## Estructura del Proyecto

- **MainActivity**: Es la actividad principal que muestra la lista de profesores.
- **Ejercicio01Activity**: Muestra detalles adicionales sobre los profesores al hacer clic en su tarjeta.
- **API**: Se utiliza Retrofit para consumir una API externa y obtener la lista de profesores.
- **Interfaz de Usuario**: Utiliza **CardView** para mostrar los datos de cada profesor de manera visualmente atractiva.

## Dependencias

Este proyecto utiliza las siguientes dependencias:

- **Retrofit** para la comunicación con la API.
- **Coil** para la carga de imágenes desde la web.
- **RecyclerView** para mostrar la lista de profesores.
- **ViewBinding** para optimizar el acceso a las vistas de la interfaz.
- **CardView** para crear las tarjetas visuales.

## Permisos

La aplicación necesita el permiso de **Internet** para realizar solicitudes HTTP a la API. Este permiso debe ser agregado en el archivo `AndroidManifest.xml`:

```xml
<uses-permission android:name="android.permission.INTERNET"/>
