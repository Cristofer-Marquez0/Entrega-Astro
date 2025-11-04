
---
### 1. ESTRUCTURA (Dónde va cada cosa)
El `README` te explica cómo está organizada tu carpeta principal (`/`):
* **`/public/`**: Para archivos que no se modifican, como el icono del navegador (`favicon.svg`).
* **`/src`**: Donde está todo tu código principal.
    * `pages`: Se convierten en tus páginas web finales (por ejemplo, `index.astro` es la página de inicio).
    * `components`: Piezas pequeñas de código reutilizable (como un menú o tarjetas).
    * `layouts`: Define el diseño general de tus páginas (dónde va el encabezado y el pie de página).
---
### 2. COMANDOS (Lo que tienes que escribir en la terminal)
Estos comandos son para trabajar con tu proyecto:
| Comando | Lo que hace |
| :--- | :--- |
| `npm install` | **Instala** todo lo necesario para que el proyecto funcione. |
| `npm run dev` | **Inicia el proyecto** para que lo veas en tu navegador (`localhost:4321`) mientras lo editas. |
| `npm run build` | **Prepara la versión final** de tu sitio web (crea una carpeta `./dist/` lista para subir). |
| `npm run preview` | Te deja **probar la versión final** (`build`) antes de subirla. |

---