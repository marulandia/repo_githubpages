# Marketplace Pastel

Pequeña landing estática con diseño "pastel" basada en Bootstrap.

**Qué incluye**
- `index.html`: Landing page responsive creada con Bootstrap 5 (CDN).
- Estilos personalizados ligeros y una estructura de cards para productos.

**Cómo ver la página (rápido)**
- Abrir directamente en Windows (PowerShell):

```powershell
start 'c:\Users\maru2\Downloads\repo_githubpages\index.html'
```

**Servir localmente (opcional, útil para probar rutas o cuando uses fetch)**
- Con Python 3 (desde la carpeta del proyecto):

```powershell
# entrar a la carpeta del proyecto si no estás ahí
Set-Location 'c:\Users\maru2\Downloads\repo_githubpages'
# servir en http://localhost:8000
python -m http.server 8000
```

**Dependencias**
- Ninguna para instalar: la página utiliza CDN de Bootstrap y Google Fonts.

**Despliegue en GitHub Pages**
- Subir este repo a GitHub y en Settings -> Pages, elegir la rama `main` y la carpeta `/ (root)` como fuente.
- Alternativa: usar una rama `gh-pages` con herramientas como `gh-pages` o GitHub Actions.

**Notas / próximas mejoras sugeridas**
- Añadir una imagen hero y una CTA (ej. "Ver catálogo") para mejorar conversión.
- Conectar el formulario de login (si decides volver a añadirlo) a una API o a Firebase.
- Reemplazar CDN por paquetes locales si necesitas trabajar offline o sin dependencias externas.

---

Si quieres, puedo:
- Añadir una CTA en la hero ahora mismo.
- Quitar completamente el JS (Bootstrap bundle) para una página 100% estática.
- Preparar un flujo básico de despliegue a GitHub Pages (workflow de GitHub Actions).

Dime qué prefieres y lo dejo listo.
