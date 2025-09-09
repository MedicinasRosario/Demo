# Demo Repository

Este repositorio fue creado con el propósito de **familiarizar al equipo con GitHub** y sus principales funcionalidades.  
Aquí podrán experimentar con la plataforma de manera libre y sin riesgo.

## Objetivo
- Practicar el flujo de trabajo en GitHub.
- Entender cómo funcionan los **issues**.
- Crear y revisar **pull requests**.
- Explorar cómo se ve y organiza la plataforma.

## Actividades sugeridas
1. Crear un **issue** con alguna propuesta o reporte ficticio.
2. Hacer un **fork o branch** y modificar un archivo (por ejemplo este README).
3. Enviar un **pull request** para revisar los cambios.
4. Revisar y comentar en los pull requests de otros.
5. Explorar la sección de **Projects** y **Discussions**.

## Notas
- No te preocupes por romper nada: este repo es solo para pruebas.
- Siéntete libre de escribir, modificar o borrar archivos según lo necesites.
- El objetivo es **aprender colaborando**.

---

¡Bienvenid@ al demo y manos a la obra 🚀!


# Demo Repository

Este repositorio fue creado con el propósito de **familiarizar al equipo con GitHub** y sus principales funcionalidades.  
Aquí podrán experimentar con la plataforma de manera libre y sin riesgo.

## Objetivo
- Practicar el flujo de trabajo en GitHub.
- Entender cómo funcionan los **issues**.
- Crear y revisar **pull requests**.
- Explorar cómo se ve y organiza la plataforma.

## Actividades sugeridas
1. Crear un **issue** con alguna propuesta o reporte ficticio.
2. Hacer un **fork o branch** y modificar un archivo (por ejemplo este README).
3. Enviar un **pull request** para revisar los cambios.
4. Revisar y comentar en los pull requests de otros.
5. Explorar la sección de **Projects** y **Discussions**.

## Notas
- No te preocupes por romper nada: este repo es solo para pruebas.
- Siéntete libre de escribir, modificar o borrar archivos según lo necesites.
- El objetivo es **aprender colaborando**.

---

¡Bienvenid@ al demo y manos a la obra 🚀!

# 🚀 GitHubCheat - Guía Interactiva de GitHub Desktop

Una herramienta web interactiva para aprender GitHub, GitHub Desktop y mejores prácticas de control de versiones. Perfecta para estudiantes, desarrolladores principiantes y cualquiera que quiera dominar el flujo de trabajo con Git.

## 📋 Descripción del Proyecto

GitHubCheat es una página web educativa que proporciona:

- 📚 **Guía completa de GitHub Desktop** - Interfaz visual amigable para principiantes
- 💻 **Comandos y flujos de trabajo** - Equivalencias entre GUI y terminal
- 🔧 **Resolución de problemas** - Soluciones a errores comunes
- 📋 **Playbook diario** - Checklists para flujos de trabajo profesionales
- 🌐 **Despliegue en GitHub Pages** - Instrucciones paso a paso

## ✨ Características

- **Interfaz moderna y responsive** - Diseñada con los colores oficiales de GitHub
- **Código copiable** - Botones para copiar comandos al portapapeles
- **Navegación fluida** - Índice interactivo y scroll suave
- **Ejemplos prácticos** - Casos de uso reales y soluciones probadas
- **Glosario completo** - 30+ términos de Git/GitHub con definiciones claras
- **Área de práctica** - Espacio seguro para hacer contribuciones reales
- **Galería de contribuidores** - Reconocimiento a la comunidad
- **Accesibilidad** - Cumple con estándares de accesibilidad web

## 🛠️ Stack Tecnológico

- **Frontend**: React 18 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Deployment**: GitHub Pages

## 🚀 Instalación y Configuración

### Prerrequisitos

- Node.js 16+ 
- npm o yarn
- Git

### Instalación

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/GitHubCheat.git
   cd GitHubCheat
   ```

2. **Instala las dependencias**
   ```bash
   npm install
   ```

3. **Inicia el servidor de desarrollo**
   ```bash
   npm run dev
   ```

4. **Abre tu navegador**
   ```
   http://localhost:5173
   ```

## 📝 Scripts Disponibles

```bash
# Desarrollo
npm run dev          # Inicia servidor de desarrollo

# Producción  
npm run build        # Construye la aplicación para producción
npm run preview      # Vista previa de la build de producción

# Calidad de código
npm run lint         # Ejecuta ESLint para revisar el código
```

## 🌐 Despliegue

### GitHub Pages (Automático)

1. Haz push a la rama `main`
2. Ve a **Settings > Pages** en tu repositorio
3. Selecciona **Deploy from a branch**
4. Elige `main` como source branch
5. Tu sitio estará disponible en `https://tu-usuario.github.io/GitHubCheat`

### Manual con GitHub CLI

```bash
# Instalar GitHub CLI
winget install GitHub.cli

# Habilitar GitHub Pages
gh api repos/:owner/:repo/pages -X POST -f source[branch]=main -f source[path]=/
```

## 📚 Contenido Educativo

### 🎯 Temas Cubiertos

1. **Fundamentos de Git y GitHub Desktop**
   - Conceptos clave (Working Directory, Staging, Repository)
   - Flujo de trabajo básico
   - Ramas y Pull Requests

2. **Trabajo Local con GitHub Desktop**
   - Clonado de repositorios
   - Commits parciales por línea
   - Manejo de ramas
   - Stash automático

3. **GitHub Pages**
   - Configuración desde la interfaz web
   - Opciones de despliegue
   - Troubleshooting común

4. **Resolución de Problemas**
   - Amend de commits
   - Revert de cambios
   - Resolución de conflictos
   - Git LFS para archivos grandes
   - Problemas de CRLF/LF

5. **Glosario Completo**
   - 30+ términos esenciales de Git/GitHub
   - Definiciones claras con ejemplos
   - Equivalencias GitHub Desktop vs Terminal
   - Términos básicos y avanzados organizados alfabéticamente

6. **Área de Práctica y Contribuciones**
   - Tutorial paso a paso para primera contribución
   - Galería interactiva de contribuidores
   - Diferentes niveles de dificultad
   - Ideas para contribuciones avanzadas

7. **Playbook Profesional**
   - Checklist diario
   - Templates de commits
   - Templates de Pull Requests
   - Mejores prácticas

## 🎨 Personalización

### Modificar Colores

Los colores están definidos en CSS custom properties en `index.html`:

```css
:root {
    --primary: #0969da;
    --primary-dark: #0550ae;
    --secondary: #6e7681;
    /* ... más variables */
}
```

### Agregar Nuevo Contenido

1. Edita `index.html` para agregar nuevas secciones
2. Actualiza el índice de contenidos
3. Asegúrate de mantener la estructura de navegación

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Este proyecto incluye un **área de práctica** perfecta para hacer tu primera contribución.

### 🎯 Tu Primera Contribución (Principiante)

La forma más fácil de contribuir es agregándote a la **Galería de Contribuidores**:

1. **Fork** este repositorio
2. **Clona** tu fork localmente
3. **Encuentra** la sección "🏆 Galería de Contribuidores" en `index.html`
4. **Agrega** tu información usando el template comentado
5. **Commit** con mensaje: `feat: agregar [tu-nombre] a contribuidores`
6. **Crea** un Pull Request

### 🚀 Contribuciones Avanzadas

Para contribuciones más complejas:

1. **Fork** del proyecto
2. **Crea** una rama para tu feature (`git checkout -b feature/nueva-seccion`)
3. **Commit** tus cambios (`git commit -m 'feat: agregar sección de hooks'`)
4. **Push** a la rama (`git push origin feature/nueva-seccion`)
5. **Abre** un Pull Request

### Ideas para Contribuir

- 🌟 **Galería de Contribuidores** - Agrega tu nombre y frase motivacional (⭐ Principiante)
- 📖 Agregar más ejemplos prácticos
- 🔧 Nuevos casos de troubleshooting
- 📚 Comandos útiles de Git
- 🌍 Traducciones a otros idiomas
- 🎨 Mejoras en el diseño (modo oscuro, animaciones)
- 📱 Optimizaciones móviles
- ♿ Mejoras de accesibilidad
- 🔍 Buscador de comandos
- 🛠️ Generador de .gitignore
- 🎭 Simulador de conflictos

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para más detalles.

## 🙏 Agradecimientos

- **GitHub** por sus excelentes herramientas y documentación
- **Comunidad Open Source** por las mejores prácticas
- **Lucide** por los iconos
- **Tailwind CSS** por el sistema de diseño

## 📞 Soporte

Si tienes preguntas o necesitas ayuda:

- 🐛 **Reporta bugs**: [GitHub Issues](../../issues)
- 💡 **Sugiere features**: [GitHub Discussions](../../discussions)
- 📧 **Contacto directo**: [tu-email@ejemplo.com]

## 🗺️ Roadmap

- [ ] **v2.0**: Agregar sección de GitHub Actions
- [ ] **v2.1**: Tutorial interactivo con simulador
- [ ] **v2.2**: Modo oscuro
- [ ] **v2.3**: Versión offline (PWA)
- [ ] **v3.0**: Integración con GitHub API para ejemplos en vivo

---

**⭐ Si este proyecto te ayudó, no olvides darle una estrella en GitHub!**

*Hecho con ❤️ para la comunidad de desarrolladores*