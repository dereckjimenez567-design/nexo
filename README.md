# Nexo — Sitio web

Sitio de **Nexo**: diseño web, sistemas, dashboards y asesoría contable.
Bilingüe (ES/EN), responsive (móvil, tablet y escritorio).

## Estructura

- `index.html` — sitio principal (una sola página con router por hash).
- `img/` — imágenes del sitio (equipo, etc.).
- `proyectos/` — portafolio interactivo. Cada subcarpeta es una página real que se
  muestra como vista previa en vivo dentro de la galería:
  - `constructora-segovia/` — sitio de una constructora (real).
  - `inversiones-marioja/` — sitio en React de alquiler de andamios (real, build).
  - `jardineros-de-pasion/` — sitio de jardinería (real).
  - `gym-titan/`, `nails-studio/`, `lavacar-premium/`, `taller-autos/` — conceptos de demostración.

## Ver localmente

Cualquier servidor estático sirve. Por ejemplo:

```
npx serve .
```

Luego abrir http://localhost:3000

## Publicación

Pensado para GitHub Pages (rutas relativas, funciona bajo un subdominio de proyecto).
