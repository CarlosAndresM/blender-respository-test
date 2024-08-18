# blender-respository-test
This repository is for testing the development of a web portfolio for a 3D designer and animator. It consumes a JSON file to dynamically render the files from the repository, showcasing the 3D models and animations along with relevant data on the website.
 
# Repositorio de Archivos para Portafolio Web de 3D

## Descripción

Este repositorio contiene archivos para un portafolio web de un diseñador y animador 3D. Incluye modelos 3D y miniaturas que seran consumidas por una pagina web para hacer las respectivas pruebas.

## Estructura del Repositorio

```
example-repository/
├───3AM
│   ├─── modelo1.glb
│   └─── thumbnail1.jpg
└───Anuvix
    ├─── modelo2.glb
    └─── thumbnail2.jpg
```

## Archivo `blender-services.json`

Ejemplo de contenido:

```json
[
  {
    "id": "model1",
    "title": "Modelo 3D Ejemplo 1",
    "description": "Descripción del modelo 3D Ejemplo 1.",
    "link": "https://github.com/tuusuario/tu-repositorio/blob/main/3AM/modelo1.glb",
    "thumbnail": "https://github.com/tuusuario/tu-repositorio/blob/main/3AM/thumbnail1.jpg"
  },
  {
    "id": "model2",
    "title": "Modelo 3D Ejemplo 2",
    "description": "Descripción del modelo 3D Ejemplo 2.",
    "link": "https://github.com/tuusuario/tu-repositorio/blob/main/Anuvix/modelo2.glb",
    "thumbnail": "https://github.com/tuusuario/tu-repositorio/blob/main/Anuvix/thumbnail2.jpg"
  }
]
```
 
