# Landing – Apuntes DAW

Página de acceso a los apuntes y documentación de los módulos del ciclo de Desarrollo de Aplicaciones Web del IES El Just.

El sitio está construido con [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) y se despliega automáticamente en [GitHub Pages](https://jbeteta-ies.github.io/).

## Prerrequisitos

- Python 3.9+

## Inicialización tras clonar

```bash
# Clonar el repositorio
git clone https://github.com/jbeteta-ies/jbeteta-ies.github.io.git
cd jbeteta-ies.github.io

# Crear el entorno virtual
python3 -m venv venv
source venv/bin/activate   # Linux/macOS
# venv\Scripts\activate    # Windows

# Instalar dependencias
pip install -r requirements.txt

# Servir en local (http://127.0.0.1:8000)
mkdocs serve
```

## Despliegue

```bash
mkdocs gh-deploy
```

Genera la carpeta `site/` y la publica en la rama `gh-pages`, que es la que sirve GitHub Pages.
