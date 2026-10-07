# Simulador de Electrofusión – NAG-140 / ISO 4427

Simulador didáctico, paso a paso, de la unión de tuberías de polietileno por electrofusión (cupla). Es un único archivo `index.html`, sin dependencias.

- Procedimiento en 7 etapas (12 operaciones) con animación en canvas.
- Botón **Simular falla / mala práctica** en cada etapa.
- Temporizador interactivo de tiempo de enfriamiento (cooling time).
- Pestaña **Parámetros eléctricos y máquina**: máquina automática vs. manual, tensión, tiempo, estado del ciclo y temperatura, con explicación física (E = V²·t/R).
- Modo de evaluación rápida con preguntas de opción múltiple.
- Responsive: funciona en celulares, tablets y PC.

> Material de capacitación. En obra siempre rige la NAG-140 vigente y el manual del fabricante del accesorio y de la máquina.

## Publicación (GitHub Pages)

El workflow `.github/workflows/pages.yml` publica el sitio en cada push a `main`.
Activación única: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
El link queda en `https://<usuario>.github.io/CURSO-ELECTROFUSION/`.

## Uso local

Abrir `index.html` en el navegador.
