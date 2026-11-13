# AGENTS.md

Static single-page site (Spanish-language, "LO PROPIO"). There is no package manager, build step, test suite, or git repo in this directory.

## Working here

- Only files: `index.html` (the whole site, CSS inline in a `<style>` block) and `Readme.md`.
- Verify changes by opening `index.html` directly in a browser (or `Start-Process index.html` on Windows); nothing to compile or serve.
- Write page copy and comments in Spanish to match existing content.

## Gotchas

- `Readme.md` lists Tailwind CSS and JavaScript, but `index.html` currently uses plain inline CSS and has no Tailwind build or scripts. Trust `index.html`, not the Readme, and do not introduce a Tailwind toolchain unless asked.

## reglas de estilo
encuentras en el archivo @guia-estilos.md
