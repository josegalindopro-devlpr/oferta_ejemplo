# candidatura-bootcamp-ia

Micro-site de candidatura de José Galindo para el Bootcamp Intensivo de IA.

- **Publicado en:** GitHub Pages, rama `main`, raíz del repo (`index.html`).
- **Tipo:** `candidatura-empleo`.
- **Fuente de contenido:** [`src/SCHEME.md`](src/SCHEME.md) — es el único fichero que se edita a mano. Basado en `MICROSITE_TEMPLATE.es.md` v0.2.
- **Derivado:** `src/SCHEME.yaml` se genera automáticamente a partir del `.md`. No editar directamente: los cambios se pierden en la siguiente regeneración.

## Cómo regenerar el sitio

1. Editar `src/SCHEME.md` (si cambia el contenido, subir `version_documento` y anotar el motivo en su historial interno).
2. Ejecutar, desde el repo `microsite-toolkit`: `python3 build.py <ruta a este proyecto>` — produce `src/SCHEME.yaml` e `index.html`.
3. Revisar `index.html` localmente antes de hacer commit.
4. `git add`, `git commit`, `git push` — GitHub Pages republica automáticamente.

## Histórico

- Generado por primera vez a mano (HTML directo).
- Migrado al esquema `SCHEME.md → SCHEME.yaml → index.html` (microsite-toolkit) como caso de validación — contenido sin cambios respecto a la versión publicada original. `version_documento: 1.0`, `plantilla_version: 0.2`.
