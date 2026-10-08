# ⚖️ LexSkill AI - Generador de Contratos de Prestación de Servicios Legales

Este proyecto es una **Landing Page interactiva y Workspace legal** diseñado para promocionar y simular el uso de la **Gemini Skill** enfocada en la creación autónoma y estructurada de **Contratos de Prestación de Servicios** en Colombia.

Inspirado estilísticamente en la firma legal executive de *Alfredo Jaramillo Lawyer*, cuenta con una paleta institucional (Azul Marino `#0b2545` y Dorado `#c5a059`), tipografías clásicas/modernas y fundamentación teórica bajo el Código Civil y Código Sustantivo del Trabajo colombiano.

---

## 📋 Características Principales

1. **Marco Jurídico Integrado:** Explicación técnica basada en:
   - **Art. 1495 Código Civil:** Definición del contrato y obligaciones de hacer.
   - **Art. 2144 Código Civil:** Mandato y servicios profesionales.
   - **Art. 23 Código Sustantivo del Trabajo:** Criterios para evitar la subordinación laboral continuada.
2. **Infografía SVG Interactiva:** Diagrama explicativo del flujo de elaboración del contrato.
3. **Workspace de Prompts para Gemini Skill:**
   - Incluye el texto/prompt predeterminado con la marca de agua y parámetros requeridos.
   - Funcionalidades JS para **Cargar Ejemplo**, **Copiar Prompt** y **Simular Minuta con AI**.
4. **Completamente Responsive:** Compatible con dispositivos móviles, tablets y monitores de escritorio.

---

## 🚀 Guía de Despliegue con OpenCode & GitHub

Sigue estos pasos para subir este proyecto a GitHub utilizando **OpenCode / VS Code CLI** y desplegarlo en **GitHub Pages**.

### 1. Inicializar el Repositorio Local
Abre tu terminal en OpenCode o la consola local en la carpeta donde guardaste los tres archivos (`index.html`, `styles.css`, `README.md`):

```bash
# Inicializar repositorio Git
git init

# Agregar todos los archivos
git add .

# Crear el primer commit
git commit -m "feat: Commit inicial LexSkill AI Gemini Contract Generator"
```

### 2. Conectar y Subir a GitHub

1. Ve a tu cuenta de **GitHub** y crea un nuevo repositorio público (ejemplo: `lexskill-gemini-contract`).
2. Copia la URL de tu repositorio e ingresa los siguientes comandos en tu terminal de OpenCode:

```bash
# Cambiar el nombre de la rama principal
git branch -M main

# Vincular con el repositorio remoto de GitHub (reemplaza con tu URL)
git remote add origin https://github.com/TU_USUARIO/lexskill-gemini-contract.git

# Subir los archivos
git push -u origin main
```

---

## 🌐 Publicar en GitHub Pages

Para habilitar la aplicación en vivo y compartir la URL pública:

1. Ve a tu repositorio en **GitHub**.
2. Haz clic en **Settings** (Configuración) > **Pages** (en el menú lateral izquierdo).
3. En la sección **Build and deployment**:
   - **Source:** Selecciona `Deploy from a branch`.
   - **Branch:** Selecciona `main` y en la carpeta elige `/ (root)`.
4. Haz clic en **Save** (Guardar).
5. En un par de minutos, GitHub generará tu enlace público (ejemplo: `https://tu-usuario.github.io/lexskill-gemini-contract/`).

---

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica para accesibilidad legal.
- **CSS3:** Estilos personalizados, CSS Grid, Flexbox y animaciones sin librerías pesadas.
- **JavaScript (Vanilla):** Simulación dinámica de generación de minutas y manejo de portapapeles.
- **FontAwesome & Google Fonts:** Iconografía y tipografías *Cinzel* & *Montserrat*.
