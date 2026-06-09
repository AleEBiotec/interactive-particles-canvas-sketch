# Animación interactiva de partículas

Autor: Ale Enriquez

## Descripción

Este proyecto consiste en una animación interactiva de partículas desarrollada en JavaScript utilizando la librería canvas-sketch.

Las partículas están organizadas en círculos concéntricos y reaccionan a la interacción del usuario mediante fuerzas físicas simuladas. Al hacer clic y mover el cursor sobre el lienzo, las partículas son repelidas y posteriormente regresan suavemente a su posición original.

El proyecto explora conceptos de creative coding, animación procedural, interacción con el usuario y simulación de movimiento basada en física simple.

## Vista previa

[Vista previa de la animación](assets/particles-demo.gif)

## Tecnologías utilizadas

- JavaScript
- Node.js
- canvas-sketch
- canvas-sketch-util
- eases
- colormap

## Estructura del proyecto

```text
interactive-particles-canvas-sketch/
├── .gitignore
├── package.json
├── package-lock.json
├── sketch-particles.js
└── README.md
```

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/AleEBiotec/interactive-particles-canvas-sketch.git
```

2. Entrar a la carpeta del proyecto:

```bash
cd interactive-particles-canvas-sketch
```

3. Instalar dependencias:

```bash
npm install
```

## Ejecución

Para ejecutar la animación:

```bash
npm start
```

O directamente:

```bash
canvas-sketch sketch-particles.js --open
```

## Características principales

- Animación generativa en tiempo real.
- Partículas distribuidas en patrones circulares.
- Interacción mediante mouse.
- Sistema de atracción y repulsión.
- Transiciones suaves mediante amortiguación.
- Escalado dinámico de partículas.
- Cambio de color basado en la distancia respecto a su posición original.

## Objetivos del proyecto

- Practicar programación creativa.
- Explorar simulaciones físicas simples.
- Comprender sistemas de partículas.
- Experimentar con interacción en tiempo real.
- Construir proyectos para portafolio profesional.

## Cómo funciona

El programa crea un conjunto de partículas distribuidas en círculos concéntricos. Cada partícula guarda su posición inicial y calcula fuerzas de movimiento en cada frame.

Cuando el usuario hace clic y arrastra el mouse sobre el canvas, las partículas cercanas al cursor reciben una fuerza de repulsión. Después, una fuerza de atracción las hace regresar gradualmente a su posición inicial.

El movimiento se suaviza mediante un factor de amortiguación, lo que genera una animación fluida y orgánica.

Proyecto creado con fines educativos y de aprendizaje.
