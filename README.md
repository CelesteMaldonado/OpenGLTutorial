
# Tutorial OpenGL en C++ con Visual Studio

Este repositorio contiene una solución de Visual Studio para aprender OpenGL en C++. La solución incluye varios proyectos que cubren diferentes aspectos de OpenGL, como shaders, index buffers, uniforms y vertex arrays. Cada proyecto está configurado para utilizar GLEW y GLFW, y genera sus ejecutables en sus respectivas carpetas `Debug` y `Release`.

## Contenido

La solución de Visual Studio incluye los siguientes proyectos:

- Shaders
- IndexBuffers
- Uniforms
- VertexArrays

## Requisitos

Antes de abrir la solución, asegúrate de tener instalados los siguientes componentes:

- Visual Studio 2019 o superior
- Paquete de desarrollo de C++ para aplicaciones desktop en Visual Studio
- GLEW (OpenGL Extension Wrangler Library)
- GLFW (Graphics Library Framework)

## Instrucciones

### Paso 1: Clonar el Repositorio

Clona este repositorio en tu máquina usando el siguiente comando:

```sh
git clone https://[your_user]@bitbucket.org/laligatech/mcodesk-opengltutorial_spt.git
```

### Paso 2: Abrir la Solución en Visual Studio

1. Navega hasta la carpeta donde clonaste el repositorio.
2. Abre el archivo `OpenGLTutorial.sln` con Visual Studio.

### Paso 3: Configurar las Dependencias

Asegúrate de que las bibliotecas de GLEW y GLFW están configuradas correctamente en cada proyecto. Los archivos necesarios para GLEW y GLFW están incluidos en la carpeta `Dependencies`.

### Paso 4: Compilar y Ejecutar los Proyectos

Cada proyecto está configurado para generar los archivos ejecutables en sus propias carpetas `Debug` y `Release`. Sigue estos pasos para compilar y ejecutar un proyecto:

1. Selecciona el proyecto que deseas ejecutar desde la solución en el Explorador de Soluciones de Visual Studio.
2. Selecciona la configuración de compilación (`Debug` o `Release`) y la plataforma (`Win32`).
3. Compila la solución.

## Estructura del Proyecto

Cada proyecto sigue la misma estructura básica:

```
Proyecto
│
├── Debug/                 # Directorio de salida para la configuración Debug
├── Release/               # Directorio de salida para la configuración Release
├── src/                   # Código fuente del proyecto
│   ├── Application.cpp    # Archivo principal del proyecto
│   └── ...                # Otros archivos fuente y de cabecera
├── res/                   # Directorio con los recursos
├── Proyecto.vcxproj       # Archivo de proyecto de Visual Studio
└── Proyecto.vcxproj.filters # Filtros de proyecto de Visual Studio
```

## Notas Adicionales

Asegúrate de tener configuradas las rutas correctas para las bibliotecas y los archivos de cabecera de GLEW y GLFW en las propiedades del proyecto.

Si encuentras algún problema con la configuración del proyecto o la compilación, revisa las rutas de inclusión y dependencias en las propiedades del proyecto en Visual Studio.
