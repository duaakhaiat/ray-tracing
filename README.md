# Vector Ray Tracing Kernel

An interactive 3D visualization of light refraction through a transparent cube. Explore how light changes direction as it crosses between materials, and see Snell's law, Fresnel reflection, and total internal reflection in action.

## Run it

Open [`ray_tracing.html`](./ray_tracing.html) in a modern browser. No build step or installation is needed.

The page loads React, Babel, Three.js, and fonts from public CDNs, so an internet connection is required.

## Features

- Real-time 3D ray tracing through a cube, with adjustable refractive index and cube size.
- Material presets for vacuum, water, glass, quartz, diamond, and rutile.
- Controls for incident angle, ray count and spread, and cube rotation speed.
- Optional ray labels, normal vectors, Fresnel reflections, and grid and axes.
- Perspective, top, and side camera views.
- Live vector components and optical statistics, including incident and refracted angles, critical angle, Fresnel reflectance, and refraction count.
- Educational formula panels covering Snell's law and Fresnel reflectance.

## Physics

The visualization applies Snell's law to calculate refraction at the cube's entry and exit surfaces. Fresnel equations determine reflected intensity, and total internal reflection is shown when refraction is not possible.

## Technology

- React 18 for the interactive controls and display.
- Three.js for 3D rendering.
- Babel Standalone to run JSX in the browser.

All dependencies are loaded from CDNs in the HTML file; there is no separate build or package-install step.
