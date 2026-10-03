# Nombre del proyecto

Proyecto web + dashboard. Repo compartido entre dos personas.

**Web en vivo:** (pega aquí el link de GitHub Pages cuando lo actives)

## Qué hay aquí
- `index.html` — portada / web pública
- `dashboard/` — el dashboard
- `assets/` — estilos e imágenes
- `docs/` — notas y decisiones compartidas

## Cómo trabajamos los dos (importante)

La regla de oro: **antes de empezar a trabajar, siempre `git pull`. Cuando termines, `git push`.** Así el otro siempre arranca sobre lo último.

### Cada vez que te pones a trabajar
```bash
git pull            # trae lo último que hizo el otro
# ...trabajas y guardas tus archivos...
git add .
git commit -m "describe qué hiciste"
git push            # subes tu trabajo para que el otro lo tenga
```

### Si al hacer pull o push da error de "conflicto"
Significa que los dos tocasteis lo mismo a la vez. No pasa nada:
1. Git te marca en el archivo las dos versiones.
2. Decides con qué parte quedarte (o las juntas).
3. `git add .` → `git commit` → `git push`.

Truco para evitar conflictos: **avisaos por mensaje de quién está trabajando**, o repartíos archivos distintos. Con dos personas, hablar es más rápido que cualquier sistema.
