# Sound Night Light (Las Torres de la Madrugada)

Un experimento audiovisual interactivo de música electroacústica generativa y redes estelares paramétricas. 

## Sobre el Proyecto

Este proyecto nació como una exploración (originalmente pensada alrededor del cuento "Los batracios de fuego") que fue evolucionando radicalmente hacia un concepto de **"Antenas Nocturnas"**: un paisaje sombrío y de alto contraste a la madrugada, donde torres de comunicación y estrellas conforman una inmensa red de energía y sonido.

### Características Principales

*   **Paisaje Asimétrico y Perspectiva Atmosférica SOTA:** Una vista nocturna brumosa con profundidad de campo óptica. Las 9 torres de telecomunicaciones (diseñadas en CSS puro) se desvanecen en la distancia absorbiendo el tono azul/púrpura del cielo, mientras que las torres en primer plano se mantienen nítidas y oscuras. El horizonte es un cerro vectorial hiper-realista e irregular (SVG fractal), rompiendo toda simetría artificial.
*   **Firmamento Extendido (9 Micro-Estrellas):** El firmamento ahora cuenta con 9 nodos celestiales esparcidos, renderizadas como micro-puntos de luz (1.5px reales) invisibles hasta ser descubiertos por el usuario, activando secuencias celestiales (Pads y Plucks arpegiados).
*   **Dinámica de Sobrecarga Láser:** Al conectar los nodos terrestres y celestiales (haciendo clic sobre ellos), un entramado de líneas mágicas se teje en el cielo:
    *   **Nivel Estable (1-5 nodos):** Tensión baja, líneas rojas cálidas.
    *   **Energía Media (6-11 nodos):** Incremento de poder, los láseres mutan a tonos fríos (**Cyan**) y el Drone base comienza a distorsionarse por FM (Frequency Modulation).
    *   **Sobrecarga Crítica (12-18 nodos):** Caos estético y sobre-voltaje. Los láseres destellan frenéticamente en **Violeta/Blanco**, y un intrincado arpegiador de alta velocidad completa la obra sonora.
*   **Mezclador SOTA (Glassmorphism HUD):** Toda la síntesis generativa de `Tone.js` se rutea a canales independientes. La interfaz expone una consola profesional transparente (efecto cristal) que permite silenciar y ecualizar por separado las 5 familias de sonido base: Drones, Nieve, Metal, Synths, y Celestial. Además, el Master Bus incluye *Reverb* y *Delay* modificables en tiempo real para reconfigurar la atmósfera del paisaje.
*   **Afinación Algorítmica (C minor 11):** Todos los componentes son generados por código asimétricamente, pero musicalmente se rigen por escalas lógicas para garantizar que la progresión siempre origine sonoridades armoniosas y misteriosas.

## Tecnologías Utilizadas

*   **HTML5 / CSS3:** Posicionamiento paramétrico avanzado, animaciones por keyframe (titileos, pulsos), sombreado y diseño 100% puro CSS sin archivos de imágenes estáticas externas.
*   **Vanilla JS (ES6+):** Motor de interacción central y manipulación del DOM / dibujado de vectores en SVG Canvas.
*   **Tone.js:** El framework de "Web Audio API" por excelencia responsable de todos los sintetizadores virtuales (Membrane, FM, Poly, Pluck, Noise), osciladores, filtros, reverbs, delays granulares y secuenciado de patrones ocultos.
*   **Vite:** Servidor ligero de desarrollo (HMR).

## Instalación y Ejecución Local

Para correr este proyecto en modo desarrollo en cualquier equipo local:

1. **Instalar dependencias necesarias:**
   ```bash
   npm install
   ```
2. **Desplegar el servidor de desarrollo Vite:**
   ```bash
   npm run dev
   # o alternativamente: npx vite --port 5005
   ```
3. Abrir la URL mostrada en la terminal (por defecto `http://localhost:5005`) en cualquier navegador moderno. Para la mejor inmersión visual y uso del Canvas SVG interactivo se recomienda interactuar a pantalla completa y con auriculares.

---

*Diseñado de manera conjunta durante las sesiones de agente AI (Prototipado "Berisso Incident").*
