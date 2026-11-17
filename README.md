# Rueda Libre (Tailwind CSS)

Página única de **Rueda Libre**, alquiler de bicicletas en Medellín, construida solo con utilidades de **Tailwind CSS v4** (sin `style=""` ni `<style>`). Todo el sitio está en un solo `index.html`: navbar, portada, flota, tarifas, beneficios, reservas y footer.

🔗 **Sitio publicado:** https://maecabrera007-afk.github.io/Proyecto_con_Tailwind/
📦 **Repositorio:** https://github.com/maecabrera007-afk/Proyecto_con_Tailwind

## Responsive
- Flota: `grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4`
- Navbar: menú oculto en móvil (`hidden`), horizontal desde `md:`
- Portada, tarifas y reservas: columnas desde `md:` y `lg:`

## Tailwind en este proyecto
Colores propios definidos con `@theme` en `src/input.css`: `ruta`, `ruta-oscuro`, `pedal`, `tinta`, `papel`.

## Cómo correrlo
```bash
npm install
npm run build
```
Abre `index.html` con Live Server. Durante el desarrollo usa `npm run dev`.

## Bootstrap vs Tailwind
La versión con Bootstrap está en otro repositorio: Rueda_libre_Miguel_Turing.