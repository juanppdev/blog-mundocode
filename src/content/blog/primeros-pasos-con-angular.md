---
title: "Primeros Pasos con Angular"
description: "Aqui te traigo los primeros pasos para que empieces con Angular 18"
pubDate: "Sept 21 2024"
heroImage:  "/img/first-steps-Angular.png"
categories: ["first-step", "Framework", "Angular"]
authors: ["Juanppdev"]
tags: ["Framework"]
---

# Primeros pasos con Angular

## Introducción
========================
Angular es un framework de desarrollo para construir aplicaciones web dinámicas y robustas. En este tutorial, te guiaré a través de los primeros pasos para comenzar a trabajar con Angular.

## Requisitos previos
========================
Antes de empezar, asegúrate de tener instalados los siguientes programas:

- Node.js (versión 12.0 o superior)
- npm (gestor de paquetes de Node.js)
- Un editor de código (recomiendo Visual Studio Code)

## Instalación de Angular CLI
========================
Angular CLI (Command Line Interface) es una herramienta que facilita la creación y gestión de proyectos Angular. Para instalar Angular CLI, abre tu terminal y ejecuta el siguiente comando:

```bash
npm install -g @angular/cli
```

## Creación de un nuevo proyecto Angular
========================
Una vez que Angular CLI esté instalado, puedes crear un nuevo proyecto Angular con el siguiente comando:

```bash
ng new mi-primer-proyecto
```

Sigue las instrucciones en pantalla para configurar tu proyecto. Puedes aceptar las opciones predeterminadas para simplificar el proceso.

## Ejecutar la aplicación
========================
Para ver tu nueva aplicación en acción, navega al directorio del proyecto y ejecuta el servidor de desarrollo:

cd mi-primer-proyecto
ng serve

Abre tu navegador y ve a http://localhost:4200/. Deberías ver la página de bienvenida de Angular.

## Estructura del proyecto
========================
Tu proyecto Angular tendrá una estructura similar a esta:

```
mi-primer-proyecto/
├── e2e/
├── node_modules/
├── src/
│   ├── app/
│   ├── assets/
│   ├── environments/
│   ├── index.html
│   ├── main.ts
│   ├── polyfills.ts
│   ├── styles.css
│   └── test.ts
├── .editorconfig
├── .gitignore
├── angular.json
├── package.json
├── README.md
└── tsconfig.json
```

## Crear un nuevo componente
==========================
Los componentes son los bloques de construcción de una aplicación Angular. Para crear un nuevo componente, usa el siguiente comando:

```bash
ng generate component mi-componente
```

Esto creará un nuevo directorio mi-componente dentro del directorio src/app/ con los archivos necesarios para tu componente.

## Conclusión
================
¡Felicidades! Has creado tu primera aplicación Angular y un nuevo componente. Desde aquí, puedes explorar más sobre Angular y sus características avanzadas.

## Recursos adicionales

[Documentación oficial de Angular](https://angular.dev/overview)

[Tutorial de Angular en YouTube](https://www.youtube.com/watch?v=_HknWXhXjwY)

[Repositorio guithub](https://github.com/juanppdev/hello-angular)

[Servidor de discord](https://discord.gg/GDDRTUpbT9)

¡Espero que este tutorial te haya sido útil! Si tienes alguna pregunta, no dudes en dejar un comentario en nuestro servidor de discord.