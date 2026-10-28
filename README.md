# sitio-web-pareja

Sitio web desarrollado únicamente con HTML como parte de la **Práctica N.° 2: Versionamiento de Aplicaciones** de la asignatura Fundamentos de Sistemas Web (Tecnologías de la Información, nivel 4, Departamento de Ciencias de la Computación).

## Objetivo

Aplicar técnicas de versionamiento con Git y GitHub para administrar los cambios del código fuente, organizar el trabajo colaborativo entre dos personas y mantener un historial ordenado de las modificaciones del proyecto.

## Integrantes

| Integrante | Rama de trabajo | Funcionalidad |
| --- | --- | --- |
| Ana Karen Yanza Giler | `feature-karen` | Página principal y navegación |
| Angeline Hidrovo Tovar | `feature-angeline` | Páginas "Sobre nosotros" y "Pasatiempos" |

## Funcionalidades implementadas

- **Página principal (`index.html`):** bienvenida, descripción del proyecto y menú de navegación hacia las demás páginas.
- **Sobre nosotros (`sobre-nosotros.html`):** presentación de las integrantes, tabla de integrantes, datos académicos y herramientas utilizadas.
- **Pasatiempos (`pasatiempos.html`):** listas de actividades, tabla de frecuencia por pasatiempo e imagen con descripción.

## Estructura de archivos

```
sitio-web-pareja/
├── index.html
├── sobre-nosotros.html
├── pasatiempos.html
├── imagenes/
│   └── pasatiempos.jpg
└── README.md
```

## Estructura de ramas

| Rama | Propósito |
| --- | --- |
| `main` | Producción: versión final aprobada |
| `pruebas` | Validación del sitio antes de pasar a producción |
| `desarrollo` | Integración de las funcionalidades individuales |
| `feature-karen` | Trabajo individual de Karen |
| `feature-angeline` | Trabajo individual de Angeline |

Flujo de integración: `feature-*` → `desarrollo` → `pruebas` → `main`.

La rama `main` está protegida: los cambios solo se incorporan mediante Pull Requests con al menos una aprobación.

## Cómo visualizar el sitio

1. Clonar el repositorio:
   ```
   git clone https://github.com/USUARIO/sitio-web-pareja.git
   ```
2. Entrar a la carpeta del proyecto: `cd sitio-web-pareja`.
3. Abrir el archivo `index.html` con doble clic en cualquier navegador web.
4. Usar el menú superior para moverse entre las páginas.

## Comandos principales utilizados

```
git init
git branch -M main
git add .
git commit -m "mensaje descriptivo"
git remote add origin <URL>
git push -u origin <rama>
git switch -c <rama>
git merge <rama>
git log --oneline --graph --all
```
