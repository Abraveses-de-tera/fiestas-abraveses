# Agenda sencilla · Fiestas de Abraveses de Tera

Esta carpeta contiene una versión independiente, ligera y pensada para móvil del programa de fiestas de Abraveses de Tera.

## Uso

Abre `index.html` en un navegador o publícala como sitio estático. No necesita Node.js, base de datos, APIs externas, mapa ni instalación de dependencias.

## Editar el programa

Los eventos están definidos al principio de `app.js`, dentro de la constante `days`.

Cada evento tiene este formato:

```js
{ time: "20:00", title: "Nombre del evento", description: "Texto opcional", note: "Aviso opcional" }
```

## Características

- Selector de programa por día
- Vista de todos los eventos
- Diseño responsive
- Colores inspirados en el cartel
- Sin contenido ni servicios heredados de Valladolid o Aldea Pucela

## Pendiente de confirmar

El cartel no muestra año. Antes de publicar, confirma que las fechas del 24 al 30 de agosto corresponden al año de la edición que se vaya a anunciar.
