# Testigos

Curso y juego interactivo para aprender redes de Petri desde cero. By FTinform.

- **Curso:** 30 lecciones guiadas, de lo más fácil a lo más difícil, incluido un parcial resuelto paso a paso.
- **Práctica:** disparos, árbol de alcanzabilidad, máquina de testigos, propiedades con justificación y método matricial.
- **Simulacros:** escrito (como el parcial, corregido al final) y guiado (paso a paso, con nota).
- **Mis errores:** vuelve a preguntar lo que fallaste, con redes nuevas.
- **Teoría:** 69 preguntas de definiciones, verdadero o falso y por qué.

## Cómo está hecho

Es una sola página: todo el HTML, el CSS, el JavaScript y las fuentes están dentro de `index.html`. No usa dependencias, compilación ni servidor.

El progreso se guarda en el navegador de cada persona con `localStorage`, y se puede pasar a otra PC con un código.

## Probarlo en tu PC

Abrí `index.html` con doble clic.

## Publicarlo

En Vercel, importá este repositorio con el preset **Other**, sin comando de build. Cada `git push` a `main` publica una versión nueva.

Para ver visitas, activá **Web Analytics** en la pestaña Analytics del proyecto en Vercel. La página ya carga el script de Vercel cuando está publicada.

La imagen para compartir (`og.png`) apunta a `https://testigos-petri.vercel.app`. Si tu dominio es otro, cambialo en las etiquetas `og:url` y `og:image` de `index.html`.

## Fuentes

Saira Stencil One, Saira Semi Condensed, Atkinson Hyperlegible y JetBrains Mono, bajo SIL Open Font License. Las licencias están en `LICENCIAS-FUENTES.txt`.
